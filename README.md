# 🚀 Project Name

## 📌 Table of Contents
- [Introduction](#introduction)
- [Demo](#demo)
- [Inspiration](#inspiration)
- [What It Does](#what-it-does)
- [How We Built It](#how-we-built-it)
- [Challenges We Faced](#challenges-we-faced)
- [How to Run](#how-to-run)
- [Tech Stack](#tech-stack)
- [Team](#team)
- Check the github access
---

## 🎯 Introduction
A brief overview of your project and its purpose. Mention which problem statement are your attempting to solve. Keep it concise and engaging.

## 🎥 Demo
artifacts\demo
🖼️ Screenshots:
attached in the Presentation.
artifacts\arch\Email Classification Design.pptx

## 💡 Inspiration
What inspired you to create this project? Describe the problem you're solving.

## ⚙️ What It Does
The solution we bulit, reads thr eml email file from the folder, reads the mail content, gets the main intent and classify the mail according to the necessary request types.
Our solution is built using Google Gemini LLM model, and also PaddleOCR is used to extract the text from mail attachments i.e., 
PDF documents. We have used in-built mechanism to identify the main intent of the mail and classify them to spam or genuine use case. 
Solution is tested with multiple type of mail documents to deliver high accuracy, and it is designed for highly scalability and robustness.


## 🛠️ How We Built It
We built using the solution usin the Google Gemini LLM for our mail text/image classification.
We used the gemini-2.0- flash model,to test and deployment.
We used PaddleOCR to extract the text from mail attachment ie a PDF document.
We used formulas and weight mechanism to identify the main intent of the mail.
We used python as coding language to develop.


## 🚧 Challenges We Faced
Gemini LLM Model is a paid model based on the consumption
Processing time of the PaddleOCR is slightly more than the paid OCR solutions available on the market

## Pre-requistes to run

1. Install Python
2. Install the python library/dependencies
- google generative ai
- Paddle ocr, PaddlePaddle
- Torch
- pandas
- numpy
- configparser
- pprint 

## 🏃 How to Run

1. Place the input eml files in the "Files" folder.
2. Run the "gemini.py" to execute.
3. Verify the output generated in the "Output" folder.


## 🏗️ Tech Stack
Python Packages used:
- google generative ai
- Paddle ocr, PaddlePaddle
- Torch
- pandas
- numpy
- configparser
- pprint 

## 👥 Team
- **Bharath Muralidharan** - [GitHub](#) | [LinkedIn](#)
- **Somasekaran Sankaranarayanan** - [GitHub](#) | [LinkedIn](#)