# Anychat

A unified chat interface for multiple AI models powered by Gradio. This application provides access to various leading AI models through a simple tab-based interface.

## Getting Started

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/anychat.git
```
2. Install dependencies:
```bash
pip install -r requirements.txt

```

### Running the Application
1. Navigate to the project directory:
```bash
cd anychat
```

2. Start the application:
```bash
python app.py
```

3. Open your web browser and go to:
```
http://localhost:7860
```

## Features

- **Tab-Based Interface**: Easy switching between different AI models
- **Model Selection**: Dropdown menus for selecting specific model versions
- **Token Authentication**: Secure API key management for each service
- **Multimodal Support**: Vision capabilities for compatible models

## Supported Models

### Gemini
- **gemini-1.5-pro**: Default model for complex reasoning tasks
- **gemini-1.5-flash**: Fast and versatile performance
- **gemini-1.5-flash-8b**: Optimized for high-volume, simpler tasks
- **gemini-exp-1114**: Experimental version with quality improvements

### ChatGPT
- **GPT-4 Series**: Including gpt-4o (most advanced), gpt-4-turbo, and standard gpt-4
- **O1 Series**: Specialized reasoning models (preview and mini versions)
- **Multiple Snapshots**: Access to specific model versions with timestamps

### Claude
- **Claude 3.5**: Latest Sonnet (20241022) and Haiku (20241022) versions
- **Claude 3**: Access to Opus, previous Sonnet, and Haiku versions
- Default set to latest Sonnet for optimal performance

### Meta Llama
- **Llama 3.2**: Models from 1B to 90B parameters, including vision-enabled versions
- **Llama 3.1**: Models from 8B to 405B parameters
- **Vision Support**: Multimodal capabilities in selected models
- Requires SambaNova API key from [SambaNova Cloud](https://cloud.sambanova.ai/)

### Grok
- Access to xAI's Grok beta model

### Qwen2.5
- 72B parameter model from Alibaba
- Requires Hyperbolic API key from [Hyperbolic](https://app.hyperbolic.xyz/)

### Perplexity
Three categories of models:
1. **Sonar Online Models** (8B-405B parameters)
   - Include real-time search capabilities
   - Requires beta access
2. **Sonar Chat Models** (8B-70B parameters)
   - Standard chat functionality
3. **Open Source Models** (8B-70B parameters)
   - Based on Hugging Face implementations

## API Keys Required

- SambaNova API key for Meta Llama models
- Hyperbolic API key for Qwen2.5
- Perplexity API key (beta access required for online features)

## Technical Details

- Built with Gradio Blocks interface
- Supports dynamic model switching
- Implements token-based authentication
- Handles multimodal inputs where supported