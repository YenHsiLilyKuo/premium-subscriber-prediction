# 🎧 Premium Subscriber Prediction

This is a predictive analytics project, aiming to identify which free users are most likely to convert to premium subscribers during a marketing campaign, using user behavior and engagement data.

![Project Type](https://img.shields.io/badge/type-academic--project-blue)
![Language](https://img.shields.io/badge/language-R-1f425f)
![Model](https://img.shields.io/badge/model-Random%20Forest%2C%20Decision%20Tree-orange)

---

## 🔍 Objective

Help a streaming platform target users most likely to become premium subscribers by analyzing:
- Listening habits (e.g., songs listened, loved tracks)
- Social interaction (e.g., shouts, friends who are subscribers)
- Changes in user behavior during the previous campaign

---

## 🧪 Techniques Used

- Data cleaning and exploratory analysis
- Random oversampling to address class imbalance
- Model training with cross-validation
  - Random Forest
  - Decision Tree
- Model evaluation:
  - AUC, ROC, F1 score, confusion matrix
  - Cumulative response curve
  - Feature importance visualization

---

## 🧠 Key Results

| Metric         | Value       |
|----------------|-------------|
| AUC (RF)       | 0.7718      |
| F1 Score (RF)  | ~0.15       |
| Conversion Coverage @ Top 25% Users | ~65% of adopters |

✅ Targeting top 25% of users captures 65% of likely converters  
✅ Model significantly outperforms random targeting

---

## 💡 Feature Insights

Top predictors of premium conversion:
- `lovedTracks`, `delta_songsListened`, `subscriber_friend_cnt`
- Users with more social engagement (e.g., `shouts`)

---
## 💡 Key Takeaways
The streaming platform can target more potential premium subscribers and optimize marketing costs using this predictive model in the next marketing campaigns.

Next Steps: We recommend testing the model in the next marketing campaign and monitor the adoption rates. By collecting more adopters data, we can further refine the predictive model to improve our targeting strategies.
