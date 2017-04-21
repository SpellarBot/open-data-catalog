# Personal Income By AGI Range

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/personal-income-by-agi-range-3b6e6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ipc3-2nbm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ipc3-2nbm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ipc3-2nbm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ipc3-2nbm |
| Name | Personal Income By AGI Range |
| Attribution | Independent Budget Office (IFO) |
| Category | City Government |
| Tags | personal income by agi range |
| Created | 2014-03-06T05:44:07Z |
| Publication Date | 2014-03-06T05:45:00Z |

## Description

Number of tax filers/payers and total income by income ranges

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                               | Data Type | Render Type |
| ======== | ============== | ================================ | ================================== | ========= | =========== |
| No       | time           | :updated_at                      | updated_at                         | meta_data | meta_data   |
| Yes      | series tag     | income_group                     | Income Group                       | text      | text        |
| Yes      | series tag     | minimun_income_in_group          | Minimun Income in group            | text      | number      |
| Yes      | numeric metric | number_of_filers                 | Number of Filers                   | number    | number      |
| Yes      | numeric metric | percentage                       | Percentage                         | number    | number      |
| Yes      | numeric metric | total_income_dollars_in_millions | Total income (dollars in millions) | number    | number      |
| No       |                | _                                | %                                  | number    | number      |
| Yes      | numeric metric | avergae_income_per_filer         | Avergae Income Per Filer           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = _
```

## Data Commands

```ls
series e:ipc3-2nbm d:2014-03-05T21:44:11.000Z t:minimun_income_in_group=0 t:income_group="1st Decile" m:number_of_filers=346320 m:percentage=10 m:total_income_dollars_in_millions=342.1 m:avergae_income_per_filer=988

series e:ipc3-2nbm d:2014-03-05T21:44:11.000Z t:minimun_income_in_group=3794 t:income_group="2nd Decile" m:number_of_filers=346026 m:percentage=10 m:total_income_dollars_in_millions=2279.1 m:avergae_income_per_filer=6587

series e:ipc3-2nbm d:2014-03-05T21:44:11.000Z t:minimun_income_in_group=9072 t:income_group="3rd Decile" m:number_of_filers=346159 m:percentage=10 m:total_income_dollars_in_millions=3995.9 m:avergae_income_per_filer=11543
```

## Meta Commands

```ls
metric m:number_of_filers p:integer l:"Number of Filers" t:dataTypeName=number

metric m:percentage p:integer l:Percentage t:dataTypeName=number

metric m:total_income_dollars_in_millions p:float l:"Total income (dollars in millions)" t:dataTypeName=number

metric m:avergae_income_per_filer p:integer l:"Avergae Income Per Filer" t:dataTypeName=number

entity e:ipc3-2nbm l:"Personal Income By AGI Range" t:attribution="Independent Budget Office (IFO)" t:url=https://data.cityofnewyork.us/api/views/ipc3-2nbm

property e:ipc3-2nbm t:meta.view v:id=ipc3-2nbm v:category="City Government" v:averageRating=0 v:name="Personal Income By AGI Range" v:attribution="Independent Budget Office (IFO)"

property e:ipc3-2nbm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ipc3-2nbm t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | income_group | minimun_income_in_group | number_of_filers | percentage | total_income_dollars_in_millions | _    | avergae_income_per_filer | 
| =========== | ============ | ======================= | ================ | ========== | ================================ | ==== | ======================== | 
| 1394055851  | 1st Decile   | 0                       | 346320           | 10         | 342.1                            | 0.1  | 988                      | 
| 1394055851  | 2nd Decile   | 3794                    | 346026           | 10         | 2279.1                           | 1    | 6587                     | 
| 1394055851  | 3rd Decile   | 9072                    | 346159           | 10         | 3995.9                           | 1.7  | 11543                    | 
| 1394055851  | 4th Decile   | 14229                   | 346193           | 10         | 5978.8                           | 2.6  | 17270                    | 
| 1394055851  | 5th Decile   | 20555                   | 246213           | 10         | 8431.3                           | 3.7  | 24353                    | 
| 1394055851  | 6th Decile   | 28213                   | 346021           | 10         | 11351                            | 4.9  | 32804                    | 
| 1394055851  | 7th Decile   | 37672                   | 346268           | 10         | 15020                            | 6.5  | 43377                    | 
| 1394055851  | 8th Decile   | 49509                   | 346132           | 10         | 20034.5                          | 8.7  | 57881                    | 
| 1394055851  | 9th Decile   | 68146                   | 346068           | 10         | 28997                            | 12.6 | 83790                    | 
| 1394055851  | 10th Decile  | 105368                  | 346121           | 10         | 134038.4                         | 58.2 | 387259                   | 
```