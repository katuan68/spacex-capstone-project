# SpaceX Falcon 9 Landing Prediction — IBM Applied Data Science Capstone

**Author:** Kieu Anh Tuan  
**Goal:** End-to-end pipeline to analyze and predict Falcon 9 first-stage landing success.

## Notebooks (open in GitHub)
- 1️⃣ Data Collection (API): `notebooks/1-Complete-the-Data-Collection-API-Lab-kieuanhtuan.ipynb`
- 2️⃣ Data Collection (Web Scraping): `notebooks/2-Complete-the-Data-Collection-with-Web-Scraping-kieuanhtuan.ipynb`
- 3️⃣ Data Wrangling: `notebooks/3-Data-wrangling-kieuanhtuan.ipynb`
- 4️⃣ EDA with SQL: `notebooks/4-Complete-the-EDA-with-SQL-kieuanhtuan.ipynb`
- 5️⃣ EDA with Visualization: `notebooks/5-EDA-with-Visualization-Lab-kieuanhtuan.ipynb`
- 6️⃣ Interactive Map (Folium): `notebooks/6-Interactive-Visual-Analytics-with-Folium-lab-kieuanhtuan.ipynb`
- 7️⃣ Predictive Analysis (ML): `notebooks/7-Complete-the-Machine-Learning-Prediction-lab-kieuanhtuan.ipynb`

## Results
- Best model (test): **Logistic Regression ~0.833 accuracy**  

## Reproduce (pip)
```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
