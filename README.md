# Netflix Data Analysis with Python

**Project from:** *13 Python Data Analytics Real World Hands-on Projects* (Udemy)  
**Dataset:** Netflix titles (movies & TV shows) up to **2021**

---

## Project Overview
This project performs **exploratory data analysis (EDA)** on the **Netflix content catalog** using **Pandas**. The dataset includes metadata on **movies and TV shows** such as release year, country, genre, duration, rating, and cast.

---

## Dataset Columns
| Column           | Description |
|------------------|-----------|
| `Show_Id`        | Unique ID |
| `Category`       | `Movie` or `TV Show` |
| `Title`          | Name of the title |
| `Director`       | Director(s) |
| `Cast`           | Actors involved |
| `Country`        | Country of production |
| `Release_Year`   | Original release year |
| `Rating`         | Age rating (e.g., TV-14, PG-13) |
| `Duration`       | Length in minutes or seasons |
| `Type`           | Genre(s) |
| `Description`    | Synopsis |

---

## Key Analysis Performed
- Filtered content by **category** and **genre**
- Extracted **duration unit** (`min` or `Season`)
- Answered real-world questions like:
  > *"Show all Movies that are Dramas OR TV Shows that are Kids' TV"*

> **Result:** 322 titles match the criteria  
> - **Movies → Dramas**  
> - **TV Shows → Kids' TV**

---

## Tools & Libraries
```python
pandas

```

### Insights Gained

- **Dramas dominate the movie category**  
- **Kids' TV is a major segment in TV shows**  
- **Duration parsing enables comparison** between movies (min) and series (seasons)  
- **Multi-country productions are common** (e.g., US + South Korea)  
- **Ideal for content strategy, audience targeting, and recommendation systems**
