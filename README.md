# Mobile Price Classification Random-forest
Project Description
Bob has started his own mobile phone company and aims to compete with industry giants like Apple and Samsung. To thrive in the competitive mobile phone market, Bob needs to accurately estimate the price range of the mobile phones his company creates based on their features. However, Bob is not proficient in Machine Learning, so he needs your help to determine the relationship between various mobile phone features (such as RAM, Internal Memory, etc.) and their selling price.

The goal of this project is to classify mobile phones into different price ranges based on their features. Instead of predicting the actual price, we aim to classify phones into predefined price ranges. This classification will help Bob make informed decisions about pricing his products competitively.

Dataset Description
The dataset contains sales data of mobile phones from various companies. Each row in the dataset represents a mobile phone and its corresponding features. The features include:

Battery Power: Total energy a battery can store in one time measured in mAh.
Bluetooth: Indicates whether the phone has Bluetooth (1: Yes, 0: No).
Clock Speed: Speed at which microprocessor executes instructions.
Dual Sim: Indicates whether the phone supports dual SIM (1: Yes, 0: No).
Front Camera: Front camera megapixels.
4G: Indicates whether the phone supports 4G (1: Yes, 0: No).
Internal Memory: Internal memory in Gigabytes.
Mobile Depth: Depth of mobile phone in cm.
Mobile Weight: Weight of mobile phone.
N-cores: Number of cores of the processor.
Primary Camera: Primary camera megapixels.
Pixel Resolution Height: Height of the mobile screen in pixels.
Pixel Resolution Width: Width of the mobile screen in pixels.
RAM: Random Access Memory in Megabytes.
Screen Height: Height of the mobile screen in cm.
Screen Width: Width of the mobile screen in cm.
Talk Time: Maximum time in hours that a phone can be used continuously without recharging.
3G: Indicates whether the phone supports 3G (1: Yes, 0: No).
Touch Screen: Indicates whether the phone has a touch screen (1: Yes, 0: No).
WiFi: Indicates whether the phone has WiFi (1: Yes, 0: No).
The target variable is price_range, which indicates the price range of the mobile phone. It is a categorical variable with the following values:

0: Low cost
1: Medium cost
2: High cost
3: Very high cost

Project Objectives
Exploratory Data Analysis (EDA): Perform EDA to understand the distribution of features and their relationship with the price range.
Data Preprocessing: Clean and preprocess the data to make it suitable for building machine learning models.
Feature Engineering: Create new features or modify existing ones to improve the model's performance.
Model Building: Train different classification models to classify mobile phones into the appropriate price range.
Model Evaluation: Evaluate the performance of the models using appropriate metrics and choose the best model.
Deployment: Provide a solution that Bob can use to classify new mobile phones based on their features.
