# CCM Web Scraping Project

This project demonstrates my ability to leverage Python, Pandas, Matplotlib, and Seaborn to extract, analyze, and visualize real-world data from web sources. Specifically, I performed a comprehensive web scraping analysis focused on box office performance metrics, showcasing key insights through four distinct visualizations.

## Project Overview

The objective of this project was to explore various aspects of the film industry’s box office trends by scraping data from Box Office Mojo. Using powerful data manipulation and visualization libraries, I crafted clear and insightful charts to answer a series of compelling questions about movie releases and revenue patterns.

- https://www.boxofficemojo.com/holiday/by-year/{year}/?grossesOption=calendarGrosses
- https://www.boxofficemojo.com/year/world/2024/
- https://www.boxofficemojo.com/intl/?ref_=bo_nb_cso_tab
- https://www.boxofficemojo.com/daily/2024/?view=year


## Skills Highlighted

- **Python** for data extraction and processing
- **Pandas** for structured data manipulation
- **Matplotlib & Seaborn** for advanced and aesthetically pleasing visualizations
- **Web Scraping** techniques using Requests and BeautifulSoup

## Research Questions Explored

1. **Holiday Box Office Impact**  
   Which holiday consistently delivers the highest average box office gross per film over the past five years, and how does that relate to its total cumulative earnings?

    ### Chart Summary:
    - **Thanksgiving** leads in both average gross per film and total gross.
    - **Independence Day and Christmas** also show strong performance.
    - **New Year’s Eve** consistently underperforms.

    ### Interpretation:
    - **Thanksgiving and Christmas** are prime windows for major releases.
    - Holiday scheduling should align with audience availability and genre fit.

2. **Domestic vs. International Performance**  
   How do the top-grossing films differ in domestic versus foreign box office revenue, and what proportion of their total earnings originates from international markets?

    ### Chart Summary:
    - **Foreign Gross**: $11.39B (57.9%)
    - **Domestic Gross**: $8.27B (42.1%)

    ### Interpretation:
    - **Foreign markets dominate** total box office revenue.
    - Success depends on **international appeal**, localization, and staggered global releases.
    - Tracking **country-level performance** is essential for multi-market strategies.

3. **International Market Analysis**  
   How does the number of film releases in a country correlate with its total weekend box office gross, and what trends can be observed across various global markets?

    ## Strategic Implications

    - **High-efficiency markets** (Japan, South Korea) are ideal for premium releases.
    - **Volume-heavy markets** (Australia, UAE) may require better targeting or marketing to improve ROI.
    - **Emerging markets** (Mexico, Brazil, Vietnam) offer growth opportunities with tailored content.
    - **Trend line analysis** helps identify countries where performance exceeds or lags expectations.

4. **Weekly Box Office Trends**  
   How does the day of the week influence total box office earnings, and what patterns emerge when comparing weekday versus weekend performance?

    ### Chart Summary:
    - **Friday and Saturday** lead with ~$0.8B each.
    - **Sunday** follows at ~$0.6B.
    - Weekdays range from ~$0.3B to ~$0.4B.
    - **Total Weekday Gross**: $2.08B  
    - **Total Weekend Gross**: $1.61B

    ### Interpretation:
    - **Weekends drive peak daily performance**, ideal for premieres.
    - **Weekdays sustain volume**, contributing more total gross due to frequency.

## Visualizations

The project includes four detailed charts, each designed to illustrate the answers to the above questions with clarity and depth. These visualizations help to contextualize the data, making the findings accessible and actionable.

---

Feel free to explore the notebook files and visualizations to gain deeper insights into the patterns and trends of the global box office landscape.
