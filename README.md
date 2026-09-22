# AI MCQ Generator

## Project Overview

AI MCQ Generator is an interactive web application built using **Python**, **Streamlit**, and the **Hugging Face Inference API**. The application generates topic-based multiple choice questions (MCQs) using a Large Language Model (LLM) and allows users to complete the quiz and view their score instantly.

## Project Objective

The objective of this project is to demonstrate how **Generative AI** can be used to automatically create educational quizzes from any user-provided topic.

## Features

* Generate MCQs from any topic
* Select the number of questions
* Four options for each question
* One correct answer per question
* Interactive quiz interface
* Automatic score calculation
* Beginner-friendly Streamlit application

## Technologies Used

* Python
* Streamlit
* Hugging Face Hub
* Hugging Face Inference API
* JSON

## AI Model

**Model:** `openai/gpt-oss-120b`

The model generates topic-based multiple choice questions in structured JSON format.

## Project Structure

```text id="ymnjkq"
AI-MCQ-Generator/
│
├── app.py
├── requirements.txt
├── README.md
└── .streamlit/
    └── secrets.toml
```

## Installation

### Step 1: Clone the repository

```bash id="1g1p6i"
git clone https://github.com/your-username/AI-MCQ-Generator.git
```

### Step 2: Open the project folder

```bash id="vdv8q3"
cd AI-MCQ-Generator
```

### Step 3: Install the required libraries

```bash id="m2a9x4"
pip install -r requirements.txt
```

## Requirements

```text id="0djdki"
streamlit
huggingface_hub
```

## Configure Hugging Face Token

Create a `.streamlit/secrets.toml` file and add your Hugging Face API token.

```toml id="33v5g0"
HF_TOKEN = "your_huggingface_token"
```

**Note:** Do not upload your API token to GitHub.

## Run the Application

Execute the following command:

```bash id="gcgj09"
streamlit run app.py
```

The application will automatically open in your web browser.

## How It Works

1. Enter a topic.
2. Select the number of questions.
3. Click **Generate MCQs**.
4. The AI generates questions with four options.
5. Choose your answers.
6. Click **Submit Quiz**.
7. The application displays your final score.

## Example

### Topic

```text id="td8v95"
Python
```

### Number of Questions

```text id="nhtbmn"
5
```

### Result

```text id="bhuxoe"
Your Score: 4/5
```

## Learning Outcomes

* Generative AI
* Large Language Models (LLMs)
* Hugging Face Inference API
* Prompt Engineering
* JSON Data Processing
* Streamlit Web Development
* Interactive Quiz Applications

## Future Enhancements

* Difficulty levels
* Quiz timer
* Performance analysis
* Answer explanations
* Downloadable results
* Multiple subject categories

## Conclusion

This project demonstrates how **Generative AI** can automatically create multiple choice questions and build an interactive quiz application using **Python**, **Streamlit**, and the **Hugging Face Inference API**.

## Author

**Keerthiga K U**

B.Sc. Computer Science with Artificial Intelligence

