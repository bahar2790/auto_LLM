Introduction

This project demonstrates how to use the AutoLLM library to create an automated query engine capable of analyzing documents and answering queries. It leverages modern machine learning tools, including OpenAI APIs and data visualization frameworks like Gradio, to provide a seamless interface for exploring information.

Key Features

Document Analysis: Reads and processes documents from GitHub repositories or local files.
Query Engine: Uses AutoQueryEngine to perform automated question-answering based on processed documents.
Gradio Interface: Provides a web-based user interface for querying the engine interactively.
Integration with PowerBI: Enables advanced data visualization for insights.
Google Colab Compatibility: Designed to run efficiently in a Colab environment.
Requirements

The project requires the following Python libraries:

autollm: For building and managing the query engine.
gradio: For creating the web-based user interface.
gitpython: For fetching documents from GitHub repositories.
nbconvert: For converting Jupyter notebooks into other formats.
Install dependencies with:
!pip install autollm gradio gitpython nbconvert -Uqq
How It Works

Environment Setup:
Set up your OpenAI API key using userdata.get for authentication.
Document Reading:
Documents can be read from GitHub repositories using read_github_repo_as_documents.
Query Engine:
The AutoQueryEngine processes documents and answers queries based on the provided context.
Web Interface:
A Gradio-based interface allows users to interactively query the engine.
Usage

Clone the repository or copy the project files into your local environment or Colab.
Set up your OpenAI API key as an environment variable.
Run the notebook cells sequentially to:
Install dependencies.
Configure the query engine.
Start the Gradio interface.
Project Structure

Notebook: The main .ipynb file containing the project code.
Configuration:
GitHub repository URL: https://github.com/langchain-ai/langchain.git
Document formats: Processes .md files.








