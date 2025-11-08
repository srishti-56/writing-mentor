# Writing Mentor for Essay Development 

Try it out at - https://write.gentleintelligence.space/

A simple AI-powered writing coach that provides sharp analysis and guided discovery for essay development. 

## Features

### 🎯 **Smart Analysis**
- **Sonar Fast Model**: Uses Perplexity's fast Sonar model for quick analysis
- **Essay types**: Specialized feedback for different essay types (Personal, Product, Reflective, Tech, Analytical, Academic, Creative)
- **Custom Coaching Focus**: Specify particular areas or styles for targeted feedback

### 💾 **Auto-Backup System**
- **Automatic Saving**: Creates backups in your browser storage while you write
- **Text File Downloads**: Each backup and feedback iteration is saved as downloadable files with timestamps
- **Privacy**: All backups are stored in the browser
- **Real-time Stats**: Live word count, character count, and reading time

## Quick Start

### 1. **Get Your API Key**
1. Visit [perplexity.ai](https://perplexity.ai)
2. Sign up for an account
3. Navigate to API settings and generate your API key
4. Copy your API key (starts with `pplx-`)

### 2. **Run the Application**

#### Option A: Simple HTTP Server (Recommended)
```bash
# Navigate to the project directory
cd /path/to/writing-mentor

# Start a local server (Python 3)
python3 -m http.server 8000

# Or with Python 2
python -m SimpleHTTPServer 8000

# Or with Node.js (if you have it installed)
npx http-server -p 8000
```

#### Option B: Open Directly
Simply open `index.html` in your web browser (some features may be limited due to CORS restrictions).

### 3. **Start Writing**
1. Open your browser and go to `http://localhost:8000`
2. Enter your Perplexity API key
3. Select your essay type and analysis mode
4. Start writing in the workspace
5. Click "Challenge Me" for feedback

## Usage Guide

### **Essay Types**
- **Product**: First principles thinking, user research, product-market fit focus
- **Tech**: Technical clarity, practical insights, implementation details
- **Reflective**: Personal growth, experience analysis, meaning-making
- **Analytical**: Breaking down complex topics, examining assumptions
- **Personal**: Authentic voice, vulnerability, specific experiences
- **Academic**: Research-based arguments, scholarly discourse
- **Creative**: Originality, artistic expression, narrative innovation


## Philosophy

This writing coach is inspired by essay styles of Paul Graham, Rega Jha and more essayists I love! I hope it encourages
- **Exploration through writing** - "Half your ideas come while writing"
- **Deeper incisive thinking** - "Doubt, re-articulate, until truest truths outlast interrogation"
- **Voice Development**: Sharpening your authentic voice through repeated practice

## Contributing

This is a client-side application that can be easily modified and extended. Key areas for enhancement:

- **Additional AI Models**: Integration with other AI providers
- **Export Features**: PDF, Word document generation
- **Templates**: Pre-built essay templates and prompts
- **Analytics**: Writing progress tracking and insights

## License

This project is open source and available under the MIT License.

---

**Happy Writing!** 🖋️

The best essays come from genuine exploration and authentic voice. Use this tool to think deeper!
