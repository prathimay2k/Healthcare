# 🏥 Healthcare Dashboard Analysis

This project analyzes healthcare data from 2,335 patients to uncover how factors such as diabetes, weight, age, transplant history, smoking, and hospital types affect healthcare costs. The findings are presented using interactive visuals built in Power BI (or Excel), providing insights for better healthcare planning, prevention, and policy-making.

---

## 📊 Executive Summary

The dashboard explores multiple dimensions of healthcare data. It shows that **obese diabetic patients incur the highest costs**, while patients aged **41–60 are the most expensive group to treat**. Smoking is strongly associated with cancer history, and transplant patients show poor diabetic control and undergo more surgeries. Additionally, the analysis highlights that **Tier 3 hospitals are the most costly**, with significant cost differences across states.

This dashboard provides a holistic view of patient health and resource utilization, supporting smarter decisions in health system management.

---

## 📈 Visual Insights

Here’s a breakdown of the key visual insights:

- **Weight & Diabetes vs. Cost**: Obese and diabetic patients contribute the highest share of healthcare expenses. Costs decrease significantly for healthy weight and non-diabetic patients.
  
- **Transplant Status**: Patients who have undergone transplants show **higher average HbA1C** levels (indicating poor diabetic control) and undergo more surgeries compared to non-transplant patients.

- **Smoking vs. Cancer**: A strong link is observed between smoking and cancer. 23% of smokers have a history of cancer, compared to only 7% of non-smokers.

- **Age vs. Healthcare Charges**: Healthcare costs rise steadily with age and peak between **ages 41–60**. There’s a slight decline post-60, possibly due to lower treatment intensity.

- **Hospital Tier Charges by State**: **Tier 3 hospitals** are significantly more expensive, with wide variation in charges depending on the region. Tier 1 hospitals are more cost-effective and consistent.


## 📘 Lessons Learned

This project provided valuable insights into healthcare management:

- **Prevention is cheaper than treatment**: Costs spike when conditions like obesity and diabetes are unmanaged.
- **Middle-aged adults (40–60)** generate the highest medical expenses due to accumulated chronic illnesses.
- **Smoking has a lasting cost impact**, especially in relation to cancer.
- **Transplant patients require ongoing monitoring**, especially for diabetes and surgical follow-ups.
- **Hospital costs vary** greatly by tier and region, indicating the need for standardization and pricing transparency.
- **Good data enables good policy**: Visual dashboards like this help identify high-risk populations and areas for cost control.

---

## 🧰 Tools Used

- **Excel / Power BI** – Dashboard creation and data visualization  
- **Pandas (optional)** – Data preparation  
- **Visualization Types** – Bar Charts, Donut Charts, Line Graphs, Pie Charts  
- **Analysis Framework** – High-level storytelling, targeted insights, actionable recommendations

---

## 📁 Repository Contents

- `Healthcare_Dashboard.pbix` / `.xlsx` – Main dashboard file  
- `README.md` – Project documentation  
- `Findings_Recommendations.xlsx` *(optional)* – Tabular summary of insights and actions  

---

## 🔄 Future Work

- Predictive modeling (e.g., cost forecasting using regression or ML)
- Trend tracking over time (time-series analysis)
- Deeper clinical outcome analysis per hospital tier


