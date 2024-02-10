# AskDoc
## Overview
This project aims to provide a platform for extracting answers from PDF documents using machine learning. Users can upload a PDF file, and the underlying machine learning model will be trained to understand and answer questions based on the content of the document.


## Features
- **PDF Upload:** Users can upload PDF files containing the content they want to analyze.
- **Machine Learning Training:** The system trains a machine learning model to understand the context and content of the uploaded PDF.
- **Question-Answering Interface:** After training, users can input questions related to the PDF content and receive accurate answers.


## Prerequisites
- [Docker](https://www.docker.com/get-started) must be installed on your machine.
-We did not deployed our website once deployed you can use with out Prerequisites.


## Getting Started
1. **Clone the Repository:**
   ```bash
   https://github.com/thrishamareddy/AskDoc.git
2. **Create .env**
  Create a .env file and copy the contents of .env.example to modify it.
3. **Run App**
  docker-compose up -d
4. **Aftere any update**
   docker-compose up -d --build
5. **now you can access the app at http://localhost:8081**

## How It Works :
1. **Opening the App Locally:**
Open your web browser and navigate to http://localhost:8081 .
![1](https://github.com/thrishamareddy/AskDoc/assets/114424485/75540524-fe32-48c7-9763-79cd0e40c09a)

2. **Configuring OpenAI API Key:**
Click on the settings icon (gear/cog icon) usually located in the upper-right corner of the app interface.
In the settings menu, there should be an option to input the OpenAI API key. If prompted, enter your personal OpenAI API key. **Each user needs to use their own key for privacy reasons.**
![WhatsApp Image 2024-02-10 at 11 04 25 PM (1)](https://github.com/thrishamareddy/AskDoc/assets/114424485/5b46e824-b0b6-4c29-a589-80b1e5341e05)

3. **Uploading PDF Documents:**
Navigate to the main page or dashboard of the app.
Look for an option to upload PDF documents. 
Click on the upload button and select the PDF file you want to analyze.
![WhatsApp Image 2024-02-10 at 11 04 27 PM](https://github.com/thrishamareddy/AskDoc/assets/114424485/09fc0deb-2572-4606-a98b-3bbba6653547)

4. **Asking Questions:**
Once the PDF is uploaded, you should see an area or input field where you can enter your questions related to the uploaded document.
Type your questions into the designated area and submit the query.
![image](https://github.com/thrishamareddy/AskDoc/assets/114424485/32bbbec8-e4b9-4d61-9a0d-92a3a90711f7)


5. **Viewing Answers:**
The app will process your questions using the machine learning models and display the answers on the interface.
6. **Accessing Previous PDFs in History Tab:**
Look for a history tab or section on the left side of the app interface.
Click on the history tab to view a list of previously uploaded PDF documents.
You may click on any document in the history tab to see details or re-query questions related to that document.


![WhatsApp Image 2024-02-10 at 11 04 26 PM (2)](https://github.com/thrishamareddy/AskDoc/assets/114424485/4f30650e-b25a-400f-95db-610f82651df5)




