# Marketing Campaign Performance - TensorFlow Business Analyst Project

**End-to-End Deep Learning Solution for Marketing Decision Making**

## Business Problem
Built a complete marketing analytics system that helps companies:
- Predict whether a new campaign will be successful (ROI ≥ 5.0x)
- Forecast exact ROI before spending budget
- Make data-driven budget allocation decisions

## Project Highlights
- **Dataset**: 200,000 real marketing campaigns (Kaggle)
- **Models Built**:
  - TensorFlow Classification (Success/Failure) → 51.6% accuracy
  - TensorFlow Regression (Exact ROI) → MAE ±1.51 ROI points
- **Tech Stack**: TensorFlow (Keras), pandas, scikit-learn, matplotlib, seaborn
- **Business Impact**: 
  - 1.6% better campaign selection than random
  - Clear recommendations for channel, audience & budget optimisation

## Project Structure
marketing_campaign_tf_project/
├── data/                  # raw CSV
├── notebooks/             # EDA + model notebooks
├── src/                   # (future scripts)
├── models/                # saved .h5 models
├── reports/               # charts & insights
└── README.md

## How to Run
1. `git clone https://github.com/yourusername/marketing_campaign_tf_project.git`
2. `cd marketing_campaign_tf_project`
3. `python -m venv venv`
4. `venv\Scripts\activate` (Windows)
5. `pip install -r requirements.txt`
6. Open `notebooks/` and run step-by-step notebooks

## Key Business Recommendations
- Use classification model first to filter campaigns
- Approve budget only if regression predicts ROI ≥ 6.0x
- Focus on high-volume channels (Instagram, Google Ads) across all segments

## Author
Vaishnavi – Aspiring Business Analyst | Marketing Analytics Enthusiast  
[LinkedIn](www.linkedin.com/in/dr-vaishnavi-k-r-577947314) | [Email](mailto:vaishnavirajeshshyni.com)
