# 🍿 **Exploring Netflix's catalogue in Power BI**
A Power BI dashboard visualising insights into Netflix' streaming content catalogue by genre and geography.

---

## 📌 **Overview**

This project analyses Netflix’s content library using **Power BI** to uncover trends related to:  

- **Content distribution** (films vs. TV shows)</br>
- **Most common genres**</br>
- **Geographical availability**</br>
- **Seasonal trends in content releases**</br>

The dashboard provides interactive visualisations that help explore the size and composition of Netflix’s catalogue across **122 countries**, **43 genres**, and over **8,800 titles**.

---

## 📊 **Key features** 

The Power BI dashboard consists of **four main pages**:  

1. **Catalogue Overview** 📺  
   - Total number & proportion of **films** and **TV shows**
   - Number of **genres** & **countries** represented by the catalogue
   - **Distribution map** showing Netflix’s content spread worldwide & number of titles per country  
   - **Content growth trend** over time
   - Slicers allowing users to filter insights by **content type** (film/TV) and **genre**  

2. **Films & TV Shows (Toggle View)** 🎬📺  
   - **Switchable view** between **Films** and **TV Shows** using an intuitive toggle button
   - Top **10 most common genres**  
   - Breakdown of genres using a **treemap**  
   - Most frequently appearing **actors** and **directors**
   - Cards showing **total number of films/TV series** (according to view selected) & **most recently added title**
   - Ability to filter by **country**, **genre** and **release year**

3. **Countries** 🌎  
   - Top 10 countries contributing the most Netflix content  
   - **Dominant genres per country**  
   - **Continental distribution** of content
   - A filterable **table** showing insights into the **number of titles contributed** and **dominant genre, director and actor** for each country
   - Filterable by **country**, **continent** and **content type**

4. **Seasonal Trends** 📆  
   - **Release patterns by month and day**  
   - **Annual and weekly release trends**, highlighting peak content drops
   - Filterable by **year**, **country**, **content type** and **genre** for more granular trends
  
---

## 📂 **Dataset**  

The dataset (Netflix Movies and TV Shows) was sourced from [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows) and contains metadata on Netflix’s catalogue, including:  

- `title`: The name of a piece of content.
- `type`: Whether a piece of content is a film or a TV show.
- `listed_in`: The **genre** of the film or TV Show.
- `director`: The director(s) of a piece of content.
- `cast`: The actors appearing in the title.
- `country`: The country (/countries) where a piece of content was produced.
- `release_year`: The year a piece of content was first released.
- `date_added`: The date a piece of content was added to the Netflix platform (not always the same as `release_year` if not an original Netflix production).

It contains a total of 12 columns and 8807 rows.

Data cleaning and transformation were performed in **Power Query**, ensuring consistency for analysis.

---

## 🚀 **Technologies used**  

- **Power BI** – For data visualisation  
- **Power Query** – Data transformation and cleaning  
- **DAX (Data Analysis Expressions)** – Custom calculations and measures  

---

## 📥 **How to use the dashboard**  
1. Install [Power BI Desktop](https://www.microsoft.com/fr-fr/power-platform/products/power-bi/desktop?msockid=38178c20f62d614234979884f7946082)
2. **Download the Power BI (.pbix) file** from this repository 
2. Open the file in **Power BI Desktop**  
3. Interact with the filters to explore different insights  

---

## 📌 **Future improvements**  
- **Deeper genre-specific analysis** (e.g., which genres dominate in certain regions)
- **More granular analysis of release trends** (e.g. hourly hotspots / see which genres or type of content tend to be uploaded at particular times of year)
- **Integration with IMDb or Rotten Tomatoes ratings** to assess content quality
- **Tracking Netflix Originals separately**

---

## 📧 **Contact**  
For questions or feedback, feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/nedchambers/).  
