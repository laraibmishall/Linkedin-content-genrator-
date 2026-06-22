n8n Workflows

A collection of automated n8n workflows for content generation, marketing, and AI-powered automation.


Workflows

1. LinkedIn Content Generator

File: workflows/Linkedin_Content_Generator.json

Automatically generates and publishes high-quality LinkedIn posts every 6 hours using Google Gemini AI. Targeted at engineering leaders in the AI/ML and Cloud space.

What it does:


Generates fresh content topics around MLOps, DevOps, Cloud Engineering, and AI/ML
Writes full LinkedIn posts (under 250 words) with hooks and CTAs
Creates optimized hashtags for better reach
Generates a relevant AI image for each post
Auto-publishes to LinkedIn


Tech Stack: Google Gemini, n8n, LinkedIn API, AI Image Generation

 How to Use


Download the .json file from the workflows/ folder
Open your n8n instance
Go to Workflows → Import from File
Upload the .json file
Set up your credentials (Google Gemini API, LinkedIn, etc.)
Activate the workflow
Required Credentials

WorkflowCredentials NeededLinkedIn Content GeneratorGoogle Gemini API, LinkedIn OAuth
Contact

Feel free to open an issue or reach out if you have questions or want to collaborate.
