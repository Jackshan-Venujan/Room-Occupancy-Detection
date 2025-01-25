# Room-Occupancy-Detection
Introduction
Room occupancy detection plays a key role in smart building systems, enabling energy efficiency and resource optimization. This project uses Logistic Regression and Decision Trees to classify room occupancy based on environmental data such as temperature, humidity, light, and CO2 levels. The models are evaluated using metrics like accuracy, precision, recall, and F1-score to identify the most effective approach for this task.

# Literature Survey
Room occupancy detection using environmental data is a key application of supervised learning.

Logistic Regression: Known for its simplicity and interpretability, Logistic Regression performs well for binary classification when relationships between features and the target are linear.

Decision Trees: These are versatile models capable of capturing nonlinear relationships, commonly used in occupancy detection due to their ability to handle diverse data types.

Evaluation Metrics: Metrics such as accuracy, precision, recall, and F1-score are critical to assessing model performance, especially for imbalanced datasets.

Applications: Accurate occupancy classification supports energy-efficient systems in smart buildings, optimizing lighting, HVAC control, and resource management.

This project utilizes Logistic Regression and Decision Trees, leveraging their strengths to classify room occupancy and compare their performance.

# Dataset Description

binary classification (room occupancy) from Temperature,Humidity,Light and CO2.
occupancy was obtained from time stamped pictures that were taken every minute.

source

Accurate occupancy detection of an office room from light, temperature, humidity and CO2 measurements using statistical learning models. Luis M. Candanedo, Véronique Feldheim. Energy and Buildings. Volume 112, 15 January 2016, Pages 28-39.
https://www.kaggle.com/datasets/kukuroo3/room-occupancy-detection-data-iot-sensor

# References
Light Luminance: https://www.glamox.com/en/pbs/human-centric-lighting/in-depth-information/

Treating outliers: https://www.analyticsvidhya.com/blog/2021/05/feature-engineering-how-to-detect-and-remove-outliers-with-python-code/

Logistic Regression: https://www.datacamp.com/tutorial/understanding-logistic-regression-python

Plotting Histogram in Python using Matplotlib: https://www.geeksforgeeks.org/plotting-histogram-in-python-using-matplotlib/

Classification technique: https://scikit-learn.org/1.5/modules/generated/sklearn.metrics.classification_report.html

Handling Imbalance Data: https://www.analyticsvidhya.com/blog/2021/06/5-techniques-to-handle-imbalanced-data-for-a-classification-problem/

ROC curve: https://scikit-learn.org/1.0/auto_examples/model_selection/plot_roc.html
