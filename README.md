# CodeExplainer - Free AI-Powered Code Analysis

A Flask web application that provides intelligent code explanations using **completely free cloud AI APIs**. Perfect for hackathons and web deployment!

## Features

- **100% Free Cloud AI**: Uses Groq and Hugging Face APIs
- **Web Deployment Ready**: No local models, works on any hosting platform
- **Fast & Reliable**: Optimized for online hackathons
- **Multi-Language Support**: Python and JavaScript
- **Smart Fallback**: Works even without API keys
- **Beautiful UI**: Modern, responsive web interface
- **Line-by-Line Breakdown**: Detailed explanations for each code line

## AI Features

### Groq API Integration (Optional)
- **Speed**: Lightning fast responses
- **Cost**: Completely free
- **Setup**: 
  1. Go to [console.groq.com](https://console.groq.com/keys)
  2. Create free account
  3. Get API key
  4. Add to `.env` file as `GROQ_API_KEY=your_key_here`

### Fallback Mode (Always Available)
- **Cost**: Completely free
- **Features**: Rule-based code analysis
- **No Setup Required**: Works immediately
- **Languages**: Python and JavaScript support

## Quick Setup

1. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Configure AI (Optional)**
   ```bash
   # Create .env file with your Groq API key (optional)
   echo "GROQ_API_KEY=your_key_here" > .env
   ```

3. **Run the Application**
   ```bash
   python app.py
   ```

4. **Access the App**
   Open `http://localhost:5000` in your browser

## Usage

1. Paste your Python or JavaScript code
2. Click "Explain Code"
3. Get instant AI explanations:
   - Overall code summary
   - Line-by-line breakdown
   - Beginner-friendly explanations

## Requirements

- Python 3.7+
- Internet connection (for Groq API, optional)
- **No paid API keys required!**

## Current Status

✅ **Application Status**: Running successfully  
✅ **Web Interface**: Accessible at http://localhost:5000  
✅ **Code Analysis**: Working with fallback explanations  
✅ **Language Support**: Python and JavaScript  
✅ **Error Handling**: Graceful fallback when AI is unavailable
