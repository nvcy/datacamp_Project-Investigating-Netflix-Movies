# 🎞️ Project: Investigating Netflix Movies

This project explores Netflix's movie catalog with a focus on **movies from the 1990s**. As part of a data analysis initiative for a nostalgic film production company, we aim to understand movie duration trends, genre prevalence, and other characteristics of that golden decade in cinema.

---

## 📂 Dataset: `netflix_data.csv`

The dataset contains metadata about Netflix shows and movies. It was provided as part of the **DataCamp Python Data Associate Exam**.

| Column Name    | Description                                      |
|----------------|--------------------------------------------------|
| `show_id`      | Unique ID for the show/movie                     |
| `type`         | Type of content: Movie or TV Show                |
| `title`        | Title of the show/movie                          |
| `director`     | Director's name                                  |
| `cast`         | List of main actors                              |
| `country`      | Country where the show/movie was produced        |
| `date_added`   | Date added to Netflix                            |
| `release_year` | Release year of the show/movie                   |
| `duration`     | Duration in minutes (for movies) or seasons      |
| `description`  | Short summary of the content                     |
| `genre`        | Primary genre category                           |

---

## 🎯 Objective

Your company specializes in **nostalgic productions**, especially those resembling 1990s classics. This analysis investigates:

- 📅 How many movies were released in the 1990s?
- ⏱️ What was the typical duration of those films?
- 🎬 What genres were dominant?
- 🔫 Specifically, how many short (< 90 minutes) action movies were released in the 1990s?

---

## 🛠️ Technologies Used

- **Python 3**
- **pandas** – Data wrangling
- **matplotlib** – Visualization
- **NumPy** – Numeric operations
- **Jupyter Notebook** – Analysis workflow

---

## 📊 Key Insights

- **Distribution of Durations**: Most 1990s Netflix movies are around 100 minutes long.
- **Action Genre Focus**: A subset was created to analyze short action movies (under 90 minutes).
- **1990s Filter**: Data was precisely filtered for movies released from 1990 to 1999 inclusive.

---

## 🧪 Steps Performed

1. Loaded the Netflix dataset and filtered for movies.
2. Narrowed the selection to only 1990s releases.
3. Visualized movie durations to identify common lengths.
4. Isolated the **Action** genre from this subset.
5. Counted how many Action movies from the 1990s were **less than 90 minutes long** using a `for` loop.

---

## 📈 Example Visualization

![Duration Histogram](your_image_path_here)  
*Distribution of Movie Durations in the 1990s*

---

## ✅ Result

**Short Action Movies (< 90 mins) in the 1990s:**  

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/netflix-1990s-analysis.git
   cd netflix-1990s-analysis
2.Install dependencies:
     **First** : Install Python 
     **Second** : pip install pandas matplotlib 
