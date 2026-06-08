# IMDb Movies Analysis Dashboard (Tableau)

## Project Overview

As part of my Tableau learning journey, I worked on an IMDb Movies dataset to perform exploratory data analysis and build an interactive dashboard using Tableau.

The objective was to analyze movie trends, genre performance, director activity, and audience ratings to uncover meaningful insights through data visualization.

---

## Live Dashboard

Tableau Public Dashboard:

https://public.tableau.com/views/imdb_movies_dashboard6/Dashboard1

---

## Dashboard Features

* Movies by Year (Trend Analysis)
* Top Genres by Movie Count
* Average Rating by Genre
* Average Rating by Censor Category
* Top Directors by Movie Count
* Interactive Genre Filter
* KPI Cards for:

  * Total Movies
  * Average Rating
  * Total Directors

---

## Key KPIs

* Total Movies: 5,562
* Average Rating: 6.76
* Total Directors: 2,320

---

## Business Questions & Insights

### 1. Why does Action have so many movies but relatively lower ratings?

Action is the most produced genre with 1,577 movies and an average rating of 6.53. While it is not the highest-rated genre, its large volume suggests that popularity and audience demand play a major role in production decisions.

### 2. Does producing many movies lower average quality?

No strong relationship was found between the number of movies produced and average ratings. Genres with high production volumes do not necessarily have lower ratings.

### 3. Does Action have a wider rating range than other genres?

Yes. Action movies show one of the widest rating distributions, indicating a mix of both highly rated and lower-rated movies within the genre.

### 4. Did Action ratings improve or decline over time?

Action movie ratings generally show a declining trend over time. The highest average rating was observed around 1954, while more recent years recorded lower average ratings.

### 5. Are a few creators responsible for most Action movies?

No. Although directors such as Steven Spielberg, Ridley Scott, and Ron Howard appear frequently, Action movie production is spread across many directors rather than being dominated by a small group.

### 6. Why do studios keep making Action movies despite lower ratings?

Action remains the most produced genre in the dataset. This suggests that factors beyond ratings, such as audience demand, commercial appeal, and franchise potential, may influence production decisions.

### 7. Are the highest-rated genres reliable?

The highest-rated genres were Western (8.1 rating from 4 movies) and Film-Noir (7.6 rating from 3 movies). Because these ratings are based on very small sample sizes, they may not be as reliable as genres such as Biography (355 movies) and Drama (1,027 movies), which maintain strong ratings across much larger datasets.

---

## Tools Used

* Tableau Public
* Data Visualization
* Exploratory Data Analysis (EDA)

---

## Dataset Information

The dataset includes:

* Movie Title
* Genre
* Director
* Rating
* Runtime
* Release Year
* Censor Classification

---

## Future Improvements

* Add Box Plot analysis for rating distributions
* Include Gross Revenue analysis
* Add Runtime analysis by genre
* Add Director performance analysis
* Create a Power BI version of the dashboard
* Add advanced interactive dashboard features
