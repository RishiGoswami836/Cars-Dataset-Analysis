# Analysis of Cars Dataset

This project contains the graphical analysis of Cars Dataset (which has been attached) using Grafana in Ubuntu_kibana.

## Dataset Description

This dataset provides comprehensive information about cars, covering various attributes related to their specifications, performance, and market positioning.
The dataset includes the following columns:

| Column         | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| **make**       | The manufacturer or brand of the car (e.g., Toyota, Ford, BMW).            |
| **model**      | The specific model name of the car.                                         |
| **price**      | The market price of the car.                                               |
| **mpg**        | The mileage of the car in miles per gallon, indicating fuel efficiency.    |
| **engineSize** | The size of the car's engine, typically measured in liters.                |
| **fueltype**   | The type of fuel used by the car (e.g., petrol, diesel, electric).         |
| **transmission** | The type of transmission the car has (e.g., manual, automatic).          |
| **km_driven**  | The total kilometers the car has been driven, usually for used cars.       |
| **tax**        | The annual road tax applicable to the car.                                 |
| **year**       | The year of manufacture or model release.                                  |

---

## Analysis

### 1. **Average Price by Transmission Type**

#### **Question:**  
How does the average price of cars vary across different transmission types (Automatic, Manual, Semi-Auto)?

#### **Interpretation:**  
- Automatic cars are the most expensive (~30,000–50,000), followed by Semi-Auto and Manual (~20,000–25,000).  
- A price spike occurs around 22:00, with convergence of Automatic and Semi-Auto prices after 22:15.  
- The market favors automatic transmissions for performance but values manual for cost stability.

---

### 2. **Engine Size and Price vs. Fuel Type**

#### **Question:**  
What is the relationship between engine size and price for Diesel and Petrol vehicles?

#### **Interpretation:**  
- Diesel vehicles are priced higher than Petrol and maintain steady prices.  
- Petrol vehicles are generally more affordable, with the gap remaining consistent except during a price spike at 22:05.  
- Diesel engines command higher value due to durability and performance.

---

### 3. **Average Engine Size Over Time**

#### **Question:**  
How has the average engine size of cars changed?

#### **Interpretation:**  
- Average engine size hovers around 1.75–2.0L, spiking to ~3.0L at 22:00.  
- The spike indicates a cluster of larger-engine vehicles in the dataset.

---

### 4. **Price-to-MPG Ratio by Fuel Type**

#### **Question:**  
What is the price-to-MPG ratio (cost efficiency) for different fuel types?

#### **Interpretation:**  
- Hybrid: Most cost-efficient (382 price units/MPG).  
- Diesel: Moderate efficiency (519 price units/MPG).  
- Petrol: Least efficient (603 price units/MPG).  
- Hybrids offer the best value, while Diesel provides a balance of performance and efficiency.

---

### 5. **Average Price by Year of Manufacturing**

#### **Question:**  
How does the average price of cars vary across different manufacturing years in the dataset from the last 9 hours?

#### **Interpretation:**  
- The average price of cars increases with newer manufacturing years, ranging from ~12,275 (2013) to ~37,063 (2020).  
- The trend reflects inflation, advancements in technology, and higher demand for premium features in newer models.  
- Older cars depreciate due to age and higher mileage.

---

### 6. **Average Tax by Year**

#### **Question:**  
What is the average tax amount for cars from different manufacturing years, tracked over 5-minute intervals?

#### **Interpretation:**  
- Newer cars (2017–2018) have higher taxes (20%, 19%) compared to older cars (2013–2015) at 16%.  
- Tax policies likely reflect stricter environmental regulations or higher engine capacities in newer vehicles.  
- Businesses can use this to advise on tax-efficient car choices.

---

### 7. **Number of Cars by Transmission Type**

#### **Question:**  
How many cars are there for each transmission type in the dataset?

#### **Interpretation:**  
- Semi-Auto: 1,150 (highest count)  
- Manual: 1,079  
- Automatic: 391 (15% of total)  
- Semi-Auto and Manual dominate, reflecting cost and market preferences.

---

### 8. **Total Tax by Fuel Type**

#### **Question:**  
What is the total tax burden for each fuel type?

#### **Interpretation:**  
- Diesel: 725 units (highest)  
- Petrol: 465 units (64% of Diesel's tax)  
- Hybrid: 135 units (lowest, likely due to eco-friendly incentives).  
- Policies favor Hybrid vehicles, while Diesel faces higher taxes, possibly for environmental reasons.

---

### 9. **Average Price by Engine Size**

#### **Question:**  
How does the average price of cars correlate with engine size?

#### **Interpretation:**  
- Prices range from ~25,000–30,000, with a significant spike to ~45,000 at 22:00.  
- Larger engines correspond to higher prices, particularly in premium or performance vehicles.

---

### 10. **Distribution of Cars by Make**

#### **Question:**  
What is the distribution of cars across different makes (manufacturers)?

#### **Interpretation:**  
- Total: 2,430 cars  
- Price variations suggest clustering in affordable ranges (~25,000–30,000) with occasional spikes in premium models.

---
