# 🎭 Corpus Analysis: Italian Comedy of the 18th Century

This project explores a corpus of theatrical works from the **18th-century Italian comedy tradition**, with a particular focus on the **genres of plays** and their **structure in terms of number of acts**.  
It was conducted during my internship at the **Sorbonne Center for Artificial Intelligence (SCAI)**, where I focused on **digital humanities**.
---

## 📁 Notebooks

- `Genres.ipynb` – Explore and visualize genres associated with plays and their representations
- `Nombre_d'actes.ipynb` – Analyze the correlation between genre and the number of acts per play

---

## 📊 Dataset

The project uses structured data in CSV format from a theatrical database, including:

- `PlayGenre.csv` – Genre ID and description mappings
- `Event.csv` – Theatrical events
- `Representation.csv` – Specific representations of plays

These are merged into a unified dataset for analysis.

---

## 🧪 Genres.ipynb – Genre Mapping and Distribution

### ✅ What it does:
- Maps **genre IDs to descriptions**
- Merges multiple CSV files to connect plays to their genres and representations
- Provides **frequency counts and visualizations** of genre distribution

### 📈 Key Results:
- The most frequent genres in the corpus are identified and displayed
- You can see how genres like *comédie*, *drame*, or *farce* are distributed across representations
- This provides insight into the **dominant theatrical forms** in Italian comedy of the period

---

## 🔢 Nombre_d'actes.ipynb – Number of Acts per Genre

### ✅ What it does:
- Merges genre, event, and representation datasets
- Associates each play with its **number of acts**
- Computes the **correlation** between genre type and number of acts

### 📈 Key Results:
- Certain genres (e.g. *drame*) tend to have more acts on average than lighter forms like *farce*
- A visual heatmap or grouped barplot reveals **genre-specific structural patterns**
- This supports hypotheses about formal conventions in 18th-century Italian theater

---

## 🧠 Interpretation

- The corpus reveals a **rich variety of genres**, but some are overwhelmingly dominant
- The **number of acts** often correlates with genre, confirming that longer forms like *drame* are structurally more complex
- These findings highlight the interplay between **genre, narrative length, and performance tradition**

---

## ▶️ How to Run

1. Make sure you have Python with `pandas`, `matplotlib`, and `seaborn` installed
2. Place the CSV files in the appropriate folder
3. Run each notebook in order:
   - `Genres.ipynb`
   - `Nombre_d'actes.ipynb`

---

## 👩‍💻 Author

Project by **Chloé Petridis**, as part of a scholarly investigation into the structure and genre conventions of 18th-century Italian comedy. 
