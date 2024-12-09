# hcde-410-final

The goal of this project is to investigate the relationship between social media and consumer behavior by identifying factors that influence spending decisions and what demographics that influence is strongest with. The research questions are (1) what demographic (age, gender, income, education level, level of social media usage, level of influence on social media, etc.) is most/least affected by social media in purchase decision-making, (2) does the amount of social media platforms a consumer uses impact their spending habits, and (3) are there certain categories of products where the consumers’ purchasing decisions are influenced by social media the most.

Dataset used: https://www.kaggle.com/datasets/lastman0800/impact-of-social-media-dataset
Dataset license: “It can be used for various analyses and studies related to consumer behavior and marketing strategies in the context of social media influence.” (no specific license listed. The only form of licensing mentioned was in the description of the data, which is quoted here)

Packages
from IPython.display import display,HTML
from PIL import Image
import csv
from scipy.stats import chi2_contingency
import numpy as np 
import matplotlib.pyplot as plt 