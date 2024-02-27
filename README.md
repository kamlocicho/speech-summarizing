# Speech Summarizer App

This Jupyter notebook contains a simple app for summarizing speeches or text documents. The app utilizes natural language processing techniques to generate concise summaries of longer texts.

## Installation

1. Clone the repository:

    ```
    git clone https://github.com/kamlocicho/speech-summarizing.git
    ```

2. Navigate into the project directory:

    ```
    cd speech-summarizing
    ```

3. Open the Jupyter notebook `summarizing-speeches.ipynb` or `summarizing-gensim.ipynb` to access and run the code.

## Usage

1. Ensure you have the speech text file or the text you want to summarize.

2. Open one of the Jupyter notebooks.

3. Follow the instructions provided in the notebook to execute the code cells.

4. Feel free to switch url variable with URL to your favorite speech!

5. The notebook will then generate a summary of the speech using natural language processing techniques.

## Methodology

The app uses techniques such as:

### Text Preprocessing
The speech text undergoes preprocessing steps such as tokenization, removing stop words, and punctuation.

### Sentence Scoring
Sentences in the speech are scored based on their importance using algorithms such as TF-IDF (Term Frequency-Inverse Document Frequency) or TextRank.

### Summary Generation
The sentences with the highest scores are selected to form the summary, ensuring that important points from the speech are included.

