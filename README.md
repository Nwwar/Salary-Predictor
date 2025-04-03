# Salary Predictor

Salary Predictor is a machine learning project aimed at predicting salaries based on survey data. It involves data cleaning, exploratory data analysis (EDA), and model building to provide accurate salary predictions.

## Table of Contents

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)

## Dataset

The project utilizes the "Ask A Manager Salary Survey 2021" dataset, which is included in the repository as `Ask A Manager Salary Survey 2021 (Responses) - Form Responses 1.csv`. This dataset contains responses from individuals regarding their salaries and related information.

## Project Structure

The repository consists of the following key files and directories:

- `.idea/` and `.ipynb_checkpoints/`: Directories containing project-specific settings and Jupyter Notebook checkpoints.
- `Data_Cleaning.ipynb`: Jupyter Notebook for data cleaning processes.
- `EDA.ipynb`: Jupyter Notebook for exploratory data analysis.
- `Model_Building.ipynb`: Jupyter Notebook for building and evaluating machine learning models.
- `main.py`: Python script to run the salary prediction model.
- `logs.log`: Log file recording the operations performed during the project.
- `Survey_data_cleaned.csv` and `EDA_data.csv`: Intermediate datasets generated during data cleaning and EDA phases.

## Usage

To use the salary predictor:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Nwwar/Salary-Predictor.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd Salary-Predictor
   ```

3. **Install the required dependencies**:

   Ensure that you have Python installed. It's recommended to use a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
   pip install -r requirements.txt
   ```

   *Note: The `requirements.txt` file should list all necessary packages. If it's not provided, you may need to install packages as you encounter import errors.*

4. **Run the Jupyter Notebooks**:

   Start Jupyter Notebook to explore and execute the data cleaning, EDA, and model building steps:

   ```bash
   jupyter notebook
   ```

   Open each notebook (`Data_Cleaning.ipynb`, `EDA.ipynb`, `Model_Building.ipynb`) and run the cells sequentially.

5. **Execute the main script**:

   After completing the above steps, you can run the main script to make salary predictions:

   ```bash
   python main.py
   ```

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues, please open an issue or submit a pull request.
