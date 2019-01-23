# Yellowbrick Ideas List

## Mentors

Dr. Rebecca Bilbro [@rebeccabilbro](https://github.com/rebeccabilbro), Dr. Benjamin Bengfort [@bbengfort](https://github.com/bbengfort), Dr. Lawrence W. Gray [@lwgray](https://github.com/lwgray), Nathan Danielsen [@ndanielsen](https://github.com/ndanielsen), Adam Morris (Backup mentor) [@wagner2010] (https://github.com/wagner2010)

## Welcome to Yellowbrick (Information for Students)
Welcome to [Yellowbrick](http://www.scikit-yb.org/en/latest/)!  We are glad you're here and we're excited about the prospect of working together this summer through Google's 2019 Summer of Code (https://summerofcode.withgoogle.com) program.  So what is Yellowbrick?  [Yellowbrick] (https://github.com/DistrictDataLabs/yellowbrick) is a completely open-sourced Python based visualization library that is designed to facilitate visualization and machine learning.  Yellowbrick is helpful for performing exploratory data analysis, machine learning tasks (classification to regression to clustering and text based analysis). What sets Yellowbrick apart are our instructive visualizations which support a concept that we call [visual steering](http://www.scikit-yb.org/en/latest/gallery.html).  We strongly believe that these visualizations will provide data scientists the added value when they are doing their machine learning that can help them better see the data, improve their hyperparameter tuning and thereby obtain better results.  **Our goal is to become synonmyous with machine learning.  This is where you come in.**     
## About Us
Yellowbrick is an open-sourced Python based project supported by a core group of contributors primarily based in Washington, D.C. but with reach in Los Angeles and around the globe.  Through our GitHub we are able to contribute with and interact with users worldwide.  We are a diverse fun loving group that values positivity, constructive feedback, respect, learning and support.  Every contribution, no matter its size and scope, matters to us and each contributor is important.  You can read more about our Code of Conduct here (http://www.scikit-yb.org/en/latest/code_of_conduct.html).  
## Project Ideas

###  Idea Title 
Extend PCA Visualizer with Component-Feature Strength
#### Abstract

Provide an optional heatmap and color bar underneath the PCA visualizer (by shifting the lower axes) that shows the magnitude of each feature value to the component.

| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Moderate}}                          | {{ Medium}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details
Provide an optional heatmap and color bar underneath the PCA visualizer (by shifting the lower axes) that shows the magnitude of each feature value to the component. This provides an explanation of which features are contributing the most to which component.  More information about this project can be found [here](https://github.com/DistrictDataLabs/yellowbrick/issues/615)


###  Idea Title 
Create Effect Plot for Linear Models 
#### Abstract

An effect plot is a visual tool that aids in interpreting linear models.


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Moderate}}                          | {{ Medium}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details
An effect plot is a visual tool that aids in interpreting linear models.  It shows the weights as a bar plot so you can see whether the impact is positive or negative and also how large the variance is.  An example of an effect plot can be found here (https://christophm.github.io/interpretable-ml-book/limo.html#visual-parameter-interpretation).  More information about this project can be found at (https://github.com/DistrictDataLabs/yellowbrick/issues/604)

###  Idea Title 
Add Support for Probabilistic Calibration Curve
#### Abstract

The student would work to add a Probabilistic Calibration Curve Visualizer for Treebased Models.


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Novice}}                            | {{ Low}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details
The student will work to create a new feature for generating calibration curves via class CalibrationCurve (subclassing ClassificationScoreVisualizer).  The student will implement the fit(), score(), and poof() methods that creates a main calibration curve graph and a mean predicted value line graph.  See http://www.scikit-yb.org/en/latest/api/classifier/class_balance.html and the initial probability calibration curve issue (https://github.com/DistrictDataLabs/yellowbrick/issues/365).

###  Idea Title 
Write blogpost highlighting Yellowbrick for a Machine Learning project.
#### Abstract

The student would write a blogpost highlighting Yellowbrick for a Machine Learning Project using a data source/domain of her choice.


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Novice}}                            | {{ Medium}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details
The student would write a blogpost based upon a data science project highlighting Yellowbrick for machine learning and visualization.  The student would go through the data science pipeline (problem statement, hypothesis, ingestion, storage, wrangling, statistical exploration, model selection, machine learning and visualization).  The blog post would center around this process.  For more information on this project, please reference this issue (https://github.com/DistrictDataLabs/yellowbrick/issues/691).

###  Idea Title 
Finish GridSearch Color Plot
#### Abstract

The student would complete a GridSearch Visualizer's steps as follows: create a test file and run tests, create integration tets by generating basic visualizations using the gridsearch visualizer and update documentation to include all features. 


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Medium}}                            | {{ High}} | {{ }}         | {{ [@foo][], [@bar][] }} |

