# 📊 Algorhythm Tech-Fest Dashboard

## 📌 Project Overview
**Algorhythm Tech-Fest Dashboard** is a business intelligence solution designed to provide data-driven insights into the financial and operational metrics of the Algorhythm Tech Fest. Developed using **Power BI**, the dashboard transforms traditional manual bookkeeping and static reporting into a dynamic, interactive, and insightful platform.

## 🎯 Objectives
- **Financial Analysis**: Track sponsorships and expenses over multiple years.
- **Performance Evaluation**: Analyze sub-events based on revenue and participation.
- **Trend Visualization**: Provide real-time, interactive visualizations for better strategic planning.

## 🛠️ Technologies Used
- **Power BI**: For dashboard design and visualization.
- **DAX (Data Analysis Expressions)**: For creating calculated columns, measures, and aggregations.
- **Python**: For data cleaning, preprocessing, and automation.

## 📈 Key Features
- **Home Page**: Displays KPIs such as total sponsorship, total expense, and revenue trends.
- **Tech Fest Insights**: Visual analysis of financial metrics with slicers for year and category.
- **Sub-Event Breakdown**: Drill-down insights on individual sub-events, ranked by revenue/participation.
- **Date-wise Revenue Insights**: Time series analysis of revenue growth.
- **Financial Growth Insights**: KPI cards, line charts, and year-wise growth tracking.

## 📂 DAX Queries Implemented
1. **Cumulative Revenue**: Tracks cumulative sponsorship revenue over time.
2. **Ranked Sub-Events**: Assigns rank to sub-events based on participant count.
3. **Total Revenue**: Sums sponsorship and participation-based revenue.
4. **Total Expense**: Sums categorized expense data.
5. **Year / YearKey (Sponsors & Expense)**: Date intelligence for filtering and comparison.
6. **Growth %**: Calculates year-over-year financial growth.

## 🧪 Testing Strategy
- **Unit Testing**: Validate DAX measures against raw data.
- **Integration Testing**: Ensure visuals sync with slicers and filters.
- **User Testing**: Feedback-driven UI/UX refinement from fest organizers.

## 👁️ Preview


  
## 📸 Screenshots

![Image](https://github.com/user-attachments/assets/705adee5-9a34-4de9-a2a4-1ac1e884d501)

![Image](https://github.com/user-attachments/assets/70b1daa5-ce55-4b24-8c86-84124d8df8bf)

![Image](https://github.com/user-attachments/assets/30bea788-18f2-4a38-ba1b-a7e742e6db2c)

![Image](https://github.com/user-attachments/assets/4a84b05e-003b-4898-86d5-f83bec7e3438)

![Image](https://github.com/user-attachments/assets/a814520f-26da-45e0-9875-eedd79e7d2f3)


## 🔍 Challenges Addressed
- Elimination of **manual spreadsheet filtering**.
- Replacement of **static reporting** with dynamic visuals.
- Integration of **custom KPIs** tailored for tech-fest events.

## 🚀 Future Enhancements
- **Real-Time Data Integration**
- **AI-based Trend Predictions**
- **Automated Report Generation**
- **Mobile Accessibility**

## 🧩 How to Create a Foreign Key in Power BI
1. Load your tables into Power BI.
2. Go to **Model View**.
3. Drag the primary key column from the main table to the foreign key column in the related table.
4. Power BI will automatically create a relationship.
5. Ensure cardinality (one-to-many) and cross-filter direction are set correctly.

> For example:
> - Table `Sponsors` has `SponsorID` (Primary Key).
> - Table `Sponsorships` has `SponsorID` (Foreign Key).
> - Drag and drop `SponsorID` from `Sponsors` to `Sponsorships` to link them.

## 👤 Developed By
**Atharva Shelar**

---

🎓 This project is part of the final year academic curriculum to promote smart event management using data analytics and business intelligence tools.
