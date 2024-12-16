# Game-Sales-Dashboard-using-Kibana

## Dataset Description
•	Total Rows: 16,598

•	Columns: 11

### Column Descriptions:

1.	Rank: Global ranking of the video game based on sales.
2.	Name: Name of the video game.
3.	Platform: The platform on which the game was released (e.g., Wii, NES, DS).
4.	Year: Year of release (some entries are missing).
5.	Genre: Genre of the game (e.g., Action, Sports).
6.	Publisher: Publisher of the game (some entries are missing).
7.	NA_Sales: Sales in North America (in millions of units).
8.	EU_Sales: Sales in Europe (in millions of units).
9.	JP_Sales: Sales in Japan (in millions of units).
10.	Other_Sales: Sales in other regions (in millions of units).
11.	Global_Sales: Total global sales (in millions of units).


### Key Observations:

•	Year: Ranges from 1980 to 2020, but there are missing values in 271 entries.

•	Sales Columns: Global sales are broken down into specific regions: NA, EU, JP, and Others.

•	Popular Genre: "Action" appears most frequently (3,316 times).

•	Top Publisher: "Electronic Arts" has the highest count (1,351 entries).


### Summary Statistics:

•	Sales (in millions): 

o	Average global sales: 0.54 million units.

o	Maximum global sales: 82.74 million units.

•	Rank: Ranges from 1 (highest) to 16,600 (lowest).

### Missing Data:
•	Year: Missing in 271 rows.

•	Publisher: Missing in 58 rows.


## Objectives

•	To identify the top-performing video games based on global sales and analyze sales contributions across different regions such as North America, Europe, Japan, and other territories.

•	To determine the most successful genres in terms of global sales and their percentage contribution to the market.

•	To analyze the performance of different platforms (PS3, PS2, X360, etc.) in terms of cumulative global sales and market dominance.

•	To evaluate the role of major publishers (e.g., Electronic Arts, Sony, Ubisoft) in driving global sales and their contributions by genre.

•	To identify trends in video game sales across years and highlight the peak periods for game releases and platform success.

## Insights
 
