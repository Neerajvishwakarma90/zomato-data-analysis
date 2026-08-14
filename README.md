# 🍽️ Zomato Data Analysis

## 📌 About the Project

I worked on this project to explore and understand Zomato restaurant data using Python.

The main idea was to take the raw dataset, clean the data, and then use different analysis and visualization techniques to find interesting patterns in restaurants, ratings, customer votes, online ordering, and pricing.

This project helped me practice the complete **data analysis process — from cleaning the data to finding insights and visualizing the results.**

## 📊 What I Analyzed

During the analysis, I looked at questions such as:

* Which type of restaurant is most common?
* Which restaurants receive the most votes?
* How are restaurant ratings distributed?
* How many restaurants provide online ordering?
* What is the approximate cost for two people?
* Do restaurants with online ordering have different ratings?
* How does online ordering vary across different restaurant types?

## 🧹 Data Cleaning

Before starting the analysis, I explored the dataset and checked its structure, missing values, data types, and basic statistics.

One of the main cleaning steps was working with the `rate` column. The ratings were stored in a format such as `4.1/5`, so I extracted the numerical rating to make the column easier to analyze and visualize.

## 📈 Visualizations

I used different types of charts to understand the data better, including:

* Count plots
* Histograms
* Box plots
* Line plots
* Pivot tables
* Heatmaps

### Restaurant Types

![Restaurant Types](images/restaurant_types.png)

### Rating Distribution

![Rating Distribution](images/rating_distribution.png)

### Online Ordering

![Online Ordering](images/online_order.png)

### Cost for Two People

![Cost for Two](images/cost_for_two.png)

### Online Ordering by Restaurant Type

![Heatmap](images/restaurant_order_heatmap.png)

## 🛠️ Tools & Libraries

I used the following tools and Python libraries:

* **Python**
* **Pandas** – for data manipulation and cleaning
* **NumPy** – for numerical operations
* **Matplotlib** – for visualization
* **Seaborn** – for statistical visualizations
* **Jupyter Notebook** – for performing the analysis

## 📂 Project Structure

```text
zomato-data-analysis/
│
├── data/
│   └── Zomato-data-.csv
│
├── images/
│   ├── restaurant_types.png
│   ├── rating_distribution.png
│   ├── online_order.png
│   ├── cost_for_two.png
│   └── restaurant_order_heatmap.png
│
├── notebooks/
│   └── zomato_data_analysis.ipynb
│
├── README.md
└── requirements.txt
```

## 🎯 What I Learned

Through this project, I got practical experience with:

* Cleaning real-world datasets
* Working with Pandas DataFrames
* Handling and transforming columns
* Grouping and summarizing data
* Creating pivot tables
* Creating different types of visualizations
* Using heatmaps to understand relationships
* Exploring data before drawing conclusions

## 🚀 How to Run the Project

Clone the repository and open the Jupyter Notebook:

```bash
git clone https://github.com/yourusername/zomato-data-analysis.git
cd zomato-data-analysis
jupyter notebook
```

Install the required libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Then open the notebook and run the cells step by step.

## 👨‍💻 About Me

**Neeraj Vishwakarma**

B.Tech Computer Science | Data Science

I'm currently building my skills in **Python, Data Analysis, Pandas, NumPy, Matplotlib, Seaborn, and Machine Learning**.

This project is one of my practical projects where I applied data cleaning, exploratory data analysis, and visualization techniques to a real-world dataset.
