
# Data Visualization Report from Jupyter Notebook

This report synthesizes key insights and visualizations from a diabetics dataset on data visualization. It aims to succinctly present the analytical and visual findings contained within the attached notebook

## Notebook Overview

The notebook encompasses various stages of data analysis, including data importing, cleaning, visualization, feature selection, and model evaluation. Key insights are drawn from the visualizations to understand the data better and inform subsequent modeling decisions.

## Data Importing and Cleaning

The notebook begins by importing necessary packages and the dataset, followed by initial data exploration. No missing data values were reported, which simplifies the preprocessing stage. However, outliers and data distribution were carefully analyzed to ensure data quality.

## Data Visualization

### Data Spread and Distribution

The notebook provides visualizations to understand the data's spread and distribution. It highlights the presence of outliers in features like glucose and blood pressure and notes the class imbalance in the outcomes.

### Outlier Visualization

Further visualizations focus on identifying and analyzing outliers across different features. The analysis concludes that most outliers do not significantly impact the output, suggesting their removal might be safe.
![image](https://github.com/jaideep-siva/Visualization_and_Featureselection/assets/112749838/9eb98844-4ddf-43ed-8cac-86fdb6f19af0)


## Model Building and Evaluation

### Feature Selection

The notebook explores feature selection techniques to identify significant predictors. Glucose and insulin were identified as impactful features, and models built using only these features performed comparably to those using the full feature set.
### Select Kbest 
![image](https://github.com/jaideep-siva/Visualization_and_Featureselection/assets/112749838/db247b0c-5344-4060-a22a-1130568d7f4b)

### Principal Component Analysis (PCA)

PCA was employed to reduce dimensionality while retaining the essential variance in the data. The notebook demonstrates that a model with reduced dimensions via PCA can still yield accurate predictions.

![image](https://github.com/jaideep-siva/Visualization_and_Featureselection/assets/112749838/9c430618-07a0-4d0b-939f-ba06c4a03dca)


### Advanced Visualization Techniques

UMAP and t-SNE techniques were used for advanced data visualization, providing a deeper understanding of the data's structure.

![image](https://github.com/jaideep-siva/Visualization_and_Featureselection/assets/112749838/6276edb6-3c3b-4255-9dfd-91dade03a658)
![newplot](https://github.com/jaideep-siva/Visualization_and_Featureselection/assets/112749838/b28c133c-346a-4171-b89f-7e260a93c45c)
![image](https://github.com/jaideep-siva/Visualization_and_Featureselection/assets/112749838/fdc01003-05e8-4acd-b6ab-819720dd717d)

### Univariate Feature Selection 
Using univariate methods to extract important features
![image](https://github.com/jaideep-siva/Visualization_and_Featureselection/assets/112749838/aac80172-67d8-4f1c-a07e-94692d4a842e)



## Conclusion

The notebook concludes with insights on the utility of various analysis and visualization techniques. It notes that while UMAP and t-SNE offer valuable data insights, PCA stands out for its ability to reduce dimensionality effectively without significantly compromising model accuracy.


