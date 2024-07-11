# Political Text Bias Analyzer

This project contains a Python script that analyzes political texts for ideological bias using advanced prompt engineering and the Anthropic Claude 3.5 Sonnet API. The analysis is based on a custom prompt designed for political scientists, aiming to detect subtle and overt political leanings in textual content.

## Project Overview

This script is part of my ongoing research projects in political science. It leverages custom prompt engineering to create a sophisticated system for political bias detection. The core of the analysis relies on a detailed prompt that instructs the AI to consider various aspects of political bias, including:

1. Portrayal of ideological groups
2. Claims about science or academia
3. Research findings and worldviews
4. Policy positions
5. Language and framing

The AI provides a nuanced analysis, categorizing texts on a spectrum from "High Conservative" to "High Liberal," with "Neutral" options for balanced or apolitical content.

## Features

- Loads data from CSV files
- Utilizes the Anthropic Claude 3.5 Sonnet API for text analysis
- Categorizes texts based on political bias
- Provides detailed explanations for each categorization
- Saves results to a new CSV file

## How It Works

1. The script loads article data from a CSV file.
2. Each article is sent to the Anthropic API for analysis.
3. The API returns a category/level of bias and a detailed explanation.
4. Results are compiled into a new DataFrame and saved to a CSV file.

## Usage

To use this script:

1. Ensure you have the required libraries installed (pandas, anthropic).
2. Replace the placeholder API key with your actual Anthropic API key.
3. Prepare your input CSV file with a column containing the texts to analyze.
4. Run the script, specifying your input file name and column name.

The script will process each text and save the results to a new CSV file named 'stuff_with_analysis.csv'.

## Note

This project is for research purposes and demonstrates the application of AI in political science research. The accuracy and bias of the AI model itself should be considered when interpreting results.
