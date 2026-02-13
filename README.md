# 🏏 Exploratory Data Analysis: ICC Men's ODI World Cup 2023

![World Cup 2023](https://img.shields.io/badge/Cricket-World%20Cup%202023-blue) ![Python](https://img.shields.io/badge/Made%20with-Python-yellow) ![Pandas](https://img.shields.io/badge/Library-Pandas-150458)

## 📄 Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the **ICC Men's ODI World Cup 2023**. The goal is to uncover statistical insights, analyze team performances, and visualize key trends that defined the tournament.

**College:** Deogiri College (Autonomous), Chhatrapati Sambhajinagar  
**Course:** MCA FY 2025-26 (Semester-II)  
**Subject:** Exploratory Data Analysis (EDA)

---

## 👥 Project Team
| Roll No | Student Name |
| :--- | :--- |
| **2025/MCA/078** | **LAKDE AMEY LINGESHWAR** |
| **2025/MCA/083** | **MAHAJAN HARSHAL RAJENDRA** |
| **2025/MCA/084** | **MANKE NILESH RAVINDRA** |

---

## 📊 Dataset Description
The analysis is based on match data sourced from the official ICC records.
- **`matches.csv`**: Contains summary details of all 48 matches (Teams, Venue, Toss, Winner, MVP).
- **`deliveries.csv`**: Ball-by-ball data for granular analysis (Run rates, Wickets, Phases of play).
- **`points_table.csv`**: Standings after the group stage.

## 🎯 Objectives
- **Venue Analysis**: Identify high-scoring vs. low-scoring grounds.
- **Toss Impact**: Does winning the toss guarantee a win? (Bat First vs. Chase).
- **Player Performance**: Top Run Scorers, Wicket Takers, and "Man of the Match" awardees.
- **Match Trends**: Compare Powerplay scores, Middle over strategies, and Death over finishing.

## 🛠️ Tech Stack
- **Language**: Python 3.x
- **Libraries**:
    - `pandas` & `numpy` (Data Manipulation)
    - `matplotlib` & `seaborn` (Data Visualization)
    - `jupyter` (Interactive Analysis)

## 🚀 How to Run
1. **Clone the repository**:
   ```bash
   git clone https://github.com/nileshmanke/EDA_PROJECT_ICC_ODI_WC_2023.git
   cd EDA_PROJECT_ICC_ODI_WC_2023
   ```

2. **Install dependencies**:
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. **Run the Analysis Script**:
   ```bash
   python pom_analysis.py
   ```
   *(Or open the Jupyter Notebooks for detailed visualization)*

## 📈 Key Insights (Preview)
- **Top Performer**: The player with the most "Man of the Match" awards was identified using `pom_analysis.py`.
- **Toss Factor**: Analysis reveals the winning percentage for teams batting first vs. chasing across different Indian venues.

---
*Submitted as part of the MCA Coursework, 2026.*
