# Yellowbrick Ideas List

## Mentors

Dr. Rebecca Bilbro, Dr. Benjamin Bengfort, Larry W. Gray, Adam Morris (Backup mentor)
## Information for Students 

## Project Ideas

###  Idea Title 
Extend PCA Visualizer with Component-Feature Strength
#### Abstract

Provide an optional heatmap and color bar underneath the PCA visualizer (by shifting the lower axes) that shows the magnitude of each feature value to the component.

| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Moderate}}                          | {{ Medium}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details
Provide an optional heatmap and color bar underneath the PCA visualizer (by shifting the lower axes) that shows the magnitude of each feature value to the component. This provides an explanation of which features are contributing the most to which component.  More information about this project can be found at (https://github.com/DistrictDataLabs/yellowbrick/issues/615)

#### Helpful Experience

Knowledge of Python is required to complete this project.  Familiarity with machine learning and matplotlib is a plus.

#### First steps

1.)Install Yellowbrick on your machine.  Details on how to do this can be found here (https://github.com/DistrictDataLabs/yellowbrick#installing-yellowbrick).  
2.)In order to get familiar with Yellowbrick, we recommend checking out examples here (https://github.com/DistrictDataLabs/yellowbrick/blob/develop/examples/examples.ipynb).  
3.)We also have a quick start guide (https://github.com/DistrictDataLabs/yellowbrick/blob/master/docs/quickstart.rst).
4.)Please read the contributor section (http://www.scikit-yb.org/en/latest/contributing.html)

###  Idea Title 
Create Effect Plot for Linear Models 
#### Abstract

An effect plot is a visual tool that aids in interpreting linear models.


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Moderate}}                          | {{ Medium}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details
An effect plot is a visual tool that aids in interpreting linear models.  It shows the weights as a bar plot so you can see whether the impact is positive or negative and also how large the variance is.  An example of an effect plot can be found here (https://christophm.github.io/interpretable-ml-book/limo.html#visual-parameter-interpretation).  More information about this project can be found at (https://github.com/DistrictDataLabs/yellowbrick/issues/604)

#### Helpful Experience

Knowledge of Python is required to complete this project.  Familiarity with machine learning and matplotlib is a plus.

#### First steps

1.)Install Yellowbrick on your machine.  Details on how to do this can be found here (https://github.com/DistrictDataLabs/yellowbrick#installing-yellowbrick).  
2.)In order to get familiar with Yellowbrick, we recommend checking out examples here (https://github.com/DistrictDataLabs/yellowbrick/blob/develop/examples/examples.ipynb).  
3.)We also have a quick start guide (https://github.com/DistrictDataLabs/yellowbrick/blob/master/docs/quickstart.rst).
4.)Please read the contributor section (http://www.scikit-yb.org/en/latest/contributing.html)

###  Idea Title 
Add FeatureImportance Visualizer for Treebased Models
#### Abstract

The student would work to add a FeatureImportance Visualizer for Treebased Models.


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Novice}}                          | {{ High}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details


#### Helpful Experience

Knowledge of Python is required to complete this project.  Familiarity with machine learning and matplotlib is a plus.

#### First steps

1.)Install Yellowbrick on your machine.  Details on how to do this can be found here (https://github.com/DistrictDataLabs/yellowbrick#installing-yellowbrick).  
2.)In order to get familiar with Yellowbrick, we recommend checking out examples here (https://github.com/DistrictDataLabs/yellowbrick/blob/develop/examples/examples.ipynb).  
3.)We also have a quick start guide (https://github.com/DistrictDataLabs/yellowbrick/blob/master/docs/quickstart.rst).
4.)Please read the contributor section (http://www.scikit-yb.org/en/latest/contributing.html)

###  Idea Title 
Add Support for Probabilistic Calibration Curve
#### Abstract

The student would work to add a Probabilistic Calibration Curve Visualizer for Treebased Models.


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Novice}}                            | {{ Low}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details
The student will work to create a new feature for generating calibration curves via class CalibrationCurve (subclassing ClassificationScoreVisualizer).  The student will implement the fit(), score(), and poof() methods that creates a main calibration curve graph and a mean predicted value line graph.  See http://www.scikit-yb.org/en/latest/api/classifier/class_balance.html and the initial probability calibration curve issue (https://github.com/DistrictDataLabs/yellowbrick/issues/365).

#### Helpful Experience

Knowledge of Python is required to complete this project.  Familiarity with machine learning and matplotlib is a plus.

#### First steps

1.)Install Yellowbrick on your machine.  Details on how to do this can be found here (https://github.com/DistrictDataLabs/yellowbrick#installing-yellowbrick).  
2.)In order to get familiar with Yellowbrick, we recommend checking out examples here (https://github.com/DistrictDataLabs/yellowbrick/blob/develop/examples/examples.ipynb).  
3.)We also have a quick start guide (https://github.com/DistrictDataLabs/yellowbrick/blob/master/docs/quickstart.rst).
4.)Please read the contributor section (http://www.scikit-yb.org/en/latest/contributing.html)

###  Idea Title 
Write blogpost highlighting Yellowbrick for a Machine Learning project.
#### Abstract

The student would write a blogpost highlighting Yellowbrick for a Machine Learning Project using a data source/domain of her choice.


| **Intensity**                          | **Priority**              | **Involves**  | **Mentors**              |
| -------------                          | ------------              | ------------- | -----------              |
| {{ Novice}}                            | {{ Medium}} | {{ }}       | {{ [@foo][], [@bar][] }} |

#### Technical Details
The student would write a blogpost based upon a data science project highlighting Yellowbrick for machine learning and visualization.  The student would go through the data science pipeline (problem statement, hypothesis, ingestion, storage, wrangling, statistical exploration, model selection, machine learning and visualization).  The blog post would center around this process.  For more information on this project, please reference this issue (https://github.com/DistrictDataLabs/yellowbrick/issues/691).

#### Helpful Experience

Knowledge of Python is required to complete this project.  Familiarity with machine learning and matplotlib is a plus.

#### First steps

1.)Install Yellowbrick on your machine.  Details on how to do this can be found here (https://github.com/DistrictDataLabs/yellowbrick#installing-yellowbrick).  
2.)In order to get familiar with Yellowbrick, we recommend checking out examples here (https://github.com/DistrictDataLabs/yellowbrick/blob/develop/examples/examples.ipynb).  
3.)We also have a quick start guide (https://github.com/DistrictDataLabs/yellowbrick/blob/master/docs/quickstart.rst).
4.)Please read the contributor section (http://www.scikit-yb.org/en/latest/contributing.html)

