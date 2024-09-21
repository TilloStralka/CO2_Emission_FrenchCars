# CO2 Emissions Analysis of Cars

## Overview

This project collects data from a French goverment website [https://www.data.gouv.fr/fr/datasets/emissions-de-co2-et-de-polluants-des-vehicules-commercialises-en-france/#_](https://www.data.gouv.fr/fr/datasets/emissions-de-co2-et-de-polluants-des-vehicules-commercialises-en-france/#_) and combines information about cars from different companies. The data includes technical specifications and CO2 emissions.

The goal of this project is to:
- Organize and structure the data.
- Visualize the data.
- Identify dependencies between car brands, technical specifications, and fuel type (diesel, gasoline and more).
- Filter the data into target and explanatory variables.

Finally, the filtered data will be used to create a machine learning model that predicts CO2 emissions based on the technical specifications of a car.

## Project Steps

1. **Data Collection**: 
   - Collect data from the French website.
   - Work with the data from different years differently, because they do not have the same format. 
   - Combine data from different companies.

2. **Data Organization**:
   - Structure and clean the data.
   - Delete empty column. 
   - Delete empty rows.
   - Add meaningful labels to the columns.
   - Combine differenet column names which mean the same. 
   - Translate column names to english. 
   
3. **Data Visualization**:
   - Create visualizations to show dependencies between brands, specifications, and fuel types.
   
4. **Machine Learning**:
   - Filter data into target (CO2 emissions) and explanatory variables (technical specifications).
   - Use machine learning algorithms to predict CO2 emissions based on car specifications.

## Technologies Used

- Python
- Pandas
- Matplotlib / Seaborn for visualization
- Scikit-learn for machine learning

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/TilloStralka/Project_DS_CO2.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the main analysis:
    ```bash
    python main.py
    ```

## Data

The data is collected from the website but **not included in the repository** due to size and privacy constraints. You can download the data from [https://www.data.gouv.fr/fr/datasets/emissions-de-co2-et-de-polluants-des-vehicules-commercialises-en-france/#_](https://www.data.gouv.fr/fr/datasets/emissions-de-co2-et-de-polluants-des-vehicules-commercialises-en-france/#_).

## License

This project is licensed under the MIT License.
