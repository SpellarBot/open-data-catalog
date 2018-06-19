# Sample 2016 Iowa Individual Affordable Care Act-Compliant Premiums

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sample-2016-iowa-individual-affordable-care-act-compliant-premiums) |
| Metadata | [Link](https://data.iowa.gov/api/views/mbex-fess) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/mbex-fess/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/mbex-fess/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | mbex-fess |
| Name | Sample 2016 Iowa Individual Affordable Care Act-Compliant Premiums |
| Category | Health |
| Tags | aca, obamacare, premium, affordable care act, health insurance, exchange, marketplace, cms, centers for medicare and medicaid services, healthcare.gov |
| Created | 2015-09-17T19:14:45Z |
| Publication Date | 2016-04-20T13:38:55Z |

## Description

Sample premium information for individual ACA-compliant health insurance plans available to Iowans for 2016.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | insurance_company   | Insurance Company   | text      | text        |
| Yes      | series tag     | plan_name           | Plan Name           | text      | text        |
| Yes      | numeric metric | age                 | Age                 | number    | number      |
| Yes      | series tag     | metal_level         | Metal Level         | text      | text        |
| Yes      | series tag     | rating_area         | Rating Area         | text      | text        |
| Yes      | numeric metric | non_tobacco_premium | Non-Tobacco Premium | number    | number      |
| Yes      | numeric metric | tobacco_premium     | Tobacco Premium     | number    | number      |
| Yes      | series tag     | marketplace_use     | Marketplace         | text      | text        |
| Yes      | series tag     | plan_id             | Plan ID             | text      | text        |
| Yes      | series tag     | counties            | Counties            | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mbex-fess d:2016-01-01T00:00:00.000Z t:marketplace_use=Off t:insurance_company="Celtic Insurance Company" t:metal_level=Bronze t:counties="Dallas, Jasper, Madison, Marion, Polk, Warren" t:rating_area="Rating Area 2" t:plan_id=87194IA0070001 t:plan_name=Bronze m:tobacco_premium=425.52 m:age=39 m:non_tobacco_premium=327.33

series e:mbex-fess d:2016-01-01T00:00:00.000Z t:marketplace_use=Off t:insurance_company="Celtic Insurance Company" t:metal_level=Bronze t:counties="Dallas, Jasper, Madison, Marion, Polk, Warren" t:rating_area="Rating Area 2" t:plan_id=87194IA0070001 t:plan_name=Bronze m:tobacco_premium=430.92 m:age=40 m:non_tobacco_premium=331.48

series e:mbex-fess d:2016-01-01T00:00:00.000Z t:marketplace_use=Off t:insurance_company="Celtic Insurance Company" t:metal_level=Bronze t:counties="Dallas, Jasper, Madison, Marion, Polk, Warren" t:rating_area="Rating Area 2" t:plan_id=87194IA0070001 t:plan_name=Bronze m:tobacco_premium=439.01 m:age=41 m:non_tobacco_premium=337.7
```

## Meta Commands

```ls
metric m:age p:integer l:Age d:"""20"" means ages 0-20; ""65"" means ages 65 and older; the others mean that specific age." t:dataTypeName=number

metric m:non_tobacco_premium p:float l:"Non-Tobacco Premium" t:dataTypeName=number

metric m:tobacco_premium p:float l:"Tobacco Premium" t:dataTypeName=number

entity e:mbex-fess l:"Sample 2016 Iowa Individual Affordable Care Act-Compliant Premiums" t:url=https://data.iowa.gov/api/views/mbex-fess

property e:mbex-fess t:meta.view v:id=mbex-fess v:category=Health v:averageRating=0 v:name="Sample 2016 Iowa Individual Affordable Care Act-Compliant Premiums"

property e:mbex-fess t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:mbex-fess t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| insurance_company        | plan_name | age | metal_level | rating_area   | non_tobacco_premium | tobacco_premium | marketplace_use | plan_id        | counties                                      | 
| ======================== | ========= | === | =========== | ============= | =================== | =============== | =============== | ============== | ============================================= | 
| Celtic Insurance Company | Bronze    | 39  | Bronze      | Rating Area 2 | 327.33              | 425.52          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 40  | Bronze      | Rating Area 2 | 331.48              | 430.92          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 41  | Bronze      | Rating Area 2 | 337.70              | 439.01          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 42  | Bronze      | Rating Area 2 | 343.67              | 446.77          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 43  | Bronze      | Rating Area 2 | 351.97              | 457.56          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 44  | Bronze      | Rating Area 2 | 362.34              | 471.04          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 45  | Bronze      | Rating Area 2 | 374.53              | 486.89          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 46  | Bronze      | Rating Area 2 | 389.06              | 505.77          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 47  | Bronze      | Rating Area 2 | 405.40              | 527.01          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
| Celtic Insurance Company | Bronze    | 48  | Bronze      | Rating Area 2 | 424.07              | 551.29          | Off             | 87194IA0070001 | Dallas, Jasper, Madison, Marion, Polk, Warren | 
```