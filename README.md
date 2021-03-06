# Kickstarter_DataAnalysis
## Summary
I chose to do this project because Kickstarter is an interesting platform for both fund seekers and backers. It's a nice platform to check out for innovative ideas and projects, and I would like to have better understanding of Kickstarter.

## Data
Dataset: 'ks-projects-201801'<br>
From: Kaggle, https://www.kaggle.com/kemical/kickstarter-projects

I mainly used Pandas, Numpy to do analysis, and Matplotlib, Seaborn and Plotly to create visualizations about the Kickstarter projects in order to gain interesting insights.

## Python Notebook Viewer
Link to IPython Notebook Viewer: http://nbviewer.jupyter.org/github/gloriadai/Kickstarter_DataAnalysis/blob/master/KickStarter_Analysis.ipynb

## Key Visualizations
Below are few key visualizations that give an overall idea of the Kickstarter projects: 
  - What are the projects?
  - Where are the projects from? 
  - How the projects are doing?

### 1. What are the projects?
<p align="center">
  <img src="Visualization_Images/3.%20Wordcloud%20-%20percentage.png" width="500"></div>
</p>

Number of Projects Seeking Funds Each Category By Year
<p align="center">
  <img src="Visualization_Images/2.%20Number%20of%20Projects%20Seeking%20Funds%20Each%20Category%20By%20Year.png" width="500"></div>
</p>


As we can see from the above:
  - Overall project counts boost in 2014&2015
  - Overall project counts decreased in 2016
  - Film & Video has always been a popular category
  - Technology increase dramatically in 2014&2015

### 2. Where are the projects from?
<p align="center">
  <img src="Visualization_Images/5.%20Map%20-%20Partial.png" width="500"></div>
</p>

The above map shows:
  - Majority fund seekers are from US. Great Britain and Canada follows.
  - Some countries are missing. China, Russia, India, etc. Might due to policy issues.

### 3. How the projects are doing?
<p align="center">
  <img src="Visualization_Images/6.%20Propotion%20of%20Projects%20by%20Status.png" width="500"></div>
</p>

From the pie chart, we see:
  - Suprisingly, most projects failed than successed. :(
