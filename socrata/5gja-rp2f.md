# Table 13.07 TOTAL AND PER CAPITA PERSONAL INCOME FOR THE UNITED STATES AND HAWAII 1969 TO 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-13-07-total-and-per-capita-personal-income-for-the-united-states-and-hawaii-1969-to-) |
| Metadata | [Link](https://data.hawaii.gov/api/views/5gja-rp2f) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/5gja-rp2f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/5gja-rp2f/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 5gja-rp2f |
| Name | Table 13.07 TOTAL AND PER CAPITA PERSONAL INCOME FOR THE UNITED STATES AND HAWAII 1969 TO 2014 |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | income |
| Created | 2012-08-27T22:09:33Z |
| Publication Date | 2015-10-21T19:46:55Z |

## Description

* Resident population as of July 1 of year indicated.							
* Per capita personal income is total personal income divided by July 1 population. 									
     Source:  U.S. Bureau of Economic Analysis, State Personal Income, and calculations by DBEDT 							
Please go to the DBEDT Databook site, http://hawaii.gov/dbedt/info/economic/databook,  for the complete data source.

## Columns

```ls
| Included | Schema Type    | Field Name                                                  | Name                                                           | Data Type | Render Type |
| ======== | ============== | =========================================================== | ============================================================== | ========= | =========== |
| Yes      | time           | year                                                        | Year                                                           | number    | number      |
| Yes      | numeric metric | personal_income_u_s_million                                 | Personal Income (U.S.), $million                               | money     | money       |
| Yes      | numeric metric | personal_income_hawaii_million                              | Personal Income (Hawaii), $million                             | money     | money       |
| Yes      | numeric metric | resident_population_u_s                                     | Resident Population (U.S.)                                     | number    | number      |
| Yes      | numeric metric | resident_population_hawaii                                  | Resident Population (Hawaii)                                   | number    | number      |
| Yes      | numeric metric | per_capita_personal_income_u_s                              | Per capita personal income (U.S.), $                           | money     | money       |
| Yes      | numeric metric | per_capita_personal_income_hawaii                           | Per capita personal income (Hawaii), $                         | money     | money       |
| Yes      | numeric metric | per_capita_personal_income_hawaii_as_percent_of_u_s_average | Per capita personal income (Hawaii as percent of U.S. Average) | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5gja-rp2f d:1969-01-01T00:00:00.000Z m:per_capita_personal_income_hawaii=4908 m:personal_income_u_s_million=791150 m:personal_income_hawaii_million=3647 m:per_capita_personal_income_hawaii_as_percent_of_u_s_average=124.9 m:per_capita_personal_income_u_s=3930 m:resident_population_hawaii=743000 m:resident_population_u_s=201298000

series e:5gja-rp2f d:1970-01-01T00:00:00.000Z m:per_capita_personal_income_hawaii=5544 m:personal_income_u_s_million=855078 m:personal_income_hawaii_million=4229 m:per_capita_personal_income_hawaii_as_percent_of_u_s_average=132.1 m:per_capita_personal_income_u_s=4196 m:resident_population_hawaii=762920 m:resident_population_u_s=203798722

series e:5gja-rp2f d:1971-01-01T00:00:00.000Z m:per_capita_personal_income_hawaii=5798 m:personal_income_u_s_million=923964 m:personal_income_hawaii_million=4589 m:per_capita_personal_income_hawaii_as_percent_of_u_s_average=129.8 m:per_capita_personal_income_u_s=4468 m:resident_population_hawaii=791580 m:resident_population_u_s=206817509
```

## Meta Commands

```ls
metric m:personal_income_u_s_million p:integer l:"Personal Income (U.S.), $million" t:dataTypeName=money

metric m:personal_income_hawaii_million p:integer l:"Personal Income (Hawaii), $million" t:dataTypeName=money

metric m:resident_population_u_s p:integer l:"Resident Population (U.S.)" t:dataTypeName=number

metric m:resident_population_hawaii p:integer l:"Resident Population (Hawaii)" t:dataTypeName=number

metric m:per_capita_personal_income_u_s p:integer l:"Per capita personal income (U.S.), $" t:dataTypeName=money

metric m:per_capita_personal_income_hawaii p:integer l:"Per capita personal income (Hawaii), $" t:dataTypeName=money

metric m:per_capita_personal_income_hawaii_as_percent_of_u_s_average p:float l:"Per capita personal income (Hawaii as percent of U.S. Average)" t:dataTypeName=number

entity e:5gja-rp2f l:"Table 13.07 TOTAL AND PER CAPITA PERSONAL INCOME FOR THE UNITED STATES AND HAWAII 1969 TO 2014" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/5gja-rp2f

property e:5gja-rp2f t:meta.view v:id=5gja-rp2f v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt/info/economic/databook v:averageRating=0 v:name="Table 13.07 TOTAL AND PER CAPITA PERSONAL INCOME FOR THE UNITED STATES AND HAWAII 1969 TO 2014" v:attribution="Department of Economic Development and Tourism"

property e:5gja-rp2f t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:5gja-rp2f t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:5gja-rp2f t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | personal_income_u_s_million | personal_income_hawaii_million | resident_population_u_s | resident_population_hawaii | per_capita_personal_income_u_s | per_capita_personal_income_hawaii | per_capita_personal_income_hawaii_as_percent_of_u_s_average | 
| ==== | =========================== | ============================== | ======================= | ========================== | ============================== | ================================= | =========================================================== | 
| 1969 | 791150                      | 3647                           | 201298000               | 743000                     | 3930                           | 4908                              | 124.9                                                       | 
| 1970 | 855078                      | 4229                           | 203798722               | 762920                     | 4196                           | 5544                              | 132.1                                                       | 
| 1971 | 923964                      | 4589                           | 206817509               | 791580                     | 4468                           | 5798                              | 129.8                                                       | 
| 1972 | 1015526                     | 5054                           | 209274882               | 818104                     | 4853                           | 6177                              | 127.3                                                       | 
| 1973 | 1131213                     | 5594                           | 211349205               | 841851                     | 5352                           | 6645                              | 124.2                                                       | 
| 1974 | 1242433                     | 6365                           | 213333635               | 858121                     | 5824                           | 7418                              | 127.4                                                       | 
| 1975 | 1359998                     | 6936                           | 215456585               | 875052                     | 6312                           | 7926                              | 125.6                                                       | 
| 1976 | 1491143                     | 7462                           | 217553859               | 892335                     | 6854                           | 8363                              | 122.0                                                       | 
| 1977 | 1646608                     | 8074                           | 219760875               | 915749                     | 7493                           | 8817                              | 117.7                                                       | 
| 1978 | 1851615                     | 8963                           | 222098244               | 928816                     | 8337                           | 9650                              | 115.7                                                       | 
```