#### Technical Details
The student would complete a GridSearch Visualizer (includes finalizing the color plot) that was created in a prior issue (https://github.com/DistrictDataLabs/yellowbrick/pull/261).  More examples and information can be    For more information on this project, please reference this issue (https://github.com/DistrictDataLabs/yellowbrick/issues/308).

###  Idea Title 
Allow model visualizer to Wrap Pipeline objects
#### Abstract

The student would work to modify the ModelVisualizer 
(https://github.com/DistrictDataLabs/yellowbrick/blob/develop/yellowbrick/base.py#L274) to change the ModelVisualizer.estimator attribute to a @property - when setting the estimator property, we can perform a check to ensure that the Pipeline has a final_estimator attribute (e.g. that it is not a transformer pipeline). 


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Medium}}                            | {{ Medium}} | {{ }}         | {{ [@foo][], [@bar][] }} |

#### Technical Details
The student would work to change the ModelVisualizer.estimator attribute to a @property.  NOTE however that we will still have to fit(), predict(), and score() on the entire pipeline, so this is a bit more nuanced than it seems on first glance. There will probably have to be is_pipeline() checking and other estimator access utilities.  For more information on this project, please reference this issue (https://github.com/DistrictDataLabs/yellowbrick/issues/498).

###  Idea Title 
Enhance Principal Component Analysis (PCA) Decompisition
#### Abstract

The student would work to upgrade the existing PCA Visualizer by adding a number of individual enhancements (i.e. color points by class, color points by heatmap, allow user to pass in a PCA transformer/pipeline etc.)


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Medium}}                            | {{ Medium}} | {{ }}         | {{ [@foo][], [@bar][] }} |

#### Technical Details
The student would work to add a list of enhancements to our Principal Component Analysis (PCA) Visualizer that are detailed in this issue ( Color points by class with a legend (See #458) (https://github.com/DistrictDataLabs/yellowbrick/issues/458), Color points by heatmap for continuous y and add a colorbar, add alpha parameter see #475(https://github.com/DistrictDataLabs/yellowbrick/issues/475), add random state to pass to PCA, allow user to pass in a PCA transformer/pipeline, update tests with better random data sets (more points; see manifold tests) and include explained variance/noise variance (or explained variance ratio) in chart, and finally enance biplots in documentation. For more information on this project, please reference this issue (https://github.com/DistrictDataLabs/yellowbrick/issues/476).  

###  Idea Title 
Extend PCA Visualizer with Component-Feature Strength
#### Abstract

The student would work to provide an optional heatmap and color bar underneath the PCA visuaqlizer (by shifting the lower axes) that highlights the magnitude of each feature value to the component.


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Medium}}                            | {{ Medium}} | {{ }}         | {{ [@foo][], [@bar][] }} |

#### Technical Details
Provide an optional heatmap and color bar underneath the PCA visualizer (by shifting the lower axes) that shows the magnitude of each feature value to the component. This provides an explanation of which features are contributing the most to which component. For more information on this project, please reference this issue  (https://github.com/DistrictDataLabs/yellowbrick/issues/615).  


#### Helpful Experience

Knowledge of Python is required to complete this project.  Familiarity with machine learning and matplotlib is a plus.

#### First steps

1.)Install Yellowbrick on your machine.  Details on how to do this can be found here (https://github.com/DistrictDataLabs/yellowbrick#installing-yellowbrick).  
2.)In order to get familiar with Yellowbrick, we recommend checking out examples here (https://github.com/DistrictDataLabs/yellowbrick/blob/develop/examples/examples.ipynb).  
3.)We also have a quick start guide (https://github.com/DistrictDataLabs/yellowbrick/blob/master/docs/quickstart.rst).
4.)Please read the contributor section (http://www.scikit-yb.org/en/latest/contributing.html)
