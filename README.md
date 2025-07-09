# Text Summarizer with GPT
# 🧠 Text Summarizer with OpenAI + BeautifulSoup

This is a personal project where I built a Python-based tool to **scrape website content and summarize it using GPT-4o or GPT-3.5 from OpenAI**. It runs inside a Jupyter Notebook and uses BeautifulSoup for web scraping and prompt engineering for summarization.

---

## 🔧 Tools & Technologies

- **Python**
- **Jupyter Notebook**
- **OpenAI GPT API (GPT-4o / GPT-3.5)**
- **BeautifulSoup** (for web scraping)
- **dotenv** (for securely storing API keys)

---

## 📚 What the Project Does

✅ Scrapes content from a given webpage  
✅ Cleans and extracts the visible text  
✅ Sends the text to OpenAI's GPT API  
✅ Prints a clean summary in bullet points or paragraph form  
✅ Keeps your API key private using `.env` and `.gitignore`

---

## 🛠️ How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/text-summarizer-llm.git
cd text-summarizer-llm


## 📦 2. Install Requirements

If you have requirements.txt, run:
pip install -r requirements.txt

Or install manually:
pip install openai beautifulsoup4 python-dotenv requests

3. Add Your API Key
OPENAI_API_KEY=your-openai-api-key-here

4. Run the Notebook
jupyter notebook
