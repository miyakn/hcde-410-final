# hcde-410-final
This study set out to explore the relationship between social media usage and consumer purchasing behavior. In particular, the study focused on identifying the demographic factors that influence this relationship and aimed to understand the types of social media platforms and product categories most associated with social media’s influence on purchase decisions.

Research Questions (in no particular order):
1. What demographic factors (age, gender, income, education level) have the strongest relationship with a consumer's purchase being influenced by social media?
2. Does the amount of social media platforms a consumer uses impact their spending habits?
3. Are there specific product categories where consumers are most likely to report that social media influenced their purchasing decisions?

I conducted chi-square tests of independence on the dataset and found that... 
* Age, gender, and income have statistically significant relationships with whether a consumer’s purchasing decisions are influenced by social media while education level did not exhibit a significant relationship.
* Among the social media platforms, Instagram emerged as the most statistically significant platform in relation to social media’s influence on a consumer’s purchase. Facebook and TikTok followed as the next most statistically significant platforms.
* The analysis of product categories revealed that electronics, home decor, and fashion/beauty were most frequently associated with social media-driven purchase decisions. 

Dataset used: https://www.kaggle.com/datasets/lastman0800/impact-of-social-media-dataset
Dataset license: “It can be used for various analyses and studies related to consumer behavior and marketing strategies in the context of social media influence.” (no specific license listed. The only form of licensing mentioned was in the description of the data, which is quoted here)

Packages
import csv
import pandas as pd
from scipy.stats import chi2_contingency
import matplotlib.pyplot as plt
import numpy as np
from IPython.display import display,HTML
from PIL import Image

