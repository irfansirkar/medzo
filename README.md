# Medzo

A domain-restricted AWS chatbot that gives the AWS Club precise answers and turns away everything else.

**Live demo:** https://irfansirkar.github.io/medzo/

Built by **Mohammad Irfan Sirkar** for **the Malla Reddy Hackathon 2024**.

## What the project does

Medzo answers AWS questions for the college AWS Club. A domain filter checks every question first, so only AWS questions reach the language model. Everything else gets a polite refusal, which keeps the bot accurate and on topic.

## Original stack

- Python
- Boto3
- An LLM behind a domain filter

## About this repository

This repository holds an interactive demo of the project. The demo runs entirely in the browser on GitHub Pages and uses built-in sample data, so it never needs a server, a GPU or an API key.

The demo really works in the browser. It uses a built-in knowledge base of about 30 AWS answers with links to the AWS docs, and a working keyword domain filter. No LLM is called, so no API key is exposed.

The original project code is not included here.

## Run the demo locally

Open `index.html` in any browser. There is no build step.

## More projects

See the full portfolio at https://irfansirkar.github.io/PERSONAL-PORFOLIO-WEBSITE/
