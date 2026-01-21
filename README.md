# SmartCrop: AI-Driven Sustainability Advisor for Farmers

## 📌 Project Overview
SmartCrop is an AI-powered decision-support tool designed to help small-scale farmers optimize their agricultural output. By analyzing soil chemistry and environmental conditions, the system recommends the most biologically suitable crops to plant, ensuring food security and efficient use of natural resources.

## 🌍 SDG Alignment
This project is strategically aligned with the following United Nations Sustainable Development Goals (SDGs):

- **SDG 2: Zero Hunger** – By maximizing crop yields through data-driven crop selection.
- **SDG 12: Responsible Consumption and Production** – By reducing the overuse of water and chemical fertilizers.
- **SDG 13: Climate Action** – By promoting crops suited to local rainfall and temperature patterns, improving climate resilience.

## ❓ Problem Statement
Small-holder farmers often face low yields and economic instability due to a trial-and-error approach to crop selection. Without scientific insights into soil chemistry such as Nitrogen, Phosphorus, and Potassium, along with environmental conditions like rainfall, temperature, and humidity, farmers frequently grow crops that are biologically unsuitable for their land. This results in inefficient water usage and excessive application of chemical fertilizers, leading to long-term soil degradation.  

How might we provide farmers with an accessible AI-powered tool to predict the most efficient crops for their land, thereby ensuring food security and reducing agricultural waste?

## 💡 Solution & AI Elements
The proposed solution is a machine learning-based recommendation system that functions as a digital agricultural extension officer.

- **Machine Learning Model:** Uses a Random Forest Classifier to deliver accurate crop recommendations.
- **Transparency (XAI):** Incorporates Feature Importance visualizations to explain why a specific crop was recommended.
- **Confidence Scoring:** Each prediction includes a probability score to enhance user trust.
- **Sustainability Advisor:** Integrates a knowledge base providing water-saving tips and soil health recommendations, supporting SDG 12.

## 👥 Target Users
- **Small-holder Farmers:** Seeking affordable, expert guidance to improve yield and income.
- **Agricultural Extension Officers:** Supporting data-driven advisory services for rural communities.

## 📊 Visualizations
The project includes the following analytical visualizations:
- **Correlation Heatmap:** Displays relationships between soil nutrients and climate parameters.
- **Nutrient Distribution:** Boxplots illustrating NPK requirements across different crops.
- **Rainfall Requirements:** Bar charts distinguishing drought-resistant crops from water-intensive ones.

## ⚖️ Responsible AI Considerations
- **Fairness:** The model is trained on a balanced dataset of 22 crop varieties to prevent bias.
- **Transparency:** Feature Importance plots make the model’s decision logic interpretable.
- **Privacy:** No personal or sensitive farmer data is collected; only anonymous soil and weather data is used.

## 🚀 How to Use
1. Upload `Crop_recommendation.csv` to the environment.
2. Run the notebook cells sequentially to train the model.
3. Use the `recommend_crop_with_confidence()` function to generate predictions.
4. Review the `sustainability_advisor()` output for eco-friendly farming guidance.

## 📦 Submission Deliverables
- **Prototype:** Google Colab notebook implementing the Random Forest model.
- **Dataset:** `Crop_recommendation.csv`.
- **Impact:** Improved crop yields (SDG 2) and reduced chemical and water usage (SDG 12).
