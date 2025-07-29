# TransBorder-Freight-Data-Analysis
The objective of this project is to analyze the transportation data provided by the Bureau of Transportation Statistics (BTS) to uncover insights related to the efficiency, safety, and environmental impacts of freight transportation across various modes (road, rail, air, and water). Using this data, the goal is to identify inefficiencies, recognize patterns, and propose actionable solutions to improve the overall performance and sustainability of transportation systems.


![TransBorder-Freight-Data-Analysis](https://github.com/ioakowuah/TransBorder-Freight-Data-Analysis/blob/main/Github%20Power%20BI%20Pic.png)

- [PowerBI Report File](https://drive.google.com/file/d/1TLaFSjVzfS4WwVOVD6nDWury2mfWMkSw/view?usp=drive_link)



##  Project Details

- **Project Title:** TransBorder-Freight-Data-Analysis Report   
- **Tool Used:** Microsoft Power BI  
- **Dataset Source:**  
- **Period Covered:** January 2020 – September 2024  (Dataset has October 2020 - December 2020 missing)

---

##  Objectives of the Analysis

- What is the total value of goods transported?
- what is the number of freight movement?
- What is the most used mode of transportation of goods?
- What is the trend of the value of goods transported over the years?
- What is top 4 states in the USA with high value of goods transported and by what type of trade?
- What is the weight of goods transported across the month and country?
- Provide Data-Driven Recommendations.

---

##  Data Preprocessing Steps

- Extract and combine csv data files into a folder for import into PowerBI.
- Transform value coded categorical columns. Eg. `MONTH` values of 1 into January, 2 into February, etc.
- Created calculated fields:
  - **Total Value of goods Transported** = Sum(Values)
  - **Number of Transportations** = Count(Transportation modes)

---

##  Dashboard Overview

**KPI Cards**
- Total Value Transported: **$108.9T**  
- Number of Freight Transported: **39M**  
 

**Visuals**
- Mode of Transportation by Value
- Trend of Value by Year
- Shipping weight by Month and Country 
- Value by USA State and Trade Type

---

##  Key Insights

-  **Truck** is the most used mode of transporting goods.
-  **2022** is the year highest value of goods were transported and it has declined for **2023** and **2024**.
-  **Texas, Michigan, California, Illinois** are the top 4 USA states that transported goods. Texas the leading state transported goods worth $15.8T.
-  **January and March** is the month where heavy weight is transported and Canada is the country leading with these heavy transportation benchedmarked with Mexico.
-  **Canada** is the top trading partner for heavy goods, surpassing Mexico.

---

##  Recommendations

- **Invest in infrastructure support for road transport**: such as improving highways and border facilities.
- **Promote digital logistics tools**: To increase trucking efficiency, promote the use of route optimization systems.
- **Root-cause analysis**: Conduct a root-cause analysis (e.g., cost of transportation, demand decline, geopolitical disruptions).
- **Policy planning**: Policy planning around these top states (Texas, Michigan, California, Illinois) to streamline trade corridors.
- **Bottlenecks or missed opportunities**: Benchmark other states against Texas to identify bottlenecks or missed opportunities.
- **Plan maintenance or upgrades**: Plan maintenance or upgrades outside of peak months to minimize disruption.
- **Bilateral trade and infrastructure**: Focus bilateral trade and infrastructure discussions more heavily with Canada.

---

##  Conclusion

This analysis was conducted using theCRISP-DMmethodology (Cross-Industry Standard Process for Data Mining), ensuring a structured, iterative approach that drives valuable business insights and leads to practical recommendations. Data wrangling, visualization, and thorough documentation will be integral to the process to ensure the insights are communicated effectively to stakeholders..

---

##  References & Resources

- [Dataset:](https://azubiafrica-my.sharepoint.com/:u:/g/personal/emmanuel_agyen_azubiafrica_org/EYddQyNqYidPuJW6qaNFxcABYaVfF-kZ14K2pJfHjKWmmg?e=wz822N)
- [GitHub Repository:](https://github.com/ioakowuah/TransBorder-Freight-Data-Analysis/blob/main/README.md)
- Power BI Desktop

---

##  About the Analyst

**Isaac Owusu Akowuah**  
Data Analyst | Power BI Developer | Machine Learning Engineer 
- [Website](https://ioakowuah.wixsite.com/isaacowusuakowuah)
- [LinkedIn](https://www.linkedin.com/in/isaac-owusu-akowuah-88337667)
- [Github](https://github.com/ioakowuah)
- Email: ioakowuah@gmail.com






