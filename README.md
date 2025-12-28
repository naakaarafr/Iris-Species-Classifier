# Iris Species Classifier

Interactive ML web app for iris species classification using Random Forest. Built with Streamlit, scikit-learn & pandas. Adjust flower measurements via sliders for real-time predictions of Setosa, Versicolor, or Virginica species.

## 🌸 Overview

This project demonstrates a complete machine learning workflow wrapped in an interactive web interface. Using the classic Iris dataset, it classifies flowers into three species based on their sepal and petal measurements, providing instant predictions as users adjust the input parameters.

## ✨ Features

- **Interactive Web Interface** - Built with Streamlit for an intuitive user experience
- **Real-time Predictions** - Instant classification as you adjust input parameters
- **Visual Slider Controls** - Easy-to-use sliders for inputting flower measurements
- **Random Forest Algorithm** - Robust machine learning model for accurate predictions
- **Optimized Performance** - Automated data caching for faster load times

## 🚀 Quick Start

### Prerequisites

- Python 3.7 or higher
- pip package manager

### Installation

1. Clone this repository:
```bash
git clone https://github.com/naakaarafr/Iris-Species-Classifier.git
cd Iris-Species-Classifier
```

2. Install required dependencies:
```bash
pip install streamlit pandas scikit-learn
```

Or use the requirements file:
```bash
pip install -r requirements.txt
```

### Running the App

```bash
streamlit run Classifier.py
```

The app will automatically open in your default browser at `http://localhost:8501`

## 🎯 How to Use

1. Launch the application
2. Use the sidebar sliders to adjust flower measurements:
   - **Sepal Length** (cm)
   - **Sepal Width** (cm)
   - **Petal Length** (cm)
   - **Petal Width** (cm)
3. View the predicted species in real-time on the main panel

## 🧠 How It Works

### The Dataset

The Iris dataset contains 150 samples of iris flowers with measurements for three species:
- **Iris Setosa**
- **Iris Versicolor**
- **Iris Virginica**

### The Model

A Random Forest Classifier is trained on the complete dataset, learning patterns that distinguish between the three species based on their physical measurements.

### The Prediction

User inputs are collected via sliders, combined into a feature vector, and fed to the trained model which returns the most likely species classification.

## 📁 Project Structure

```
Iris-Species-Classifier/
├── Classifier.py          # Main application file
├── LICENSE               # MIT License
└── README.md            # Project documentation
```

## 🛠️ Built With

- **[Streamlit](https://streamlit.io/)** - Web framework
- **[scikit-learn](https://scikit-learn.org/)** - Machine learning library
- **[pandas](https://pandas.pydata.org/)** - Data manipulation
- **Random Forest Classifier** - ML algorithm

## 📊 Technical Details

- **Model**: Random Forest Classifier (default parameters)
- **Training Data**: 150 samples, 4 features, 3 target classes
- **Features**: Sepal length, Sepal width, Petal length, Petal width
- **Caching**: Streamlit's `@st.cache_data` for optimized performance

## 🔮 Future Enhancements

- Add model evaluation metrics (accuracy, confusion matrix)
- Visualize feature importance and decision boundaries
- Include probability scores for each prediction
- Implement multiple algorithm comparison
- Add data visualization (scatter plots, distributions)
- Support for custom data upload

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- The Iris dataset was introduced by Ronald Fisher in 1936
- Dataset provided by scikit-learn
- Built with Streamlit framework

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/naakaarafr/Iris-Species-Classifier/issues).

## ⭐ Show your support

Give a ⭐️ if this project helped you!
