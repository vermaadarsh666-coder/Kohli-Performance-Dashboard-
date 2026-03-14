# Kohli-Performance-Dashboard-
📊 Power BI dashboard analyzing Virat Kohli's cricket performance using match-level data.

Virat Kohli Performance Analysis Dashboard

📊 Short Description
This project is a Power BI dashboard that analyzes the cricket performance of Virat Kohli using match-level data. The dashboard provides insights into runs scored, highest scores, centuries, half-centuries, and consistent performances across matches.

━━━━━━━━━━━━━━━━━━━━━━━━

📑 Table of Contents
• Introduction
• Dataset / Inputs
• Tech Stack
• Installation
• Usage
• Analysis / Features
• Results / Insights
• Project Structure
• Contributing
• License
• Contact

━━━━━━━━━━━━━━━━━━━━━━━━

📘 Introduction
The Virat Kohli Performance Analysis Dashboard is a data analytics project built using Power BI. The goal of this project is to explore and visualize Virat Kohli’s batting performance through interactive charts and statistics.

The dashboard highlights important performance indicators such as:

• Total Runs
• Highest Score
• Number of Centuries (100s)
• Number of Half-Centuries (50s)
• Number of 30+ scores
• Total Matches Played

This project demonstrates how Power BI can be used for sports data analysis using calculated columns, DAX measures, and data visualization.

━━━━━━━━━━━━━━━━━━━━━━━━

📂 Dataset / Inputs
The dataset contains match-level information about Virat Kohli’s batting performance.

Main fields in the dataset include:

• Date
• Opponent Team
• Runs Scored
• Match Information

Additional calculated columns were created for analysis such as:

• 100s (Centuries)
• 50s (Half-centuries)
• 30+ Scores
• Calendar table for time-based analysis

━━━━━━━━━━━━━━━━━━━━━━━━

🛠 Tech Stack

• Power BI
• DAX (Data Analysis Expressions)
• CSV Dataset

━━━━━━━━━━━━━━━━━━━━━━━━

⚙️ Installation

1. Download the project files from the repository.
2. Open the .pbix file in Power BI Desktop.
3. Load the dataset if required.
4. Refresh the data.
5. Explore the dashboard visuals.

━━━━━━━━━━━━━━━━━━━━━━━━

🚀 Usage

The dashboard allows users to explore Virat Kohli’s performance interactively.

Users can:

• Analyze total runs scored
• Identify highest scoring innings
• Check the number of centuries and half-centuries
• Analyze consistent performances with 30+ scores
• View match statistics against different opponents
• Explore performance trends using the date filter

━━━━━━━━━━━━━━━━━━━━━━━━

📊 Analysis / Features

Performance Metrics
• Total Runs
• Highest Score
• Total Matches

Score Categories
• Centuries (100s)
• Half-centuries (50s)
• 30+ Score Contributions

Date Analysis
A custom calendar table was created for time-based insights including:

• Year
• Month
• Day

Important DAX Measures used in the dashboard:

Runs = SUM(Virat_Kohli[runs])

HighestScore = MAX(Virat_Kohli[runs])

Total_Matches = COUNT(Virat_Kohli[opponent])

100s = SUM(Virat_Kohli[100s])

50s = SUM(Virat_Kohli[50s])

30+ = SUM(Virat_Kohli[30+])

━━━━━━━━━━━━━━━━━━━━━━━━

📈 Results / Insights

The dashboard provides useful insights such as:

• Virat Kohli’s highest scoring innings
• Frequency of centuries and half-centuries
• Consistency through 30+ scores
• Match performance distribution
• Trends in performance over time

These insights help understand batting performance patterns using visual analytics.

━━━━━━━━━━━━━━━━━━━━━━━━

📁 Project Structure

Virat-Kohli-PowerBI-Dashboard
│
├── data
│   └── Source.csv
│
├── dashboard
│   └── Virat_Kohli_Dashboard.pbix
│
├── measures
│   └── Virat_Kohli_Measures.txt
│
└── README.md

━━━━━━━━━━━━━━━━━━━━━━━━

🤝 Contributing

Contributions are welcome.
If you would like to improve the dashboard, dataset, or documentation, feel free to submit a pull request.

━━━━━━━━━━━━━━━━━━━━━━━━

📜 License

This project is licensed under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files to deal in the software without restriction.

The software is provided “as is”, without warranty of any kind.

━━━━━━━━━━━━━━━━━━━━━━━━

📬 Contact

Adarsh Verma
Email: [vermaadarsh666@gmail.com]
