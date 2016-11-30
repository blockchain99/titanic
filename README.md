# titanic
In 1912, the ship RMS Titanic struck an iceberg on its maiden voyage and sank, resulting in the deaths of most of its passengers and crew. In this introductory project, we will explore a subset of the RMS Titanic passenger manifest to determine which features best predict whether someone survived or did not survive. 

In this project, I used decision tree, which splits a set of data into smaller and smaller groups (called nodes), by one feature at a time. Each time a subset of the data is split, our predictions become more accurate if each of the resulting subgroups are more homogeneous (contain similar labels) than before.

This model, decision tree is one of supervised learnig. In supervised learning, we attempt to use features of the data to predict or model things with objective outcome labels. That is to say, each of our data points has a known outcome value, such as a categorical, discrete label like 'Survived', or a numerical, continuous value like predicting the price of a house.

### Data 
Data for this project is privided as student-data.csv, which is in https://github.com/blockchain99/titanic
in_file = 'titanic_data.csv'
full_data = pd.read_csv(in_file)

### Installation and usage

Program is written in python 2.7, it one may need anaconda shoulde be installed(including numpy, scipy, pandas, matplotlib, jupyter) ( https://docs.continuum.io/anaconda/install ) or install python 2.7 and then install Numpy, Scipy, Pandas, matplotlib,jupyter manually as follows.

sudo pip install numpy scipy matplotlib
after anaconda installed , one may need to jupyter run, by type in command line and hit the enter. > jupyter notebook and then upload and select Titanic_Survival_Exploration_yoonsu.ipynb in web page.

### Meta

Yoonsu Park - http://www.patternics.com Distributed under the MIT license. See LICENSE for more information( https://en.wikipedia.org/wiki/MIT_License ). https://github.com/blockchain99/titanic
