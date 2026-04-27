# AgriNutrientNet-Deep-Learning-Based-Estimation-of-Micronutrient-Deficiency-in-Crops
🌱AgriNutrientNet is a Deep Learning based web application  that identifies crop type and detects nutrient deficiencies from plant leaf images.  The system helps farmers, students, and researchers quickly diagnose crop health issues and receive fertilizer recommendations.
Built using Flask, TensorFlow/Keras, SQLite, HTML, CSS, JavaScript.

🚀 Features
✅ Detect crop type from uploaded leaf image  
✅ Identify nutrient deficiency automatically  
✅ Show prediction confidence score  
✅ Provide fertilizer / treatment recommendation  
✅ User Sign Up / Sign In system  
✅ Contact inquiry form with database storage  
✅ Attractive responsive UI with glassmorphism design  
✅ SQLite database integration  

 🧠 Supported Crops
- Banana   
- Bottle Gourd 
- Cucumber   
- Maize  
- Rice 
- Tomato

🔬 Nutrient Deficiency Detection
The system can detect multiple deficiencies such as:
- Nitrogen  
- Phosphorus  
- Potassium  
- Zinc  
- Iron  
- Magnesium  
- Boron  
- Calcium  
- Sulphur  
- Healthy Leaf  
(Varies by crop)

🛠️ Tech Stack
 Frontend
- HTML5
- CSS3
- JavaScript
 Backend
- Python
- Flask
Deep Learning
- TensorFlow
- Keras
- CNN Models
(Due to GitHub file size restrictions, trained model files are not included. Please contact author or train models locally.)
Database
- SQLite
(The SQLite database is created automatically on first run.)

📂 Project Structure
AGRINUTRIENTNET/
│── app.py
│── requirements.txt
│
├── instance/
│   └── agrinutrient.db
│
├── models/
│   ├── crop_model.h5
│   ├── BANANA_deficiency.h5
│   ├── BOTTLE_GOURD_deficiency.h5
│   ├── CUCUMBER_deficiency.h5
│   ├── MAIZE_deficiency.h5
│   ├── RICE_deficiency.h5
│   └── TOMATO_deficiency.h5
│
├── static/
│   ├── css.css
│   ├── Bg.jpeg
│   ├── L1.jpeg ... L14.jpg
│
└── templates/
    ├── base.html
    ├── home.html
    ├── about.html
    ├── contact.html
    ├── signin.html
    ├── signup.html
    └── upload.html
