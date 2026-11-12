# TEXT-to-SQL-Converter

QueryCraft converts natural-language questions into SQL using Google's Gemini API.
It generates SQL text for review; it does not connect to or execute queries against a database.

## Setup

1. Install Python and the dependencies:

   ```powershell
   python -m pip install -r requirements.txt
   ```

2. Copy `.env.example` to `.env` and set your Gemini API key:

   ```text
   GOOGLE_API_KEY=your_gemini_api_key_here
   ```

   Keep `.env` private. It is ignored by Git.

3. Start the app:

   ```powershell
   streamlit run app.py
   ```
