# Exploring-San-Diego-Burrito-Ratings

# 🌯 Exploring San Diego Burrito Ratings

This project analyzes burrito ratings and Yelp reviews from 65 San Diego restaurants collected in 2016. By using Excel for data aggregation, ranking, and conditional formatting, the goal is to identify top burrito spots, uncover trends, and create meaningful insights around local food reviews.

## 📊 Dataset Summary

- **Year**: 2016  
- **Scope**: 65 San Diego burrito-serving locations  
- **Dimensions**:
  - `Location`, `Burrito`, `Date`, `Recommendation`, `Reviewer`, `Notes`
- **Measures**:
  - `Yelp Rating`, `Cost`, `Tortilla (0-5)`, `Temp (0-5)`, `Fillings (0-5)`, `Meat Volume (0-5)`, `Uniformity (0-5)`, `Salsa (0-5)`, `Synergy (0-5)`, `Wrap Quality (0-5)`

## 🛠 Skills Demonstrated

- COUNT & Aggregation
- AVERAGE & SUM in PivotTables
- RANK with “Show Values As”
- Conditional Formatting for Heat Mapping
- Calculated Fields in PivotTables

---

## 🔍 Analysis Tasks & Insights

### ✅ Task 1: Compare average ratings for Tortilla, Temp, Fillings, Synergy, and Wrap Quality by location

📄 *Check:* `San-Diego-Burrito-Ratings.xlsx` → Sheet **"Task 1"**

**Insight**:  
Comparing these five core quality metrics by location gives a holistic view of where each restaurant excels—or underperforms—beyond just Yelp scores.

---

### ✅ Task 2: How many locations recorded more than 2 ratings?

**Answer**:  
- 📍 *19 locations*

📄 *Check:* `San-Diego-Burrito-Ratings.xlsx` → Sheet **"Task 2"**

**Insight**:  
Only a portion of locations had sufficient review volume, which is important when weighing average scores—more reviews often lead to more reliable insights.

---

### ✅ Task 3: Create a calculated field for "Average Total Score" by location

**Formula**:  
```

(('Tortilla (0-5)' + 'Temp (0-5)' + 'Fillings (0-5)' + 'Synergy (0-5)' + 'Wrap Quality (0-5)') / 5) / 'Number Review'

````

📄 *Check:* `San-Diego-Burrito-Ratings.xlsx` → Sheet **"Task 3"**

**Insight**:  
This composite metric provides a standardized way to compare overall burrito quality across restaurants, balancing outliers and focusing on consistency.

---

### ✅ Task 4: Among locations with more than 2 reviews, which one is ranked #7?

**Answer**:  
- 🏅 *Rigoberto's Taco Shop*

📄 *Check:* `San-Diego-Burrito-Ratings.xlsx` → Sheet **"Task 4"**

**Insight**:  
Even if not #1, being in the top 10 suggests strong performance across multiple quality dimensions—making Rigoberto’s a consistent choice for burrito fans.

---

### ✅ Task 5: Which location has the highest and lowest average total score?

**Answer**:  
- 🔝 *Highest*: **Los Tacos** (4.08)  
- 🔻 *Lowest*: **Goody's** (1.97)

📄 *Check:* `San-Diego-Burrito-Ratings.xlsx` → Sheet **"Task 5"**

**Insight**:  
The scoring range shows significant variation in perceived quality—some spots clearly stand out, while others may need serious improvement or repositioning.

---

### ✅ Task 6: How does the Average Yelp Rating compare to the Average Total Score field?

**Answer**:  
- ✔️ *They follow a similar directional trend*

📄 *Check:* `San-Diego-Burrito-Ratings.xlsx` → Sheet **"Task 6"**

**Insight**:  
Even though the metrics are from different sources (external review vs. internal criteria), they align directionally—validating the reliability of the internal scoring method.

---

## 📂 Repository Structure

```plaintext
📁 Exploring-San-Diego-Burrito-Ratings/
├── 📄 README.md
└── 📊 San-Diego-Burrito-Ratings.xlsx
````

---

## 📬 Contact

* **LinkedIn**: [Max Nguyen Hoang Minh](https://www.linkedin.com/in/max-nguyen-hoang-minh)
* **Email**: [maxnguyenhoangminh@gmail.com](mailto:maxnguyenhoangminh@gmail.com)
* **WhatsApp**: +84 96 958 74 45

---


