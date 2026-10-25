# Project: Scratch Academy

Scratch Academy aims to teach young kids interested in S.T.E.M. how to code using Scratch. Scratch is a great starting point for anyone getting into programming. To encourage learning, our platform features 8 different lessons and an AI agent designed to help students master Scratch and fundamental programming concepts.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes. Also open Scratch.mit.edu in a new tab and follow along

### Prerequisites

The project requires Python 3 and the following external packages:
* Flask
* openai
* python-dotenv

*Note: Built-in Python modules used include `base64`, `json`, `sqlite3`, and `os`.*

### Installation & Setup

1. **Clone or navigate to the project directory:**
   ```bash
   cd /path/to/SCRATCHWEBSITE
   ```

2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   ```
   *(Try `python3` if `python` does not work on your system)*

3. **Activate the virtual environment:**
   * **Windows (PowerShell):** `.\venv\Scripts\Activate.ps1`
   * **Windows (CMD):** `venv\Scripts\activate.bat`
   * **Mac / Linux:** `source venv/bin/activate`

4. **Install the external packages:**
   ```bash
   pip install -r requirements.txt
   ```

5. **Run the application:**
   ```bash
   python app.py
   ```

## How to Use

1. Open your browser and navigate to the local host URL provided by Flask (usually `http://127.0.0.1:5000`).
2. Sign up or log in using the buttons on the top right.
3. Click on **Lesson 1** (our sample lesson for testing).
4. Interact with the AI agent by asking questions or uploading screenshots of your Scratch code as you follow the lesson plan.

## Usage Examples

<img width="1200" height="600" alt="Screenshot 2026-10-25 000757" src="https://github.com/user-attachments/assets/119544b3-48d0-44f2-b6ae-a6ed071f1c5f" />
<img width="1361" height="632" alt="Screenshot 2026-10-25 002823" src="https://github.com/user-attachments/assets/5a285ba9-444c-4059-a9c3-274fcb192bea" />
<img width="1313" height="621" alt="Screenshot 2026-10-25 002735" src="https://github.com/user-attachments/assets/68faa350-0cd7-4102-9f82-a545cee3e8d7" />
<img width="967" height="578" alt="Screenshot 2026-10-25 003030" src="https://github.com/user-attachments/assets/2104c19d-9b7e-413c-9b1c-4a96a5c2fc42" />

<img width="967" height="578" alt="Screenshot 2026-10-25 002959" src="https://github.com/user-attachments/assets/e5345d94-f17b-40d5-84d9-9b8ef0932e49" />






## Authors

**Roger Chao and Aahan Kumar**


## Acknowledgments

* Built using the OpenAI API for the interactive AI tutoring agent.
