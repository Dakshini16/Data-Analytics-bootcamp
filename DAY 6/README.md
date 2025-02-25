📌 IPL Commentary Scraper - What I Learned :  
🔹 Understanding `robots.txt` & Web Scraping Ethics : 
- Explored `robots.txt` for Amazon, ESPN Cricinfo, and Instagram to understand scraping limitations.  
- Learned how websites restrict automated access and how to comply with ethical scraping practices.  
- Used User-Agent switching to bypass "Access Denied" errors while following guidelines.  
🔹 Extracting Ball-by-Ball Commentary : 
- Successfully scraped structured data from ESPN Cricinfo for IPL matches.  
- Learned how to identify dynamic elements (ball number, over, bowler, batter, shot type, ball speed, and runs scored).  
- Implemented scrolling automation to load hidden content dynamically.  
🔹 Scraping Entire IPL 2022 Series (All Matches) :  
- Automated navigation through multiple matches without manually copying URLs.  
- Learned to extract match-specific details, including:  
  ✅ Match Winner  
  ✅ Team Scores  
  ✅ Venue & Date  
- Handled delayed page loading using `time.sleep()` and `WebDriverWait` for stability.  
🔹 Extracting Data for IPL 2021, 2022, 2023 :
- Learned to handle dropdown automation to switch between different IPL seasons.  
- Implemented dynamic XPath selection to extract match links accurately.  
- Gained experience in handling multiple datasets efficiently using Pandas.  
📌 Key Takeaways :  
✅ Web Scraping Best Practices – Following `robots.txt` and ethical scraping principles.  
✅ Dynamic Page Handling – Using scrolling and waits to extract hidden content.  
✅ Automated Navigation – Extracting data from entire IPL seasons programmatically.  
✅ Data Structuring – Transforming unstructured text into meaningful, structured tables.  
