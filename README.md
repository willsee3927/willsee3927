# Will Charles — Portfolio

This is the source for my personal portfolio site, live at **[willsee3927.github.io](https://willsee3927.github.io/)**. It's where I document the data science and machine learning projects I've worked on, from initial data exploration all the way through to the final model.

I'm a recent graduate with a Master's in Computer Science (Data Science) and a background in Discrete Mathematics. I like discovering insights through data — collecting it, cleaning it, structuring it, and figuring out the clearest way to tell the story it holds. This site is my attempt to show that process, not just the results.

## What's here

Each project gets its own page that walks through how I approached it:

- **Retail Sales Forecasting** — A multi-stage pipeline that forecasts weekly sales across 45 stores. I started from a naive baseline and worked up through time-based regression, SVD denoising, and holiday-aware smoothing to beat the benchmark WMAE.
- **House Price Prediction** — Cleaning and feature engineering on the Ames, Iowa housing data, then ElasticNet and XGBoost models compared across 10 folds.
- **Movie Sentiment Analysis** — An interpretable NLP model that predicts review sentiment and uses SHAP to explain which words drove each prediction.
- **Energy & GDP Narrative** — A narrative visualization exploring the relationship between a country's energy use and income per capita.
- **Global Economics Dashboard** — An interactive Tableau dashboard on global energy and economic trends.

## How it's built

It's a static site, kept deliberately simple:

- Plain HTML with [Tailwind CSS](https://tailwindcss.com/) for styling
- A small custom palette layer (`assets/css/pallete.css`) with CSS variables and light/dark mode
- Interactive Plotly and SHAP charts embedded as standalone HTML in `assets/interactive/`
- Hosted on **GitHub Pages** with a custom domain set via `CNAME`

No build step — just open `index.html` or push to the main branch and it deploys.

## Layout

```
index.html                 Home page — about, portfolio grid, contact
sales-forecasting.html     Project pages
project-house-price.html
movie-sentiment.html
assets/
  css/pallete.css          Theme variables + utility classes
  images/                   Thumbnails and model output charts
  interactive/             Embedded Plotly / SHAP visualizations
```

## Get in touch

Always happy to connect about new opportunities or collaborations.

- Email: wjcc91@gmail.com
- LinkedIn: [williamjcharles](https://linkedin.com/in/williamjcharles)
- GitHub: [willsee3927](https://github.com/willsee3927)
