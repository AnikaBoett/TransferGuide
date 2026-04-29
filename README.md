# TransferGuide
This project is a transfer equivalency tool for Utah Tech University that allows students to:

- Upload a transcript (PDF or image)
- Automatically extract completed courses
- Compare them against degree requirements
- Track progress toward General Education and Major requirements

Features:
- Transcript upload (PDF + image support)
- AI-based course extraction using OpenAI API **Please note that the file upload uses an OpenAI API. To get the upload program working, you will need to connect an API key. 
- Manual course selection/search
- Degree requirement tracking:
      - General Education
      - Core Requirements
      - Electives
      - Tracks
- Progress percentage display
- Course equivalency mapping between schools

Tech Stack: 
Frontend
- HTML / CSS / JavaScript

Backend
- Node.js + Express.js
- File uploads via Multer

AI / Parsing
- OpenAI Responses API (gpt-4o)
- pdf-parse for text-based PDFs

Prerequisites
- Node.js (v18+ recommended)
- OpenAI API key
