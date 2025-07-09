# Movie Genre Ratings Analysis

This project explores trends in movie ratings using a dataset from my IT course. 
The goal was to analyze how ratings and popularity vary across genres and over time.

## Tools Used:
- Google Colab (Python, Pandas, Matplotlib)
- GitHub for version control
- Dataset: `moviesBasicData.csv`

---

## Key Analyses & Insights

### 1. ⭐ Average Rating by Genre
> **Crime movies** had the highest average ratings among all genres, followed closely by Action, Adventure, and Animation.  
> **Comedy** and **Romance** genres had the lowest average ratings in this dataset.

![Genre Ratings Bar Chart](genre_rating_chart.png)

---

### 2. Movies Released Per Year
> The number of movies released per year shows fluctuations, with some notable increases in recent decades. This might reflect growth in the film industry or broader distribution.

```python
# Code run for this:
movies_per_year = df['year'].value_counts().sort_index()

Next Steps:
Analyze trends in director-specific ratings
Explore correlation between rating volume and average score
Compare genre performance over time
