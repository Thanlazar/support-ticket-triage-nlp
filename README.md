# Support Ticket Triage Optimization with NLP

## About the Project
In this project, I wanted to explore whether the text of support tickets can help predict their category.  
The idea was to build a simple NLP workflow and see how useful ticket text is for faster triage.

## Dataset
The dataset contains IT support tickets and their category labels.

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

## Tools
- Python
- pandas
- matplotlib
- scikit-learn
- Jupyter Notebook

## Project Files
- `data/` for the dataset files
- `notebooks/` for the analysis and modeling notebooks
- `outputs/` for plots and results

## Final Note
This project helped me better understand how text data can be explored, prepared, and used in a simple classification task.  
In the future, I would like to improve the preprocessing and compare more models.