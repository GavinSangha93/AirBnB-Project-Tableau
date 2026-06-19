<h1>Airbnb Investment & Pricing Analysis Dashboard | Tableau Public</h1>

<h2>Project Overview</h2>
This project leverages Tableau Public to analyze Airbnb market data and build an interactive business intelligence dashboard that helps identify pricing patterns, revenue opportunities, and high-performing geographic markets.
<br />
<br />
Using Airbnb listing and calendar datasets, the dashboard transforms thousands of rows of raw data into a visual decision-making tool that can assist hosts, investors, and stakeholders in evaluating potential opportunities within the short-term rental market.

<br />
<br />
The project demonstrates how data visualization can simplify complex datasets and convert them into actionable business insights.


<h2>Business Problem</h2>
The rapid growth of short-term rental platforms has created a highly competitive market for property owners and investors. Determining where to invest, how to price properties, and which property characteristics maximize revenue can be difficult without proper analysis.
<br/>
<br/> 
Stakeholders need answers to several business questions:

<br />
<br />

- Which zip codes generate the highest Airbnb prices?
- How does the number of bedrooms impact pricing?
- Which markets may provide stronger investment opportunities?
- What areas have the greatest revenue potential?
- How can data be used to support pricing strategies?

This project was developed to provide an interactive solution that enables users to explore these questions and support data-driven decision-making.

<h2>Dataset Information</h2> 

The analysis uses Airbnb datasets imported from Microsoft Excel and integrated within Tableau Public.

<b> Listings Dataset </b>

Contains property-level information, including:

- Listing ID
- Property information
- Zip code location
- Number of bedrooms
- Property type
- Pricing information
- Host details
- Availability metrics

<b>Calendar Dataset</b>

Contains daily operational data, including:

- Listing ID
- Dates
- Availability status
- Daily pricing information

The datasets were connected within Tableau to create a unified analytical model.

<h2>Analytical Questions Addressed</h2> 

This dashboard was built to answer the following questions:

1. Which zip codes command the highest Airbnb prices?
2. How does pricing change as the number of bedrooms increases?
3. Which geographic markets may offer stronger investment opportunities?
4. What annual revenue patterns emerge from the available data?
5. How can interactive visualizations improve business decision-making?

<h2>Analysis Performed</h2>

Several exploratory analyses were conducted to identify patterns and relationships within the data.

- <b>Geographic Market Analysis</b>
    - Analyzed Airbnb pricing across multiple zip codes to identify high-value markets and geographic pricing disparities.
  
- <b> Bedroom Pricing Analysis </b>
    - Examined the relationship between property size and listing price by comparing average prices across bedroom counts.
      
- <b>Revenue Analysis</b>
    - Evaluated annual revenue trends to estimate market performance and identify potential opportunities for hosts and investors.
      
<b>Dashboard Development</b>

Built an interactive dashboard that allows users to:

- Explore pricing by zip code
- Compare average prices by bedroom count
- Analyze annual revenue trends
- Investigate market opportunities through visual storytelling

<h2>Tools Used</h2>
  
- Tableau Public
- Microsoft Excel
- Data Visualization
- Exploratory Data Analysis (EDA)
- Dashboard Design
- Business Intelligence Reporting

<h2>Skills Demonstrated</h2>

<b>Data Analysis</b>
- Exploratory Data Analysis
- Trend Identification
- Geographic Analysis
- Revenue Analysis

<b>Data Visualization</b>
- Interactive Dashboard Development
- KPI Reporting
- Visual Storytelling
- Dashboard Design

<b>Technical Skills</b>
- Tableau Public
- Microsoft Excel
- Data Integration
- Business Intelligence

<h2>Environments used</h2>
- Windows 10 (22H2)

<h2>Key Insights</h2>

- Airbnb pricing varies significantly across zip codes.
- Larger properties generally command higher average prices.
- Geographic location is a major factor influencing listing value.
- Interactive dashboards improve the ability to identify market opportunities quickly.
- Visual analytics can simplify large datasets into actionable insights.

<h2>Project Outcome</h2>

The project successfully transformed raw Airbnb data into an interactive business intelligence dashboard that enables stakeholders to identify trends, evaluate market opportunities, and make data-driven decisions.

