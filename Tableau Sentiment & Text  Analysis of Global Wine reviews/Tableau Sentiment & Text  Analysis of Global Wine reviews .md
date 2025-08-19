# Sentiment & Text Analysis of Global Wine Reviews  

📊 **Duration:** 4 months  
🍷 **Dataset:** 6,000 wine reviews across 3 continents (Europe, North America, South America)  
🛠️ **Tools Used:** Netlytic, Tableau  

---

## 📌 Project Overview
This project was born from a classic challenge in consumer goods:  
**How can thousands of unstructured, subjective customer reviews be transformed into quantifiable, strategic insights?**  

The dataset consisted of **6,000 wine reviews**—rich in detail but chaotic in form. The goal was to architect an **end-to-end text analytics pipeline** to uncover the words, sentiments, and themes that shape global wine preferences.  

---

## 🔑 Approach
My guiding philosophy:  
> “Every review is a story, and at scale, those stories become a strategy.”  

1. **Data Structuring (Netlytic)**  
   - Transformed raw review text into structured datasets.  
   - Generated "bag of words" models to quantify word frequencies per continent.  

2. **Exploratory Visualization (Tableau)**  
   - Created treemaps of the **top 150 terms** per continent.  
   - Initial insight: generic terms (“wine,” “fruit,” “flavors”) dominated → limited business value.  

3. **Pivot to Sentiment Analysis**  
   - Integrated pre-processed CSV of **polarity (compound) sentiment scores**.  
   - Built histograms of sentiment distributions by continent.  

4. **Comparative Insights**  
   - Europe & North America: moderately positive reviews.  
   - **South America:** strong positive skew, significantly higher density of extremely positive reviews.  

---

## 📈 Key Visuals

### Average Price & Review Points of Wine by Country
![Price vs Points](./images/Screenshot1.png)

### Word Frequency Clouds (Top 150 Terms)
![Top Terms](./images/Screenshot2.png)

### Sentiment Distribution by Continent
![Sentiment Distribution](./images/Screenshot3.png)

---

## 💡 Insights
- **Language Consistency:** The vocabulary of wine reviews is globally similar (fruit, flavors, palate).  
- **Sentiment Divergence:** South American reviews show **higher emotional intensity**, with a greater proportion of near-perfect sentiment scores.  
- **Strategic Implication:** For businesses, this suggests tailoring marketing to emphasize **passionate consumer sentiment in South America** while focusing on **refinement and sophistication** in Europe and North America.  

---

## 🛠️ Tools & Tech
- **Netlytic** → text cleaning, bag-of-words extraction.  
- **Tableau** → data visualization, dashboards, comparative analysis.  

---

## 🚀 What This Project Demonstrates
✔️ Ability to build **end-to-end text analytics pipelines**.  
✔️ Skill in **pivoting analysis** from frequency-based to sentiment-driven insights.  
✔️ Competence in **turning unstructured text into business strategy**.  
✔️ Expertise with **Netlytic** (text analysis) and **Tableau** (visual storytelling).  

---

## 📂 Repository Structure
```
.
├── data/               # (optional) CSV files, polarity scores
├── images/             # Screenshots & visualizations
├── notebooks/          # Preprocessing or sentiment scripts (if applicable)
├── README.md           # Project documentation
```

---

## 📢 Future Work
- Expand dataset beyond 6,000 reviews for stronger generalization.  
- Integrate **topic modeling (LDA)** to uncover hidden themes beyond word frequency.  
- Deploy interactive **Tableau dashboards** for live exploration.  

---

## 👤 Author
**Kripa Hariharan**  
- Mechanical Design & Product Development | Data Visualization Enthusiast  
- 🌐 [Portfolio](http://harandesigns.com) | [LinkedIn](https://linkedin.com/in/kripahariharan)
