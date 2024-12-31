# **Crop Recommendation System with Weather Insights** 🌾🌦️

This project is an intelligent web application that assists farmers and agricultural enthusiasts by recommending suitable crops based on soil parameters and providing real-time weather updates.

---

## **Features** 🚀

- **Crop Recommendation**:  
  Built using a **Random Forest** machine learning model to analyze soil parameters and suggest optimal crops for cultivation.

- **Weather Information**:  
  Integrates real-time weather data using an API to provide localized weather insights, including temperature, humidity, and more.

- **User-Friendly Interface**:  
  A responsive and interactive frontend built with **HTML, CSS, and JavaScript** for seamless user experience.

---

## **Technologies Used** 🛠️

### Backend:
- Python  
- Flask (or your backend framework)  
- Machine Learning: Random Forest

### Frontend:
- HTML  
- CSS  
- JavaScript  

### API Integration:
- Weather API (e.g., OpenWeatherMap or similar)

---

## **Setup Instructions** 📦

### Prerequisites:
- Python 3.x  
- Required libraries (install using `pip install -r requirements.txt`)  

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/xaemio/Crop-Recommendation-System-Weather-API-.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Crop-Recommendation-System-Weather-API-
   ```
3. Set up a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Add your Weather API key to the appropriate configuration file (ensure it is not tracked by Git).  
6. Run the application:
   ```bash
   python app.py
   ```
7. Open your browser and navigate to:
   ```
   http://127.0.0.1:5000/
   ```

---

## **Project Structure** 📁

```plaintext
├── api_key.txt             # API key file (add to .gitignore)
├── app.py                  # Backend logic
├── static/                 # Frontend assets (CSS, JS, Images)
│   ├── style.css
│   ├── script.js
├── templates/              # HTML templates
│   ├── index.html
├── .gitignore              # Ignored files
├── README.md               # Project documentation
├── requirements.txt        # Python dependencies
```

---

## **Future Enhancements** 🌟
- Add crop yield prediction based on weather patterns.  
- Enable multi-language support for wider accessibility.  
- Incorporate AI/ML models for pest detection and management.

---

## **Contributors** 👩‍💻👨‍💻
- **Saumya** ([xaemio](https://github.com/xaemio))  
