# Veecook-AI-Recommendation

An AI-powered recipe recommendation system that helps users discover personalized recipes based on their preferences and available ingredients.

## 🚀 Features

- Personalized recipe recommendations using AI/ML algorithms
- User-friendly web interface
- Ingredient-based recipe search
- Recipe details including ingredients, instructions, and nutritional information
- Data-driven approach using a comprehensive recipe dataset

## 🤖 AI/ML Components

The system utilizes several advanced machine learning techniques:

1. **Text Processing**
   - TF-IDF (Term Frequency-Inverse Document Frequency) vectorization for ingredient text processing
   - Converts ingredient lists into numerical features for ML processing

2. **Feature Engineering**
   - Nutritional features (calories, fat, carbohydrates, protein, etc.)
   - Ingredient-based features
   - Standardized scaling of numerical features

3. **Recommendation Algorithm**
   - K-Nearest Neighbors (KNN) algorithm for similarity-based recommendations
   - Hybrid approach combining:
     - Content-based filtering (ingredients and nutritional content)
     - Feature-based similarity matching

4. **Data Processing**
   - Pandas for data manipulation and preprocessing
   - NumPy for numerical computations
   - Scikit-learn for ML pipeline implementation

## 🧠 AI/ML Methods & Techniques

### 1. Data Preprocessing
- **StandardScaler**: Normalizes numerical features (calories, fat, protein, etc.)
- **TF-IDF Vectorization**: Converts text-based ingredient lists into numerical vectors
- **Feature Selection**: Combines nutritional and ingredient-based features
- **Data Cleaning**: Handles missing values and outliers

### 2. Machine Learning Algorithms
- **K-Nearest Neighbors (KNN)**
  - Used for similarity-based recipe recommendations
  - Euclidean distance metric for feature comparison
  - Configurable number of neighbors (k) for recommendation diversity

### 3. Feature Engineering Techniques
- **Text Feature Extraction**
  - TF-IDF vectorization for ingredient lists
  - Word embedding for ingredient similarity
- **Numerical Feature Processing**
  - Standardization of nutritional values
  - Feature scaling for balanced comparison

### 4. Recommendation System Approach
- **Hybrid Recommendation System**
  - Content-based filtering using ingredient similarity
  - Feature-based matching using nutritional content
  - Combined similarity scoring for final recommendations

### 5. Model Evaluation Metrics
- Cosine similarity for recipe matching
- Feature importance analysis
- Recommendation diversity measurement

## 📋 Prerequisites

- Python 3.x
- Flask
- Pandas
- NumPy
- Scikit-learn
- Other dependencies listed in requirements.txt

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Veecook-AI-Recommendation.git
cd Veecook-AI-Recommendation
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## 💻 Usage

1. Start the Flask application:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

3. Enter your preferences or available ingredients to get personalized recipe recommendations.

## 📁 Project Structure

```
Veecook-AI-Recommendation/
├── AI-Powered-Recipe-Recommendation/
│   ├── app.py                 # Main Flask application
│   ├── templates/             # HTML templates
│   ├── static/               # Static files (CSS, JS, images)
│   ├── recipe_final.csv      # Dataset
│   ├── recipe_recommendation_system.ipynb  # Jupyter notebook for model development
│   └── Data Preparing.ipynb  # Data preprocessing notebook
├── README.md
└── requirements.txt
```

## 🔍 How It Works

The system uses machine learning algorithms to:
1. Process and analyze recipe data
2. Understand user preferences
3. Generate personalized recipe recommendations
4. Present results in an intuitive web interface

## 📊 Data

The system uses a comprehensive recipe dataset that includes:
- Recipe names and descriptions
- Ingredients and quantities
- Cooking instructions
- Nutritional information
- Cooking time and difficulty

