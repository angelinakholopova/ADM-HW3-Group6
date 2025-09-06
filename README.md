# ADM-HW3_Group6

## Project Overview

This project focuses on creating a restaurant search engine and solving a navigation algorithm problem. The goal was to process and analyze restaurant data, implement efficient search techniques, visualize the results, and solve a grid navigation problem.

---

## Dataset

The dataset was created by web-scraping Michelin-starred restaurants in Italy. It includes:
- **Restaurant Details**: Name, address, city, postal code, country, description, and website.
- **Cuisine Information**: Cuisine type and price range.
- **Facilities and Services**: Details such as terrace, air conditioning, and accepted credit cards.
- **Contact Information**: Phone numbers and URLs.

---

## Objectives

The primary objectives of this project were to:
1. **Build a Search Engine**:
   - Conduct text preprocessing on restaurant descriptions for efficient querying.
   - Implement two types of search engines:
     - **Conjunctive Search**: Returns restaurants where all query terms are present.
     - **Ranked Search**: Ranks restaurants by relevance using `TF-IDF` and cosine similarity.
   - Develop a custom ranking metric to incorporate user preferences, such as price range, facilities, and cuisine type.

2. **Visualize Restaurant Data**:
   - Create an interactive map to display the geographic distribution of restaurants across Italy.
   - Use visual cues (e.g., color or size) to represent price ranges and other restaurant attributes.

3. **Solve the Robot Navigation Problem**:
   - Determine whether a robot can collect packages on a grid using only upward and rightward movements.
   - Find the lexicographically smallest path, or determine if collecting the packages is impossible.
   - Explore alternate approaches when the robot can also move downward and left.


Code from Google Drive: https://drive.google.com/file/d/1SQ_IQCCU7KX_EBjAktLYajek3SCVLbHs/view?usp=sharing


