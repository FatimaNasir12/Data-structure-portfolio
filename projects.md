# Projects

## Project 1: Electric Vehicles and Charging Infrastructure

### Research Question

**Is charging infrastructure growing fast enough to support electric vehicle growth?**

### Overview

Electric vehicle adoption in the United States has grown rapidly in recent years. As more people use electric vehicles, charging infrastructure needs to grow as well.

For this project, I compared electric vehicle registrations with charging stations and charging outlets from 2016 to 2025.

### Data Sources

The data for this project came from the U.S. Department of Energy's Alternative Fuels Data Center (AFDC).

I used:

- Historical charging station and outlet counts by state and year
- Electric vehicle registration counts by state and year
- Data from 2016 through 2025

The final dataset contains 510 state-year observations.

### Tools Used

- Python
- pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

### Analysis

I cleaned and combined the datasets using state and year. I then compared the growth of EV registrations with the growth of charging outlets.

I also calculated the number of registered EVs per charging outlet to examine how the relationship between EV adoption and charging infrastructure changed over time.

### Key Findings

EV registrations increased from about **280,300 in 2016** to more than **5.6 million in 2025**.

Charging outlets also increased, from about **44,299 in 2016** to **271,488 in 2025**.

However, EV registrations grew much faster than charging outlets. The number of registered EVs per charging outlet increased from approximately **6.3 in 2016** to approximately **21.0 in 2025**.

These results suggest that charging infrastructure is growing, but it may not be keeping pace with the rapid growth of electric vehicle registrations.

### Visualizations

The project includes two visualizations:

1. **EV Registrations vs. Charging Outlet Growth**  
   This visualization compares the growth of EV registrations and charging outlets using 2016 as the baseline.

2. **EV Registrations per Charging Outlet**  
   This visualization shows how the number of registered EVs per charging outlet changed from 2016 to 2025.

### Limitations and Ethics

The EV registration data are approximate and rounded to the nearest 100. The charging infrastructure data include public and private non-residential locations, so not every charging outlet is available to every EV driver.

The EVs-per-outlet calculation is also a simple measure and does not account for charger speed, location, usage, or availability.

The historical charging data also have a methodology change around 2021, which may affect comparisons across years.

The project uses publicly available data from the U.S. Department of Energy's Alternative Fuels Data Center and does not use personal identifying information.

### Reflection

This project helped me practice collecting, cleaning, combining, and analyzing real-world data using Python. It also helped me understand the importance of considering data limitations when interpreting results.

### Project Files

[View the Project Notebook](https://github.com/FatimaNasir12/Data-structure-portfolio/blob/main/EV_project1.ipynb)

[View My GitHub Repository](https://github.com/FatimaNasir12/Data-structure-portfolio)