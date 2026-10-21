# Plant Disease Prediction

Leaf photo upload karo ya camera se lo. AI bimari batayega, saath me cure aur prevention tips.

## Run locally
```
pip install -r requirements.txt
streamlit run app.py
```

## Deploy on Streamlit Community Cloud
1. Is folder ko GitHub repo me push karo (sab files, `plant_model.keras` bhi).
2. https://share.streamlit.io pe jao, **New app** dabao.
3. Repo chuno, branch `main`, main file `app.py`.
4. Advanced settings me Python 3.11 chuno, phir **Deploy**.

## Files
- `app.py` : main app
- `liquid_ether.html` : animated background
- `cures.json` : bimari ke hisaab se cure/prevention
- `class_names.json`, `plant_model.keras` : model
- `.streamlit/config.toml` : dark theme
