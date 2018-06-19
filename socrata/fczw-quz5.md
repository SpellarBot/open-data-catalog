# Sample 2017 Iowa Individual Affordable Care Act-Compliant Premiums

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sample-2017-iowa-individual-affordable-care-act-compliant-premiums) |
| Metadata | [Link](https://data.iowa.gov/api/views/fczw-quz5) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/fczw-quz5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/fczw-quz5/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | fczw-quz5 |
| Name | Sample 2017 Iowa Individual Affordable Care Act-Compliant Premiums |
| Attribution | Iowa Insurance Division, Iowa Department of Commerce |
| Category | Health |
| Tags | aca, obamacare, premium, affordable care act, health insurance, exchange, marketplace, cms, centers for medicare and medicaid services, healthcare.gov |
| Created | 2016-09-19T20:13:22Z |
| Publication Date | 2016-10-05T14:41:41Z |

## Description

Sample premium information for individual ACA-compliant health insurance plans available to Iowans for 2017 based on age, rating area and metal level.  These are premiums for individuals, not families..

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | plan_id             | Plan ID             | text      | text        |
| Yes      | series tag     | insurance_company   | Insurance Company   | text      | text        |
| Yes      | series tag     | plan_name           | Plan Name           | text      | text        |
| Yes      | series tag     | rating_area         | Rating Area         | text      | text        |
| Yes      | numeric metric | age                 | Age                 | number    | number      |
| Yes      | series tag     | metal_level         | Metal Level         | text      | text        |
| Yes      | series tag     | market_place        | Market Place        | text      | text        |
| Yes      | numeric metric | non_tobacco_premium | Non-Tobacco Premium | money     | money       |
| Yes      | numeric metric | tobacco_premium     | Tobacco Premium     | money     | money       |
| Yes      | series tag     | counties            | Counties            | text      | text        |
```

## Time Field

```ls
Value = 2017
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fczw-quz5 d:2017-01-01T00:00:00.000Z t:insurance_company="Freedom Life Ins. Co." t:metal_level=Bronze t:counties="Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster" t:rating_area="Rating Area 1" t:market_place=Off t:plan_name="Essential Health Bronze" t:plan_id=18492IA0200001 m:tobacco_premium=237.12 m:age=20 m:non_tobacco_premium=197.6

series e:fczw-quz5 d:2017-01-01T00:00:00.000Z t:insurance_company="Freedom Life Ins. Co." t:metal_level=Bronze t:counties="Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster" t:rating_area="Rating Area 1" t:market_place=Off t:plan_name="Essential Health Bronze" t:plan_id=18492IA0200001 m:tobacco_premium=373.6 m:age=21 m:non_tobacco_premium=311.33

series e:fczw-quz5 d:2017-01-01T00:00:00.000Z t:insurance_company="Freedom Life Ins. Co." t:metal_level=Bronze t:counties="Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster" t:rating_area="Rating Area 1" t:market_place=Off t:plan_name="Essential Health Bronze" t:plan_id=18492IA0200001 m:tobacco_premium=373.6 m:age=22 m:non_tobacco_premium=311.33
```

## Meta Commands

```ls
metric m:age p:integer l:Age d:"The age of the individual for which the premium applies. ""20"" means ages 0-20; ""65"" means ages 65 and older; the others mean the specific age listed." t:dataTypeName=number

metric m:non_tobacco_premium p:double l:"Non-Tobacco Premium" t:dataTypeName=money

metric m:tobacco_premium p:double l:"Tobacco Premium" t:dataTypeName=money

entity e:fczw-quz5 l:"Sample 2017 Iowa Individual Affordable Care Act-Compliant Premiums" t:attribution="Iowa Insurance Division, Iowa Department of Commerce" t:url=https://data.iowa.gov/api/views/fczw-quz5

property e:fczw-quz5 t:meta.view v:id=fczw-quz5 v:category=Health v:averageRating=0 v:name="Sample 2017 Iowa Individual Affordable Care Act-Compliant Premiums" v:attribution="Iowa Insurance Division, Iowa Department of Commerce"

property e:fczw-quz5 t:meta.view.license v:name="Public Domain"

property e:fczw-quz5 t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:fczw-quz5 t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| plan_id        | insurance_company     | plan_name               | rating_area   | age | metal_level | market_place | non_tobacco_premium | tobacco_premium | counties                                                                                             | 
| ============== | ===================== | ======================= | ============= | === | =========== | ============ | =================== | =============== | ==================================================================================================== | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 20  | Bronze      | Off          | 197.6               | 237.12          | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 21  | Bronze      | Off          | 311.33              | 373.6           | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 22  | Bronze      | Off          | 311.33              | 373.6           | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 23  | Bronze      | Off          | 311.33              | 373.6           | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 24  | Bronze      | Off          | 311.33              | 373.6           | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 25  | Bronze      | Off          | 312.42              | 374.91          | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 26  | Bronze      | Off          | 318.65              | 382.37          | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 27  | Bronze      | Off          | 326.11              | 391.34          | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 28  | Bronze      | Off          | 338.25              | 405.9           | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
| 18492IA0200001 | Freedom Life Ins. Co. | Essential Health Bronze | Rating Area 1 | 29  | Bronze      | Off          | 348.21              | 417.85          | Boone, Calhoun, Carroll, Greene, Grundy, Hamilton, Hardin, Marshall, Poweshiek, Story, Tama, Webster | 
```