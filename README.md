# PS2
## Project information
- **Author**: Runkun Guo, Applied Mathematics, 2023 , Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2023 Spring Term (Seven Week - First) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: [How to Acknowledge?](https://www.scribbr.co.uk/thesis-dissertation/acknowledgements/)
[notes: please include all professors, students, and staff who have contributed to your completetion of the project.]
- **Project Summary**: 
  - Background: To predict the outcome of a certain soccer match may have a petential commercial value. We tried to find the correlation between the total number of shooting and the total number of goals in a match as a part of outcome of a match. Not many scholars are still doing research on this quite traditional gambling game theory. Thus, I want to make some improvements to this field.
  - Research Question: Does the number of shootings has correlation with the number of goals in a certain soccer match?
  - Data Source: I use the data queried from football.data.co.uk website which is a gambling website that records all the historical data for football matches in UK
  - Methods: I tried to use linear regression to predict the total numner of goals given a number of shooting and I also tried Ramdom forest Regression. Besides, I also consider the number of goals as a group of classes and I use Decision Tree Classifier to get the confusion matrix.
  - Results: From the Regression part, I found out that the accuracy of Random Forest Regression is only 19.49%. For the decision tree classification, the accuracy of f1 score is 22%. I may conclude that there's no direct or few connection between the total number of shooting and the number of goals.
  - Intellectual Merits: The result is quite opposite to my expectation that this two variables have few connections. In the beginging, I found out that the accuracy of regression is not very high, thus I try to make the discrete number as different classes and use the Decision Tree Classifier to make a prediction. However, the accuracy is still ideal enough. Therefore, based on my simulation resultes, I could only conclude my X and Y have few connections now. In the future, I may try to make my data more suitable for the models and may try to consider the discrete number into one-hot code for classification part to improve the accuracy

## Table of Contents
- [data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Runkun_Guo/tree/main/data)
- [code](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Runkun_Guo/tree/main/Code)
- [spotlight](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Runkun_Guo/tree/main/spotlight)


## Data
- [Data Source](https://www.football-data.co.uk/data.php)
- [Queried Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Runkun_Guo/blob/main/data/E0.csv)
- [Processed Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Runkun_Guo/tree/main/data/Data)



## Code
- [Query Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Runkun_Guo/blob/main/Code/Query_Data_Runkun_Guo.ipynb)
- [Process Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Runkun_Guo/blob/main/Code/Process_Data_PrepareX%26Y_Variable_Runkun_Guo.ipynb)
- [Analyze Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Runkun_Guo/blob/main/Code/“Analyze_Data_Predicting_Runkun_Guo_ipynb”.ipynb)

## Spotlight


## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

