# Mini Project: Analysing Quality of Diamonds 
This is a small project to publish on GitHub for Data Science course. The focus of the project is on reproducibility and git skills.

## Assignment Description
Course: ECBS5293 - Data Science 1

Submitted by: Zariza Chowdhury

Due Date: 8 October 2025

Assignment Name: Mini Project on GitHub

## Assignment Requirements: 

Reproducibility (3 pts): Follow the principles of reproducibility discussed in class: clear folder structure, raw data included, all analysis steps included in code, output created automatically. Goal is that an independent peer should be able to reproduce it with no (or minimal) modifications.

Environment (3 pts): Project should be easy to reproduce (ideally with one click). You should define the environment or requirements for this.

Documentation (3 pts): Provide a well-structured README.md using proper Markdown formatting. The README should briefly describe your project, data, folder structure, requirements, steps to reproduce and other necessary notes.

Analysis (3 pts): Perform a very basic analysis. Minimal cleaning if needed, then one descriptive statistic or a simple graph is enough. Code must be clean and easy to follow.

Version Control (3 pts): Use Git properly with at least 3 meaningful commit messages (additional to the init).

## Project Description
I analysed a dataset containing information about diamonds, to find out the distribution of different cuts of diamonds. I displayed my results as a barchart.

## Data Source
I have used a copywrite free dataset which is available on the internet,called "diamonds.csv" which was shared with me in another course: ECBS5208 - Coding 1: Introduction to Python

## Folder Structure
```
├── LICENSE
├── README.md
├── codes
│   └── analysis-1.ipynb
├── data
│   ├── cleaned
│   │   └── cut_value_counts.csv
│   └── raw
│       └── diamonds.csv
├── reports
├── requirements.txt
└── visualizations
    └── cut_bar_chart.png
```

## Libraries
I used Python environment in VS Code.
The following libraries were used for my analysis:
```
pandas
seaborn
numpy
```

## Reproducibility
Open terminal and run the code below to clone my repository from GitHub
```
git clone https://github.com/zarizachow/mini-project.git
```

Install the libraries listed in requirements.txt

Have fun with my project, and make it yours!