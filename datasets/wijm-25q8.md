# SFY 14 Medicaid Expenditures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfy-14-medicaid-expenditures) |
| Metadata | [Link](https://data.ct.gov/api/views/wijm-25q8) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/wijm-25q8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/wijm-25q8/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | wijm-25q8 |
| Name | SFY 14 Medicaid Expenditures |
| Attribution | CT Dept of Social Services |
| Category | Health and Human Services |
| Tags | medicaid expenditures |
| Created | 2014-12-19T19:49:13Z |
| Publication Date | 2014-12-23T14:52:30Z |

## Description

CT Medicaid Expenditures

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                           | Data Type | Render Type |
| ======== | ============== | ======================== | ============================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | provider_code            | PROVIDER CODE                  | text      | text        |
| Yes      | numeric metric | july2013                 | July2013                       | money     | money       |
| Yes      | numeric metric | august2013               | August2013                     | money     | money       |
| Yes      | numeric metric | september2013            | September2013                  | money     | money       |
| Yes      | numeric metric | october2013              | October2013                    | money     | money       |
| Yes      | numeric metric | november2013             | November2013                   | money     | money       |
| Yes      | numeric metric | december2013             | December2013                   | money     | money       |
| Yes      | numeric metric | january2014              | January2014                    | money     | money       |
| Yes      | numeric metric | february2014             | February2014                   | money     | money       |
| Yes      | numeric metric | march2014                | March2014                      | money     | money       |
| Yes      | numeric metric | april2014                | April2014                      | money     | money       |
| Yes      | numeric metric | may2014                  | May2014                        | money     | money       |
| Yes      | numeric metric | june2014                 | June2014                       | money     | money       |
| Yes      | numeric metric | ytd_totalmedicalvariance | YTD TOTAL MEDICAL EXPENDITURES | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wijm-25q8 d:2014-12-23T06:48:37.000Z t:provider_code="Hospital  Inpatient" m:april2014=47420389.56 m:november2013=52125335.25 m:august2013=72902128.57 m:december2013=51619875.9 m:october2013=57915643.29 m:january2014=67607902.76 m:february2014=61480947.92 m:ytd_totalmedicalvariance=756302763.59 m:july2013=57470111.55 m:may2014=102086259.02 m:march2014=64631771.87 m:september2013=59323391.04 m:june2014=61719006.86

series e:wijm-25q8 d:2014-12-23T06:48:37.000Z t:provider_code="Hospital  Outpatient" m:april2014=56322246.85 m:november2013=55736248.13 m:august2013=65790431.45 m:december2013=48216845.78 m:october2013=53481197.93 m:january2014=61669708.83 m:february2014=57025688.34 m:ytd_totalmedicalvariance=670367492.37 m:july2013=52626114.27 m:may2014=67873372.75 m:march2014=58303449.33 m:september2013=61595174.66 m:june2014=31727014.05

series e:wijm-25q8 d:2014-12-23T06:48:37.000Z t:provider_code="Hospital Supplemental Payment" m:april2014=0 m:november2013=57460857 m:august2013=0 m:december2013=0 m:october2013=0 m:january2014=0 m:february2014=57460857 m:ytd_totalmedicalvariance=229943427 m:july2013=0 m:may2014=100000 m:march2014=0 m:september2013=57460856 m:june2014=57460857
```

## Meta Commands

```ls
metric m:july2013 p:double l:July2013 t:dataTypeName=money

metric m:august2013 p:double l:August2013 t:dataTypeName=money

metric m:september2013 p:double l:September2013 t:dataTypeName=money

metric m:october2013 p:double l:October2013 t:dataTypeName=money

metric m:november2013 p:double l:November2013 t:dataTypeName=money

metric m:december2013 p:double l:December2013 t:dataTypeName=money

metric m:january2014 p:double l:January2014 t:dataTypeName=money

metric m:february2014 p:double l:February2014 t:dataTypeName=money

metric m:march2014 p:double l:March2014 t:dataTypeName=money

metric m:april2014 p:double l:April2014 t:dataTypeName=money

metric m:may2014 p:double l:May2014 t:dataTypeName=money

metric m:june2014 p:double l:June2014 t:dataTypeName=money

metric m:ytd_totalmedicalvariance p:double l:"YTD TOTAL MEDICAL EXPENDITURES" t:dataTypeName=money

entity e:wijm-25q8 l:"SFY 14 Medicaid Expenditures" t:attribution="CT Dept of Social Services" t:url=https://data.ct.gov/api/views/wijm-25q8

property e:wijm-25q8 t:meta.view v:id=wijm-25q8 v:category="Health and Human Services" v:averageRating=0 v:name="SFY 14 Medicaid Expenditures" v:attribution="CT Dept of Social Services"

property e:wijm-25q8 t:meta.view.license v:name="Public Domain"

property e:wijm-25q8 t:meta.view.owner v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"

property e:wijm-25q8 t:meta.view.tableauthor v:id=ka29-5hhu v:screenName="Marsha Goldberg" v:displayName="Marsha Goldberg"
```

## Top Records

```ls
| :updated_at | provider_code                 | july2013    | august2013  | september2013 | october2013 | november2013 | december2013 | january2014 | february2014 | march2014   | april2014   | may2014      | june2014    | ytd_totalmedicalvariance | 
| =========== | ============================= | =========== | =========== | ============= | =========== | ============ | ============ | =========== | ============ | =========== | =========== | ============ | =========== | ======================== | 
| 1419317317  | Hospital Inpatient            | 57470111.55 | 72902128.57 | 59323391.04   | 57915643.29 | 52125335.25  | 51619875.90  | 67607902.76 | 61480947.92  | 64631771.87 | 47420389.56 | 102086259.02 | 61719006.86 | 756302763.59             | 
| 1419317317  | Hospital Outpatient           | 52626114.27 | 65790431.45 | 61595174.66   | 53481197.93 | 55736248.13  | 48216845.78  | 61669708.83 | 57025688.34  | 58303449.33 | 56322246.85 | 67873372.75  | 31727014.05 | 670367492.37             | 
| 1419317317  | Hospital Supplemental Payment | 0.00        | 0.00        | 57460856.00   | 0.00        | 57460857.00  | 0.00         | 0.00        | 57460857.00  | 0.00        | 0.00        | 100000.00    | 57460857.00 | 229943427.00             | 
| 1419317317  | Hospital Retro                | -371283.00  | -284337.00  | 0.00          | 0.00        | 0.00         | 24628679.04  | 2766114.00  | 0.00         | 0.00        | -529195.00  | 0.00         | 38729315.00 | 64939293.04              | 
| 1419317317  | Physician Services            | 22686919.02 | 29176741.83 | 22287111.68   | 26245249.37 | 30309228.57  | 22777084.47  | 26972593.91 | 26634212.95  | 27846793.41 | 27120978.10 | 36207761.69  | 27244931.47 | 325509606.47             | 
| 1419317317  | Physician ACA Services        | 2367862.95  | 4293454.76  | 23545788.86   | 5001167.15  | 6021248.48   | 6257667.58   | 5442271.89  | 5217732.54   | 5068132.47  | 6881627.22  | 6731583.55   | 5336712.48  | 82165249.93              | 
| 1419317317  | Clinic Services               | 22808042.07 | 28224855.78 | 23334169.21   | 24503634.25 | 15999232.53  | 23802595.93  | 26305678.90 | 24121548.61  | 37735554.41 | 11903499.89 | 34517853.02  | 26804917.34 | 300061581.94             | 
| 1419317317  | Dental Services               | 13370663.61 | 18207658.52 | 13828816.17   | 15194416.61 | 18943664.50  | 14406112.72  | 15403684.99 | 14542507.95  | 15952601.49 | 15956506.77 | 21246329.25  | 16453214.35 | 193506176.93             | 
| 1419317317  | Vision Care Services          | 2007515.91  | 2762697.82  | 2391096.87    | 2427670.45  | 3052006.91   | 2204378.72   | 2290626.86  | 2259027.73   | 2677036.99  | 2652700.70  | 3559133.34   | 2543431.14  | 30827323.44              | 
| 1419317317  | Other Practitioner            | 4454107.97  | 5279634.43  | 4367530.58    | 3040984.81  | 5712403.95   | 4944377.06   | 3562470.32  | 4811405.21   | 4705926.88  | 4734883.31  | 4855963.35   | 4414477.88  | 54884165.75              | 
```