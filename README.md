# YouTubeSummaryVideoGenerator
This project provides a pipeline to generate a summarized transcript of any YouTube video, convert the summary to speech using AWS Polly, and create a video with subtitles using MoviePy.

## Features
**Transcript Extraction:** Automatically extract the transcript of a YouTube video using the YouTubeTranscriptApi.
**Summarization:** Summarize the extracted transcript using the Llama3 model through Groq.
**Text-to-Speech:** Convert the summary into speech using AWS Polly.
**Video Creation:** Generate a video with the summarized speech as audio and the corresponding subtitles using MoviePy.
