# Number of Diabetes Deaths among Maryland Residents, 1920-2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/number-of-diabetes-deaths-among-maryland-residents-1920-2011-a950a) |
| Metadata | [Link](https://data.maryland.gov/api/views/smru-f5wc) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/smru-f5wc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/smru-f5wc/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | smru-f5wc |
| Name | Number of Diabetes Deaths among Maryland Residents, 1920-2011 |
| Attribution | Maryland Vital Statistics Administration |
| Category | Health and Human Services |
| Tags | death, diabetes mellitus, vital statistics |
| Created | 2012-10-26T21:15:24Z |
| Publication Date | 2012-11-19T21:11:43Z |

## Description

Number of deaths among Maryland residents for which diabetes mellitus was the underlying cause of death.  This includes deaths coded to the following International Classification of Diseases codes:
ICD-3 (1920-1929) -- 57
ICD-4 (1930-1938) -- 59
ICD-5 (1939-1948) -- 61
ICD-6 (1949-1957) -- 260
ICD-7 (1958-1967) -- 260
ICD-8 (1968-1978) -- 250
ICD-9 (1979-1998) -- 250
ICD-10 (1999-present) -- E10-E14.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | time           | year                      | Year                      | number    | number      |
| Yes      | numeric metric | number_of_diabetes_deaths | Number of Diabetes Deaths | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:smru-f5wc d:1920-01-01T00:00:00.000Z m:number_of_diabetes_deaths=252

series e:smru-f5wc d:1921-01-01T00:00:00.000Z m:number_of_diabetes_deaths=259

series e:smru-f5wc d:1922-01-01T00:00:00.000Z m:number_of_diabetes_deaths=303
```

## Meta Commands

```ls
metric m:number_of_diabetes_deaths p:integer l:"Number of Diabetes Deaths" t:dataTypeName=number

entity e:smru-f5wc l:"Number of Diabetes Deaths among Maryland Residents, 1920-2011" t:attribution="Maryland Vital Statistics Administration" t:url=https://data.maryland.gov/api/views/smru-f5wc

property e:smru-f5wc t:meta.view v:id=smru-f5wc v:category="Health and Human Services" v:attributionLink=http://dhmh.maryland.gov/vsa/SitePages/reports.aspx v:averageRating=0 v:name="Number of Diabetes Deaths among Maryland Residents, 1920-2011" v:attribution="Maryland Vital Statistics Administration"

property e:smru-f5wc t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:smru-f5wc t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| year | number_of_diabetes_deaths | 
| ==== | ========================= | 
| 1920 | 252                       | 
| 1921 | 259                       | 
| 1922 | 303                       | 
| 1923 | 308                       | 
| 1924 | 310                       | 
| 1925 | 283                       | 
| 1926 | 364                       | 
| 1927 | 305                       | 
| 1928 | 372                       | 
| 1929 | 318                       | 
```