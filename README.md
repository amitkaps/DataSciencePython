# Introduction to Data Science using PyData Stack

Main Objectives of the workshop:

1. What is data analysis?
2. How to approach a data analysis problem?
3. What are the various questions one can ask given data? 
4. How to perform data analysis and gain insights?.

By the end of the workshop, the attendees should be able to take a dataset and be confident to perform data analysis in a scientific manner using Python.

The following steps need to be followed to understand how to do data analysis/data analytics

**Introduction** \- "I think, therefore I am"
* What is data analysis?
* What type of questions can be answered?
* Developing a hypothesis drive approach.
* Making the case.

**Acquire** \- "Data is the new oil"
* Download from an internal system
* Obtained from client, or other 3rd party
* Extracted from a web-based API
* Scraped from a website
* Extracted from a PDF file
* Gathered manually and recorded

**Refine** \- "Data is messy"
* Missing e.g. Check for missing or incomplete data
* Quality e.g. Check for duplicates, accuracy, unusual data
* Parse e.g. extract year from date
* Merge e.g. first and surname for full name
* Convert e.g. free text to coded value
* Derive e.g. gender from title
* Calculate e.g. percentages, proportion
* Remove e.g. remove redundant data
* Aggregate e.g. rollup by year, cluster by area
* Filter e.g. exclude based on location
* Sample e.g. extract a representative data
* Summary e.g. show summary stats like mean

**Explore - "I don't know, what I don't know"**
* Why do visual exploration?
* Understand Data Structure & Types
* Explore single variable graphs - (Quantitative, Categorical)
* Explore dual variable graphs - (Q & Q, Q & C, C & C)
* Explore multi variable graphs

**Model** \- "All models are wrong, Some of them are useful"
* The power and limits of models
* Tradeoff between Prediction Accuracy and Model Interpretability
* Assessing Model Accuracy
* Regression models (Simple, Multiple)
* Classification model

**Insight** \- "The goal is to turn data into insight"
* Why do we need to communicate insight?
* Types of communication - Exploration vs. Explanation
* Explanation: Telling a story with data
* Exploration: Building an interface for people to find stories

**Types of Data Analysis/Analytics Question:**

* **Descriptive** \- "seeks to summarize a characteristic of a set of data"
* **Exploratory** \- "analyze the data to see if there are patterns, trends, or relationships between variables" (hypothesis generating)
* **Inferential** \- "a restatement of this proposed hypothesis as a question and would be answered by analyzing a different set of data" (hypothesis testing)
* **Predictive** \- "determine the impact on one factor based on other factor in a population - to make a prediction"
* **Causal** \- "asks whether changing one factor will change another factor in a population - to establish a causal link"
* **Mechanistic** \- "establish how the change in one factor results in change in another factor in a population - to determine the exact mechanism"

In this workshop, we take a dataset and go through many of the steps listed above.

Instead of introducing libraries, our approach is to introduce the problem and provide the approach on how to solve it. As we go about solving the problem(s), we will introduce a number of libraries commonly used in the Python data stack (`numpy`, `pandas`, `matplotlib`, `seaborn`, `scipy` etc).

The repository has instructions on what packages to install and the data we would be using for the workshop. Please see the [installation](installation.md) file for detailed installation instructions. That also has instructions on how to run a script to check if the required packages are installed.  From our prior experience, attendees have been able to install the requirements on Windows, Linux and Mac without any issue. We strongly advise attendees to install the requirements prior to the workshop. If faced with a bug or challenge, please submit an issue on the repo.

---

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Introduction to Data Science in Python</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://twitter.com/amitkaps/" property="cc:attributionName" rel="cc:attributionURL">Amit Kapoor</a> , <a xmlns:cc="http://creativecommons.org/ns#" href="https://twitter.com/bargava/" property="cc:attributionName" rel="cc:attributionURL">Bargava</a> and <a xmlns:cc="http://creativecommons.org/ns#" href="https://twitter.com/nischalhp/" property="cc:attributionName" rel="cc:attributionURL">Nischal</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.

