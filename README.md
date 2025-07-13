# Spotify Streaming Trends Analysis

## 📌 Overview

This project explores global music streaming trends using Spotify's daily top charts data. By analyzing track-level and artist-level statistics across dates and regions, we identify the most popular content, visualize streaming patterns over time, and uncover regional differences in listening behavior.

The goal is to extract meaningful insights from the dataset and communicate them through data analysis, aggregation, and visualization using Python.

---

## Dataset

The dataset contains daily Spotify streaming statistics, including:

- **track_name**: Name of the song
- **artist_name**: Performing artist(s)
- **streams**: Daily number of streams
- **region**: Country or 'Global'
- **date**: Date of the record

> 📍 **Note:** You can obtain the dataset from [Spotify Charts](https://spotifycharts.com/regional).

---

## Technologies Used

- **Python 3**
- **Pandas** – data loading and analysis
- **Matplotlib & Seaborn** – static and statistical visualizations
- **Altair & Plotly** – interactive and advanced charts
- **Requests & BeautifulSoup** – web scraping for additional metadata or data enrichment
- **Scipy (k-means)** – clustering analysis to group tracks or regions
- **Re (Regular Expressions)** – text processing and cleaning
- **Jupyter Notebook** – interactive data exploration
---

## Key Analyses

- Track and artist popularity rankings by total streams
- Regional breakdowns and comparisons
- Temporal streaming trends with interactive and static plots
- Clustering analysis using k-means to identify groups of similar tracks or regions based on streaming patterns
- Additional metadata scraping to enhance insights (e.g., genre, release dates)

---

## Insights & Findings

- A small subset of tracks dominates the global charts
- Artist popularity varies significantly across regions
- Certain tracks show sharp spikes—often coinciding with events like album releases or viral trends
- Streaming trends are highly dynamic and can change weekly

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/spotify-streaming-trends.git
   cd spotify-streaming-trends
    ```
2. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Open jupyter notebook
    ```bash
    jupyter notebook spotify_analysis.ipynb
    ```
---

## File Structure
Spotify Streaming Trends/<br />
├─ spotify_analysis.ipynb  # Jupyter Notebook with all code and plots <br />
├─ Requirements.txt # Python dependencies <br />
├─ README.md # Project overview
         
---

## Future Work
- Extend clustering analysis to include sentiment scores or lyrical features
- Integrate scraped metadata such as genres or chart positions from other sources
- Build a web-based dashboard for interactive exploration of regional trends
- Apply more advanced machine learning models to predict future streaming dynamics

---

## Acknowledgments

- Kworb(https://kworb.net/spotify/)
- UBC Data Science - Project is inspired by DATA 301 Coursework and Lab Assignments

---

## Contact 
Taksh Girdhar<br />
Data Science BSc | UBC Okanagan <br />
[LinkedIn](https://www.linkedin.com/in/taksh-girdhar-0a7552260/)| [GitHub](https://github.com/Takshg)
