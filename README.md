
# Netflix Data Analysis

This project performs an exploratory data analysis (EDA) of Netflix titles using R and various libraries. The dataset includes information about movies and TV shows on Netflix, such as title, director, cast, country, date added, and other metadata.

## Libraries Used

The following R libraries are used in this project:

- **tidyverse**: Collection of R packages for data manipulation and visualization.
- **forcats**: Handling factors in R.
- **janeaustenr**: Text mining dataset.
- **tidytext**: Text mining and sentiment analysis.
- **reshape2**: Reshaping data.
- **lubridate**: Working with date and time objects.

## Dataset

The dataset used for this project is the `netflix_titles.csv` file, which contains the following columns:

- `show_id`
- `type`
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `description`

## Analysis Steps

1. **Data Import and Overview**: Reading the dataset, checking column types, and summarizing basic information.
2. **Data Cleaning**: Handling missing values, separating columns for analysis, and ensuring data consistency.
3. **Country Analysis**:
    - Analyzing the number of movies per country.
    - Visualizing the top countries producing movies on Netflix.
4. **Genre Analysis**:
    - Identifying popular genres on Netflix globally and in specific countries (e.g., the United States and India).
5. **Text Analysis**:
    - Performing tokenization and text analysis on movie descriptions.
    - Finding similar movies based on term frequency.
6. **Temporal Analysis**:
    - Analyzing the trend of movies and TV shows added over time.

## Visualizations

- Bar charts and histograms for country and genre distribution.
- Polar plots for top movie types in the US and India.
- Density plots and frequency polygons for temporal trends.

## Results

- The United States and India contribute the most movies to Netflix.
- Dramas and International Movies are the most popular genres globally.
- Movies dominate in quantity compared to TV shows, but the trend for TV shows has increased in recent years.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## MIT License

```
MIT License

Copyright (c) 2024 Sukrut Bidwai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
