# Writing Coach - Essay Development Assistant

A sophisticated AI-powered writing coach that provides sharp analysis and guided discovery for essay development, built with modern web technologies and powered by Perplexity AI.

## Features

### 🎯 **Smart Analysis**
- **Sonar Fast Model**: Uses Perplexity's fast Sonar model for quick, cost-effective analysis
- **Essay Type Detection**: Automatically detects and suggests optimal essay types (Tech, Reflective, Analytical, Personal, Academic, Creative)
- **Multi-level Analysis**: Quick Analysis, Deep Analysis, and Expert Mode options
- **Custom Coaching Focus**: Specify particular areas for targeted feedback

### 💾 **Auto-Backup System**
- **Automatic Saving**: Creates backups every minute while you write
- **5 Version History**: Keeps the latest 5 backup versions for easy recovery
- **Text File Downloads**: Each backup saved as downloadable `.txt` files with timestamps
- **Smart Recovery**: Easy restore from any backup version with one click

### 🎨 **Modern Interface**
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Dark/Light Mode**: Automatically adapts to your system preferences
- **Real-time Stats**: Live word count, character count, and reading time
- **Visual Feedback**: Color-coded analysis sections with intuitive icons

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
cd /path/to/writing-coach

# Start a local server (Python 3)
python3 -m http.server 8000

# Or with Python 2
python -m SimpleHTTPServer 8000

# Or with Node.js (if you have it installed)
npx http-server -p 8000
```

#### Option B: Open Directly
Simply open `index 3.html` in your web browser (some features may be limited due to CORS restrictions).

### 3. **Start Writing**
1. Open your browser and go to `http://localhost:8000`
2. Enter your Perplexity API key
3. Select your essay type and analysis mode
4. Start writing in the workspace
5. Click "Quick Analysis" or "Deep Analysis" for feedback

## Usage Guide

### **Essay Types**
- **Tech**: Technical clarity, practical insights, implementation details
- **Reflective**: Personal growth, experience analysis, meaning-making
- **Analytical**: Breaking down complex topics, examining assumptions
- **Personal**: Authentic voice, vulnerability, specific experiences
- **Academic**: Research-based arguments, scholarly discourse
- **Creative**: Originality, artistic expression, narrative innovation

### **Analysis Modes**
- **Quick Analysis**: Fast feedback on core issues (400 words max)
- **Deep Analysis**: Comprehensive analysis with detailed suggestions (800 words max)
- **Expert Mode**: Advanced reasoning and sophisticated insights

### **Backup System**
- **Automatic**: Starts when you begin typing, saves every minute
- **Manual**: Click "Save Now" for immediate backup
- **Recovery**: Use "View Backups" to restore from any previous version
- **Control**: Pause/resume auto-save as needed

## File Structure

```
writing-coach/
├── index 3.html          # Main application (latest version)
├── index 2.html          # Previous version with hardcoded examples
├── test_backup.html      # Backup system test file
└── README.md            # This file
```

## Technical Details

### **API Integration**
- **Provider**: Perplexity AI
- **Model**: Sonar (fast, cost-effective)
- **Authentication**: Bearer token via API key
- **Rate Limiting**: Built-in error handling for rate limits

### **Browser Compatibility**
- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Features**: ES6+ JavaScript, CSS Grid, CSS Custom Properties
- **Storage**: Session-based (no persistent storage)

### **Security**
- **API Keys**: Stored in memory only (session-based)
- **No Data Collection**: All processing happens client-side
- **HTTPS Recommended**: For production use

## Troubleshooting

### **Common Issues**

#### API Key Problems
- **Invalid Format**: Ensure your key starts with `pplx-` and is at least 20 characters
- **Rate Limits**: Wait a moment and try again if you hit rate limits
- **Network Issues**: Check your internet connection

#### Backup Issues
- **Downloads Not Working**: Ensure your browser allows downloads
- **Timer Not Starting**: Make sure you have content in the text area
- **File Names**: Backup files use ISO timestamps for unique naming

#### Analysis Problems
- **Empty Response**: Check your API key and try again
- **Parsing Errors**: The system will show raw AI response if parsing fails
- **Model Errors**: Try switching analysis modes or essay types

### **Performance Tips**
- **Large Essays**: Use Quick Analysis for very long texts
- **Frequent Analysis**: Consider pausing auto-backup during heavy analysis
- **Browser Memory**: Refresh the page if performance degrades

## Philosophy

This writing coach is built on the principles of:

- **Paul Graham**: "Half your ideas come while writing" - encouraging exploration through writing
- **Rega Jha**: "Doubt, re-articulate, until truest truths outlast interrogation" - pushing for deeper thinking
- **Independent Thinking**: Resisting received wisdom and pursuing genuine novelty
- **Voice Development**: Sharpening authentic voice through repeated practice

## Contributing

This is a client-side application that can be easily modified and extended. Key areas for enhancement:

- **Additional AI Models**: Integration with other AI providers
- **Export Features**: PDF, Word document generation
- **Collaboration**: Real-time collaborative editing
- **Templates**: Pre-built essay templates and prompts
- **Analytics**: Writing progress tracking and insights

## License

This project is open source and available under the MIT License.

---

**Happy Writing!** 🖋️

Remember: The best essays come from genuine exploration and authentic voice. Use this tool to push your thinking deeper, not to replace your own insights.
