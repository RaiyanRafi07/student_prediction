# Student Performance Prediction System

A machine learning application that predicts student pass/fail outcomes using Random Forest classification. The system analyzes various student performance factors and provides personalized feedback for improvement.

## Features

- Pass/fail prediction based on student data
- Personalized feedback and improvement suggestions
- Support for large dataset processing
- User-friendly Java Swing GUI
- High prediction accuracy (>90%)
- CSV data import functionality

## Requirements

- Java JDK 8 or higher
- Maven for dependency management
- Minimum 4GB RAM recommended
- Storage space for datasets

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YourUsername/student-prediction.git
```

2. Navigate to the project directory:
```bash
cd student-prediction
```

3. Build the project using Maven:
```bash
mvn clean install
```

## Usage

1. Run the application:
```bash
java -jar target/student-prediction.jar
```

2. Upload training data:
   - Click "Upload CSV File"
   - Select a properly formatted CSV file
   - Wait for model training completion

3. Enter student data:
   - Fill in all required fields
   - Numeric values (e.g., hours studied, attendance)
   - Categorical values (e.g., motivation level, school type)

4. Generate prediction:
   - Click "Predict" button
   - Review prediction result
   - Export feedback if desired

## Data Format

Required CSV columns:
- Hours Studied (0-168)
- Attendance (0-100)
- Previous Scores (0-100)
- Sleep Hours (0-24)
- And other relevant features

See stuent_data.csv for format example.

## Testing

Run the test suite:
```bash
mvn test
```

## Contributors

- Kamisha Baijnauth
- Sebastian Mejia
- Raiyan Rafi
