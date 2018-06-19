# Income By Type Of Income And AGI Range

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/income-by-type-of-income-and-agi-range-797f2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/gffu-ps8j) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/gffu-ps8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/gffu-ps8j/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | gffu-ps8j |
| Name | Income By Type Of Income And AGI Range |
| Attribution | NYC Independent Budget Office (IBO) |
| Category | City Government |
| Tags | income by type of income and agi range |
| Created | 2014-03-06T05:45:25Z |
| Publication Date | 2014-03-06T05:46:07Z |

## Description

Number of tax filers/payers and income from various types of income by income ranges

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                         | Data Type | Render Type |
| ======== | ============== | ========================================== | ============================================ | ========= | =========== |
| No       | time           | :updated_at                                | updated_at                                   | meta_data | meta_data   |
| Yes      | series tag     | income_group                               | Income Group                                 | text      | text        |
| Yes      | numeric metric | wages_and_saleries_dollars_in_millions     | Wages and Saleries (dollars in millions)     | number    | number      |
| Yes      | numeric metric | percentage                                 | Percentage                                   | number    | number      |
| Yes      | numeric metric | dividends_and_interest_dollars_in_millions | Dividends and Interest (Dollars in millions) | number    | number      |
| Yes      | numeric metric | percent                                    | Percent                                      | number    | number      |
| Yes      | numeric metric | business_income                            | Business Income                              | number    | number      |
| No       |                | _                                          | %                                            | number    | number      |
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
series e:gffu-ps8j d:2014-03-05T21:45:28.000Z t:income_group="1st Decile" m:wages_and_saleries_dollars_in_millions=830.7 m:percent=6.6 m:percentage=0.5 m:business_income=-4832 m:dividends_and_interest_dollars_in_millions=918.9

series e:gffu-ps8j d:2014-03-05T21:45:28.000Z t:income_group="2nd Decile" m:wages_and_saleries_dollars_in_millions=1202.6 m:percent=1.7 m:percentage=0.7 m:business_income=731.3 m:dividends_and_interest_dollars_in_millions=233.4

series e:gffu-ps8j d:2014-03-05T21:45:28.000Z t:income_group="3rd Decile" m:wages_and_saleries_dollars_in_millions=2511.8 m:percent=1.7 m:percentage=1.5 m:business_income=1011.4 m:dividends_and_interest_dollars_in_millions=237.8
```

## Meta Commands

```ls
metric m:wages_and_saleries_dollars_in_millions p:float l:"Wages and Saleries (dollars in millions)" t:dataTypeName=number

metric m:percentage p:double l:Percentage t:dataTypeName=number

metric m:dividends_and_interest_dollars_in_millions p:float l:"Dividends and Interest (Dollars in millions)" t:dataTypeName=number

metric m:percent p:double l:Percent t:dataTypeName=number

metric m:business_income p:float l:"Business Income" t:dataTypeName=number

entity e:gffu-ps8j l:"Income By Type Of Income And AGI Range" t:attribution="NYC Independent Budget Office (IBO)" t:url=https://data.cityofnewyork.us/api/views/gffu-ps8j

property e:gffu-ps8j t:meta.view v:id=gffu-ps8j v:category="City Government" v:averageRating=0 v:name="Income By Type Of Income And AGI Range" v:attribution="NYC Independent Budget Office (IBO)"

property e:gffu-ps8j t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:gffu-ps8j t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | income_group | wages_and_saleries_dollars_in_millions | percentage         | dividends_and_interest_dollars_in_millions | percent            | business_income | _     | 
| =========== | ============ | ====================================== | ================== | ========================================== | ================== | =============== | ===== | 
| 1394055928  | 1st Decile   | 830.7                                  | 0.5                | 918.9                                      | 6.6                | -4832           | -16.7 | 
| 1394055928  | 2nd Decile   | 1202.5999999999999                     | 0.7                | 233.4                                      | 1.7                | 731.3           | 2.5   | 
| 1394055928  | 3rd Decile   | 2511.8000000000002                     | 1.5                | 237.8                                      | 1.7                | 1011.4          | 3.5   | 
| 1394055928  | 4th Decile   | 4483.1000000000004                     | 2.7                | 237.1                                      | 1.7                | 722.6           | 2.5   | 
| 1394055928  | 5th Decile   | 7220.8                                 | 4.4000000000000004 | 244.6                                      | 1.8                | 506.2           | 1.8   | 
| 1394055928  | 6th Decile   | 10346.299999999999                     | 6.3                | 340.5                                      | 2.4                | 367.4           | 1.3   | 
| 1394055928  | 7th Decile   | 13983.3                                | 8.5                | 376.3                                      | 2.7                | 225.9           | 0.8   | 
| 1394055928  | 8th Decile   | 18542.3                                | 11.2               | 529.70000000000005                         | 3.8                | 493             | 1.7   | 
| 1394055928  | 9th Decile   | 26864.7                                | 16.2               | 698.1                                      | 5                  | 747.4           | 2.6   | 
| 1394055928  | 10th Decile  | 79252.399999999994                     | 48                 | 10137.5                                    | 72.599999999999994 | 28920.5         | 100.1 | 
```