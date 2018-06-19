# Number of Deaths among Maryland Residents, 1902-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-deaths-among-maryland-residents-1902-2011-41ed8) |
| Metadata | [Link](https://data.maryland.gov/api/views/97pp-kdid) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/97pp-kdid/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/97pp-kdid/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 97pp-kdid |
| Name | Number of Deaths among Maryland Residents, 1902-2011 |
| Attribution | Maryland Vital Statistics Administration |
| Category | Health and Human Services |
| Tags | death, vital statistics |
| Created | 2012-10-26T20:54:36Z |
| Publication Date | 2012-10-26T20:57:52Z |

## Description

Number of deaths among Maryland residents by year of death.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | numeric metric | number_of_deaths | Number of Deaths | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:97pp-kdid d:1902-01-01T00:00:00.000Z m:number_of_deaths=18690

series e:97pp-kdid d:1903-01-01T00:00:00.000Z m:number_of_deaths=18708

series e:97pp-kdid d:1904-01-01T00:00:00.000Z m:number_of_deaths=20350
```

## Meta Commands

```ls
metric m:number_of_deaths p:integer l:"Number of Deaths" t:dataTypeName=number

entity e:97pp-kdid l:"Number of Deaths among Maryland Residents, 1902-2011" t:attribution="Maryland Vital Statistics Administration" t:url=https://data.maryland.gov/api/views/97pp-kdid

property e:97pp-kdid t:meta.view v:id=97pp-kdid v:category="Health and Human Services" v:attributionLink=http://dhmh.maryland.gov/vsa/SitePages/reports.aspx v:averageRating=0 v:name="Number of Deaths among Maryland Residents, 1902-2011" v:attribution="Maryland Vital Statistics Administration"

property e:97pp-kdid t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:97pp-kdid t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| year | number_of_deaths | 
| ==== | ================ | 
| 1902 | 18690            | 
| 1903 | 18708            | 
| 1904 | 20350            | 
| 1905 | 19491            | 
| 1906 | 20204            | 
| 1907 | 20982            | 
| 1908 | 20284            | 
| 1909 | 20138            | 
| 1910 | 20568            | 
| 1911 | 20290            | 
```