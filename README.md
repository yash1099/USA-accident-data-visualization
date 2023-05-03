# USA-accident-data-visualization
USA Accidents Data Visualization
This project aims to visualize the USA accidents data obtained from Kaggle. The dataset contains information about accidents that occurred in the USA between February 2016 and March 2019, including their severity, location, weather conditions, and other factors.

The project consists of three main components:

Data exploration and preprocessing: In this step, we explore the dataset and preprocess it to prepare it for visualization. The Jupyter notebooks used for this step are data_exploration.ipynb and data_preprocessing.ipynb. The cleaned data is stored in the data/accidents_clean.csv file.

Data visualization: In this step, we use the processed data to create visualizations that allow us to explore the relationships between different variables and gain insights about the accidents. The Jupyter notebook used for this step is data_visualization.ipynb, and the interactive map generated from the data is stored in the outputs/map.html file.

Project report: Finally, we create a project report that summarizes the main findings and insights from the data visualization. The report is stored in the outputs/report.pdf file.

Installation
To run this project, you need to have Python 3.x installed on your machine, as well as the packages listed in the requirements.txt file. You can install these packages using pip:

bash
Copy code
pip install -r requirements.txt
Usage
To reproduce the results of this project, you need to follow these steps:

Download the USA accidents data from Kaggle and save it to the data/accidents.csv file.

Run the data_exploration.ipynb notebook to explore the dataset and identify any issues or missing data.

Run the data_preprocessing.ipynb notebook to preprocess the data and clean it up for visualization.

Run the data_visualization.ipynb notebook to generate the interactive map and explore the relationships between different variables.

Generate the project report by compiling the report.tex file using your favorite LaTeX editor.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Kaggle for providing the USA accidents dataset.
Mapbox for providing the map visualization platform used in this project.
Bokeh for providing the interactive data visualization library used in this project.
