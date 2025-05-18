# cluster-analysis

This project provides a flexible and universal financial cluster analysis script using Torque Clustering. The script is designed to work with any financial time series data in CSV format, allowing you to identify patterns, clusters, and anomalies in price changes over time. The code is written in Python and includes data loading, clustering, and visualization components, making it a comprehensive starting point for financial data analysis.

🚀 Features

Flexible data loading from CSV files

Price change calculation (percentage)

Torque clustering for identifying market phases

Clear and customizable data visualizations

Easy to extend and integrate with other financial models

🔧 Installation

Make sure you have the required Python packages installed:

pip install pandas matplotlib numpy


📈 Sample Output

The script will produce a scatter plot showing price changes over time, with clusters color-coded for easier interpretation. It will also print a statistical summary of each cluster, including count, mean, standard deviation, minimum, and maximum values.

📁 Data Format

Your CSV file should have the following columns:

Open Time (datetime)

Close (float)

High (float)

Low (float)

Volume (float)

Example:

Open Time,Close,High,Low,Volume
2023-01-01 00:00:00,1200.5,1250.0,1190.0,3000
2023-01-01 12:00:00,1300.5,1350.0,1280.0,3500



📄 License

This project is licensed under the MIT License. Feel free to modify and distribute.

🤝 Contributing

Contributions are welcome! If you have ideas for improving this project or want to add new features, feel free to open a pull request or create an issue.



