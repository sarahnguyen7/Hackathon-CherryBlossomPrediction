# Cherry Blossom Date Prediction
![Cherry Blossom](https://github.com/TasnimAhmedEee/Cherry-Blossom-Date-Prediction/blob/master/bloom-blossom.jpg)
 ## Introduction
 <p>
 In a year, sakura(Cherry) trees basically go through 4 phases: energy production, hibernation, growth, and of course flowering. These phases roughly follow the seasons, but not exactly.

Production phase： Initial development of the buds（Summer-Fall）
Hibernation phase： Bud growth stops while the tree goes into hibernation（Late Fall-Winter）
Growth phase： Buds once again continue to grow when the tree comes out of its winter hibernation（Late Winter-Spring）
Flowering phase： The buds finally bloom in spring (as climate conditions allow), once they have been able to fully develop.（Spring）

Each year, near the end of winter but before the trees finally bloom, the hibernation period ends. The sakura that rested through the winter once gain become metabolically active, and the buds continue to grow (though we may not immediately notice when this happens.) However, the cycle is not simply clockwork- for example, in places where the temperature is above 20℃ year-round, the trees are unable to hibernate sufficiently, and thus cannot blossom.</p>

## About the challenge
<p>
  In this challenge, we have outlined the basic mechanism by which the sakura(cherry) reach their eventual bloom-date. We consider building a bloom-date prediction model for the case of sakura in Tokyo, with the data split as follows:

Test years： 1966, 1971, 1985, 1994, and 2008
Training years: 1961 to 2017 (Excluding the test years)

You should fit the model to the weather-data(as feature) and bloom-date-data(as label) from the training years, then use the model to predict the bloom-date for each of the test years. This task has to be done by applying 3 different models:

1. 600 degree rule
2. Linear Regression
3. Neural Network

A brief description and specifications on each of these models are given in jupyter-notebook file: <b>problem.ipynb</b> The required weather-data and bloom-dates are given in the <b>datasets-folder</b>. The solution is given in <b>solution.ipynb</b> file.
</p>

Python Dependencies:

    NumPy
    Pandas
    Sklearn
    Tensorflow
    Matplotlib

## Point to be noted
Jupyter-notebook files are large and may not be displayed properly in GitHub
Use the online Notebook viewer: https://nbviewer.jupyter.org/ to view the notebooks
