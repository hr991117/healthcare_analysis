# Healthcare Data - Patient Wait List

## Overall Objective
The primary goals of this project are to:
1. Track the current status of the patient waiting list.
2. Analyze historical monthly trends of the waiting list in both inpatient and outpatient categories.
3. Conduct a detailed specialty-level and age profile analysis.

## Data Scope
The data used in this project spans from 2018 to 2021.

## Metrics Required
The analysis focuses on the following metrics:
1. Average & Median Waiting List
2. Current Total Waiting List

## Views Required
The project includes the following views:
1. **Summary Page**: Provides an overview of key metrics and trends.
2. **Detailed Page**: Offers granular analysis for deeper insights.

## Project Structure
- `data/`: Contains the dataset files.
- `powerbi/`: Power BI report files (.pbix).
- `README.md`: This file.

## Setup and Installation
To set up the project on your local machine and view the Power BI dashboard, follow these steps:

1. Ensure you have [Power BI Desktop](https://powerbi.microsoft.com/desktop) installed.

2. Clone the repository:
    ```sh
    git clone https://github.com/hr991117/healthcare_analysis.git
    cd healthcare-data-patient-wait-list
    ```

3. Open the Power BI report file (`powerbi/Main.pbix`) in Power BI Desktop.

4. If necessary, update the data source settings to point to the location of your dataset files.

## Usage
1. Open the Power BI report in Power BI Desktop to explore the data and visualizations.
2. Interact with the dashboard by using filters and slicers to drill down into specific metrics and trends.
3. Publish the report to the Power BI Service to share it with others.

## Results
- **Summary Page**: Presents an overview of the average, median, and total waiting lists with visualizations.
- **Detailed Page**: Provides in-depth analysis by specialty and age profile with interactive charts and graphs.

## Contributing
If you would like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
