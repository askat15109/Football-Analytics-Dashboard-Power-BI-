
# ⚽ Euro 2024 Player Analytics Dashboard

An interactive Power BI dashboard that provides deep, data-driven insights into player and team performances from the **UEFA Euro 2024** tournament. The project leverages detailed player statistics and advanced metrics to enable scouting, comparison, and tactical analysis.

---

## 📊 Dashboard Overview

This Power BI project is structured into multiple report pages, each offering unique visualizations and analytical insights:

### ✅ 1. **Player Profile**
- Individual player stats from all phases of play
- Goals, Assists, xG, xA, Passing %, Possession metrics, Defensive actions
- Goals per 90, Minutes Played, Pass Types, Shot Zones, and more

### ✅ 2. **Overview Page**
- Top Scorers & Creators
- xG Over/Under Performers
- Most Involved Players (xGChain)
- Best Ball Progressors (xT, OBV)
- Team-level summary of attacking/defensive performance

### ✅ 3. **Team Comparison**
- Compare two selected squads using disconnected slicers
- Visualize key metrics side by side (Goals, xG, Possession, Pressures, Tackles, etc.)
- Ideal for pre-match tactical analysis

### ✅ 4. **Goalkeeper Zone Map**
- Shot Zones faced by GKs
- Save % by zone (Left, Right, Center)
- GK Distribution Map

---

## 🧠 Key Features

- ✅ **Disconnected Slicers** for Team A vs Team B Comparison
- ✅ **Dynamic DAX Measures** for xG, OBV, xT, Goals/90, Pass Types
- ✅ **Custom Tooltips** for deeper metric breakdowns
- ✅ **Performance Radar Charts** for player profile comparison
- ✅ **Drillthrough Pages** for match-by-match and player-level deep dives

---

## 📁 Dataset Details

> All data is publicly available and collected from **StatsBomb Open Data** or scraped from public Euro 2024 sources.

**Files Used (11 Excel files):**
- `Standard_Stats.xlsx`  
- `Shooting.xlsx`  
- `Passing.xlsx`  
- `Passing_Types.xlsx`  
- `Possession.xlsx`  
- `Defense.xlsx`  
- `Goalkeeping.xlsx`  
- `Goalkeeping_Advanced.xlsx`  
- `xT_Model_Output.csv`  
- `OBV_Model_Output.csv`  
- `xGChain_Data.csv`

---

## 🧰 Tools & Technologies

- **Power BI Desktop** – Data modeling, visualization
- **Microsoft Excel** – Data cleaning
- **Python (Pandas, NumPy)** – Preprocessing, advanced metric generation
- **DAX** – Custom measures and dynamic visual logic
- **GitHub** – Version control and repository

---

## 🚀 How to Run

1. Download this repository or clone it:
   ```bash
   git clone https://github.com/your-username/euro2024-powerbi-dashboard.git
   ```

2. Open the `.pbix` file using **Power BI Desktop**

3. Ensure all **Excel data sources** are correctly mapped:
   - Go to **Transform Data → Data Source Settings**
   - Update file paths if necessary

4. Refresh the data

---

## 📌 Future Improvements

- Add **Match Timeline Analysis**
- Add **Tournament Heatmap Trends**
- Integrate **Live Euro Data Feeds**
- Export to **Paginated Reports or PDF**

---

## 🙌 Acknowledgements

- [StatsBomb](https://statsbomb.com/)
- [FBref](https://fbref.com/)
- [UEFA Official Stats](https://www.uefa.com/)
- [Understat xG](https://understat.com/)

---

## 📬 Contact

**Made with ❤️ by Akshat Choubey**

📍 Nagpur, India  
📧 akshatchoubey2@gmail.com  
📸 [LinkedIn](https://linkedin.com/in/akshatchoubey)

---

> “Data beats opinion. Visuals make it powerful.”
