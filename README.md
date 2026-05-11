# Agentic OCR System 
🔐 Agentic OCR System 

A privacy-first OCR system built with Streamlit that extracts text from images, detects sensitive information, applies intelligent redaction, and generates structured AI-powered insights using LLM integration.

It is designed for secure document processing, data privacy enforcement, and explainable AI-based OCR pipelines.

🌟 Features
🧠 Intelligent OCR
Extracts text from images using Tesseract OCR
Advanced preprocessing for:
Blur reduction
Noise removal
Contrast enhancement
Image upscaling for better accuracy
🔐 Privacy Shield Engine

Automatically detects and redacts:

CNIC numbers
Emails
Phone numbers
Sensitive patterns

Replaces them with secure masked values like:

█████-███████-█
████@████.██
🤖 AI-Powered Analysis (Groq API)
Uses LLM (LLaMA 3 via Groq API)
Provides structured insights from extracted text
Helps in:
Document summarization
Context understanding
Smart interpretation
📊 Interactive Dashboard
Privacy leak counter
Security status indicator (SAFE / REDACTED)
Processing mode display
Clean beige-themed UI
📋 Audit Logging System

Tracks system activity:

Upload events
OCR execution
Privacy scan results
Redaction actions
AI processing logs
⚖️ Ethical AI Design (Consent-Based)
Requires user consent before processing
Ensures ethical handling of sensitive documents
Aligns with responsible AI principles
🖼️ UI Preview
Modern beige-themed dashboard
Clean card-based layout
Real-time results display
Audit log panel
Side-by-side original vs processed view
⚙️ Tech Stack
Python 🐍
Streamlit 🎈
Tesseract OCR 👁️
Pillow (Image Processing) 🖼️
Regex (Pattern Detection)
Groq API (LLM Integration) 🤖
python-docx (Report Export)
