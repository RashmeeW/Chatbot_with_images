# PDF-Based Chatbot with Image-Supported Answers
This project is a PDF-based intelligent chatbot designed to provide accurate answers supported by relevant visual context. Unlike traditional text-only chatbots, this system enhances responses by displaying images extracted directly from the PDF to improve user understanding.

## Features

 Image-Supported Responses – Displays relevant images alongside LLM-generated answers.

 Table-Aware Question Answering – If a question refers to tabular data, the chatbot retrieves the answer and shows the complete table from the PDF.

 Efficient for Low-End GPU Systems – A practical alternative to Vision LLMs for small-scale projects with hardware constraints.

 Improved Contextual Understanding – Combines text, images, and tables for better response quality

## How It Works
  Image Extraction - 
    Images are extracted from the PDF using the OpenCV library in Python.
  
  Image Captioning - 
    Extracted images are processed with the BLIP (Bootstrapping Language-Image Pretraining) model to generate meaningful captions.
  
  Language Model Integration - 
    The chatbot uses the Mistral LLM to generate accurate and context-aware responses.
  
  Table Handling - 
    When a query involves tabular data, the chatbot retrieves the relevant table and presents it along with the answer.

## Tech Stack

Python
OpenCV – Image extraction, 
BLIP Model – Image captioning, 
Mistral LLM – Response generation

## Use Case

1. This chatbot is ideal for:
2. Small-scale AI projects
3. Systems with limited GPU resources
Document-heavy workflows
Technical manuals and knowledge bases
