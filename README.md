# Medical Information Extraction using Ollama API

This repository provides a code framework for extracting structured medical information from doctor-patient conversations using the Ollama `nuextract` model. The model takes unstructured conversation text, extracts relevant medical information, and organizes it into a predefined template, useful for automating medical documentation and analytics.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)

## Overview

In medical settings, capturing information from conversations between doctors and patients can be valuable for creating structured records, which can aid in analysis and follow-up care. This repository demonstrates how to use the `nuextract` model from Ollama to parse conversation text and extract relevant information, including symptoms, assessments, diagnoses, and treatment plans.

## Features

- **Automated information extraction**: Extracts structured data fields such as symptoms, assessments, and prescriptions from raw text.
- **Flexible template system**: Customize the extraction template to match your specific data fields.
- **Ollama API integration**: Uses the `nuextract` model from Ollama for efficient information extraction.
- **Easy-to-use interface**: Run the extraction with a few lines of code.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/heydibyendu/nuextract.git
   cd nuextract
   ```
## Usage

1. Define your input conversation text and extraction template.
2. Use the extract_info function to retrieve structured information.
3. Print or save the results as needed.
