# Penguin Analytics: Advanced Power BI & Python Integration #

This project demonstrates how to extend Power BI capabilities using Python for machine learning and high-end statistical visualizations. Using the Palmer Penguins dataset, this report performs outlier detection and exploratory data analysis that goes beyond native Power BI features.

## *🚀 Features* ##

->Python Data Connectivity: Data is fetched and cleaned using pandas directly within Power BI.

->ML-Powered Outlier Detection: Utilizes the Scikit-Learn Isolation Forest algorithm to identify statistical anomalies in penguin body measurements.

->Advanced Statistical Visualizations:

->Seaborn Pair Plot: A comprehensive grid showing relationships between all numeric variables.

->Correlation Heatmap: A color-coded matrix displaying Pearson correlation coefficients.

->Violin Plots: Detailed density distributions of penguin mass by species.

->Hybrid Dashboarding: Seamlessly combines Python visuals with interactive native Power BI slicers and KPI cards.

## *🛠️ Tech Stack* ##

->BI Tool: Power BI Desktop

->Language: Python 3.x

->Libraries: * pandas (Data manipulation)

->seaborn & matplotlib (Advanced plotting)

->scikit-learn (Machine Learning / Anomaly Detection)

## *📂 Project Structure* ##

->Penguin_Analytics.pbix: The main Power BI project file.

->Scripts/: Folder containing the standalone Python scripts used for the visuals.

->Data/: A link or CSV of the Palmer Penguins dataset.

## *⚙️ Setup Instructions* ##

To view or edit this report, you must have Python installed and linked to your Power BI Desktop:

### 1.Install Python Libraries: ###

->pip install pandas matplotlib seaborn scikit-learn

### 2.Configure Power BI: ###

->Go to File > Options and Settings > Options > Python Scripting.

->Ensure your Python home directory is correctly detected.

### 3.Enable Scripts: ###

->When opening the .pbix file, click Enable on the yellow security bar to allow the Python scripts to run.

## *📊 Key Insights from the Analysis* ##

->Correlation: A strong positive correlation exists between Flipper Length and Body Mass across all species.

->Cluster Separation: The Pair Plot clearly shows that the Gentoo species forms a distinct cluster in terms of body mass compared to Adelie and Chinstrap.

->Anomalies: Using Isolation Forest, roughly 5% of the data was flagged as outliers—these represent penguins with unusual proportions (e.g., high body mass but short bill length).
