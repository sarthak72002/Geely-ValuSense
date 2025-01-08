# Geely ValuSense: Car Price Prediction

## Overview
This project leverages machine learning to predict car prices based on various attributes. The analysis uses Python and explores the relationship between car
features and their market value. This repository contains the Python Jupyter Notebook used for the study, detailed insights into the dataset, and
implementation of the predictive models.

## Dataset Attributes
The dataset includes the following features:

1. **Car_ID**: Unique ID for each observation.
2. **Symboling**: Insurance risk rating (+3 = risky, -3 = safe).
3. **carCompany**: Name of the car manufacturer.
4. **fueltype**: Type of fuel used.
5. **aspiration**: Aspiration mechanism.
6. **doornumber**: Number of doors.
7. **carbody**: Type of car body.
8. **drivewheel**: Type of drive wheel.
9. **enginelocation**: Location of the car engine.
10. **wheelbase**: Wheelbase of the car.
11. **carlength**: Length of the car.
12. **carwidth**: Width of the car.
13. **carheight**: Height of the car.
14. **curbweight**: Weight of the car without occupants or luggage.
15. **enginetype**: Type of engine.
16. **cylindernumber**: Number of cylinders.
17. **enginesize**: Size of the engine.
18. **fuelsystem**: Fuel system type.
19. **boreratio**: Bore ratio.
20. **stroke**: Stroke or volume inside the engine.
21. **compressionratio**: Compression ratio of the engine.
22. **horsepower**: Horsepower output.
23. **peakrpm**: Peak RPM of the engine.
24. **citympg**: Mileage in city driving.
25. **highwaympg**: Mileage on highways.
26. **price (dependent variable)**: Price of the car.

## Requirements
- Python 3.12 or higher
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - PIL (Python Imaging Library)

## Project Structure
- `Geely ValuSense-SarthakParashar.ipynb`: The Jupyter Notebook containing all analysis and modeling.

## Key Steps in the Notebook
1. **Data Exploration**: Initial understanding of dataset attributes and statistics.
2. **Data Cleaning**: Handling missing values, correcting data types, and removing outliers.
3. **Feature Engineering**: Encoding categorical variables and normalizing numerical features.
4. **Model Building**: Implementation of regression models to predict car prices.
5. **Evaluation**: Assessing model performance using metrics such as RMSE, R-squared, etc.

## Results
The final model provides insights into the most influential factors affecting car prices and predicts prices with high accuracy.

## Contributing
Feel free to fork this repository, make updates, and submit a pull request. Contributions are welcome!



