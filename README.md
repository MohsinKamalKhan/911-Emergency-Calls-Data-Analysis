# 📊 911 Emergency Calls Data Analysis

This project analyzes the 911 emergency call data from Montgomery County, PA, USA. The dataset is sourced from Kaggle:
🔗 [911 Calls Dataset on Kaggle](https://www.kaggle.com/datasets/mchirico/montcoalert/data)

## 📁 Project Structure

* `911_project.ipynb`: Main Jupyter notebook with complete exploratory data analysis.
* Dataset is expected to be in `.csv` format, downloaded from Kaggle.

## 📌 Objective

The goal of this project is to extract insights from emergency call records, such as:

* The most common reasons for 911 calls
* Call distribution over time (hours, days, months)
* Patterns in emergency types across different zip codes or townships

## 🛠️ Technologies Used

* Python 🐍
* **Pandas** – for data manipulation and preprocessing
* **NumPy** – for numerical operations
* **Seaborn** – for visualizing distributions and trends
* **Matplotlib** – for plotting charts and graphs

## 📈 Key Insights

Some of the analytical steps and visualizations performed in the notebook include:

* Top 5 zip codes and townships with the highest call volume
* Distribution of call types: EMS, Fire, Traffic
* Trend of 911 calls over hours of the day and days of the week
* Heatmaps to show call frequency over time
* Grouping by 'Reason' derived from the 'title' column for better understanding of the call nature

## 🔧 How to Use

1. Clone this repository or download the `911_project.ipynb` file.
2. Download the dataset from Kaggle: [Montco 911 Emergency Calls Dataset](https://www.kaggle.com/datasets/mchirico/montcoalert/data)
3. Place the dataset in the same directory or update the path in the notebook.
4. Run the notebook using Jupyter Notebook or any compatible Python environment.

## 📚 Dataset Information

* **File:** `911.csv`
* **Columns of Interest:**

  * `lat`, `lng`: Geographic coordinates
  * `title`: Contains reason and description
  * `timeStamp`: When the call was received
  * `twp`: Township
  * `zip`: Zip code
  * `e`: Dummy variable (usually 1)

## 📎 Notes

* The `title` column was split to extract high-level call `Reason` (e.g., EMS, Fire, Traffic).
* Timestamps were converted to datetime format for temporal analysis.
* Missing data handling and type conversions were performed where necessary.

## 📷 Sample Visuals

Visuals include:

* Count plots for top zip codes and townships
* Pie charts and bar plots of call reasons
* Line plots of call frequency over time
* Heatmaps showing patterns in days/hours

## 🧠 Conclusion

This project demonstrates how to clean, explore, and visualize real-world emergency response data to identify actionable insights and patterns. It serves as a foundational example of data analysis using Python and its powerful libraries.

