# Mobile Price Classification

## Project Description
This project aims to classify mobile phones into different price ranges based on their features using machine learning techniques. The dataset includes various features of mobile phones, and the target variable is the price range.

## Data Description
The dataset contains detailed information about mobile phones and their features. Here is the list of variables and their meanings:
- **id**: Unique identifier for each phone.
- **battery_power**: Total energy a battery can store in mAh.
- **blue**: Indicates if the phone has Bluetooth (1: Yes, 0: No).
- **clock_speed**: Speed at which the microprocessor executes instructions in GHz.
- **dual_sim**: Indicates if the phone supports dual SIM (1: Yes, 0: No).
- **fc**: Front camera resolution in megapixels.
- **four_g**: Indicates if the phone supports 4G (1: Yes, 0: No).
- **int_memory**: Internal memory in GB.
- **m_dep**: Depth of the phone in cm.
- **mobile_wt**: Weight of the phone in grams.
- **n_cores**: Number of cores of the processor.
- **pc**: Rear camera resolution in megapixels.
- **px_height**: Height of the screen resolution in pixels.
- **px_width**: Width of the screen resolution in pixels.
- **ram**: RAM in MB.
- **sc_h**: Height of the screen in cm.
- **sc_w**: Width of the screen in cm.
- **talk_time**: Maximum time that a phone can be used continuously without recharging in hours.
- **three_g**: Indicates if the phone supports 3G (1: Yes, 0: No).
- **touch_screen**: Indicates if the phone has a touchscreen (1: Yes, 0: No).
- **wifi**: Indicates if the phone supports WiFi (1: Yes, 0: No).
- **price_range**: Target variable indicating the price range of the mobile phone:
  - 0: Low cost
  - 1: Medium cost
  - 2: High cost
  - 3: Very high cost

## Data Analysis
The analysis includes the following steps:
1. **Loading Libraries and Data**: Importing necessary libraries and loading the dataset.
2. **Data Overview**: Displaying the first few rows of the dataset and checking column names.
3. **Descriptive Statistics**: Generating summary statistics for the dataset.
4. **Data Cleaning**: Checking for missing or duplicated values.
5. **Exploratory Data Analysis (EDA)**:
   - **Proportion of Price Ranges**: Visualizing the distribution of the price range variable.
   - **Correlation Matrix**: Displaying the correlation between different features and the price range.

## Results
- **Data Quality**: The dataset is well-prepared for analysis with no missing or duplicated values.
- **Balanced Dataset**: The target variable (price range) is evenly distributed, ensuring that the model will not favor any particular class.
- **Strong Correlations**: RAM has a very strong positive correlation with the price range, followed by battery power and screen resolution.

## Conclusion
This project provides a detailed analysis of mobile phone features and their impact on the price range. The insights gained from this analysis can be used to build predictive models for classifying mobile phones into different price ranges.

## References
- [Mobile Price Prediction Random Forest on Kaggle](https://www.kaggle.com/code/rafaaell/mobile-price-predicition-random-forest)
