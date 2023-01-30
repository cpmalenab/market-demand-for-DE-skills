# Project: Market Demand Analysis for Data Engineering Skills using Data Modeling and Text Mining

Understanding the labor market demand can (1) help present and future professionals build their portfolio with the most marketable skills, (2) supplement the frameworks of educational institutions and training centers to better prepare students in the digital industry, and (3) give an insight to the general landscape of data engineering industry with the Philippines as the geographical focus.

The figure below shows a high-level view of the data flow to extract the in-demand skillsets from the online job portal. The data flow architecture is composed of five layers including: (1) data source, (2) data ingest layer, (3) data warehouse, (4) machine learning, and (5) data visualization.


<p align="center">
  <img src="https://github.com/cpmalenab/market_demand_analysis_for_DE_skills/blob/main/images/Data%20Flow%20Diagram.jpg">
</p>
<p align="center">Figure. Data Flow Diagram</p>

<p align="center">
  <img src="https://github.com/cpmalenab/market_demand_analysis_for_DE_skills/blob/main/images/Data%20Flow%20Diagram.jpg">
</p>


* Scraped over 1000 job descriptions on indeed.com using BeautifulSoup and Selenium.
* Performed data filtering and cleaning using Pandas. 
* Modeled the data in PostgreSQL using psycopg2 and SQLAlchemy libraries.
* Conducted data visualization of geospatial distribution, industry demand, and in-demand hard and soft skills.
* Performed topic modeling to extract the most sought after skill set combination.