This project demonstrates the ability to:

- Clean and integrate datasets
- Build interactive dashboards
- Analyze business problems
- Communicate insights through data visualization
- Translate data into actionable recommendations

<h1>Dashboard Summary</h1>

The interactive dashboard consolidates these analyses into a single business intelligence tool that enables users to:

- Explore pricing differences across geographic markets
- Identify high-performing zip codes
- Evaluate the relationship between property size and pricing
- Analyze annual revenue trends
- Understand market supply distribution


<img src="https://imgur.com/ZdAYLBq.png" height="100%" width="100%" />
<br />
<br />

<h2>Dashboard Components and Analysis</h2>

<p align="center">
    
<h3>1. Price By Zipcode</h3>

<b>Purpose</b> 

This visualization analyzes the average Airbnb listing price across zip codes to identify geographic pricing trends.

<b>Analysis Performed</b>

- Grouped listings by zip code
- Calculated the average listing price for each location
- Compared price variations across different areas

<b>Business Value</b>

This analysis helps investors and hosts identify premium markets where properties command higher prices.

<b>Key Insight</b>

Location is a major factor influencing Airbnb pricing, with some zip codes significantly outperforming others.   

<img src="https://imgur.com/HQucnzD.png" height="100%" width="100%"/>
<br />
<br />

<h3>2. Price Per Zipcode (Geographic Map)</h3>

<b>Purpose</b>

This map visualization displays Airbnb prices geographically to provide spatial context.

<b>Analysis Performed</b>

- Plotted listings using generated latitude and longitude coordinates
- Visualized price distribution geographically
- Highlighted pricing clusters across different areas

<b>Business Value</b>

Geographic visualizations allow stakeholders to quickly identify high-performing markets and potential investment opportunities.

<b>Key Insight</b>

Airbnb pricing is not evenly distributed and tends to cluster in specific geographic areas.

<img src="https://imgur.com/QnFTYAQ.png" height="100%" width="100%" />
<br />
<br />

<h3>3. Revenue For Year</h3>

<b>Purpose</b>

This visualization examines revenue trends over time to understand annual market performance.

<b>Analysis Performed</b>

- Aggregated calendar pricing data
- Summed revenue values over time
- Visualized seasonal fluctuations throughout the year

<b>Business Value</b>

Revenue trends help hosts and investors understand periods of higher demand and adjust pricing strategies accordingly.

<b>Key Insight</b>

Revenue patterns fluctuate throughout the year, demonstrating the seasonality of the short-term rental market.

<img src="https://imgur.com/xlUxeKL.png" height="100%" width="100%"/>
<br />
<br />

<h3>4. Average Price per Bedroom</h3>

<b>Purpose</b>

This analysis evaluates how property size influences listing prices.

<b>Analysis Performed</b>

- Grouped listings by bedroom count
- Calculated average prices for each category
- Compared pricing differences across property sizes

<b>Business Value</b>

This visualization helps determine whether larger properties justify higher pricing.

<b>Key Insight</b>

Properties with more bedrooms generally command higher prices, although price increases are not always proportional to bedroom count.

<img src="https://imgur.com/hJotNdn.png" height="100%" width="100%" />
<br />
<br />

<h3>5. Distinct Count of Bedroom Listings</h3>

<b>Purpose</b>

This visualization measures the inventory distribution of Airbnb properties by bedroom count.

<b>Analysis Performed</b>

- Counted distinct listings for each bedroom category
- Evaluated supply distribution within the market
- Identified the most common property sizes

<b>Business Value</b>

Understanding market inventory helps hosts and investors identify saturated versus underserved segments.

<b>Key Insight</b>

Certain bedroom categories dominate the Airbnb market, revealing where competition is highest.

<img src="https://imgur.com/DaXiWux.png" height="100%" width="100%"/>
<br />
<br />

<h1>Business Recommendations</h1>

Based on the analysis, stakeholders could:

1. Prioritize investments in higher-priced zip codes.
2. Use bedroom count as a pricing strategy input.
3. Adjust pricing to account for seasonal demand fluctuations.
4. Identify underserved market segments with lower competition.
5. Use geographic analysis to discover emerging opportunities.

