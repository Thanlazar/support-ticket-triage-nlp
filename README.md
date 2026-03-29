# Support Ticket Triage Optimization with NLP

## About the Project
In this project, I wanted to explore whether the text of support tickets can help predict their category.  
The idea was to build a simple NLP workflow and see how useful ticket text is for faster triage.

## Dataset
Dataset source: Zenodo – Classification of IT Support Tickets

It contains 2,229 IT support tickets classified into 7 categories.  
The dataset is based on real support ticket data, is multilingual, and has been cleaned from personal information, which makes it a useful dataset for text classification practice.

## What I did
- loaded and explored the dataset
- checked the distribution of ticket categories
- looked at ticket text length
- checked for repeated ticket patterns
- built a baseline text classification model
- evaluated the model with standard metrics

## What I found
- the dataset contains 7 ticket categories
- Fileservice and Support general are the largest categories
- most tickets are short, but some are much longer
- many tickets follow repeated or template-like patterns
- the baseline model reached about 75.8% accuracy on the test set

## Results
- Baseline model accuracy: 75.8%
- Strong performance on Fileservice and EOL categories
- Several categories were often misclassified as Support general

## Tools
- Python
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook

## Project Files
- `01_data_loading.ipynb` for data loading and exploration
- `02_baseline_model.ipynb` for baseline modeling and evaluation
- `requirements.txt` for the main Python dependencies

## How to Run
1. Install the required libraries from `requirements.txt`
2. Open the notebooks in Jupyter Notebook
3. Download the dataset files from Zenodo and place them in a local folder before running the notebooks

## Final Note
This project helped me better understand how text data can be explored, prepared, and used in a simple classification task.  
In the future, I would like to improve the preprocessing and compare more models.