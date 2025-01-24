# RoadWise

RoadWise is a web application that allows users to upload PDFs containing government orders for road safety and translate them into multiple Indian languages. The translated content is also available as audio playback, ensuring accessibility for diverse audiences.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Features](#features)
- [Team](#team)

---

## About the Project
This tool extracts text from uploaded PDFs, translates it into the selected Indian language, generates a translated PDF, and provides audio playback of the translated text.

---

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Flask
- **Libraries:**
  - `pdfplumber` for text extraction
  - `GoogleTranslator` for translations
  - `gTTS` for audio generation
  - `reportlab` for PDF generation

---

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Malaharshana/RoadWise
   ```
2. Navigate to the project directory:
   ```bash
   cd RoadWise
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the application:
   ```bash
   python app.py
   ```
5. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000
   ```

---

## Features
- **PDF Text Extraction:** Extracts text content from uploaded PDFs.
- **Text Translation:** Translates extracted text into supported Indian languages (Hindi, Tamil, Telugu, etc.).
- **PDF Generation:** Generates a translated PDF for download.
- **Audio Translation:** Converts translated text into audio format.

---

## Team
- **Team Name:** Code Crew
- **Members:**
  - Harshini Y
  - Malaharshana A P
  - Srijaa A

---



