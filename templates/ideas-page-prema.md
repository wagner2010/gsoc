# Yellowbrick Ideas List

## Mentors

**Dr. Rebecca Bilbro** [@rebeccabilbro](https://github.com/rebeccabilbro), [Twitter](https://twitter.com/rebeccabilbro?lang=en), [LinkedIn](https://www.linkedin.com/in/rebeccabilbro), **Dr. Benjamin Bengfort** [@bbengfort](https://github.com/bbengfort), [Twitter](https://twitter.com/bbengfort?lang=en), [LinkedIn](https://www.linkedin.com/in/bbengfort), **Dr. Lawrence W. Gray** [@lwgray](https://github.com/lwgray), [Twitter](https://twitter.com/larrygray?lang=en), [LinkedIn](https://www.linkedin.com/in/larry-gray-phd), **Nathan Danielsen** [@ndanielsen](https://github.com/ndanielsen), [Twitter](https://twitter.com/nate_somewhere?lang=en), [LinkedIn](https://www.linkedin.com/in/nathandanielsen), **Prema Roman** [@pdamodaran](https://github.com/pdamodaran) [Twitter](https://twitter.com/premaroman), [LinkedIn](https://www.linkedin.com/in/premaroman), **Adam Morris** (Backup mentor) [@wagner2010](https://github.com/wagner2010), [Twitter](https://twitter.com/dsindc), [LinkedIn](https://www.linkedin.com/in/amorris2010)

## Welcome to Yellowbrick (Information for Students)
Welcome to [Yellowbrick](http://www.scikit-yb.org/en/latest/)!  We are glad you are here and we are excited about the prospect of working together this summer through [Google's 2019 Summer of Code](https://summerofcode.withgoogle.com) program.  So what is Yellowbrick?  [Yellowbrick](https://github.com/DistrictDataLabs/yellowbrick) is an open-source Python based visualization library that is designed to facilitate visualization and machine learning.  Yellowbrick is helpful for both performing exploratory data analysis and machine learning tasks (classification, regression, clustering and text based analysis, etc.). What sets Yellowbrick apart are its instructive visualizations which support a concept that we call [visual steering](http://www.scikit-yb.org/en/latest/gallery.html).  We strongly believe that these visualizations will provide data scientists the added value they need when they are working on their machine learning projects as it will help them better understand the data, improve their hyperparameter tuning, and will thereby help them obtain better results, all with Yellowbrick.  **Our goal is for Yellowbrick to become synonmyous with machine learning.  This is where you come in.**     
## About Us
Yellowbrick is an open-source Python based [NumFOCUS affiliated](https://numfocus.org/sponsored-projects/affiliated-projects) project supported by a core group of contributors primarily based in Washington, D.C. but with reach in Los Angeles and around the globe.  Yellowbrick was co-founded by Dr. Rebecca Bilbro [@rebeccabilbro](https://github.com/rebeccabilbro) and Dr. Benjamin Bengfort [@bbengfort](https://github.com/bbengfort)  when they saw a need for using visualization to help with the various machine learning tasks mentioned above.  Through our [GitHub](https://github.com/DistrictDataLabs/yellowbrick) we are able to contribute and interact with users worldwide.  We are a diverse, fun-loving group that values positivity, constructive feedback, respect, learning and support.  Every contribution, no matter its size and scope, matters to us and each contributor is important.  You can read more about our [Code of Conduct](http://www.scikit-yb.org/en/latest/code_of_conduct.html).  For an awesome slide deck primer on Yellowbrick, [click here](https://www.slideshare.net/BenjaminBengfort/visualizing-model-selection-with-scikityellowbrick-an-introduction-to-developing-visualizers)  
![the gang](https://github.com/wagner2010/gsoc/blob/e01958b9558930551a3518638a23244586db3610/templates/DsPMG9vXgAU7gnV.jpg?raw=true)
![the gang](https://github.com/wagner2010/gsoc/blob/e01958b9558930551a3518638a23244586db3610/templates/DdL3sHEX0AAXfX2.jpg)
![the gang](https://github.com/wagner2010/gsoc/blob/a46ec122e9eabebdfb3ca34960b48374391c5101/templates/DdQ25VNW0AA8RcQ.jpg-large.jpeg?raw=true)
#### Helpful Experience

Knowledge of Python is required to complete all projects.  Familiarity with machine learning and matplotlib is a plus.  We also value collaboration, communication and openness.

#### First steps (for all projects)
1. Follow and engage with us on Twitter [@scikit-yb](https://twitter.com/scikit_yb)
2. Check out our [GitHub repo](https://github.com/DistrictDataLabs/yellowbrick).  Don't forget to fork us and star us while you're there!   
3. Install Yellowbrick on your machine.  Details on how to do this can be found [here](https://github.com/DistrictDataLabs/yellowbrick#installing-yellowbrick).  
4. In order to get familiar with Yellowbrick, we recommend running our [examples](https://github.com/DistrictDataLabs/yellowbrick/blob/develop/examples/examples.ipynb) Jupyter Notebook.  
5. Read and work through our [quick start guide](https://github.com/DistrictDataLabs/yellowbrick/blob/master/docs/quickstart.rst).
6. Read the [contributor section](http://www.scikit-yb.org/en/latest/contributing.html).

## Project Ideas
So what are the projects that we have in mind for summer 2019?  Yellowbrick's current release version is at Version 0.9.  We have a road map and are highly motivated to get us to Version 1.0.  The following projects help us move towards that Version 1.0 mark by addressing key areas such as gridsearch, pipeline support, expanded tree based model support, improved PCA visualizer and marketing/promotion of Yellowbrick.  Our goals are to support you this summer while helping Yellowbrick advance forward. 
To help you navigate these projects, we have broken them down by topic area:

- [Gridsearch-expansion](#Gridsearch-expansion)
- [Pipeline-support](#Pipeline-support)
- [PCA-Visualizer-strengthening](#PCA-Visualizer-strengthening) 
- [Effect-Plot-for-linear-models](#Effect-Plot-for-linear-models)
- [Tree-based-models-support](#Tree-based-models-support)
- [Marketing-research-and-publication](#Marketing-research-and-publication)

## Gridsearch-expansion
###  Finish GridSearch Color Plot
#### Abstract

The student would work to complete testing, integration and documentation updating for gridsearch color plot.  This work is important because it will allow the user to use our color plot for gridsearch in order to get and enjoy a better experience when hyperparamater tuning (i.e. using cross validation). 

#### Technical Details
The student would complete a GridSearch Visualizer (includes finalizing the color plot) that was created in a prior issue [here](https://github.com/DistrictDataLabs/yellowbrick/pull/261).  For more information on this project, please reference this issue [here](https://github.com/DistrictDataLabs/yellowbrick/issues/308).

## Pipeline-support

###  Allow model visualizer to Wrap Pipeline objects
#### Abstract

The student would work to modify the ModelVisualizer [code](https://github.com/DistrictDataLabs/yellowbrick/blob/develop/yellowbrick/base.py#L274) to change the ModelVisualizer.estimator attribute to a @property - when setting the estimator property, we can perform a check to ensure that the Pipeline has a final_estimator attribute (e.g. that it is not a transformer pipeline).  The purpose of this work would be to expand the capacity and capability of the ModelVisualizer code to have support for Pipeline objects to be passed through.  As the code currently stands, Pipeline objects are not able to be passed in as a model because the pipeline object masks essential attributes needed by the visualizer.   

#### Technical Details
The student would work to change the ModelVisualizer.estimator attribute to a @property.  Please note however that we will still have to **fit(), predict(), and score()** on the entire pipeline, so this is a bit more nuanced than it seems on first glance. There will probably have to be **is_pipeline()** checking and other estimator access utilities.  For more information on this project, please reference this issue by clicking [here](https://github.com/DistrictDataLabs/yellowbrick/issues/498).

## PCA-Visualizer-strengthening
###   Enhance Principal Component Analysis (PCA) Decomposition
#### Abstract

The student would work to upgrade the existing PCA Visualizer by adding a number of individual enhancements is needed to make its functionality more robust abnd meaningful for users also while increasing its flexibility to handle random state.

#### Technical Details
The student would work to add a list of enhancements to our Principal Component Analysis (PCA) Visualizer that are detailed in this issue (Color points by class with a legend) (See the relavant issue by clicking [here](https://github.com/DistrictDataLabs/yellowbrick/issues/458)): 
- Color points by heatmap for continuous y and add a colorbar 
- add alpha parameter see the related issue by clicking [here](https://github.com/DistrictDataLabs/yellowbrick/issues/475) 
- add random state to pass to PCA 
- allow user to pass in a PCA transformer/pipeline 
- update tests with better random data sets (more points; see manifold tests) 
- include explained variance/noise variance (or explained variance ratio) in chart 
- enance biplots in documentation. For more information on this project, please reference this issue [here](https://github.com/DistrictDataLabs/yellowbrick/issues/476).  

###  Extend PCA Visualizer with Component-Feature Strength
#### Abstract

The student's work to extend the PCA visualizer by providing an optional heat map and color bar will further pinpoint the magnitude of each feature principal component more clearly than is capable currently (by providing the extra information).   

#### Technical Details
Provide an optional heatmap and color bar underneath the PCA visualizer (by shifting the lower axes) that shows the magnitude of each feature value to the component. This provides an explanation of which features are contributing the most to which component.  More information about this project can be found [here](https://github.com/DistrictDataLabs/yellowbrick/issues/615). 

## Effect-Plot-for-linear-models
### Create Effect Plot for linear models 
#### Abstract

An effect plot is a visual tool that aids in interpreting linear models. The purpose of the effect plot is to aid the user in the task of interpreting linear model results.  The effect plot shows weights as a bar plot so that users can see the impact and size of the variance.  The student would work to create an effect plot to better interpret regression and linear models by showing the associated weights.  

#### Technical Details
An effect plot is a visual tool that aids in interpreting linear models.  It shows the weights as a bar plot so you can see whether the impact is positive or negative and also how large the variance is.  An example of an effect plot can be found [here](https://christophm.github.io/interpretable-ml-book/limo.html#visual-parameter-interpretation).  More information about this project can be found [here](https://github.com/DistrictDataLabs/yellowbrick/issues/604).

## Tree-based-models-support
###  Add Support for Probabilistic Calibration Curve for Tree-based Models.
#### Abstract

The student would work to add a Probabilistic Calibration Curve Visualizer for Tree-based Models.  The purpose and importance of probabilistic calibration curves are to help provide the extra information needed to instill a higher level of confidence for the user and to provide greater comparability as they can be visualized across multiple models.  The goal is to help the user make the best possible model selection based on reliability indicators.  The student's work will help improve the user's confidence in their class label and compare results across multiple models. 

#### Technical Details
The student will work to create a new feature for generating calibration curves via class CalibrationCurve (subclassing ClassificationScoreVisualizer).  The student will implement the **fit(), score(), and poof()** methods that creates a main calibration curve graph and a mean predicted value line graph.  See the class-balance documentation by clicking [here](http://www.scikit-yb.org/en/latest/api/classifier/class_balance.html) and the initial probability calibration curve issue by clicking [here](https://github.com/DistrictDataLabs/yellowbrick/issues/365).

## Marketing-research-and-publication
###  Write a blog post highlighting Yellowbrick for a Machine Learning project.
#### Abstract

The student would write a blogpost highlighting Yellowbrick for a machine learning project using a data source/domain of her choice.  The purpose of this project is for the student to use a machine learning task (i.e. regression, classification, clustering etc.) and dataset(s) of her choice to highlight Yellowbrick in your machine learning workflow.  As long as sound data science principles are applied, we give wide latitude for content and machine learning tasks applied (i.e. a traditional blogpost, a YouTube video series, etc.).  

#### Technical Details
The student would write a blog post based upon a data science project highlighting Yellowbrick for machine learning and visualization.  The student would go through the data science pipeline (problem statement, hypothesis, ingestion, storage, wrangling, statistical exploration, model selection, machine learning and visualization).  The blog post would center around this process.  For more information on this project, please reference this issue by clicking [here](https://github.com/DistrictDataLabs/yellowbrick/issues/691).
