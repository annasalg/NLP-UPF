# README

Code repository for Laura Moset Estruch & Anna Lívia Salgueiro's exercise on Zipf’s Law of Abbreviation for the course Natural Language Processing at UPF (2024)

### Requirements

The code is written using Python in Colab's version published on 2024-01-29. Thus, the authors recommend also using Colab for easier and better performance.
You can access the original Colab with this [link](https://colab.research.google.com/drive/1jOqb-YKAMgCCsBTWl_6a5MDxhVn37-N3).

Packages required:
* Downloading the datasets:
   * gdown
* Preprocessing and tokenization:
   * re
   * spacy
      * en_core_web_sm
      * es_core_news_sm
* Counting frequency:
   * collections
* Visualizations:
   * pandas
   * matplotlib.pyplot
   * seaborn
   * adjustText

### Data
The txt files are automatically downloaded when the code is run using _gdown_.
>[!NOTE]
>If there is any problem with the download, the files are also provided in this repository as "mecano_lyrics.txt" and "tswift_lyrics.txt".
