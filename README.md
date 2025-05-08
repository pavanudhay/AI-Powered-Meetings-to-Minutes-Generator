# AI-Powered-Meetings-to-Minutes-Generator
Uses AI to generate a summary of a meeting

This project helps automatically generate and format meeting minutes from raw meeting text using Natural Language Processing (NLP). It extracts important information such as attendees, discussion topics, key points, decisions, and action items, and then formats it in a clear and readable way.

Features

Extracting

      Attendees

      Key discussion points

      Decisions made

      Action items (with assignees and deadlines)
Finally

    Summarizes the overall meeting content

    Identifies topics using zero-shot classification

    Formats the output for better readability

  Technologies Used

    Python

    Hugging Face Transformers (BART for summarization)

    spaCy (for named entity recognition)

    PyTorch (for model support)

    Requirements

To run this project, install the following dependencies:

    pip install transformers spacy torch
    python -m spacy download en_core_web_sm

Usage

  Input the raw meeting text.

    Use MeetingMinutesGenerator().generate_minutes() to generate structured meeting minutes.

    Use the provided formatting script to display the output.

  This project is licensed under the MIT License.
