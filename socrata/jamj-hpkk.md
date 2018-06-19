# Maryland Infant Deaths and Infant Death Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-infant-deaths-and-infant-death-rates-1904-2012-f917a) |
| Metadata | [Link](https://data.maryland.gov/api/views/jamj-hpkk) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/jamj-hpkk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/jamj-hpkk/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | jamj-hpkk |
| Name | Maryland Infant Deaths and Infant Death Rates |
| Attribution | Vital Statistics Administration |
| Category | Health and Human Services |
| Tags | infant deaths, infant mortality rate, vital statistics, governor's office of performance improvement |
| Created | 2012-08-23T20:06:50Z |
| Publication Date | 2014-09-27T14:33:59Z |

## Description

Rate and number of infant deaths per 1,000 live births by year. The total rate and number variables include all available races and are not limited to white and black races. Blank cells indicate that the data are not available.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                          | Data Type | Render Type |
| ======== | ============== | =========================== | ============================= | ========= | =========== |
| Yes      | time           | year                        | Year                          | number    | text        |
| Yes      | numeric metric | infant_mortality_rate_total | Infant Mortality Rate (Total) | number    | number      |
| Yes      | numeric metric | infant_mortality_rate_white | Infant Mortality Rate (White) | number    | number      |
| Yes      | numeric metric | infant_mortality_rate_black | Infant Mortality Rate (Black) | number    | number      |
| Yes      | numeric metric | infant_deaths_total         | Infant Deaths (Total)         | number    | number      |
| Yes      | numeric metric | infant_deaths_white         | Infant Deaths (White)         | number    | number      |
| Yes      | numeric metric | infant_deaths_black         | Infant Deaths (Black)         | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jamj-hpkk d:1904-01-01T00:00:00.000Z m:infant_mortality_rate_total=347.6 m:infant_deaths_total=5896

series e:jamj-hpkk d:1906-01-01T00:00:00.000Z m:infant_mortality_rate_total=324 m:infant_deaths_total=6127

series e:jamj-hpkk d:1907-01-01T00:00:00.000Z m:infant_mortality_rate_total=361.3 m:infant_deaths_total=6541
```

## Meta Commands

```ls
metric m:infant_mortality_rate_total p:float l:"Infant Mortality Rate (Total)" t:dataTypeName=number

metric m:infant_mortality_rate_white p:float l:"Infant Mortality Rate (White)" t:dataTypeName=number

metric m:infant_mortality_rate_black p:float l:"Infant Mortality Rate (Black)" t:dataTypeName=number

metric m:infant_deaths_total p:integer l:"Infant Deaths (Total)" t:dataTypeName=number

metric m:infant_deaths_white p:integer l:"Infant Deaths (White)" t:dataTypeName=number

metric m:infant_deaths_black p:integer l:"Infant Deaths (Black)" t:dataTypeName=number

entity e:jamj-hpkk l:"Maryland Infant Deaths and Infant Death Rates" t:attribution="Vital Statistics Administration" t:url=https://data.maryland.gov/api/views/jamj-hpkk

property e:jamj-hpkk t:meta.view v:id=jamj-hpkk v:category="Health and Human Services" v:attributionLink=http://dhmh.maryland.gov/vsa/SitePages/Home.aspx v:averageRating=0 v:name="Maryland Infant Deaths and Infant Death Rates" v:attribution="Vital Statistics Administration"

property e:jamj-hpkk t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:jamj-hpkk t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| year | infant_mortality_rate_total | infant_mortality_rate_white | infant_mortality_rate_black | infant_deaths_total | infant_deaths_white | infant_deaths_black | 
| ==== | =========================== | =========================== | =========================== | =================== | =================== | =================== | 
| 1904 | 347.6                       |                             |                             | 5896                |                     |                     | 
| 1905 |                             |                             |                             |                     |                     |                     | 
| 1906 | 324.0                       |                             |                             | 6127                |                     |                     | 
| 1907 | 361.3                       |                             |                             | 6541                |                     |                     | 
| 1908 | 299.1                       |                             |                             | 5802                |                     |                     | 
| 1909 | 305.5                       |                             |                             | 5998                |                     |                     | 
| 1910 | 196.3                       |                             |                             | 4038                |                     |                     | 
| 1911 | 281.8                       |                             |                             | 5593                |                     |                     | 
| 1912 |                             |                             |                             |                     |                     |                     | 
| 1913 |                             |                             |                             |                     |                     |                     | 
```