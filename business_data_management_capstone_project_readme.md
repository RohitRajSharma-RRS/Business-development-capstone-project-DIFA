# Business Data Management (BDM) Capstone Project: DIFA Velachery Data Strategy 🚀

[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data_Manipulation-yellow.svg)](https://pandas.pydata.org/)
[![Data Analysis](https://img.shields.io/badge/Data-Analysis-green.svg)]()
[![IITM](https://img.shields.io/badge/IITM-BS_Degree-maroon.svg)]()

Welcome to the repository for my Business Data Management Capstone Project! 

This project demonstrates the end-to-end process of taking raw, real-world business data from an unorganized dataset, cleaning it, analyzing it, and delivering actionable, data-driven recommendations to a real business owner. 

📄 **Read the full detailed study here:** `BDM_Capstone_Final_Report_23f2002469_preview_2.pdf`

---

## 🎯 Project Objectives (The Problem Statement)
I collaborated with **DIFA Velachery**, a franchise-owned, franchise-operated fashion-accessories store in Chennai. The business owner faced two primary challenges:

1. **Product and Store Performance (The Assortment Blind Spot):** The owner lacked a data-driven view of which categories, price points, and sub-types were actually carrying the store's revenue. Buying and display decisions were made entirely on intuition.
2. **Marketing ROI (The Awareness Problem):** The store was spending approximately ₹40,000 a month on marketing with zero measured link to footfall, yet struggled with local brand awareness.

## 🛠️ Methodology & Tech Stack
To provide concrete solutions, I moved the final analysis into a **Python** environment (using `pandas`, `matplotlib`, and `seaborn`) to ensure reproducible and accurate data transformations. 

* **Data Cleaning & Wrangling:** Processed over 17,800 item-month records across 5,888 product identifiers. Standardized 89 raw messy category labels into 38 clean, business-logical categories (e.g., merging 37 separate nail polish shades into one category, removing packaging materials from sales analysis).
* **Analysis Window:** Defined a strict 8-month analysis window (April - November 2025) analyzing a total revenue of ₹1.05 Crores and 81,520 net units sold.
* **Techniques Used:** ABC Classification (Revenue-weighted), Portfolio Screening (Volume vs. Realized Price), Row-normalized Heat Mapping, and Micro-Influencer Scoring Models (Min-Max Scaling).

## 📊 Key Results & Findings

### 1. Extreme Assortment Concentration (The 80/20 Rule in Action)
* **Finding:** Just **7 out of 38 categories drive 81.8% of the store's revenue.** 
* **The "Hero" Category:** *Earrings alone account for 51.0% of total revenue*. Going deeper, just 5 specific earring sub-types (Western, Stud, Jhumkas, Hoops, Flat) carry 36.5% of the *entire store's revenue*.

### 2. Price over Volume
* **Finding:** While unit volume dropped 6.6% in the second half of the year, revenue only fell 3.2%.
* **Insight:** This was driven by a shift in sales mix towards higher-ticket items (like neck sets and bracelets), increasing the average realized price per unit from ₹122.3 to ₹139.1. 

### 3. Data-Driven Marketing Strategy (Solving the ₹40k blind spend)
* **Finding:** Built a custom scoring model evaluating 15 local NIFT (National Institute of Fashion Technology) Chennai student micro-influencers. The score weighted past peak reel views (0.60) and audience ability/efficiency (0.40).
* **Action:** Shortlisted 6 highly targeted creators for a 30-day pilot. Implemented a unique QR/Discount code tracking framework to finally calculate a true **Cost Per Attributed Visit** and **Cost Per Sale**.

## 💡 Actionable Recommendations Provided to the Business
* **Weekly Stock Triggers:** Placed the top 5 earring sub-types on a strict weekly stock-check to prevent out-of-stock losses on the most critical inventory.
* **Visual Merchandising:** Recommended relocating high-value, lower-volume items (Neck sets, bracelets) to premium display spots to capitalize on their recent growth.
* **Marketing Pilot:** Execute the ₹6,000 micro-influencer pilot alongside the ₹40k traditional spend to A/B test true ROI based on tracked redemptions.

---

## 📚 About the Course / Project Background

*"Gains in knowledge without application is a missed learning opportunity" - Roger Best*

**Business Data Management (BDM) Capstone Project**
BDM Capstone Project is an independent research project where the student is expected to reach out to a business firm (either from organized sectors viz., well established businesses in manufacturing, IT, automobile sectors etc. which has excellent systems in place to handle and manage data or from an unorganized sectors like Kirana stores, vegetable vendors etc. which do not maintain proper records), identify the issues or the problem(s) they face, collect primary data pertaining to it, clean the data, analyze it, and provide novel/ valuable insights to the decision maker(s).

BDM theory course is a pre-requisite for this project. While decision making these days is driven by data, it is also important to explain and justify the reasoning behind using a particular approach, report them in a professional manner, by knitting one section to the next and how the novel insights benefits decision maker(s). Thus, this capstone project gives the students a hands-on experience in dealing with real world problems and providing solutions.

**The project has 4 stages of submissions:**
1. **Proposal Stage:** A 4-5 page write-up detailing the organization, problem definition, problem-solving approach, expected timelines (WBS and Gantt Chart), and probable outcomes (20% weightage).
2. **Midterm Submission:** An 8-10 page write-up including tangible evidence (videos/pictures), metadata information, descriptive statistics, preliminary analysis, and initial findings (20% weightage).
3. **Final Report:** An 18-20 page complete report involving an in-depth explanation of the entire process from start to finish. Please see `BDM_Capstone_Final_Report_23f2002469_preview_2.pdf` for my submission (40% weightage).
4. **Viva Voce:** A presentation not exceeding 10 slides defending the final submission (20% weightage).

---
*Developed by Rohit Raj (Roll number: 23f2002469) | IITM Online BS Degree Program*