![image](https://github.com/user-attachments/assets/ff07b63b-918b-46df-be42-8312290194e6)

The Top 5 Games by Global Sales have nearly identical sales, averaging around 0.9 million units, with "007: The World is Not Enough" and "Blue Dragon" leading the list. This highlights strong competition and similar performance among the top games.

 ![image](https://github.com/user-attachments/assets/aa1b0e8d-a879-44f7-9379-1802fede72a5)

The Global Sales by Genre pie chart shows that Adventure (17.12%) leads as the top-performing genre, followed closely by Strategy (16.74%). This indicates a relatively even distribution of global sales among multiple genres, highlighting diverse player preferences.

![image](https://github.com/user-attachments/assets/63f931e6-46e0-4c0f-831b-0d370a1c7c98)
 
The Regional Sales Analysis graph shows that North America dominates sales for the top 5 games, contributing the highest share across all regions, while Europe, Japan, and Other regions contribute relatively smaller portions. This highlights North America's significant role in video game sales.

 ![image](https://github.com/user-attachments/assets/d2fdb2b0-0842-4119-99a5-5f3780810d3e)

The Bottom 5 Games Sales table shows that these games have JP Sales as the primary contributor to their global sales, with minimal to no sales in other regions. This highlights the strong regional popularity of certain games in Japan but limited appeal globally.

 ![image](https://github.com/user-attachments/assets/4baa7863-3ccd-4885-a82c-abee2f6314d8)

The Yearly Sales Trend graph shows that the number of platforms releasing games peaked between 2005 and 2010, indicating a golden period for the gaming industry. After 2010, there is a noticeable decline, suggesting market saturation or shifting industry trends.

 ![image](https://github.com/user-attachments/assets/07f190dd-c136-4c57-8623-076baf3c26b2)

The Top Platforms by Sales graph highlights that PS3 leads among individual platforms in global sales, but the "Other" category dominates overall, suggesting a significant share of sales comes from multiple less common or niche platforms combined.

 ![image](https://github.com/user-attachments/assets/8295235a-da4d-4ce0-aa75-883fb8a66840)

The Top Platform by Sales graph shows that Electronic Arts is the leading individual publisher in global sales, but the "Other" category contributes the majority, indicating a highly fragmented market with numerous smaller publishers driving significant cumulative sales.

 ![image](https://github.com/user-attachments/assets/beb029d5-0d68-4550-8ec9-7a2430d52048)

The Sales by Genre and Publisher graph highlights that Sports (22.91%) and Action (21.77%) are the dominant genres, with Electronic Arts leading Sports sales (11.46%). This indicates a strong correlation between the Sports genre's popularity and Electronic Arts' dominance in publishing within this segment.
 
![image](https://github.com/user-attachments/assets/ceff784d-754f-4353-a8c8-b0d0111aa597)

The Genre and Name Wise Sales Analysis graph shows that specific games in genres like Racing, Action, and Sports achieve the highest sales, as indicated by the deep red color (≥ 0.709). This highlights that these genres consistently produce top-performing individual games.

## Managerial Insights

**1.	Top Game Sales Consistency:**
The Top 5 Games have nearly identical global sales (~0.9 million units), indicating that competition at the top is intense. Managers should focus on distinguishing features or marketing strategies to stand out among top-performing games.

**2.	Genre Diversity in Global Sales:**
The Adventure and Strategy genres lead global sales with relatively close shares (17.12% and 16.74%), reflecting diverse player preferences. Companies can explore these genres for new game development opportunities to attract a broad audience.

**3.	North America's Dominance:**
North America contributes the highest regional sales for top games, emphasizing the importance of focusing marketing and distribution efforts in this region to maximize revenue.

**4.	Regional Market Specialization:**
Games in the Bottom 5 Sales perform exceptionally well in Japan, showing strong regional appeal. Managers can tailor specific games to regional preferences to optimize niche markets.

**5.	Golden Era of Gaming (2005-2010):**
The Yearly Sales Trend highlights a peak period (2005–2010) for platforms and sales. Managers should study strategies and trends from this period to understand consumer behavior and industry factors driving growth.

**6.	Platform Fragmentation:**
While PS3 leads among individual platforms, the "Other" category dominates global sales. This suggests a large market for niche or emerging platforms, encouraging exploration of smaller platforms to boost revenue.

**7.	Publisher Concentration in Top Genres:**
Electronic Arts dominates Sports, the highest-selling genre (22.91%), showing a strong link between genre popularity and publisher success. Managers should identify dominant publishers in other genres for potential collaboration or competition analysis.

**8.	Focus on High-Selling Genres:**
The Action, Racing, and Sports genres consistently produce high-performing games. Allocating resources to develop or acquire games in these genres can improve revenue prospects.

**9.	Strategic Niche Publisher Partnerships:**
The "Other" publishers contribute the largest share of global sales, indicating fragmentation. Partnering with smaller publishers or platforms can unlock hidden market potential and diversify sales channels.

**10.	Regional Sales Optimization:**
North America dominates sales for most games, but Japan emerges as a strong niche market for certain titles. Managers should adopt region-specific marketing, localization, and platform strategies to maximize sales across global regions.

# Dashboard Video

[Games Sales Dashboard Video.webm](https://github.com/user-attachments/assets/cf8d02a3-d32a-4945-ad7a-03993b505f60)

### Conclusion

1. The video game sales dataset provides comprehensive insights into global sales trends, regional performance, platform dominance, and genre-specific popularity. Key observations highlight North America's dominance in sales, the critical role of popular genres like Sports, Action, and Adventure, and the golden period for gaming platforms between 2005 and 2010.
2. Major publishers, such as Electronic Arts, have capitalized on the popularity of dominant genres, particularly Sports, while smaller publishers collectively contribute significantly to global sales, suggesting a fragmented market. Regional preferences, notably Japan's strong niche appeal, emphasize the importance of tailoring games to specific markets.
3. From a managerial perspective, opportunities exist in emerging platforms, genre diversification, and region-specific marketing strategies. By focusing on high-performing genres, understanding past trends, and optimizing regional sales efforts, businesses can drive growth and improve competitive positioning in a diverse and evolving gaming industry.



