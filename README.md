# 🎵 Spotify Data Analysis using Python

<div align="center">

![Spotify](https://img.shields.io/badge/Spotify-Data%20Analysis-brightgreen?style=flat-square&logo=spotify)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Processing-blue?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-blue?style=flat-square)

</div>

## 📊 Project Overview

This project performs a comprehensive **Exploratory Data Analysis (EDA)** and **Data Visualization** on Spotify datasets using Python. It explores patterns, relationships, and insights from Spotify's music data, including audio features analysis, genre comparisons, and popularity trends.

---

## ✨ Key Features

- 🔍 **Exploratory Data Analysis (EDA)** - Comprehensive data inspection and cleaning
- 📈 **Statistical Analysis** - Correlation analysis between audio features
- 🎨 **Data Visualization** - Professional charts and heatmaps using Matplotlib and Seaborn
- 🎯 **Popular Insights** - Identification of trending songs and genres
- ⏱️ **Temporal Analysis** - Music trends over years and duration changes
- 🎼 **Genre Comparison** - Comparative analysis across different music genres

---

## 🛠️ Tech Stack

| Technology      | Purpose                        |
| --------------- | ------------------------------ |
| **Python 3.8+** | Core programming language      |
| **Pandas**      | Data manipulation and analysis |
| **NumPy**       | Numerical computing            |
| **Matplotlib**  | Data visualization             |
| **Seaborn**     | Statistical data visualization |

---

## 📚 Dataset Information

### Data Sources

- **Spotify Tracks Dataset** - Track information and metadata from Kaggle
- **Spotify Features Dataset** - Audio features and genre classification

### Key Columns

- `track_name` - Name of the track
- `artists` - Artist(s) name
- `popularity` - Popularity score (0-100)
- `duration_ms` - Track duration in milliseconds
- `release_date` - Release date of the track
- `genre` - Music genre classification
- **Audio Features:** `energy`, `loudness`, `acousticness`, `danceability`, `valence`, etc.

---

## 🚀 Installation & Setup

### Prerequisites

- Python 3.8 or higher
- pip (Python package manager)

### Step 1: Clone the Repository

```bash
git clone https://github.com/VaishuK0209/Spotify-Data-Analysis-using-Python.git
cd Spotify-Data-Analysis-using-Python
```

### Step 2: Create Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Download Datasets

The datasets are sourced from Kaggle. You can find them at:

- **Spotify Tracks Dataset** - Search on [Kaggle Datasets](https://www.kaggle.com/datasets)
- **Spotify Features Dataset** - Search on [Kaggle Datasets](https://www.kaggle.com/datasets)

Once downloaded, place the CSV files in the `data/` directory.

**Note:** The notebook uses Kaggle's input paths (`../input/`). If running locally, update the paths to point to your `data/` directory.

---

## 📖 Usage Instructions

### Running the Jupyter Notebook

```bash
jupyter notebook "Spotify Data Analysis using Python Project.ipynb"
```

### Key Analysis Sections

1. **Data Import & Cleaning** - Load and preprocess datasets
2. **Exploratory Analysis** - Statistical summaries and null value checks
3. **Popularity Rankings** - Top 10 most/least popular songs
4. **Correlation Analysis** - Feature relationships using heatmaps
5. **Temporal Trends** - Songs per year and duration changes
6. **Genre Analysis** - Genre popularity and characteristics

---

## 💡 Key Insights & Findings

### 1. **Top Popular Songs** 🎵

Identified songs with popularity scores > 90, revealing current trending tracks

### 2. **Correlation Heatmap** 🔥

**Strong Correlations Found:**

- Loudness ↔ Energy: High positive correlation
- Valence ↔ Danceability: Moderate positive correlation
- Acousticness ↔ Energy: Negative correlation

### 3. **Genre Insights** 🎼

- Duration varies significantly across genres
- Pop and Hip-Hop dominate popularity metrics
- Classical music shows different audio feature patterns

### 4. **Temporal Trends** 📅

- Rapid increase in Spotify tracks post-2010
- Average song duration remains stable (~3.5 min)
- Recent years show more diverse genre inclusion

### 5. **Audio Features Distribution** 📊

- Most songs have high danceability (avg: 0.65)
- Energy distribution is bimodal (peaks at high and low values)
- Acousticness varies widely across different genres

---

## 📁 Project Structure

```
Spotify-Data-Analysis-using-Python/
│
├── README.md                                          # Project documentation
├── requirements.txt                                   # Python dependencies
├── Spotify Data Analysis using Python Project.ipynb   # Main analysis notebook
│
├── data/                                              # Dataset directory
│   ├── tracks.csv                                     # Spotify tracks data
│   └── SpotifyFeatures.csv                           # Audio features data
│
└── images/                                            # Visualization outputs
    ├── Correlation Heatmap between Variable.png
    ├── Regression plot - Correlation between Loudness and Energy.png
    ├── Regression plot - Correlation between Popularity and Acousticness.png
    ├── Distibution plot - Visualize total number of songs on Spotify since 1992.png
    ├── Change in Duration of songs wrt Years.png
    ├── Duration of songs in different Genres.png
    └── Top 5 Genres by Popularity.png
```

---

## 🎯 Future Improvements

- [ ] Integrate Spotify API for real-time data fetching
- [ ] Implement machine learning models (classification, clustering, regression)
- [ ] Add sentiment analysis of song lyrics
- [ ] Create interactive dashboards using Plotly or Dash
- [ ] Perform time-series forecasting for trending songs
- [ ] Expand analysis to user playlist recommendations
- [ ] Build web application for visualization
- [ ] Add statistical hypothesis testing

---

## 📖 Learning Resources

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Tutorial](https://matplotlib.org/stable/tutorials/index.html)
- [Seaborn Gallery](https://seaborn.pydata.org/examples.html)
- [NumPy Documentation](https://numpy.org/doc/)
- [Python Data Science Guide](https://www.kaggle.com/learn)

---

## 📝 License

This project is open source and available under the **MIT License** - feel free to use it for educational and research purposes.

## 📧 Contact & Support

For questions, suggestions, or collaboration:

- 📌 Open an [Issue](https://github.com/VaishuK0209/Spotify-Data-Analysis-using-Python/issues)
- 🔗 Create a [Pull Request]
- 💬 Reach out via GitHub Discussions

---

<div align="center">

⭐ **If this project helped you, please consider giving it a star!** ⭐

**Author: [Vaishnavi Kushwah](https://github.com/VaishuK0209)**

</div>
