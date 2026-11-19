# Netflix Data Analysis

## Project Overview

This project explores the Netflix Movies and TV Shows dataset to understand the distribution, characteristics, and content patterns of titles available on Netflix.

Using Python and data analysis libraries, the project examines content types, release years, ratings, countries of production, genres, and movie durations. The analysis uses exploratory data analysis (EDA) and data visualisation to identify meaningful patterns and communicate insights.

## Project Objectives

The main objectives of this project are to:

- Examine the distribution of Movies and TV Shows on Netflix.
- Analyse the distribution of titles by release year.
- Explore the content ratings available on Netflix.
- Identify the countries contributing the most titles.
- Determine the most common genres.
- Examine the distribution of movie durations.
- Present findings through clear and informative visualisations.

## Dataset

**Dataset:** Netflix Movies and TV Shows

**Source:** [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

The dataset contains 8,807 records and 12 columns, including:

| Column | Description |
|---|---|
| show_id | Unique identifier for each title |
| type | Movie or TV Show |
| title | Name of the title |
| director | Director of the title |
| cast | Actors involved |
| country | Country or countries of production |
| date_added | Date the title was added to Netflix |
| release_year | Original release year |
| rating | Content rating |
| duration | Movie duration or number of seasons |
| listed_in | Genre categories |
| description | Brief description of the title |

## Tools and Technologies

The following tools and libraries are used:

- **Python 3.12** – Programming language.
- **Pandas** – Data manipulation and analysis.
- **NumPy** – Numerical operations.
- **Matplotlib** – Data visualisation.
- **Seaborn** – Statistical data visualisation.
- **Jupyter Notebook** – Interactive analysis environment.
- **VS Code** – Development environment.
- **Git and GitHub** – Version control and project hosting.

## Project Structure

```text
netflix-data-analysis/
│
├── data/
│   └── netflix_titles_cleaned.csv
│
├── notebooks/
│   └── netflix_analysis.ipynb
│
├── reports/
│
├── visuals/
│
├── .gitignore
└── README.md
```

## Analysis and Visualisations

The project covers the following areas:

1. **Content Distribution:** Comparison of Movies and TV Shows.
2. **Release Year Analysis:** Examination of the distribution of titles by release year.
3. **Content Ratings:** Analysis of the different content rating categories.
4. **Country Analysis:** Identification of countries with the highest number of titles.
5. **Genre Analysis:** Exploration of the most common genres.
6. **Movie Duration:** Examination of movie running times.

Visualisations generated during the analysis are saved in the `visuals/` directory.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/netflix-data-analysis.git
```

### 2. Navigate into the project directory

```bash
cd netflix-data-analysis
```

### 3. Create and activate the Conda environment

```bash
conda create -n netflix-env python=3.12 pandas numpy matplotlib seaborn jupyter ipykernel
```

```bash
conda activate netflix-env
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Alternatively, open the project folder in VS Code and run `notebooks/netflix_analysis.ipynb` using the `netflix-env` kernel.

## Key Findings

*This section will be updated after completing the exploratory data analysis.*

## Conclusion

This project demonstrates the use of Python for exploratory data analysis, data cleaning, and visualisation. It aims to transform raw dataset information into meaningful insights about the content available on Netflix.

## Author

**Chukwuebuka Delight Amandi**

[LinkedIn](https://www.linkedin.com/in/chukwuebuka-delight-amandi)
