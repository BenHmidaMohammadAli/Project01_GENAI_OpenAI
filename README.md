# Project01_GENAI_OpenAI
# Sentiment Classification Script

This script uses OpenAI's GPT-3.5-turbo model to classify the sentiment of given text reviews as either positive or negative.

## Requirements

- Python 3.6+
- `openai` library

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/BenHmidaMohammadAli/Project01_GENAI_OpenAI.git
    cd Project01_GENAI_OpenAI
    ```

2. Install the required libraries:

    ```bash
    pip install openai
    ```

3. change OPENAI_API_KEY variable with your OpenAI API key :

    ```bash
    OPENAI_API_KEY =  " API KEY "
    ```

## Usage

1. Update the list of reviews in the script as needed:

    ```python
    reviews = [
        'The mochi is excellent!',
        'Best soup dumplings I have ever eaten.',
        'Not worth the 3 month wait for a reservation.',
        'The colorful tablecloths made me smile!',
        'The pasta was cold.'
    ]
    ```

2. Run the next cells:


3. The script will output the sentiment for each review:

    ```plaintext
    Review: The mochi is excellent!
    Sentiment: positive

    Review: The colorful tablecloths made me smile!
    Sentiment: positive

    Review: The pasta was cold.
    Sentiment: negative
    ```

