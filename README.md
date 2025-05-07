# My11-IPLData
# 🏏 My11-IPLData

This project presents a detailed **data analysis of IPL cricket tournament** using data collected directly from [ESPNcricinfo](https://www.espncricinfo.com/) through **Bright Data’s web scraper**. It highlights key patterns, player performances, and match outcomes with the help of **Power BI dashboards**.

![Dashboard Screenshot](images/dashboard.png) <!-- Add a screenshot here -->

---

## 📊 Project Overview

- **Tools Used:**  
  - 🧰 Data Collection: Bright Data Web Scraper  
  - 📊 Visualization: Power BI  

- **Website Scraped:** [ESPNcricinfo](https://www.espncricinfo.com/)
- **Data Format:** JSON to Excel/CSV (converted for visualization)
- **Focus Areas:**
  - **Fast Bowlers’ Performance**  
     Evaluated using Economy Rate, Bowling Strike Rate, Bowling Average, Dot Ball Percentage, and Wicket Efficiency.
  - **Power Hitters/Openers**  
      Assessed via Strike Rate, Batting Average, Boundary Percentage, Innings Played, and Runs Scored.
  - **Middle-Order Anchors**  
      Analyzed based on Runs Scored, Batting Average, Strike Rate, Boundary Percentage, and Balls Faced.
  - **Lower-Order Finishers/All-Rounders**  
      Judged on both batting (Runs, Average, Strike Rate, Balls Faced) and bowling (Wickets, Economy, Bowling SR, Innings Bowled).
  - **Trendlines**
      Show consistent performance in Batting Average, Strike Rate, Boundary Percentage, Balls Faced, and Bowling SR.
  - **Scatter Plots**  
      Visual analysis of Batting Average vs Strike Rate and Bowling Strike Rate vs Economy.
  - **Key Player Performances**  
      Standout contributions from Stubbs, Green, Pooran, Dhoni, Bumrah, and Pathirana across different roles.
  - **Role-Based Insights**  
      Help in understanding balanced team composition through diverse player contributions.

---

## 🔧 Data Collection Process

- Bright Data’s web scraping tools were used to extract:
  - **Match Summary** – match type, result, toss, venue, teams.
  - **Player Stats** – performance metrics, career data, etc.
  - **Batting Summary** – runs scored, strike rate, boundaries, dismissal info.
  - **Bowling Summary** – overs, wickets, economy, extras conceded.
- The raw JSON data was cleaned and converted into CSV format for analysis and visualization in Power BI.

---

## 📈 Key Insights

- How toss decisions affect match wins
- Top-performing players and teams
- Win distribution across venues and seasons
- Player comparisons using performance metrics

---

## 📊 Visualizations

Includes:
- Bar and line charts, Scatterplots
- Top performing players for each category
- Best 11 players selected through all the metrics combined
- Player Info card when hovering over a player name

> 📷 **To Add a Screenshot**  
> Save your Power BI dashboard as an image and place it in a folder named `images/` inside the repo. Then reference it in this README.

---

## 📁 Project Structure

Cricket-Data-Analysis/
│
├── images/
│ └── dashboard.png # Add a screenshot of your dashboard here
├── datasets/
│ └── cleaned_data.csv # Optional: include clean datasets
├── powerbi/
│ └── cricket_analysis.pbix # Optional: include your PBIX file
├── scripts/
│ └── scraping_code.js # Optional: Bright Data scripts if allowed
├── MinorProject.pdf
├── README.md

---

## 👨‍💻 Created By

**Dipanshu Modi**  
B.Tech Computer Science, KIIT University  
Skills: Python | Power BI | SQL | Web Scraping
