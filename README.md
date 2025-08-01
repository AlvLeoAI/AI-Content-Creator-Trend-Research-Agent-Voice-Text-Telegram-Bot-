# AI-Content-Creator-Trend-Research-Agent-Voice-Text-Telegram-Bot-
AI Content Creator; Trend Research Agent (Voice &amp; Text Telegram Bot) - n8n 

## Overview

This Telegram-based automation allows users to send a voice or text message describing a content need. The system transcribes voice input, researches trends via YouTube and the web, and uses GPT-4.1 to generate SEO-optimized content. Output is saved in Airtable and/or sent directly by email.

---

## What It Can Do

- Accept voice or text prompts via Telegram
- Transcribe audio using Whisper
- Use YouTube and web trends to enrich content
- Generate blog posts, article ideas, or social media copy
- Store ideas in Airtable (with Prompt, Output, Type, Date, Status)
- Deliver content via email
- Detect duplicates and avoid repetition

---

## Tools Used

| Tool / Platform | Purpose |
|-----------------|---------|
| **n8n**          | Workflow orchestration |
| **Telegram Bot** | User input (text or voice) |
| **Whisper**      | Voice transcription |
| **OpenAI GPT-4.1-mini3** | Content generation |
| **YouTube Agent** | Trending topic discovery |
| **Web Agent (Perplexity)** | Web research |
| **Airtable**     | Content idea storage |
| **Gmail Agent**  | Email delivery |
