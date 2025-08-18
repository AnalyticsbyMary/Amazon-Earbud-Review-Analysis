# Amazon Earbuds Sentiment Analysis Dashboard
<img width="790" height="405" alt="earbud" src="https://github.com/user-attachments/assets/1f406f64-db75-4748-9023-34501372b0f9" />

## Project Summary
This project explores customer sentiment from Amazon reviews on earbuds—looking beyond the star rating to understand how customers really feel. One key insight: some customers rate a product 4 stars, but the review itself reads like a complaint. That disconnect makes sentiment analysis essential for accurate customer experience tracking.

## What This Project Covers
- Web Scraping: Amazon reviews were scraped using the Oxylabs API and exported in JSON format.

- Preprocessing: Cleaned and structured into CSV format. Text data was processed using NLTK and TextBlob.

- Sentiment Analysis: Initially attempted model training using IMDb dataset (positive/negative only), but switched to TextBlob to account for neutral sentiments.

- Visualization: Power BI was used to create a dashboard split into three pages: Product Overview, Rating Analysis, Review Details
  
<img width="837" height="481" alt="Review Details" src="https://github.com/user-attachments/assets/c3b11a0c-6272-45f5-8111-ed6c6a95b97f" />
<img width="833" height="482" alt="Rating Analysis" src="https://github.com/user-attachments/assets/de50cec6-3f83-4711-b88d-ee6713927355" />
<img width="831" height="483" alt="Earbud Overview" src="https://github.com/user-attachments/assets/13e5deb9-bbb6-4b10-a7e3-6ec7e1b549cd" />

🔗 Link
[Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZDBkMjM5ZjUtM2RjZC00ODNjLTg2ZmYtNTljYjU5Y2Y1MzdhIiwidCI6Ijc3ZGJjZTk5LTYwNTQtNGFiYS04MjUwLTE5YzBlZmI0MzE4ZCJ9)

## Tools
- Oxylabs API

- Jupyter Notebook

- Power BI

## Key Insights
📌 1. Ratings Alone Can Be Misleading
Many reviews that appear neutral or even negative in content are still paired with 3–4 star ratings. This shows that customers often rate generously, even when their words reveal dissatisfaction. Brands relying solely on star ratings may miss critical feedback signals.

📌 2. Review Length Has No Influence on Sentiment
Contrary to expectations, longer reviews are not more negative or positive than shorter ones. This shows that brevity doesn’t equal satisfaction, and sentiment must be assessed beyond word count.

📌 3. Black Is the Most Preferred Color — Except for Apple
Across all products analyzed, black is the dominant preference for earbuds — except for Apple AirPods, which do not offer a black variant. This suggests an opportunity for Apple to tap into a clear market preference.

📌 4. Rating Consistency Varies by Brand
1MORE ComfoBuds had the highest rating inconsistency, meaning customers gave a wider range of star ratings.
Apple AirPods had the most consistent ratings, suggesting more uniform customer satisfaction or clearer expectations.

📌 5. Common Customer Concerns Center Around Key Features
Across brands, customers repeatedly mentioned:

- Good sound quality

- Noise cancellation performance

- Ear fit and comfort

- Battery life and durability
These are the core features that influence satisfaction and retention in this category.

📌 6. Target Audience Positioning Is Clear from Product Traits
From design to feature emphasis, each product appears tailored to specific customer segments from:

fitness-focused users with sporty design and sweat resistance to brand-conscious, minimalist users and to tech-savvy or price-conscious users.

Recognizing this can help brands double down on their core audience or expand into adjacent segments.

<img width="1920" height="1080" alt="2025" src="https://github.com/user-attachments/assets/cc1d3b7b-bfec-415a-a6d7-b813d6870f18" />






