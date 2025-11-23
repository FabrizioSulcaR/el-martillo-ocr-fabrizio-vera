# El Martillo OCR - Fabrizio Vera

## Overview
This project digitizes and analyzes a historical newspaper page from "El Martillo" (Chiclayo, 1903–1919) using the Claude API for OCR. The goal is to transform the unstructured image data into a structured dataset and provide exploratory insights.

## Repository Structure
- `data/el_martillo/`: Contains the source image (`page_01.png`).
- `analysis.ipynb`: Python notebook with the OCR extraction, data processing, and visualization logic.
- `el_martillo_dataset.csv`: Structured dataset extracted from the newspaper page.
- `report.md`: Short report with insights and analysis.
- `requirements.txt`: List of Python dependencies.

## Setup
1.  Clone the repository.
2.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3.  Set up your Anthropic API key. You can create a `.env` file in the root directory with:
    ```
    ANTHROPIC_API_KEY=your_api_key_here
    ```
4.  Run the `analysis.ipynb` notebook.

## Deliverables
- **Python Notebook**: `analysis.ipynb`
- **Structured Dataset**: `el_martillo_dataset.csv`
- **Short Report**: `report.md`
- **Raw Media**: `data/el_martillo/page_01.png`
