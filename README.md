# CadetX Project - Sprint 1

* **Shared Team Genre:** Fitness & Health Apps
* **Chosen Individual Product:** MyFitnessPal
* **Justification for the Selection:** I chose MyFitnessPal because it is one of the most widely used food and workout tracking applications globally. It features a massive and highly active user base across various online communities where users frequently post their daily achievements, feature requests, and complaints, making it an excellent source for gathering rich social signal data for our upcoming pipeline analytics phases.
* **List of Platforms for Data Collection:**
    * Reddit: Focus on highly targeted sub-communities such as r/MyFitnessPal and r/Fitness to analyze granular user discussions, feature complaints, and sentiment patterns.
    * Twitter / X: Capture high-velocity, real-time user feedback, spontaneous feature mentions, and direct customer service queries.
    * YouTube: Review video tutorials, comprehensive user-generated product reviews, and associated community comment engagement metrics.

---

## Task 02: External Data Collection Methodology Note

* **Sources Used:** Reddit (r/MyFitnessPal, r/Fitness), Twitter/X, and YouTube.
* **Method:** Data was collected manually by searching public social media streams for keyword mentions of "MyFitnessPal" to track social signal indicators including post volume, engagement counts (likes, views, upvotes), and qualitative consumer sentiment.
* **Why These Platforms Matter:** 
    * Reddit provides long-form text discussions that highlight deep user issues, bug workarounds, and community feature requests.
    * Twitter/X captures immediate, high-velocity real-time feedback and system status alerts.
    * YouTube shows structured reviews, long-term feedback, and tutorial engagement data.

## Task 03: Data Cleaning Note

### 1. Overview
We cleaned the MyFitnessPal social media data to make it ready for analysis.

### 2. Steps Taken
* **Lowercase:** Changed all text to small letters.
* **Noise Removal:** Removed links, emojis, and hashtags.
* **Stopwords:** Removed common words like the, of, and after.
* **Lemmatization:** Shortened words back to their root form.
* **Metrics:** Kept engagement counts as clean numbers.

### 3. File Link
The clean data is saved in myfitnesspal_cleaned_signals.csv.
