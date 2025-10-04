# Kickstarter Project Analysis

## Executive Summary
This project analyzes historical Kickstarter project data (2009–2018) to identify the key factors and trends that contribute to funding success. By exploring success rates across different categories, analyzing outlier performance, and tracking annual trends, this analysis provides **actionable, data-driven insights** for potential investors looking to maximize their funding success and manage platform risk.

---

## Business Problem
A potential investor needs a clear, data-driven strategy for allocating capital on the Kickstarter platform. The objective of this analysis is to cut through the platform's noise to identify patterns and behaviors that differentiate successful projects from failed ones. The key questions addressed in this analysis are:

1.  Which project **category** has the **highest success percentage**?
2.  What does the **most successful project** (by Pledged/Goal ratio) reveal about **high-reward outlier potential**?
3.  Can we identify any **trends** in project **success rates over the years**, indicating market saturation or maturity?
4.  As an investor, what types of projects should you be looking at to guarantee future success?

---

## Results & Business Recommendations
The analysis was performed using **Python (Pandas, Matplotlib, Seaborn)**, with a focus on trend analysis, grouping, and statistical ranking. Key findings and their corresponding business recommendations are as follows:

### Statistically Reliable Categories Are Key
* **Finding:** Categories like **Dance**, **Theater**, and **Comics** consistently show success rates significantly above the platform average. Dance, for example, often maintains a success rate above $60\%$.
* **Recommendation:** Prioritize the allocation of capital to categories that offer the highest **statistical probability of success** for reliable returns.

<img width="634" height="455" alt="output4" src="https://github.com/user-attachments/assets/43855f03-fa20-4cf9-8e97-61c0653fe973" />


### High-Reward Outliers Require Focus
* **Finding:** The project with the highest Goal Completion Percentage was **Exploding Kittens**, which exceeded its goal by over **$87,000\%$**. This demonstrates massive, exponential return potential often found in **Games** and **Design** projects with strong viral appeal.
* **Recommendation:** Reserve a small portion of capital for low-goal projects (over \$1,000) that show **extreme early traction** to capture potentially massive, outlier returns.
  
<img width="967" height="455" alt="output5" src="https://github.com/user-attachments/assets/e3004e23-5635-40f5-a8e0-0e022047e59f" />

### Market Saturation Must Be Managed
* **Finding:** The platform's overall success rate peaked around 2011 and has **declined significantly** since, indicating a more competitive environment due to increased project volume. **Despite this trend, the Dance category emerged as the most successful between 2009 and 2017.**
* **Recommendation:** Due diligence is more critical now than ever before. Investors should no longer rely on average platform success rates but must focus on **niche expertise** and **high-probability categories** like Dance to mitigate increased market risk.


<img width="1229" height="317" alt="output6 1" src="https://github.com/user-attachments/assets/e30f9546-634d-4e9c-86e0-46d5dc1432db" />


<img width="1238" height="316" alt="output7" src="https://github.com/user-attachments/assets/f53a865a-400c-44cd-991f-202faa8188bc" />


---

## Project Structure
| File Name | Description |
| :--- | :--- |
| `Kickstarter+Projects python project.ipynb` | The main Jupyter notebook containing all the code for data cleaning, trend analysis, visualization, and the final investor recommendation. |
| `kickstarter_projects.csv` | The primary dataset containing project details, goals, pledged amounts, and success states. |

**Data Source:** (https://app.mavenanalytics.io/datasets)
