This project demonstrates a custom-built OCR and NLP pipeline that converts handwritten notes (such as sticky notes or planner pages) into structured calendar events. It also includes a shared calendar feature to facilitate collaborative scheduling.

Overview

Optical Character Recognition (OCR): A custom-trained OCR model extracts handwritten text from images of notes or calendars.
Text Processing: A spacing and autocorrect model refines the raw OCR output into readable, properly spaced text.
Event Parsing: An NLP pipeline using named entity recognition and rule-based logic extracts event titles, dates, and times from the processed text.
Calendar Integration: Extracted events are formatted for integration with Google Calendar, iOS Calendar, or Slack (demo stage).
Shared Calendars: A feature enabling collaborative scheduling and event sharing among users.
Technology Stack

Python, PyTorch, HuggingFace Transformers
IAM Handwriting Dataset (OCR training)
Custom T5-based model for text spacing
Fuzzy matching, regex, and dateparser for event extraction
Flask for demo server
OpenCV for image preprocessing
Planned integration with Google Calendar API
Demo

A working video demonstration is available on LinkedIn:
[View Demo on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7303614174335492096)

