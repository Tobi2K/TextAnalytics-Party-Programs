# Semi-automatic evaluation of German party manifestos

### Requirements:

Install all requirements with pip:
> pip install -r .\requirements.txt

### Structure

* **topic_classification.ipynb**
    * The final pipeline for classification and summarization (final result)
* **classification**
    * Different approaches for the classification
* **data_exploration**
    * All files used to find out different properties of the data
* **diagrams**
    * A selection of graphics for different presentations
* **resources**
    * Here are the party programs of the German parties for the year 2021 in text form
* **summary**
    * The code for the extractive summarization
* **website**
    * Source code of the webpage: [https://tadl.kalmbach.dev](https://tadl.kalmbach.dev)

---

### Distribution of work

Generally, we tried to work in groups, so the following is an approximation, of which persons are mainly responsible for
the corresponding files. The distribution of work on our paper can be found in the appendix of the paper.

* Tobias Kalmbach
    * [resource_statistics.ipynb](data_exploration/resource_statistics.ipynb)
    * [resource_statistics.py](data_exploration/resource_statistics.py)
    * [text_summarization.ipynb](summary/text_summarization.ipynb)
    * [website](website)

* Fabian Karl
    * [topic_modeling_playground.ipynb](data_exploration/topic_modeling_playground.ipynb)
    * [custom_stopwords.txt](data_exploration/custom_stopwords.txt)
    * [topic_classification.ipynb](topic_classification.ipynb)

* Tim Knittel
    * [bert_cosine_similarity.ipynb](classification/bert_cosine_similarity.ipynb)
    * [bertopic.ipynb](classification/bertopic.ipynb)

* Nicolas Zellner
    * [Preprocessing.py](data_exploration/Preprocessing.py)
    * [hirarchical_dirichlet.ipynb](classification/hirarchical_dirichlet.ipynb)

### Notes

* This project was created on [github](https://github.com/Supelir1/TextAnalytics)