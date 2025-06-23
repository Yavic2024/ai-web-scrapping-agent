# 🌐 AI-Powered Web Scraper

A powerful Streamlit application that leverages OpenAI's advanced language models to intelligently extract and process web content. Transform any website into structured data with natural language instructions.

## ✨ Key Features

- **Universal Web Compatibility**: Extract data from virtually any website with a simple URL
- **AI-Enhanced Processing**: Powered by OpenAI's cutting-edge language models (GPT-3.5-turbo or GPT-4)
- **Custom Extraction**: Define exactly what information you need using natural language prompts
- **User-Friendly Interface**: Intuitive Streamlit-based interface for seamless interaction

## 🚀 Quick Start Guide

### Prerequisites
- Python 3.7+
- OpenAI API key
- Git (for repository cloning)

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Yavic2024/ai-web-scrapping-agent.git
      ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up API Access**
   - Create an account at [OpenAI](https://platform.openai.com/)
   - Generate your API key from the dashboard

4. **Launch the Application**
   ```bash
   streamlit run ai_scrapper.py
   ```

## 🛠 How It Works

1. **Authentication**
   - Input your OpenAI API key to authenticate with the service
   - Select your preferred language model (GPT-3.5-turbo or GPT-4)

2. **Content Extraction**
   - Provide the target website URL
   - Specify your data requirements using natural language

3. **AI Processing**
   - The application constructs a SmartScraperGraph instance
   - The selected LLM processes the webpage according to your instructions
   - Structured data is extracted and formatted

4. **Results**
   - View the processed output directly in the application
   - Results are presented in a clean, readable format

## 📝 Usage Tips

- Be specific in your prompts for more accurate results
- For complex websites, try breaking down your requests into multiple, simpler queries
- Monitor your OpenAI API usage through the [OpenAI Dashboard](https://platform.openai.com/account/usage)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
