# YouTube Sentiment Analyzer 🎥📊

A Python script that analyzes sentiment distribution in YouTube comments using TextBlob, visualizes results with Matplotlib, and summarizes findings using Gemini AI.

![Sentiment Analysis Pie Chart]

## Features ✨
- Fetches comments from any YouTube video
- Removes emojis and processes multilingual comments
- Performs sentiment analysis (Positive/Negative/Neutral)
- Generates visualizations of sentiment distribution
- Summarizes comments using Gemini 1.5 Flash AI
- Handles Hindi comments (optional transliteration)

## Dependencies ⚙️

!pip install googletrans==4.0.0-rc1
!pip install textblob matplotlib
!pip install google-generativeai
!pip install regex