# Task 07: Cross-Product Comparison & Genre Insights Report

## 1. Cross-Product Comparison Matrix
Below is the benchmarking data comparing our predictive modeling performance across the four baseline products in the Health & Fitness ecosystem:

| Product Name | Model Used | Accuracy | Key Predictor Variable | Primary Platform Driver |
| :--- | :--- | :--- | :--- | :--- |
| **MyFitnessPal** | Logistic Regression | 83.3% | trend_velocity | YouTube / X |
| **Strava** | Random Forest | 85.0% | engagement_ratio | Reddit / Strava Clubs |
| **Nike Run Club** | Gradient Boosting | 88.2% | influencer_weight | Instagram / TikTok |
| **Fitbit** | Logistic Regression | 81.5% | trend_velocity | Online Forums / X |

---

## 2. Genre Insights & Analytical Patterns

### Universal Predictors (Applies to All Products)
* **Trend Velocity:** Across all four models, a surge in community speed and search momentum over a 7-day window serves as a foundational indicator for feature adoption.
* **Engagement Ratio Consistency:** Baseline engagement depth consistently correlates with software feature stickiness regardless of the product type.

### Product-Specific Variances
* **MyFitnessPal vs. Strava:** MyFitnessPal leans heavily on mass viral platforms (YouTube/X) for tracking calorie/diet trend signals. Strava, being community-centric, sees its predictive power shift toward deeper community hubs (Reddit/Internal clubs) where `engagement_ratio` takes priority over influencer pull.
* **Nike Run Club:** Relies profoundly on `influencer_weight` due to high celebrity athletic endorsements, a signal that is far less influential for community-driven tracking apps like Fitbit or Strava.

---

## 3. Strategic Conclusions for Launch Success
To maximize future deployment accuracy, predictive frameworks in the fitness sector should use a hybrid engine: applying global weights to **Trend Velocity** while scaling specific platform coefficients depending on whether the app's core loop relies on social peer pressure (Strava), celebrity endorsement (Nike), or utility tracking (MyFitnessPal).
