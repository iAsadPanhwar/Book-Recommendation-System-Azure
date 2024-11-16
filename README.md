
# 📚 **Book Recommendation System**

A Machine Learning-based application to recommend books based on user preferences, built with **K-Nearest Neighbors (KNN)** and an intuitive **Streamlit** interface.

---

## 🚀 **Overview**

This project aims to provide book recommendations by analyzing user preferences using collaborative filtering. Leveraging machine learning, the system suggests books similar to the one selected by the user. The application also displays metadata such as book titles and cover images, enhancing the user experience.

---

## 💡 **Key Features**

* **Personalized Recommendations** : Suggests books similar to the one chosen by the user.
* **Book Metadata Display** : Displays book titles and corresponding cover images.
* **Interactive Web Interface** : Easy-to-use, responsive interface built with Streamlit.
* **Scalable Machine Learning Model** : Pre-trained K-Nearest Neighbors (KNN) model optimized for book recommendations.

---

## 🏆 **What’s Achieved**

1. **Data Processing** :

* Processed user-item interaction data to create a pivot table for recommendations.
* Integrated book metadata such as titles and cover images for better visualization.

1. **Machine Learning** :

* Trained a **KNN-based collaborative filtering model** for book similarity.
* Serialized the model and datasets using **pickle** for seamless deployment.

1. **Streamlit Application** :

* Designed an interactive UI that allows users to select a book and view recommendations.
* Displayed results in a grid format with book titles and cover images.

---

## 📂 **Project Structure**

 ├── 📂 artifacts/             # Pre-trained model and serialized data
 │    ├── model.pkl            # Trained KNN model
 │    ├── books_name.pkl       # List of book titles
 │    ├── final_rating.pkl     # Processed dataset with ratings and metadata
 │    └── book_pivot.pkl       # User-item pivot table
 ├── 📄 app.py                 # Main Streamlit application
 ├── 📄 requirements.txt       # List of required Python libraries
 ├── 📄 README.md              # Project documentation
 └── 📂 .gitignore             # Specifies files to exclude from version control

---

## 🖥️ **How to Run the Project**

Follow these steps to run the project locally on your computer:

### 1️⃣ Clone the Repository

Clone the project repository using Git:

```
git clone https://github.com/yourusername/book-recommendation-system.git
cd book-recommendation-system
```

### 2️⃣ Install Dependencies

Ensure you have **Python 3.8+** installed. Then, install the required dependencies:

``pip install -r requirements.txt ``

### 3️⃣ Ensure All Files Are Present

Verify the following files and folders exist in your project directory:

* `app.py`
* `requirements.txt`
* `artifacts/` (containing `model.pkl`, `books_name.pkl`, `final_rating.pkl`, `book_pivot.pkl`)

### 4️⃣ Run the Application

Start the Streamlit application with this command:

```
streamlit run app.py
```


### 5️⃣ Open in Your Browser

After running the command, a URL will appear in the terminal (e.g., `http://localhost:8501`). Open it in your browser to start exploring book recommendations!

---

## 🔧 **Dependencies**

The project uses the following Python libraries:

* **Streamlit** : For building the web application.
* **NumPy** : For efficient numerical operations.
* **Pandas** : For data processing and manipulation.
* **Scikit-learn** : For implementing the KNN recommendation model.

The full list of dependencies is provided in `requirements.txt`.

---

## 🛠️ **How It Works**

1. **Data Loading** :

* Pre-trained model (`model.pkl`) and datasets (`book_pivot.pkl`, `final_rating.pkl`, etc.) are loaded into memory.

1. **User Input** :

* The user selects a book from the dropdown menu in the app interface.

1. **Recommendation Generation** :

* The KNN model identifies books most similar to the selected title.

1. **Result Display** :

* The app displays the recommended books with their cover images in a visually appealing grid layout.

---

## 🌟 **Future Enhancements**

* **Content-Based Recommendations** : Use book metadata like genres, authors, and descriptions to complement collaborative filtering.
* **Search Feature** : Allow users to search for books not listed in the dropdown.
* **Deployment** : Host the application on a cloud service like  **Streamlit Community Cloud** ,  **Heroku** , or **AWS** for wider accessibility.
* **User Feedback** : Add a feature for users to rate recommendations, enabling continuous model improvement.

---

## 📧 **Contact**

 **Author** : *Asad Ali Panhwar*
 **Email** : [asadalipuh5@gmail.com]()

Feel free to reach out with questions, suggestions, or feedback.

---

**Happy Reading! 📖✨**
