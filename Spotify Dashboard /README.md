# 🎵 Spotify Analytics Dashboard – Power BI

## 📋 Overview  
This **interactive dashboard** provides insights into Spotify track data, including artist popularity, song characteristics, and catalog composition. Built with **Power BI**, it helps explore trends in music streaming.

![Dashboard Preview](image.png)  
*(Replace with actual screenshot)*

---

## ✨ Features  
- 🎤 **Top Artists by Popularity** – see who dominates the charts  
- 🎶 **Track List** – quick reference of popular songs with artist names  
- 📊 **Album Type Breakdown** – distribution of albums, singles, and compilations  
- 📈 **Key Metrics** – total songs, average popularity, average duration, artist count, track count  

---

## 📀 Data Source  
The dataset contains Spotify track metadata, including:
- Track name, artist, album, duration
- Popularity score (based on streaming frequency)
- Album type (album, single, compilation)

Data is anonymized and used for demonstration purposes.

---

## 📊 Key Metrics  

| Metric | Value | Description |
|--------|-------|-------------|
| 🎵 Total Songs | 28K | Number of unique tracks analyzed |
| ⭐ Avg Popularity | 2M | Average popularity score (scale may be custom) |
| ⏱️ Avg Duration | 3.28 | Average track length in minutes |
| 🧑‍🎤 Count of Artists | 342 | Unique artists in the dataset |
| 💿 Count of Tracks | 282K | Total tracks (may include duplicates or extended catalog) |

> **Note:** The discrepancy between “Total Songs” and “Count of Tracks” suggests the latter includes multiple versions or extended catalog data. This dashboard focuses on the 28K song sample.

---

## 📈 Visual Insights  

### 1️⃣ Top Artists by Popularity  
- **Taylor Swift**, **Billie Eilish**, **Sabrina Carpenter**, **The Weeknd**, **Arctic Monkeys**  
  *Bar chart ranking artists based on average popularity.*

### 2️⃣ Song List  
- A table displaying track names alongside artists:  
  - Taylor Swift – “Slut!” (Taylor’s Version)  
  - Peggy Gou – (It Goes Like) Nanaa - Edit  
  - KAROL G & Feid & DF – +57  
  - Beyoncé – 16 CARRIAGES  
  - Tate McRae – 2 hands  
  - Zach Bryan – 28  
  - Charli XCX – 360  
  - Jung Kook & Jack Harlow – 3D (feat. Jack Harlow)  
  *(and more)*

### 3️⃣ Album Type Distribution  
- Pie or bar chart showing proportion of **album**, **single**, and **compilation** tracks.

---

## 🛠️ Usage  
1. Open the `.pbix` file in **Power BI Desktop**.  
2. Interact with slicers (e.g., filter by artist, album type).  
3. Hover over visuals to see detailed tooltips.  

---

## 🧰 Requirements  
- **Power BI Desktop** (latest version)  
- Windows OS or Power BI service for online viewing  

---

## 🔧 How to Replicate  
1. Load your Spotify dataset (CSV/Excel) into Power BI.  
2. Create measures like:
