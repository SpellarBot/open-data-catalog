# Substance Problems among Admissions to Maryland State-Supported Alcohol and Drug Abuse Treatment Programs, SFY 2008-2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/substance-problems-among-admissions-to-maryland-state-supported-alcohol-and-drug-abus-2008-41ec6) |
| Metadata | [Link](https://data.maryland.gov/api/views/iydi-jrpd) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/iydi-jrpd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/iydi-jrpd/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | iydi-jrpd |
| Name | Substance Problems among Admissions to Maryland State-Supported Alcohol and Drug Abuse Treatment Programs, SFY 2008-2012 |
| Attribution | Alcohol and Drug Abuse Administration |
| Category | Health and Human Services |
| Tags | alcohol, drug abuse, substance, treatment, alcohol and drug abuse administration |
| Created | 2013-01-03T23:31:43Z |
| Publication Date | 2013-01-04T18:33:12Z |

## Description

Up to three substance problems are reported for each admission so percentages do not total to 100.  Only includes data from state-supported treatment programs.  Data is by state fiscal year (SFY) which runs from July 1 - June 30.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | substance_problems | Substance Problem  | text      | text        |
| Yes      | series tag     | fy_2008_number     | Number (SFY 2008)  | text      | number      |
| Yes      | numeric metric | fy_2008_percent    | Percent (SFY 2008) | number    | number      |
| Yes      | series tag     | fy_2009_number     | Number (SFY 2009)  | text      | number      |
| Yes      | numeric metric | fy_2009_percent    | Percent (SFY 2009) | number    | number      |
| Yes      | series tag     | fy_2010_number     | Number (SFY 2010)  | text      | number      |
| Yes      | numeric metric | fy_2010_percent    | Percent (SFY 2010) | number    | number      |
| Yes      | series tag     | fy_2011_number     | Number (SFY 2011)  | text      | number      |
| Yes      | numeric metric | fy_2011_percent    | Percent (SFY 2011) | number    | number      |
| Yes      | series tag     | fy_2012_number     | Number (SFY 2012)  | text      | number      |
| Yes      | numeric metric | fy_2012_percent    | Percent (SFY 2012) | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:iydi-jrpd d:2008-01-01T00:00:00.000Z t:fy_2009_number=22958 t:fy_2008_number=22725 t:fy_2010_number=23568 t:substance_problems=Alcohol t:fy_2012_number=22585 t:fy_2011_number=23900 m:fy_2011_percent=53.4 m:fy_2010_percent=53.9 m:fy_2012_percent=51.6 m:fy_2009_percent=55.3 m:fy_2008_percent=56.6

series e:iydi-jrpd d:2008-01-01T00:00:00.000Z t:fy_2009_number=9971 t:fy_2008_number=11732 t:fy_2010_number=9204 t:substance_problems=Crack t:fy_2012_number=8615 t:fy_2011_number=8817 m:fy_2011_percent=19.7 m:fy_2010_percent=21.1 m:fy_2012_percent=19.7 m:fy_2009_percent=24 m:fy_2008_percent=29.2

series e:iydi-jrpd d:2008-01-01T00:00:00.000Z t:fy_2009_number=5048 t:fy_2008_number=5756 t:fy_2010_number=4985 t:substance_problems="Other Cocaine" t:fy_2012_number=5161 t:fy_2011_number=5123 m:fy_2011_percent=11.4 m:fy_2010_percent=11.4 m:fy_2012_percent=11.8 m:fy_2009_percent=12.2 m:fy_2008_percent=14.3
```

## Meta Commands

```ls
metric m:fy_2008_percent p:float l:"Percent (SFY 2008)" t:dataTypeName=number

metric m:fy_2009_percent p:float l:"Percent (SFY 2009)" t:dataTypeName=number

metric m:fy_2010_percent p:float l:"Percent (SFY 2010)" t:dataTypeName=number

metric m:fy_2011_percent p:float l:"Percent (SFY 2011)" t:dataTypeName=number

metric m:fy_2012_percent p:float l:"Percent (SFY 2012)" t:dataTypeName=number

entity e:iydi-jrpd l:"Substance Problems among Admissions to Maryland State-Supported Alcohol and Drug Abuse Treatment Programs, SFY 2008-2012" t:attribution="Alcohol and Drug Abuse Administration" t:url=https://data.maryland.gov/api/views/iydi-jrpd

property e:iydi-jrpd t:meta.view v:id=iydi-jrpd v:category="Health and Human Services" v:averageRating=0 v:name="Substance Problems among Admissions to Maryland State-Supported Alcohol and Drug Abuse Treatment Programs, SFY 2008-2012" v:attribution="Alcohol and Drug Abuse Administration"

property e:iydi-jrpd t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:iydi-jrpd t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| substance_problems | fy_2008_number | fy_2008_percent | fy_2009_number | fy_2009_percent | fy_2010_number | fy_2010_percent | fy_2011_number | fy_2011_percent | fy_2012_number | fy_2012_percent | 
| ================== | ============== | =============== | ============== | =============== | ============== | =============== | ============== | =============== | ============== | =============== | 
| Alcohol            | 22725          | 56.6            | 22958          | 55.3            | 23568          | 53.9            | 23900          | 53.4            | 22585          | 51.6            | 
| Crack              | 11732          | 29.2            | 9971           | 24.0            | 9204           | 21.1            | 8817           | 19.7            | 8615           | 19.7            | 
| Other Cocaine      | 5756           | 14.3            | 5048           | 12.2            | 4985           | 11.4            | 5123           | 11.4            | 5161           | 11.8            | 
| Marijuana/Hashish  | 14793          | 36.9            | 16260          | 39.2            | 17185          | 39.3            | 18414          | 41.1            | 17640          | 40.3            | 
| Heroin             | 12469          | 31.1            | 12575          | 30.3            | 13586          | 31.1            | 12766          | 28.5            | 13131          | 30.0            | 
| Non-Rx Methadone   | 458            | 1.1             | 521            | 1.3             | 520            | 1.2             | 552            | 1.2             | 523            | 1.2             | 
| Oxycodone          | 2096           | 5.2             | 2990           | 7.2             | 4231           | 9.7             | 5102           | 11.4            | 5759           | 13.2            | 
| Other Opioids      | 1402           | 3.5             | 1786           | 4.3             | 2274           | 5.2             | 2718           | 6.1             | 2815           | 6.4             | 
| PCP                | 697            | 1.7             | 861            | 2.1             | 916            | 2.1             | 943            | 2.1             | 955            | 2.2             | 
| Hallucinogens      | 232            | 0.6             | 277            | 0.7             | 224            | 0.5             | 324            | 0.7             | 303            | 0.7             | 
```