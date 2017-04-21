# CT Occupational Employment & Wages (OES) - 2016-Q1

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ct-occupational-employment-wages-oes-2016-q1) |
| Metadata | [Link](https://data.ct.gov/api/views/tids-7w95) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/tids-7w95/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/tids-7w95/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | tids-7w95 |
| Name | CT Occupational Employment & Wages (OES) - 2016-Q1 |
| Attribution | Department of Labor, Office of Research |
| Category | Government |
| Tags | oes, wage, ct, occupational employment & wages |
| Created | 2016-06-16T17:55:12Z |
| Publication Date | 2016-06-16T18:01:16Z |

## Description

The Connecticut Occupational Employment and Wage data provides employment and wage data by occupation and is based on the results of the Occupational Employment Statistics (OES) survey. The OES program conducts a bi-annual mail survey designed to produce estimates of employment and wages for over 800 occupations. These estimates are generated at the national, state, and metropolitan area levels. For more information, please visit us at http://www1.ctdol.state.ct.us/lmi/wages/default.asp.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | series tag     | area                       | Area                       | text      | text        |
| Yes      | series tag     | areaname                   | AreaName                   | text      | text        |
| Yes      | series tag     | soc_code                   | SOC Code                   | text      | text        |
| Yes      | series tag     | soc_title                  | SOC Title                  | text      | text        |
| Yes      | numeric metric | employment                 | Employment                 | number    | text        |
| Yes      | series tag     | meanhourlywage             | MeanHourlyWage             | text      | text        |
| Yes      | series tag     | meanannualwage             | MeanAnnualWage             | text      | text        |
| Yes      | series tag     | entrylevelhourlywage       | EntryLevelHourlyWage       | text      | text        |
| Yes      | series tag     | entrylevelannualwage       | EntryLevelAnnualWage       | text      | text        |
| Yes      | numeric metric | experiencedlevelhourlywage | ExperiencedLevelHourlyWage | number    | number      |
| Yes      | series tag     | experiencedlevelannualwage | ExperiencedLevelAnnualWage | text      | text        |
| Yes      | series tag     | 10_hourlywage              | 10%HourlyWage              | text      | text        |
| Yes      | series tag     | 10_annualwage              | 10%AnnualWage              | text      | text        |
| Yes      | series tag     | 25_hourlywage              | 25%HourlyWage              | text      | text        |
| Yes      | series tag     | 25_annualwage              | 25%AnnualWage              | text      | text        |
| Yes      | series tag     | medianhourlywage           | MedianHourlyWage           | text      | text        |
| Yes      | series tag     | medianannualwage           | MedianAnnualWage           | text      | text        |
| Yes      | series tag     | 75_hourlywage              | 75%HourlyWage              | text      | text        |
| Yes      | series tag     | 75_annualwage              | 75%AnnualWage              | text      | text        |
| Yes      | series tag     | 90_hourlywage              | 90%HourlyWage              | text      | text        |
| Yes      | series tag     | 90_annualwage              | 90%AnnualWage              | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tids-7w95 d:2016-01-01T00:00:00.000Z t:90_hourlywage=50.14 t:areaname="Connecticut Statewide" t:experiencedlevelannualwage=73,859 t:75_hourlywage=34.34 t:soc_code=00-0000 t:25_annualwage=27,748 t:90_annualwage=104,304 t:medianhourlywage=21.45 t:75_annualwage=71,426 t:meanhourlywage=27.54 t:area=000009 t:meanannualwage=57,287 t:soc_title="Total all occupations" t:entrylevelhourlywage=11.61 t:10_annualwage=20,389 t:entrylevelannualwage=24,165 t:25_hourlywage=13.34 t:medianannualwage=44,615 t:10_hourlywage=9.80 m:employment=1659430 m:experiencedlevelhourlywage=35.5

series e:tids-7w95 d:2016-01-01T00:00:00.000Z t:90_hourlywage=>90.00 t:areaname="Connecticut Statewide" t:experiencedlevelannualwage=164,974 t:75_hourlywage=77.89 t:soc_code=11-0000 t:25_annualwage=82,953 t:90_annualwage=>187,200 t:medianhourlywage=55.95 t:75_annualwage=162,006 t:meanhourlywage=63.74 t:area=000009 t:meanannualwage=132,585 t:soc_title="Management Occupations" t:entrylevelhourlywage=32.60 t:10_annualwage=57,471 t:entrylevelannualwage=67,807 t:25_hourlywage=39.88 t:medianannualwage=116,375 t:10_hourlywage=27.63 m:employment=114720 m:experiencedlevelhourlywage=79.32

series e:tids-7w95 d:2016-01-01T00:00:00.000Z t:90_hourlywage=>90.00 t:areaname="Connecticut Statewide" t:experiencedlevelannualwage=280,684 t:75_hourlywage=>90.00 t:soc_code=11-1011 t:25_annualwage=167,727 t:90_annualwage=>187,200 t:medianhourlywage=>90.00 t:75_annualwage=>187,200 t:meanhourlywage=111.90 t:area=000009 t:meanannualwage=232,751 t:soc_title="Chief Executives" t:entrylevelhourlywage=65.81 t:10_annualwage=121,492 t:entrylevelannualwage=136,883 t:25_hourlywage=80.64 t:medianannualwage=>187,200 t:10_hourlywage=58.41 m:employment=1370 m:experiencedlevelhourlywage=134.95
```

## Meta Commands

```ls
metric m:experiencedlevelhourlywage p:float l:ExperiencedLevelHourlyWage t:dataTypeName=number

entity e:tids-7w95 l:"CT Occupational Employment & Wages (OES) - 2016-Q1" t:attribution="Department of Labor, Office of Research" t:url=https://data.ct.gov/api/views/tids-7w95

property e:tids-7w95 t:meta.view v:id=tids-7w95 v:category=Government v:attributionLink=http://www1.ctdol.state.ct.us/lmi/wages/default.asp v:averageRating=0 v:name="CT Occupational Employment & Wages (OES) - 2016-Q1" v:attribution="Department of Labor, Office of Research"

property e:tids-7w95 t:meta.view.license v:name="Public Domain"

property e:tids-7w95 t:meta.view.owner v:id=dm7v-mmvk v:screenName="Andrew Condon" v:displayName="Andrew Condon"

property e:tids-7w95 t:meta.view.tableauthor v:id=dm7v-mmvk v:screenName="Andrew Condon" v:roleName=editor v:displayName="Andrew Condon"
```

## Top Records

```ls
| area   | areaname              | soc_code | soc_title                                 | employment | meanhourlywage | meanannualwage | entrylevelhourlywage | entrylevelannualwage | experiencedlevelhourlywage | experiencedlevelannualwage | 10_hourlywage | 10_annualwage | 25_hourlywage | 25_annualwage | medianhourlywage | medianannualwage | 75_hourlywage | 75_annualwage | 90_hourlywage | 90_annualwage | 
| ====== | ===================== | ======== | ========================================= | ========== | ============== | ============== | ==================== | ==================== | ========================== | ========================== | ============= | ============= | ============= | ============= | ================ | ================ | ============= | ============= | ============= | ============= | 
| 000009 | Connecticut Statewide | 00-0000  | Total all occupations                     | 1,659,430  | 27.54          | 57,287         | 11.61                | 24,165               | 35.50                      | 73,859                     | 9.80          | 20,389        | 13.34         | 27,748        | 21.45            | 44,615           | 34.34         | 71,426        | 50.14         | 104,304       | 
| 000009 | Connecticut Statewide | 11-0000  | Management Occupations                    | 114,720    | 63.74          | 132,585        | 32.60                | 67,807               | 79.32                      | 164,974                    | 27.63         | 57,471        | 39.88         | 82,953        | 55.95            | 116,375          | 77.89         | 162,006       | >90.00        | >187,200      | 
| 000009 | Connecticut Statewide | 11-1011  | Chief Executives                          | 1,370      | 111.90         | 232,751        | 65.81                | 136,883              | 134.95                     | 280,684                    | 58.41         | 121,492       | 80.64         | 167,727       | >90.00           | >187,200         | >90.00        | >187,200      | >90.00        | >187,200      | 
| 000009 | Connecticut Statewide | 11-1021  | General and Operations Managers           | 34,400     | 68.64          | 142,757        | 30.25                | 62,926               | 87.82                      | 182,678                    | 25.76         | 53,572        | 37.35         | 77,682        | 57.22            | 119,005          | 91.73         | 190,814       | >90.00        | >187,200      | 
| 000009 | Connecticut Statewide | 11-1031  | Legislators                               | 400        | N/A            | 43,308         | N/A                  | 21,275               |                            | 54,319                     | N/A           | 19,669        | N/A           | 20,395        | N/A              | 35,459           | N/A           | 44,096        | N/A           | 89,257        | 
| 000009 | Connecticut Statewide | 11-2011  | Advertising and Promotions Managers       | 290        | 60.02          | 124,838        | 32.62                | 67,858               | 73.71                      | 153,328                    | 29.18         | 60,674        | 37.72         | 78,460        | 57.18            | 118,934          | 76.09         | 158,261       | >90.00        | >187,200      | 
| 000009 | Connecticut Statewide | 11-2021  | Marketing Managers                        | 4,790      | 71.44          | 148,601        | 41.68                | 86,708               | 86.32                      | 179,536                    | 37.01         | 76,997        | 48.59         | 101,056       | 62.64            | 130,283          | 85.79         | 178,441       | >90.00        | >187,200      | 
| 000009 | Connecticut Statewide | 11-2022  | Sales Managers                            | 6,990      | 72.29          | 150,361        | 38.78                | 80,681               | 89.04                      | 185,206                    | 34.67         | 72,115        | 46.37         | 96,430        | 64.60            | 134,386          | 89.50         | 186,168       | >90.00        | >187,200      | 
| 000009 | Connecticut Statewide | 11-2031  | Public Relations and Fundraising Managers | 920        | 58.92          | 122,556        | 35.52                | 73,886               | 70.62                      | 146,892                    | 32.12         | 66,804        | 40.58         | 84,396        | 54.38            | 113,121          | 73.25         | 152,366       | 90.99         | 189,248       | 
| 000009 | Connecticut Statewide | 11-3011  | Administrative Services Managers          | 4,260      | 51.61          | 107,339        | 34.68                | 72,136               | 60.07                      | 124,951                    | 31.67         | 65,873        | 39.53         | 82,226        | 48.61            | 101,117          | 60.41         | 125,657       | 75.06         | 156,132       | 
```