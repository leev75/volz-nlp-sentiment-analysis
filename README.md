# Volz App — NLP Sentiment Analysis

**Google Play Store · 527 Reviews · Aug 2024 – Mar 2026**

A full NLP pipeline applied to real user reviews of [Volz](https://volz.app) — Algeria's leading flight-booking app. The analysis transforms multilingual user feedback (Arabic, French, English) into a ranked product roadmap and actionable business insights.

---

## Project Overview

| Phase | Description |
|-------|-------------|
| 1 | Data Collection — Google Play scraping (5 configs) |
| 2 | Preprocessing & Feature Engineering |
| 3 | Exploratory NLP Visualizations (9 charts) |
| 4 | Business Insights & Recommendations |
| 5 | Arabic NLP Pipeline (CAMeL Tools) |
| 6 | App Version Sentiment Tracker |
| 7 | Payment Method Granularity Analysis |
| 8 | B2B / Corporate Signal Detector |
| 9 | Diaspora vs Local User Segmentation |

---

## Key Findings

- **74.5%** of reviews are Positive — the app is broadly liked
- **Bugs & Crashes = 100% Pain Index** — every mention is a complaint
- **Pricing** is the #1 driver of dissatisfaction (`trop cher`, `prix`)
- **Core strengths to protect:** `rapide`, `facile`, `excellent`
- **Bimodal rating pattern** — users either love (5★) or hate (1★) the app

---

## Tech Stack

```
Python · Pandas · NLTK · Matplotlib · Seaborn
NetworkX · WordCloud · CAMeL Tools · google-play-scraper
```

---

## Setup & Usage

```bash
# Install dependencies
pip install google-play-scraper pandas nltk matplotlib seaborn \
            wordcloud networkx camel-tools scikit-learn

# Run Phase 1 first to collect data
# Then run each phase sequentially
```

> **Note:** Phase 1 (Data Collection) requires an internet connection to scrape Google Play. All subsequent phases read from the saved CSV file.

---

## Dataset

- **Source:** Google Play Store — `app.volz`
- **Size:** 527 unique reviews after deduplication
- **Period:** August 2024 – March 2026
- **Languages:** Arabic, French, English
- **Scraping configs:** `ar/dz · fr/dz · en/dz · fr/fr · en/us`

---

## Visualizations

| Chart | Description |
|-------|-------------|
| Score Distribution | Rating split across 1–5 stars |
| Sentiment Over Time | Monthly positive/neutral/negative trends |
| Activity Heatmap | User review patterns by day and hour |
| Word Clouds | Top vocabulary per sentiment group |
| N-gram Analysis | Top bigrams and trigrams |
| Co-occurrence Network | Word cluster relationships |
| Topic Overview | Volume and Pain Index per topic |
| Rating Funnel | Keyword analysis per star rating |
| Payment Analysis | Pain index per payment method |

---
**Supervisor:** Nesrine Lahiani  
**Academic Overseer:** Hadjer Ykhlef  
**Year:** 2026
