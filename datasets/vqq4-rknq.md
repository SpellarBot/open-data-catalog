# IDES - Illinois Industry Projections 2008-2018

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ides-illinois-industry-projections-2008-2018-79b91) |
| Metadata | [Link](https://data.illinois.gov/api/views/vqq4-rknq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vqq4-rknq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vqq4-rknq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vqq4-rknq |
| Name | IDES - Illinois Industry Projections 2008-2018 |
| Attribution | IDES - Economic Information and Analysis Division |
| Category | Economics |
| Tags | ides, illinois industry projections 2008-2018, projections, industry |
| Created | 2012-04-12T20:42:11Z |
| Publication Date | 2012-04-12T20:52:58Z |

## Description

Illinois Long Term 2008-2018 Long Term Industry Projections

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag  | region                      | Region                      | text      | text        |
| Yes      | series tag  | industrycode                | IndustryCode                | text      | text        |
| Yes      | series tag  | industrytitle               | IndustryTitle               | text      | text        |
| Yes      | series tag  | baseyearemployment2008      | BaseYearEmployment2008      | text      | text        |
| Yes      | series tag  | projectedyearemployment2018 | ProjectedYearEmployment2018 | text      | text        |
| Yes      | series tag  | employmentchange            | EmploymentChange            | text      | text        |
| Yes      | series tag  | annualcompoundgrowthrate    | AnnualCompoundGrowthRate    | text      | text        |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vqq4-rknq d:2008-01-01T00:00:00.000Z t:employmentchange=548,419 t:industrytitle="TOTAL, ALL INDUSTRIES" t:region=Illinois t:industrycode=000000 t:projectedyearemployment2018=6,881,612 t:baseyearemployment2008=6,333,193 t:annualcompoundgrowthrate=0.83 m:row_number.vqq4-rknq=1

series e:vqq4-rknq d:2008-01-01T00:00:00.000Z t:employmentchange=15,583 t:industrytitle="Self Employed and Unpaid Family Workers" t:region=Illinois t:industrycode=100000 t:projectedyearemployment2018=301,866 t:baseyearemployment2008=286,283 t:annualcompoundgrowthrate=0.53 m:row_number.vqq4-rknq=2

series e:vqq4-rknq d:2008-01-01T00:00:00.000Z t:employmentchange=-5,243 t:industrytitle="Agricultural Production, Total" t:region=Illinois t:industrycode=110000 t:projectedyearemployment2018=66,150 t:baseyearemployment2008=71,393 t:annualcompoundgrowthrate=-0.76 m:row_number.vqq4-rknq=3
```

## Meta Commands

```ls
metric m:row_number.vqq4-rknq p:long l:"Row Number"

entity e:vqq4-rknq l:"IDES - Illinois Industry Projections 2008-2018" t:attribution="IDES - Economic Information and Analysis Division" t:url=https://data.illinois.gov/api/views/vqq4-rknq

property e:vqq4-rknq t:meta.view v:id=vqq4-rknq v:category=Economics v:attributionLink="http://www.ides.illinois.gov/page.aspx?item=911" v:averageRating=0 v:name="IDES - Illinois Industry Projections 2008-2018" v:attribution="IDES - Economic Information and Analysis Division"

property e:vqq4-rknq t:meta.view.owner v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"

property e:vqq4-rknq t:meta.view.tableauthor v:id=6i42-mskp v:screenName="David Egan" v:displayName="David Egan"
```

## Top Records

```ls
| region   | industrycode | industrytitle                           | baseyearemployment2008 | projectedyearemployment2018 | employmentchange | annualcompoundgrowthrate | 
| ======== | ============ | ======================================= | ====================== | =========================== | ================ | ======================== | 
| Illinois | 000000       | TOTAL, ALL INDUSTRIES                   | 6,333,193              | 6,881,612                   | 548,419          | 0.83                     | 
| Illinois | 100000       | Self Employed and Unpaid Family Workers | 286,283                | 301,866                     | 15,583           | 0.53                     | 
| Illinois | 110000       | Agricultural Production, Total          | 71,393                 | 66,150                      | -5,243           | -0.76                    | 
| Illinois | 120000       | Total Nonfarm                           | 5,975,517              | 6,513,596                   | 538,079          | 0.87                     | 
| Illinois | 210000       | Natural Resources and Mining            | 9,879                  | 8,807                       | -1,072           | -1.14                    | 
| Illinois | 210113       | Logging                                 | N.A.                   | N.A.                        | N.A.             | N.A.                     | 
| Illinois | 211000       | Oil and Gas Extraction                  | N.A.                   | N.A.                        | N.A.             | N.A.                     | 
| Illinois | 212000       | Mining (Except Oil and Gas)             | N.A.                   | N.A.                        | N.A.             | N.A.                     | 
| Illinois | 213000       | Support Activities for Mining           | N.A.                   | N.A.                        | N.A.             | N.A.                     | 
| Illinois | 230000       | Construction                            | 258,502                | 280,329                     | 21,827           | 0.81                     | 
```