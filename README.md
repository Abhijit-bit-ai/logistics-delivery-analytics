# Logistics Delivery Analytics

An end-to-end logistics data analytics project focused on understanding delivery performance, identifying factors associated with delivery time, and developing data-driven operational insights.

## Project Objective

The main objective of this project is to analyze delivery operations and understand how factors such as distance, traffic, weather, vehicle type, city, and delivery-person characteristics are associated with delivery time.

The project progresses from raw data cleaning and exploratory analysis to visualization and predictive modeling.

## Dataset

The project uses the Zomato Delivery Operations Analytics Dataset.

- Records: 45,584
- Features: 20
- Target Variable: `Time_taken (min)`
- Data includes delivery-person information, restaurant and delivery coordinates, traffic conditions, weather, vehicle information, city, and delivery duration.

## Key KPIs

- Average Delivery Time
- Average Delivery Distance
- Average Delivery Person Rating
- Traffic-wise Average Delivery Time
- City-wise Average Delivery Time

## Project Roadmap

### Week 1 - Strategic Planning and Data Acquisition
- Define the logistics business problem
- Select the dataset
- Define project objectives and KPIs
- Plan the analytical approach
- Prepare the project roadmap

### Week 2 - Data Cleaning and Preprocessing
- Handle missing values
- Check duplicates
- Correct data types
- Clean categorical variables
- Perform feature engineering
- Calculate delivery distance from geographic coordinates

### Week 3 - Data Analysis and Visualization
- Exploratory Data Analysis (EDA)
- KPI analysis
- Traffic, weather, vehicle and city analysis
- Data visualization
- Business insights
- Power BI dashboard (planned)

### Week 4 - Predictive Modeling and Optimization
- Feature preparation
- Regression modeling
- Delivery-time prediction
- Model evaluation
- Clustering analysis
- Operational recommendations

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Power BI
- Git & GitHub

## Current Progress

- [x] Week 1 - Strategic Planning and Data Acquisition
- [ ] Week 2 - Data Cleaning and Preprocessing
- [ ] Week 3 - Data Analysis and Visualization
- [ ] Week 4 - Predictive Modeling and Optimization


## Week 2 – Data Cleaning and Preprocessing

During Week 2, the raw Zomato delivery dataset was cleaned and prepared for further exploratory data analysis and modeling.

### Tasks Completed
- Inspected dataset structure, data types, and missing values
- Checked and handled missing values across important features
- Validated delivery partner age and rating data
- Cleaned categorical variables such as weather, traffic density, city, festival, and multiple deliveries
- Converted `Order_Date` into datetime format
- Investigated inconsistent order and pickup time formats
- Handled both standard time values and Excel fractional-day time values
- Handled special time values such as `24:05`, `24:10`, and `24:15`
- Created `Order_DateTime` and `Pickup_DateTime`
- Engineered `Pickup_Delay_Minutes`
- Checked duplicate records and invalid numerical values
- Validated pickup delay and delivery time
- Exported the final cleaned dataset

### Week 2 Deliverables
- `Week_2_Data_Cleaning.ipynb`
- `Zomato_Delivery_Cleaned.csv`

The cleaned dataset is now ready for exploratory data analysis and visualization in the next stage of the project.



## Author

**Abhijit Das**  
Logistics Data Analyst Intern
