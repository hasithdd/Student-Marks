## Student Marks Predictor

This project is a simple linear regression model that predicts student marks based on the number of courses they are taking and the time they spend studying.

## Dependencies

- numpy
- pandas
- plotly
- sklearn

## Data

The data used in this project is stored in a CSV file named `Student_Marks.csv`. The data includes the following columns:

- `number_courses`: The number of courses a student is taking.
- `time_study`: The amount of time a student spends studying.
- `Marks`: The marks scored by the student.

## Usage

To use this project, run the `Student_Marks.ipynb` file in a Jupyter notebook. The notebook includes code for data exploration, visualization, and model training and testing.

## Model

The model used in this project is a simple linear regression model from the sklearn library. The model is trained on 80% of the data, and tested on the remaining 20%.

## Results

The model's performance is evaluated using the score method, which returns the coefficient of determination R^2 of the prediction.

## Future Work

Future work could include trying out different models, tuning model parameters, or using different features for prediction.
