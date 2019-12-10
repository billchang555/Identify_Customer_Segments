# Identify_Customer_Segments_Project

In this project, I will work with real-life data provided to us by Bertelsmann partners AZ Direct and Arvato Finance Solution. The data here concerns a company that performs mail-order sales in Germany. Their main question of interest is to identify facets of the population that are most likely to be purchasers of their products for a mailout campaign. I will be to use unsupervised learning techniques to organize the general population into clusters, then use those clusters to see which of them comprise the main user base for the company. Prior to applying the machine learning methods, I will also need to assess and clean the data in order to convert the data into a usable form.


The unsupervised learning branch of machine learning is key in the organization of large and complex datasets. While unsupervised learning lies in contrast to supervised learning in the fact that unsupervised learning lacks objective output classes or values, it can still be important in converting the data into a form that can be used in a supervised learning task. Dimensionality reduction techniques can help surface the main signals and associations in your data, providing supervised learning techniques a more focused set of features upon which to apply their work. Clustering techniques are useful for understanding how the data points themselves are organized. These clusters might themselves be a useful feature in a directed supervised learning task.

This project uses Python 3 and is designed to be completed through the Jupyter Notebooks IDE. The following libraries are expected to be used in this project:

- NumPy
- pandas
- Sklearn / scikit-learn
- Matplotlib (for data visualization)
- Seaborn (for data visualization)

Main files involved:
- Udacity_AZDIAS_Subset.csv: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns).
- Udacity_CUSTOMERS_Subset.csv: Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns).
- Data_Dictionary.md: Information file about the features in the provided datasets.
- AZDIAS_Feature_Summary.csv: Summary of feature attributes for demographic data.
- Identify_Customer_Segments.ipynb: Jupyter Notebook divided into sections and guidelines for completing the project. The notebook provides more details and tips than the outline given here.

Steps: Preprocessing - Feature Transformation - Clustering
