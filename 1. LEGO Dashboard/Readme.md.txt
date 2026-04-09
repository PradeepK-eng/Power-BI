📊 Project Title

LEGO Sets Analytics Dashboard – Interactive Power BI Report

🎯 Objective

To build an interactive, business-driven analytics dashboard using Power BI that helps users explore LEGO datasets by themes, pricing, age groups, and product characteristics, enabling data-driven insights and decision-making.

📖 Project Description This project is a fully interactive Power BI dashboard built on LEGO dataset (~4,385 sets). It focuses on: i) Understanding product distribution across themes, ii) Analyzing price vs pieces relationshipm iii) Exploring age-based segmentation

The dashboard is designed with user-centric navigation, enabling both high-level summaries and deep exploration.

🔧 Technologies Used Power BI Desktop (.pbix), DAX (Data Analysis Expressions), Power Query (ETL), GitHub (Version Control) CSV Dataset

🚀 Features (Your Project Strength 🔥)

📊 Interactive Visualizations: KPI Cards: Total Sets, Avg Pieces, Avg Price, Table with filtering & sorting
🔍 Advanced Filtering System: Theme Group slicer, Age Range slicer, Dynamic filtering across visuals
🔗 Visual Interactions (Highlight) : This dashboard uses cross-filtering + cross-highlighting:
🎯 Custom Tooltip (Advanced Feature): Hover over visuals → shows detailed insights, Improves UX without cluttering dashboard
🔖 Bookmark Actions (Key Highlight): Buttons:, Reset Filters, Set Explore
🎛️ Parameters / Dynamic Inputs: Price range input (manual selection), Enables what-if style exploration
📄 Page Navigation:Multi-view dashboard structure, Smooth navigation using buttons/icons
🌊 Decomposition Tree (Second Image) Deep drill-down: Category → Theme Group → Theme → Set Name Helps identify: High-performing segments Data hierarchy insights 👨‍💻 What Users Can Do
📁 Project Structure (Recommended) LEGO-PowerBI-Dashboard/ │ ├── data/ │ └── lego_sets.csv │ ├── dashboard/ │ └── LEGO Dashboard.pbix │ ├── images/ │ └── dashboard_preview.png │ └── README.md

Users can:

✔ Filter LEGO sets by theme, age, and price ✔ Explore detailed breakdown using decomposition tree ✔ Compare pricing vs pieces ✔ Identify popular categories ✔ Drill down to specific products ✔ Reset dashboard instantly

⚙️ How It Works (Process) Step 1: Data Collection: LEGO dataset (CSV) Step 2: Data Cleaning (Power Query), Removed nulls, Renamed columns, Data type corrections Step 3: Data Modeling, Relationships (if multiple tables), Optimized structure Step 4: DAX Calculations

📊 Business Calculations (DAX) Total Sets = COUNT(Set ID); Avg Pieces = AVERAGE(Pieces); Avg Price = AVERAGE(Price); Price segmentation (
,
$, $$$, $$$$)

📊 Key Insights / Conclusions

Star Wars & Creator themes dominate high-value sets
Higher price → generally higher piece count
Majority of sets target age 5–9 group
Premium sets ($$$$) are limited but high-piece
🧠 What I Learned Advanced Power BI UX design, Bookmark-driven navigation, Using decomposition tree for storytelling, Designing interactive dashboards for real users. Data modeling & DAX optimization

🔧 How to Run the Project Download .pbix file Open in Power BI Desktop Refresh dataset (if needed) Interact with dashboard 🌐 Deployment (GitHub Reality ⚠️ Important)

👉 You CANNOT directly run .pbix in GitHub GitHub is only for: Version control Documentation

👉 According to limitations: PBIX cannot be rendered directly in web/GitHub Embedding requires Power BI Service ✅ Recommended Deployment Options: Option 1: Power BI Service (Best) Publish to Power BI Service Get Embed/Public link

Images: LEGO_1-PBI

LEGO_2-PBI