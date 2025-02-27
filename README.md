# SmartTrip Assistant

SmartTrip Assistant is a Streamlit-based web application that utilizes Google Gemini AI to provide smart travel planning. The application offers optimized trip plans, estimated costs, and travel recommendations based on user preferences.

## ✈️ Features

✅ **AI-Powered Travel Planning**: Uses Google Gemini AI to generate personalized travel plans.

✅ **Comprehensive Trip Details**: Provides estimated total budget, travel modes, hotel recommendations, and must-visit attractions.

✅ **Multiple Travel Modes**: Supports flight, train, bus, and car recommendations.

✅ **Customizable Preferences**:
   - Select preferred mode of transport.
   - Choose a currency for budget estimation.
   - Sort travel options by recommended, fastest, or cheapest.

✅ **Interactive UI**: User-friendly interface built with Streamlit.

✅ **Budget Breakdown**: Estimates costs for transport, hotels, food, and activities.

✅ **Weather Forecast & Local Insights**: Provides insights into climate and local culture.

---

## 🛠️ Tech Stack

- **Frontend**: Streamlit
- **AI Model**: Google Gemini Pro
- **Backend**: Python

---

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Suneelsuni/SmartTrip-Assistant.git
cd SmartTrip-Assistant
```

### 2️⃣ Install Dependencies
Ensure you have Python installed, then run:
```bash
pip install streamlit google-generativeai pillow
```

### 3️⃣ Set Up the API Key
- Get a Google Gemini AI API key from [Google AI Studio](https://aistudio.google.com/).
- Add your API key in the `os.environ["GOOGLE_API_KEY"]` line inside the script.

### 4️⃣ Run the Application
```bash
streamlit run app.py
```

---

## 📈 Upcoming Features

🌟 Multi-Destination Trip Planning  
🛠️ Real-Time Flight & Hotel Price Tracking  
👨‍💻 Multi-Language Support  
✨ Offline Mode for Saved Trips  

---

## 📜 License
This project is open-source and licensed under the MIT License.

---
## 📂 Repository Structure
```bash
Suneelsuni/SmartTrip Assistant
├── .gitignore                # Ignore unnecessary files
├── LICENSE                   # License information
├── README.md                 # Project documentation
├── app.py                    # Main Streamlit application
├── banner.png                # Banner image for UI
```
## 👨‍💻 Developed By **Suneel Gangapuram**
