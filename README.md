# YouTube Video Agent

This project demonstrates how to build an OpenAI agent SDK to work with YouTube videos. The agent is capable of extracting transcripts from YouTube video URLs using the `youtube_transcript_api` and integrates with OpenAI's language models to process and interact with the video content.

## Features

- Extract YouTube video transcripts with timestamps
- Build a custom OpenAI agent with predefined instructions
- Environment variable management with `.env`
- Async event loop handling for smooth OpenAI API calls

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/maghaeef/YouTube_Video_Agent.git
   cd YouTube_Video_Agent
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your `.env` file with your OpenAI API key:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```