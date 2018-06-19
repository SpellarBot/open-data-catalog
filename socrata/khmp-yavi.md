# Table 13.02 GROSS DOMESTIC PRODUCT, TOTAL AND PER CAPITA AND RESIDENT POPULATION 1963 TO 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-13-02-gross-domestic-product-total-and-per-capita-and-resident-population-1963-to-20-10b17) |
| Metadata | [Link](https://data.hawaii.gov/api/views/khmp-yavi) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/khmp-yavi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/khmp-yavi/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | khmp-yavi |
| Name | Table 13.02 GROSS DOMESTIC PRODUCT, TOTAL AND PER CAPITA AND RESIDENT POPULATION 1963 TO 2014 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | gdp, capita, resident |
| Created | 2012-08-27T22:02:30Z |
| Publication Date | 2015-10-21T20:14:47Z |

## Description

* Real GDP is an inflation-adjusted measure of each State?s gross product that is based on national prices for the goods and services produced within that State.							
*  Midyear population estimates of the Census Bureau.  Last updated on December 2014.							
* There is a discontinuity in the GDP time series at 1997, when the data change from SIC industry definitions to NAICS industry definition.  This data discontinuity may affect both the levels and the growth rates of the GDP estimates. Users of the GDP estimates are strongly cautioned against appending the two data series in an attempt to construct a single time series of GDP estimates for 1963 to 2014. 							
     Source:  U.S. Bureau of Economic Analysis, Gross Domestic Product by Industry 1963 to 2014,  Annual State Personal Income and Employment, "SA1-3 Personal income summary, Population 1929-2014" and DBEDT calculation							
Please go to the DBEDT Databook site, http://hawaii.gov/dbedt/info/economic/databook,  for the complete data source.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                     | Data Type | Render Type |
| ======== | ============== | =================================== | ======================================== | ========= | =========== |
| Yes      | time           | year_and_category                   | Year and category                        | number    | number      |
| Yes      | numeric metric | gdp_current_million                 | GDP (current), $million                  | number    | number      |
| Yes      | series tag     | gdp_chained_2009_dollars_million    | GDP (chained 2009 dollars), $million     | text      | text        |
| Yes      | numeric metric | per_capita_gdp_current              | Per capita GDP (current), $              | number    | number      |
| Yes      | series tag     | per_capita_gdp_chained_2009_dollars | Per capita GDP (chained 2009 dollars), $ | text      | text        |
| Yes      | numeric metric | resident_population                 | Resident population                      | number    | number      |
```

## Time Field

```ls
Value = year_and_category
Format & Zone = yyyy
```

## Data Commands

```ls
series e:khmp-yavi d:1963-01-01T00:00:00.000Z t:gdp_chained_2009_dollars_million=NA t:per_capita_gdp_chained_2009_dollars=NA m:gdp_current_million=2367 m:per_capita_gdp_current=3471 m:resident_population=682000

series e:khmp-yavi d:1964-01-01T00:00:00.000Z t:gdp_chained_2009_dollars_million=NA t:per_capita_gdp_chained_2009_dollars=NA m:gdp_current_million=2571 m:per_capita_gdp_current=3673 m:resident_population=700000

series e:khmp-yavi d:1965-01-01T00:00:00.000Z t:gdp_chained_2009_dollars_million=NA t:per_capita_gdp_chained_2009_dollars=NA m:gdp_current_million=2849 m:per_capita_gdp_current=4047 m:resident_population=704000
```

## Meta Commands

```ls
metric m:gdp_current_million p:integer l:"GDP (current), $million" t:dataTypeName=number

metric m:per_capita_gdp_current p:integer l:"Per capita GDP (current), $" t:dataTypeName=number

metric m:resident_population p:integer l:"Resident population" t:dataTypeName=number

entity e:khmp-yavi l:"Table 13.02 GROSS DOMESTIC PRODUCT, TOTAL AND PER CAPITA AND RESIDENT POPULATION 1963 TO 2014" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/khmp-yavi

property e:khmp-yavi t:meta.view v:id=khmp-yavi v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/info/economic/databook v:averageRating=0 v:name="Table 13.02 GROSS DOMESTIC PRODUCT, TOTAL AND PER CAPITA AND RESIDENT POPULATION 1963 TO 2014" v:attribution="Department of Economic Development and Tourism"

property e:khmp-yavi t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:khmp-yavi t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:khmp-yavi t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year_and_category | gdp_current_million | gdp_chained_2009_dollars_million | per_capita_gdp_current | per_capita_gdp_chained_2009_dollars | resident_population | 
| ================= | =================== | ================================ | ====================== | =================================== | =================== | 
| 1963.0            | 2367                | NA                               | 3471                   | NA                                  | 682000              | 
| 1964.0            | 2571                | NA                               | 3673                   | NA                                  | 700000              | 
| 1965.0            | 2849                | NA                               | 4047                   | NA                                  | 704000              | 
| 1966.0            | 3110                | NA                               | 4380                   | NA                                  | 710000              | 
| 1967.0            | 3307                | NA                               | 4574                   | NA                                  | 723000              | 
| 1968.0            | 3722                | NA                               | 5071                   | NA                                  | 734000              | 
| 1969.0            | 4262                | NA                               | 5736                   | NA                                  | 743000              | 
| 1970.0            | 4813                | NA                               | 6309                   | NA                                  | 762920              | 
| 1971.0            | 5188                | NA                               | 6554                   | NA                                  | 791580              | 
| 1972.0            | 5624                | NA                               | 6874                   | NA                                  | 818104              | 
```