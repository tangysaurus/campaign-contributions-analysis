# Campaign Contributions and Election Results Analysis

### Description
This notebook analyzes over 44 million campaign contribution records and economic census data from 2,471 counties to explore donation patterns and predict election outcomes. Using machine learning, the notebook predicts county-level donation volumes and Democratic vote shares for the 2020 U.S. presidential election.

### Table of Contents
1. [Features](#features)
2. [Requirements](#requirements)
3. [Usage](#usage)
4. [License](#license)
5. [Data Sources](#data-sources)

### Features
- Analyze 44 million+ campaign contribution records.
- Predict donation volumes for counties using gradient boosting regression.
- Predict Democratic vote shares for the 2020 U.S. presidential election.
- Visualize the correlation between donation volumes and socioeconomic factors.

### Requirements
This project requires the following Python libraries:
- pandas
- seaborn
- matplotlib
- numpy
- scikit-learn
- xgboost
- statsmodels
- plotly.express
- dash
  
To install these dependencies, you can run: 
pip install -r requirements.txt

### Usage
1. **Open the notebook**:
   - Download or open the Jupyter notebook from this repository.

2. **Run the notebook**:
   - Execute each cell in the notebook by running the provided Python code.

3. **Install dependencies** (if needed):

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Data Sources

The following data sources were used in this project:

1. **Campaign Contributions Data (2023-24)**:
    - **Source**: [Federal Election Commission (FEC)](https://www.fec.gov/data/browse-data/?tab=bulk-data)
    - **Description**: This dataset contains each contribution from an individual to a federal committee. It includes the ID number of the committee receiving the contribution, the name, city, state, zip code, and place of business of the contributor along with the date and amount of the contribution.

2. **Election Results (2020)**:
    - **Source**: [MIT Election Data and Science Lab](https://electionlab.mit.edu/data)
    - **Description**: This dataset provides the official results of the 2020 U.S. presidential election by county, including voting totals and vote share percentages.
   
3. **Crime Data (2016)**
    - **Source**: [ICPSR University of Michigan](https://www.icpsr.umich.edu/web/NACJD/studies/37059/summary)
    - **Description**: This dataset contains county-level counts of arrests and offenses for Part I and Part II offenses.

4. **Cost of Living (2022)**
    - **Source**: [U.S. Department of Commerce](https://www.commerce.gov/news/blog/2024/03/estimating-county-level-regional-price-parities-public-data)
    - **Description**: This dataset provides regional price parities for U.S. counties.
     
5. **County Boundaries**
    - **Source**: (https://gist.github.com/sdwfrost/d1c73f91dd9d175998ed166eb216994a)
    - **Description**: This dataset provides geographical boundaries for U.S. counties.

6. **Demographics (2023)**
    - **Source**: [U.S. Census Bureau](https://www.census.gov/data/tables/time-series/demo/popest/2020s-counties-detail.html)
    - **Description**: This dataset provides population estimates by age, sex, and race for U.S. counties.
     
7. **Education (2022)**
    - **Source**: [U.S. Department of Agriculture](https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/)
    - **Description**: This dataset provides educational attainment for adults age 25 and older in U.S. counties.

8. **County FIPS Codes**
    - **Source**: [MDR Education](https://mdreducation.com/pdfs/US_FIPS_Codes.xls), (https://github.com/kjhealy/fips-codes/blob/master/state_and_county_fips_master.csv)
    - **Description**: These datasets provide FIPS codes for every U.S. county.

9. **GDP (2022)**
    - **Source**: [U.S. Bureau of Economic Analysis](https://www.bea.gov/data/gdp/gdp-county-metro-and-other-areas)
    - **Description**: This dataset provides GDP by county.
     
10. **Overdose Deaths (2022)**
    - **Source**: [CDC](https://www.cdc.gov/nchs/nvss/vsrr/prov-county-drug-overdose.htm)
    - **Description**: This dataset provides overdose death counts by county.

11. **Personal Income (2023)**
    - **Source**: [U.S. Bureau of Economic Analysis](https://www.bea.gov/data/income-saving/personal-income-county-metro-and-other-areas)
    - **Description**: This dataset provides personal income by county.

12. **Population and Migration (2023)**
    - **Source**: [U.S. Department of Agriculture](https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/)
    - **Description**: This dataset provides population and migration estimates by county.

13. **Poverty (2021)**
    - **Source**: [U.S. Department of Agriculture](https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/)
    - **Description**: This dataset provides poverty estimates by county.

14. **Unemployment and Median Household Income (2021)**
    - **Source**: [U.S. Department of Agriculture](https://www.ers.usda.gov/data-products/county-level-data-sets/county-level-data-sets-download-data/)
    - **Description**: This dataset provides unemployment rates and median household income estimates by county.

15. **U.S. Counties**
    - **Source**: (https://github.com/grammakov/USA-cities-and-states)
    - **Description**: This dataset provides every U.S. city and its corresponding state and county.

16. **Voting Age Population (2022)**
    - **Source**: [U.S. Census Bureau](https://www.census.gov/programs-surveys/decennial-census/about/voting-rights/cvap.html)
    - **Description**: This dataset provides voting age population estimates by race and ethnicity for every county.

  All datasets are publicly available and can be downloaded from the links provided above.
  Please refer to the individual sources for licensing details, terms of use, and citation requirements.
