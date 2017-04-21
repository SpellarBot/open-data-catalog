# Maryland Infant Mortality and Infant Mortality Rates, 1904-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-infant-mortality-and-infant-mortality-rates-1904-2013-3e3b0) |
| Metadata | [Link](https://data.maryland.gov/api/views/p6r3-wfed) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/p6r3-wfed/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/p6r3-wfed/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | p6r3-wfed |
| Name | Maryland Infant Mortality and Infant Mortality Rates, 1904-2013 |
| Attribution | Vital Statistics Administration, Maryland Department of Health and Mental Hygiene |
| Category | Health and Human Services |
| Tags | infant deaths, infant mortality, rate, vital statistics |
| Created | 2013-05-22T21:28:52Z |
| Publication Date | 2014-10-02T17:29:59Z |

## Description

Rate and number of infant deaths per 1,000 live births by year. The total rate and number variables include all available races and are not limited to white and black races. Blank cells indicate that the data are not available.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                            | Data Type | Render Type |
| ======== | ============== | ============================= | =============================== | ========= | =========== |
| Yes      | time           | year                          | Year                            | number    | number      |
| Yes      | numeric metric | infant_mortality_rate_total   | Infant Mortality Rate (Total)   | number    | number      |
| Yes      | numeric metric | infant_mortality_rate_white   | Infant Mortality Rate (White)   | number    | number      |
| Yes      | numeric metric | infant_mortality_rate_black   | Infant Mortality Rate (Black)   | number    | number      |
| Yes      | numeric metric | number_of_infant_deaths_total | Number of Infant Deaths (Total) | number    | number      |
| Yes      | numeric metric | number_of_infant_deaths_white | Number of Infant Deaths (White) | number    | number      |
| Yes      | numeric metric | number_of_infant_deaths_black | Number of Infant Deaths (Black) | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:p6r3-wfed d:1904-01-01T00:00:00.000Z m:number_of_infant_deaths_total=5896 m:infant_mortality_rate_total=347.6

series e:p6r3-wfed d:1906-01-01T00:00:00.000Z m:number_of_infant_deaths_total=6127 m:infant_mortality_rate_total=324

series e:p6r3-wfed d:1907-01-01T00:00:00.000Z m:number_of_infant_deaths_total=6541 m:infant_mortality_rate_total=361.3
```

## Meta Commands

```ls
metric m:infant_mortality_rate_total p:float l:"Infant Mortality Rate (Total)" t:dataTypeName=number

metric m:infant_mortality_rate_white p:float l:"Infant Mortality Rate (White)" t:dataTypeName=number

metric m:infant_mortality_rate_black p:float l:"Infant Mortality Rate (Black)" t:dataTypeName=number

metric m:number_of_infant_deaths_total p:integer l:"Number of Infant Deaths (Total)" t:dataTypeName=number

metric m:number_of_infant_deaths_white p:integer l:"Number of Infant Deaths (White)" t:dataTypeName=number

metric m:number_of_infant_deaths_black p:integer l:"Number of Infant Deaths (Black)" t:dataTypeName=number

entity e:p6r3-wfed l:"Maryland Infant Mortality and Infant Mortality Rates, 1904-2013" t:attribution="Vital Statistics Administration, Maryland Department of Health and Mental Hygiene" t:url=https://data.maryland.gov/api/views/p6r3-wfed

property e:p6r3-wfed t:meta.view v:id=p6r3-wfed v:category="Health and Human Services" v:attributionLink=http://dhmh.maryland.gov/vsa/SitePages/Home.aspx v:averageRating=0 v:name="Maryland Infant Mortality and Infant Mortality Rates, 1904-2013" v:attribution="Vital Statistics Administration, Maryland Department of Health and Mental Hygiene"

property e:p6r3-wfed t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:p6r3-wfed t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| year | infant_mortality_rate_total | infant_mortality_rate_white | infant_mortality_rate_black | number_of_infant_deaths_total | number_of_infant_deaths_white | number_of_infant_deaths_black | 
| ==== | =========================== | =========================== | =========================== | ============================= | ============================= | ============================= | 
| 1904 | 347.6                       |                             |                             | 5896                          |                               |                               | 
| 1905 |                             |                             |                             |                               |                               |                               | 
| 1906 | 324.0                       |                             |                             | 6127                          |                               |                               | 
| 1907 | 361.3                       |                             |                             | 6541                          |                               |                               | 
| 1908 | 299.1                       |                             |                             | 5802                          |                               |                               | 
| 1909 | 305.5                       |                             |                             | 5998                          |                               |                               | 
| 1910 | 196.3                       |                             |                             | 4038                          |                               |                               | 
| 1911 | 281.8                       |                             |                             | 5593                          |                               |                               | 
| 1912 |                             |                             |                             |                               |                               |                               | 
| 1913 |                             |                             |                             |                               |                               |                               | 
```