Movie Recommendation System using Machine Learning

A simple machine learning-based movie recommendation system built in Python using content-based filtering.  
It recommends similar movies based on cosine similarity and visualizes the top 20 results using a vertical bar chart.

---

How It Works

- The system takes a movie title as input.
- It searches for the closest matching movie from the dataset.
- Using cosine similarity, it finds and ranks the 20 most similar movies.
- A bar chart is displayed to visualize the similarity scores of these movies.

---

Files

Files
`AI_FinalPRoject(1).ipynb` | Main Jupyter Notebook (Google Colab supported)
`movies.csv` | Dataset used for generating movie recommendations

---

Technologies & Libraries

- Python
- `pandas`
- `scikit-learn`
- `difflib`
- `matplotlib`

---

Output Example

The output is a list of top 20 recommended movies printed in the notebook,  
followed by a vertical bar chart showing the similarity score of each.

![Sample Bar Chart]
_(https://ibb.co/RkgVsZ4c)_

---

Getting Started

1. Clone or download the repo
2. Open `AI_FinalPRoject(1).ipynb` in Google Collab or Jupyter Notebook
3. Upload `movies.csv`
4. Run all cells
5. Enter a movie name when prompted and view results

---

Credits

This project was based on a tutorial by [Siddhardhan]
Original source: [https://youtu.be/7rEagFH9tQg?si=TLytMOYYiSE_0DTf]

I followed the main logic and structure of the tutorial, and made the following changes:
- Added vertical bar chart visualization using `matplotlib`
- Improved output formatting
- Customized small parts of the code

---

About Me

**Shees Saleem**  
Aspiring AI/ML Engineer | Python Learner | Final Year CS Student  
Reach out: [sheesmemon334455@gmail.com]

---

Future Improvements

- Add collaborative filtering using user ratings
- Add a web interface using Streamlit or Flask
- Expand dataset for more accurate results

---

##License

This project is for learning and demonstration purposes only.
