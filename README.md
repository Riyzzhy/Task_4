Name : PATEL RIYANSH BHAVESHBHAI Company : CODTECH IT SOLUTIONS Intern_ID : CT04DF487 Domain : MACHINE LEARNING Duration Time : 24 MAY TO JUNE 2025 Mentor Name : NEELA SANTHOSH KUMAR


📚 Book Recommendation System – Project Overview

The Book Recommendation System is a machine learning-based web application that helps users discover books similar to the ones they love. Built using collaborative filtering techniques, the system analyzes user ratings and book features to suggest the most relevant and popular titles. This project uses the publicly available Book-Crossing dataset, which contains thousands of books, user ratings, and metadata like authors and book covers.
The core idea is to provide intelligent book recommendations by calculating similarity scores between books using user behavior patterns. The similarity scores are precomputed using techniques like cosine similarity applied on a pivot table of users vs books, and then stored for quick access. Alongside, a list of the most popular books is also displayed on the homepage based on average ratings and number of votes.
This project is ideal for demonstrating the application of machine learning for recommender systems, Flask for web deployment, and effective use of data preprocessing and storage techniques using pickle files.

The project is structured to be modular, scalable, and easy to deploy either locally or on a platform like Heroku or Replit. It offers a minimal front-end interface, ensuring a seamless and intuitive experience for users who want quick, meaningful book suggestions.

🚀 Project Features
Recommends top similar books based on a selected book
Uses collaborative filtering and similarity scores
Flask-based web app with a user-friendly interface
Utilizes real-world book ratings dataset (Book-Crossing Dataset)
![InterfaceMasaWorksDesignGIF](https://github.com/user-attachments/assets/54063962-7e38-4c28-8829-27916848c613)


![2](https://github.com/user-attachments/assets/074628c4-ebc3-455a-b965-ca5cb0634e0e)




📂 Project Structure
├── app.py                      # Flask application
├── book-recommender-system.ipynb  # Jupyter Notebook for model development
├── templates/
│   ├── index.html              # Home page UI
│   └── recommend.html          # Recommendation result UI
├── popular.pkl                 # Pickled DataFrame of popular books
├── pt.pkl                      # Pickled pivot table for books vs users
├── books.pkl                   # Pickled book metadata
├── similarity_scores.pkl       # Pickled cosine similarity scores
![1](https://github.com/user-attachments/assets/3cfa1e0a-c665-4336-9526-9b3abbbda30b)


📊 Dataset Used
This project uses the Book-Crossing Dataset, which includes:
books.csv: Book details (title, author, image)
ratings.csv: User ratings of books
users.csv: Metadata of users

🛠️ Tech Stack
Python 3
Flask (for web app)
Pandas, NumPy (for data handling)
Scikit-learn (for similarity model)
HTML/CSS (for basic UI)

⚙️ How It Works
User selects or types a book name.
System finds the book's index in the pivot table.
Retrieves cosine similarity scores for the book.
Displays top 4 most similar books with title, author, and image.

