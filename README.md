# Exploratory Data Analysis and Dimensionality Reduction on Graduate Admission Dataset.

### Domain: Education

 **Problem Statement:**  What factors are affecting Graduate Admissions in America for Students? 

**Dataset:** Graduate Admission dataset on [Kaggle](https://www.kaggle.com/mohansacharya/graduate-admissions)

### **Data Fitness:** 
This dataset is choosen because it contains several parameters which are considered important during the application for Masters Programs. The parameters included are: 
   1. GRE Scores ( out of 340 ) 
   2. TOEFL Scores ( out of 120 ) 
   3. University Rating ( out of 5 ) 
   4. Statement of Purpose and Letter of Recommendation Strength ( out of 5 ) 
   5. Undergraduate GPA ( out of 10 ) 
   6. Research Experience ( either 0 or 1 ) 
   7. Chance of Admit ( ranging from 0 to 1 ).

*Although the dataset contains only 500 records, it is a very relevant dataset.*


### Analysis Code and Demo:
* **Exploratory Data Visualization of Graduate Admission Data set:** 
   * Performed data analysis and visualizationon various factors and their effect on Chances of getting an admit.
   * This involves interactive graphing using [Plotly](https://plot.ly) and [Cufflinks](https://plot.ly/ipython-notebooks/cufflinks/). Make sure you have that installed where you are trying to run the notebooks locally.
   ```pip install plotly```
   ```pip install cufflinks```
   * Demo: [HTML Webage](https://vinay-jaju.github.io/EDA-and-PCA-on-Graduate-Admission-Dataset/eda-using-cufflinks-plotly.html) | [Kaggle](https://www.kaggle.com/vinayjaju/eda-using-cufflinks-plotly?scriptVersionId=12904187)
   

* **Principal Component Analysis (PCA) and Visualization:** 
  
   * Demo involves both numpy and sklearn implementation
   * This is mainly performed to visualize the 6-D features in 2-D.
   * Demo: [HTML Webpage](https://vinay-jaju.github.io/EDA-and-PCA-on-Graduate-Admission-Dataset/pca-using-graduate-admissions-dataset.html) | [Kaggle](https://www.kaggle.com/vinayjaju/pca-using-graduate-admissions-dataset) 
   <!-- * *To do: Implement Dimensionality reduction using neural networks. Follow this tutorial [here](https://medium.com/@tomas.bouda/dimensionality-reduction-w-neural-nets-ddeeab548f12)* -->


### Analysis Summary:
* CPGA plays the most important role in admissions followed by GRE score and TOEFL.
* Good SOPs and LORs are essential to get into the best universities.
* Research makes your SOP and LOR better. No worries if you don't have research experience, you can still get admission
* Studious students generally tend to do good at GRE and TOEFL.

*The Analysis results are in accordance to the data given. To perform more analysis, it is essential that we have more records and features.*


**This repository is built for the Homework Assignment ( Data Visualization) of DataLit course.**
