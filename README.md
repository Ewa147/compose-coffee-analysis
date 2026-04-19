# Compose Coffee — Korean brand sentiment analysis

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

Multi-platform sentiment analysis of **컴포즈커피 (Compose Coffee)**, a Korean coffee chain,
using data from Naver Blog, YouTube, TikTok, and Instagram. The project compares how brand
perception differs across platforms and between Korean- and English-language audiences.

---

## Research questions

1. What is the overall sentiment toward Compose Coffee across Korean social media platforms?
2. Does sentiment differ between Naver Blog (domestic) and international platforms like YouTube and TikTok?
3. Which aspects — taste, price, service, atmosphere — drive positive vs negative sentiment?
4. Does Naver search volume correlate with shifts in sentiment over time?

---

## Data sources

| Platform | Method | Query terms |
|---|---|---|
| Naver Blog | Official Search API | 컴포즈커피 |
| YouTube | Data API v3 | 컴포즈커피, Compose Coffee |
| TikTok | Playwright (unofficial) | #컴포즈커피, #composecoffee |
| Naver DataLab | Official API | 컴포즈커피 |

Raw data is **not committed** to this repo. See `data/README.md` for schema documentation.
