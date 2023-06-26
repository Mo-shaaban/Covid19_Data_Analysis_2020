# HCL's Hackathon CodeForCovid19

This project was developed during HCL's Hackathon, CodeForCovid19, in a team of 3 during the summer of 2020. Our objective was to analyze COVID-19 infection data and assess the differential impact on minority groups. We aimed to understand how the pandemic affected different ethnic groups and identify any disparities.

## Project Overview

Our analysis focused on the following key steps:

1. Data Cleaning and Preparation:
   - We obtained COVID-19 infection data from reliable sources, specifically targeting the United States.
   - The data included the number of cases and deaths per ethnic group in different states.
   - We cleaned and processed the data to ensure accuracy and consistency.

2. K-means Clustering Analysis:
   - We employed the k-means clustering algorithm to analyze the COVID-19 data.
   - The algorithm allowed us to identify patterns and groupings among the different ethnic groups based on infection rates and mortality.
   - By clustering the data, we aimed to reveal any disparities or disproportionate impacts on specific minority groups.

## Usage

To run the code and replicate our analysis, please follow these instructions:

1. Ensure that you have the required dependencies installed. You can find a list of dependencies in the `requirements.txt` file.

2. Download the dataset:
   - Obtain the COVID-19 infection data for the United States, including the number of cases and deaths per ethnic group, in a CSV format.
   - Place the dataset file in the designated directory: `data/covid_data.csv`.

3. Open the `main.ipynb` Jupyter Notebook file.

4. Execute the notebook cells sequentially to perform the analysis.
   - The notebook will load the dataset, clean the data, and perform the k-means clustering algorithm on the COVID-19 data.
   - Visualizations and analysis results will be generated and displayed within the notebook.

Please note that the code and analysis provided in this project are specific to the COVID-19 infection data and the context of HCL's CodeForCovid19 Hackathon. Modifications may be required to adapt the code to other datasets or analysis objectives.

## File Descriptions

- `main.ipynb`: The main Jupyter Notebook file containing the code and analysis.
- `data/covid_data.csv`: The dataset file containing COVID-19 infection data per ethnic group in different states.

## Results

Based on our analysis, we were able to identify potential disparities in the impact of COVID-19 on different minority groups. The k-means clustering algorithm helped us detect patterns and groupings, highlighting areas where specific ethnic groups may have experienced a higher infection rate or mortality rate compared to others.

The results and visualizations generated during the analysis are presented within the `main.ipynb` notebook. They provide insights into the differential impact of COVID-19 on minority groups, allowing for a better understanding of the pandemic's social and health implications.

## Contributing

As this project was developed for a specific hackathon, we do not currently accept contributions. However, we encourage you to use the code and insights provided as a foundation for further research and analysis. Feel free to adapt the code and methodology to explore additional questions or datasets related to COVID-19 or other health-related topics.

## License

This project is licensed under the [MIT License].

For any questions or inquiries regarding this project, please contact me at mo.shaaban2000@gmail.com
