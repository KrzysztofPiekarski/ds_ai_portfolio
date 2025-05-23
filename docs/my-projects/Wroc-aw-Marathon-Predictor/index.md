# 🏃‍♂️ Wrocław Marathon Predictor

*Date of creation: 2025-04*

A simple and powerful app that predicts your **half marathon finish time** based on your **5k result**. Powered by **Machine Learning**, enhanced with **Streamlit**, and supported by **Langfuse** & **OpenAI**.

---

## ✨ Features

- 🎯 **Half Marathon Time Prediction**  
  Input your **age**, **gender**, **5k time**, and **pace stability** to receive a predicted finish time.

- ☁️ **Model Source Selection**  
  Load the regression model from either:
  - 🔗 **Cloud** (e.g. DigitalOcean Spaces via S3)
  - 💾 **Local disk**

- ⏱️ **Time Format Compatibility**  
  Supports formats like `MM:SS`, `HH:MM:SS`, and more — the app handles conversion internally.

---

## ⚙️ How It Works

1. 🧾 **User Input**  
   Fill in age, gender, 5k time, and pace stability.

2. 🧠 **Model Choice**  
   Choose between loading the model from a local file or the cloud.

3. 🔄 **Data Preparation**  
   Input data is converted to a numerical format:
   - Time converted to seconds
   - Age and gender categorized

4. 📈 **Prediction**  
   The data is passed to a **trained regression model** to calculate the predicted half marathon time.

5. 📤 **Display**  
   The result is shown in a friendly format like `1h 45m 32s`.

✨ Advanced text processing is handled using **Langfuse** and **OpenAI** for enhanced natural language interaction.

---

## 📦 Installation

### Requirements

Make sure you have the following installed:

- Python 3.x  
- Streamlit
- Joblib  
- Boto3  
- Langfuse  
- Pydantic  
- OpenAI  
- python-dotenv

[Link to repository](https://github.com/KrzysztofPiekarski/Wroc-aw-Marathon-Predictor)
