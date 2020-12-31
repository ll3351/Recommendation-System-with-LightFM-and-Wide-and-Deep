<p align="center">
  <a href="https://github.com/ds-personalization/final-project-finalproject_zz_hjw_why_llhy">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>
  <h3 align="center">Final Project</h3>
  <p align="center">
    BUILDING A HYBRID RECOMMENDER SYSTEM 
    <br />
    <em>By Team FinalProject_zz_hjw_why_llhy</em>
    <br />
    ·
    <a href="https://github.com/ds-personalization/final-project-finalproject_zz_hjw_why_llhy/blob/main/Report_of_final_project.ipynb">View Notebook</a>
  </p>





## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
  * [Installation](#installation)
  * [Open Notebook](#open-notebook)
* [Analysis](#Analysis)
* [Contributors](#Contributors)
* [Contact](#contact)



## About The Project

Our report provides an analysis and evaluation of a new recommendation system for recommending Top 50 movies to existing valuable users, who have rated over 20 movies. Sequential hybrid models are used, which includes lightFM as basic recommendation algorithm, ANN and a powerful Wide & Deep model as reorder model. Our main evaluation metric is Precision@K and NDCG, but we also consider diversity, novelty and coverage.

Our recommendation system could beat the original MF and Item-based collaborative filtering model in all metrics we care about. Besides high performance on the same metric, the new system could deal with cold-start problems by combining content information in lightFM and Wide & Deep models.

Our experiments find the best parameter combination for each model. In order to run cross validation successfully on large dataset, we create seperate scripts to run cross Validation for Deep & Wide model.

Based on evaluation results, compared with the single model we experimented in last homework, our models performed better. Also, with the help of ANN, we improved the recommendation efficiency. In the end, we trained the whole pipeline in a large dataset and used results as final recommendations.



## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo and change to directory
```sh
git clone https://github.com/ds-personalization/final-project-finalproject_zz_hjw_why_llhy.git
cd final-project-finalproject_zz_hjw_why_llhy
```
2. Install requirements
```sh
pip install -r requirement.txt
````

### Open Notebook 

Open our notebook and show all results

```sh
jupyter notebook Report_of_final_project.ipynb
```



## Analysis

We generally provide our analysis in our report with all the code showing how to reach our results. The report is divided into 12 parts -- Executive Summary, Objective Statement, Evaluation criteria, Module and Method, Sampling, Train Test Split, EDA, Baseline Model, The detailed building and Analysis of each model in new hybrid system, Whole pipeline of new hybrid system, Model Comparision, and Use case : Online presentting final recommendation for a single user.

_For more details, please refer to the [Documentation](https://github.com/ds-personalization/final-project-finalproject_zz_hjw_why_llhy/blob/main/Report_of_final_project.ipynb)_




## Contributors

Zi Zhuang - zz2693 - zz2693@columbia.edu

Jiawen Huang - jh4179 - jh4179@columbia.edu

Hanyu Wu - hw2753 - hw2753@columbia.edu

Liuhaoyue Li - ll3351 - ll3351@columbia.edu



## Contact

You can contact any one of us for more information.

Project Link: https://github.com/ds-personalization/final-project-finalproject_zz_hjw_why_llhy


