# GPT Explainer Web Application

The GPT Explainer Web Application is a tool that allows users to upload PowerPoint presentations and receive generated answers for each slide using the OpenAI GPT-3.5 Turbo model. This application is designed to simplify the process of summarizing presentation content and providing insightful explanations.

## Features

- Upload PowerPoint presentations for processing.
- Generate answers for each slide using the GPT-3.5 Turbo model.
- Store and manage uploaded files' status and explanations.
- View the status of uploaded files and retrieve generated explanations.
- User-friendly web interface for easy interaction.

## Table of Contents
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Web Application Structure](#web-application-structure)


### Prerequisites
Before using the GPT Explainer Web Application, make sure you have the following software installed:

- Python (version 3.7 or higher)
- OpenAI API key
- Flask (install via `pip install flask`)
- SQLAlchemy (install via `pip install sqlalchemy`)

### Usage
1. Upload a PowerPoint presentation using the provided form.
2. Monitor the status of your upload and view generated explanations.
3. Retrieve explanations for each slide generated using the GPT-3.5 Turbo model.


### Web Application Structure
The web application consists of the following main components:

- web_app.py: The Flask web application script handling file uploads and status retrieval.
- pptx_parser.py: Functions to read PowerPoint presentations and extract slide text.
- gpt.py: Interaction with the GPT-3.5 Turbo model to generate explanations.
- db.py: Database models and setup using SQLAlchemy.
- HTML templates in the templates folder for rendering the web pages.
- The uploads folder for storing uploaded PowerPoint presentations.
- The outputs folder for storing generated explanations.
