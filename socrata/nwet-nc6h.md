# Tax Credits By Agi Range

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-credits-by-agi-range-4503f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nwet-nc6h) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nwet-nc6h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nwet-nc6h/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nwet-nc6h |
| Name | Tax Credits By Agi Range |
| Attribution | NYC Independent Budget Office (IBO) |
| Tags | tax credits by agi range |
| Created | 2014-03-06T05:47:36Z |
| Publication Date | 2014-03-06T05:48:25Z |

## Description

Number of tax filers/payers using various tax credits and amount of credit, by income ranges

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                             | Data Type | Render Type |
| ======== | ============== | ============================== | ================================ | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                       | meta_data | meta_data   |
| Yes      | series tag     | income_group                   | Income Group                     | text      | text        |
| Yes      | numeric metric | total_eitc_dollars_in_millions | Total EITC (dollars in millions) | number    | number      |
| Yes      | numeric metric | number_of_eitc_recipients      | Number of EITC Recipients        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nwet-nc6h d:2014-03-05T21:47:39.000Z t:income_group="1st Decile" m:number_of_eitc_recipients=58511 m:total_eitc_dollars_in_millions=1.5

series e:nwet-nc6h d:2014-03-05T21:47:39.000Z t:income_group="2nd Decile" m:number_of_eitc_recipients=198405 m:total_eitc_dollars_in_millions=11.7

series e:nwet-nc6h d:2014-03-05T21:47:39.000Z t:income_group="3rd Decile" m:number_of_eitc_recipients=216446 m:total_eitc_dollars_in_millions=27.4
```

## Meta Commands

```ls
metric m:total_eitc_dollars_in_millions p:float l:"Total EITC (dollars in millions)" t:dataTypeName=number

metric m:number_of_eitc_recipients p:integer l:"Number of EITC Recipients" t:dataTypeName=number

entity e:nwet-nc6h l:"Tax Credits By Agi Range" t:attribution="NYC Independent Budget Office (IBO)" t:url=https://data.cityofnewyork.us/api/views/nwet-nc6h

property e:nwet-nc6h t:meta.view v:id=nwet-nc6h v:averageRating=0 v:name="Tax Credits By Agi Range" v:attribution="NYC Independent Budget Office (IBO)"

property e:nwet-nc6h t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nwet-nc6h t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | income_group    | total_eitc_dollars_in_millions | number_of_eitc_recipients | 
| =========== | =============== | ============================== | ========================= | 
| 1394056059  | 1st Decile      | 1.5                            | 58511                     | 
| 1394056059  | 2nd Decile      | 11.7                           | 198405                    | 
| 1394056059  | 3rd Decile      | 27.4                           | 216446                    | 
| 1394056059  | 4th Decile      | 27                             | 147528                    | 
| 1394056059  | 5th Decile      | 18.899999999999999             | 135940                    | 
| 1394056059  | 6th Decile      | 7.6                            | 105057                    | 
| 1394056059  | 7th Decile      | 0.8                            | 22975                     | 
| 1394056059  | 8th-10th Decile | 0                              | 0                         | 
```