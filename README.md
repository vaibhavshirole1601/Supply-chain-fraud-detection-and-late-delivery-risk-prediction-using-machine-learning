**Project Title**

Supply chain fraud detection and late delivery risk prediction using machine learning

**Project Overview**

This project implements a smart supply chain using big data analysis, focusing on optimizing delivery times and detecting fraud. The aim is to leverage machine learning techniques to enhance the efficiency and security of the supply chain.

**Feature Engineering**

**Stage 1: Domain Knowledge Application**
In the initial stage, feature engineering was performed by applying domain knowledge. This involved identifying and creating relevant features based on the intricacies of the supply chain domain.

**Stage 2: Geospatial Feature Engineering**
To incorporate geospatial information, latitude and longitude features were added to the dataset. This was achieved by utilizing the geopy library, mapping order regions, cities, states, and countries to their respective coordinates. The resulting features improved location-based analysis while reducing the overall feature count.

**Stage 3: SelectKBest Feature Selection**
The SelectKBest module was applied to select the most impactful features for the target variable. By focusing on the most informative features, the dimensionality of the dataset was reduced, improving computational efficiency and potentially enhancing model performance.

**Data Preprocessing**

Data preprocessing steps included cleaning, normalization, and encoding to ensure the dataset was suitable for model training. These steps aimed to handle missing values, standardize numerical features, and convert categorical variables into a format suitable for machine learning algorithms.

**Model Training**

**Late Delivery Prediction:**
Models were separately trained to predict late deliveries. Various algorithms were considered, and the performance was evaluated using metrics such as accuracy, precision, recall, and F1 score.

**Fraud Detection:**
Similarly, a separate model was trained for fraud detection. The chosen algorithms were tailored to the characteristics of fraud detection, and model performance was assessed using appropriate evaluation metrics.

**Hybrid Model**

The best-performing models from both the late delivery prediction and fraud detection tasks were selected to create a hybrid model. This ensemble approach aimed to capitalize on the strengths of different algorithms, potentially improving overall predictive accuracy.

**Multi-Output Classifier**

The hybrid model was transformed into a multi-output classifier, allowing it to handle multiple prediction tasks simultaneously. This approach provided a cohesive solution for both late delivery prediction and fraud detection within the supply chain.

**Model Evaluation**

The performance of the model was rigorously evaluated on testing data using relevant metrics. Results were analyzed to assess the effectiveness of the hybrid model in optimizing delivery times and detecting fraud.
