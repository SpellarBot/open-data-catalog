# Overdose Deaths, Impaired Motor Vehicle Crashes, and Individuals in State-Supported Substance Abuse Programs by Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/overdose-deaths-impaired-motor-vehicle-crashes-and-individuals-in-state-supported-substanc-c184f) |
| Metadata | [Link](https://data.maryland.gov/api/views/kqrh-bm8r) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/kqrh-bm8r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/kqrh-bm8r/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | kqrh-bm8r |
| Name | Overdose Deaths, Impaired Motor Vehicle Crashes, and Individuals in State-Supported Substance Abuse Programs by Month |
| Attribution | DHMH |
| Category | Health and Human Services |
| Tags | substance abuse, dhmh, department of health and mental hygiene, overdose, drug, substance, heroin, cocaine |
| Created | 2012-08-23T20:40:59Z |
| Publication Date | 2015-09-08T16:11:55Z |

## Description

Data are provided by the Department of Health and Mental Hygiene. This dataset shows the number of statewide accidental overdose deaths, impaired motor vehicle crashes, and enrollment in state-sponsored substance abuse treatment programs.

## Columns

```ls
| Included | Schema Type    | Field Name                                        | Name                                                       | Data Type | Render Type |
| ======== | ============== | ================================================= | ========================================================== | ========= | =========== |
| No       |                | year                                              | Year                                                       | number    | text        |
| Yes      | time           | month                                             | Month                                                      | text      | text        |
| Yes      | numeric metric | individuals_in_state_supported_treatment_programs | Average Daily Active Patients in State Sponsored Treatment | number    | number      |
| Yes      | numeric metric | overdose_deaths                                   | Monthly Overdose Deaths                                    | number    | number      |
| Yes      | numeric metric | drug_or_alcohol_impaired_crashes                  | Drug or alcohol impaired crashes                           | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:kqrh-bm8r d:2011-01-01T00:00:00.000Z m:overdose_deaths=62 m:individuals_in_state_supported_treatment_programs=21242 m:drug_or_alcohol_impaired_crashes=586

series e:kqrh-bm8r d:2011-02-01T00:00:00.000Z m:overdose_deaths=54 m:individuals_in_state_supported_treatment_programs=21967 m:drug_or_alcohol_impaired_crashes=579

series e:kqrh-bm8r d:2011-03-01T00:00:00.000Z m:overdose_deaths=66 m:individuals_in_state_supported_treatment_programs=23619 m:drug_or_alcohol_impaired_crashes=638
```

## Meta Commands

```ls
metric m:individuals_in_state_supported_treatment_programs p:integer l:"Average Daily Active Patients in State Sponsored Treatment" t:dataTypeName=number

metric m:overdose_deaths p:integer l:"Monthly Overdose Deaths" t:dataTypeName=number

metric m:drug_or_alcohol_impaired_crashes p:integer l:"Drug or alcohol impaired crashes" t:dataTypeName=number

entity e:kqrh-bm8r l:"Overdose Deaths, Impaired Motor Vehicle Crashes, and Individuals in State-Supported Substance Abuse Programs by Month" t:attribution=DHMH t:url=https://data.maryland.gov/api/views/kqrh-bm8r

property e:kqrh-bm8r t:meta.view v:id=kqrh-bm8r v:category="Health and Human Services" v:attributionLink=http://dhmh.maryland.gov/SitePages/Home.aspx v:averageRating=0 v:name="Overdose Deaths, Impaired Motor Vehicle Crashes, and Individuals in State-Supported Substance Abuse Programs by Month" v:attribution=DHMH

property e:kqrh-bm8r t:meta.view.license v:name="Public Domain"

property e:kqrh-bm8r t:meta.view.owner v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:displayName="Kristen Ahearn"

property e:kqrh-bm8r t:meta.view.tableauthor v:id=qkre-c4b4 v:screenName="Kristen Ahearn" v:roleName=publisher v:displayName="Kristen Ahearn"
```

## Top Records

```ls
| year | month  | individuals_in_state_supported_treatment_programs | overdose_deaths | drug_or_alcohol_impaired_crashes | 
| ==== | ====== | ================================================= | =============== | ================================ | 
| 2011 | Jan-11 | 21242                                             | 62              | 586                              | 
| 2011 | Feb-11 | 21967                                             | 54              | 579                              | 
| 2011 | Mar-11 | 23619                                             | 66              | 638                              | 
| 2011 | Apr-11 | 23812                                             | 50              | 680                              | 
| 2011 | May-11 | 23312                                             | 47              | 708                              | 
| 2011 | Jun-11 | 23305                                             | 44              | 592                              | 
| 2011 | Jul-11 | 23098                                             | 57              | 663                              | 
| 2011 | Aug-11 | 23696                                             | 45              | 603                              | 
| 2011 | Sep-11 | 23350                                             | 51              | 677                              | 
| 2011 | Oct-11 | 23365                                             | 47              | 663                              | 
```