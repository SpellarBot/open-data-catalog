# 2013 Maryland HOPE Counseling Network Grant Awards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2013-maryland-hope-counseling-network-grant-awards) |
| Metadata | [Link](https://data.maryland.gov/api/views/xmse-9b3g) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/xmse-9b3g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/xmse-9b3g/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | xmse-9b3g |
| Name | 2013 Maryland HOPE Counseling Network Grant Awards |
| Attribution | Department of Housing and Community Development |
| Category | Housing |
| Tags | housing, dhcd, foreclosure, prevention, counseling |
| Created | 2013-10-01T14:02:10Z |
| Publication Date | 2013-10-01T14:05:53Z |

## Description

On February 14, 2013 members of the Maryland HOPE Counseling Network were awarded $11.8 million in grant awards, the highest level of funding for foreclosure prevention counseling in state history. The period covered by these awards is fiscal years 2013-2015. The Network is a group of 39 statewide nonprofit agencies that provide foreclosure prevention assistance. The Department of Housing and Community Development (DHCD) provides financial support and training to these agencies. These counselors are the critical link in assisting individuals facing foreclosures, acting as a resource to negotiate reasonable terms with mortgage servicers, and advising citizens on the best actions to take to save their homes. The funds, made available through the Office of Attorney General Douglas Gansler and the Maryland Housing Counseling Fund, are part of Maryland?s award from the National Mortgage Loan Servicing Practices Settlement and are being administered by DHCD.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| Yes      | series tag     | counseling_agency | Counseling Agency | text      | text        |
| Yes      | numeric metric | award             | Award             | money     | money       |
| Yes      | series tag     | phone             | Phone             | text      | text        |
| Yes      | series tag     | region            | Region            | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xmse-9b3g d:2013-01-01T00:00:00.000Z t:region="Baltimore Metro" t:phone=410-342-3234 t:counseling_agency="Southeast Community Development" m:award=320000

series e:xmse-9b3g d:2013-01-01T00:00:00.000Z t:region="Baltimore Metro" t:phone=410-679-3200 t:counseling_agency="Home Partnership, Inc." m:award=130900

series e:xmse-9b3g d:2013-01-01T00:00:00.000Z t:region="Washington, D.C. Metro" t:phone=301-322-5700 t:counseling_agency="United Communities Against Poverty" m:award=320000
```

## Meta Commands

```ls
metric m:award p:integer l:Award t:dataTypeName=money

entity e:xmse-9b3g l:"2013 Maryland HOPE Counseling Network Grant Awards" t:attribution="Department of Housing and Community Development" t:url=https://data.maryland.gov/api/views/xmse-9b3g

property e:xmse-9b3g t:meta.view v:id=xmse-9b3g v:category=Housing v:attributionLink=http://www.dhcd.maryland.gov v:averageRating=0 v:name="2013 Maryland HOPE Counseling Network Grant Awards" v:attribution="Department of Housing and Community Development"

property e:xmse-9b3g t:meta.view.license v:name="Public Domain"

property e:xmse-9b3g t:meta.view.owner v:id=3dic-mdyq v:profileImageUrlMedium=/api/users/3dic-mdyq/profile_images/THUMB v:profileImageUrlLarge=/api/users/3dic-mdyq/profile_images/LARGE v:screenName=TDavis v:profileImageUrlSmall=/api/users/3dic-mdyq/profile_images/TINY v:displayName=TDavis

property e:xmse-9b3g t:meta.view.tableauthor v:id=3dic-mdyq v:profileImageUrlMedium=/api/users/3dic-mdyq/profile_images/THUMB v:profileImageUrlLarge=/api/users/3dic-mdyq/profile_images/LARGE v:screenName=TDavis v:profileImageUrlSmall=/api/users/3dic-mdyq/profile_images/TINY v:roleName=editor v:displayName=TDavis
```

## Top Records

```ls
| counseling_agency                                      | award  | phone           | region                 | 
| ====================================================== | ====== | =============== | ====================== | 
| Southeast Community Development                        | 320000 | 410-342-3234    | Baltimore Metro        | 
| Home Partnership, Inc.                                 | 130900 | 410-679-3200    | Baltimore Metro        | 
| United Communities Against Poverty                     | 320000 | 301-322-5700    | Washington, D.C. Metro | 
| Centro de Apoyo Familiar                               | 250000 | 301-328-3292    | Washington, D.C. Metro | 
| Allegany County Human Resources Development Commission | 153550 | 301-777-5970    | Western Maryland       | 
| Housing Options& Planning Enterprises                  | 250000 | 301-567-3330    | Washington, D.C. Metro | 
| Neighborhood Housing Services (NHS) of Baltimore       | 550000 | 410-327-1200    | Baltimore Metro        | 
| Asian American Homeownership Counseling , Inc          | 129020 | 301-760-7636    | Washington, D.C. Metro | 
| Consumer Credit Counseling Services of MD & Delaware   | 600000 | 410-869-8828    | Statewide Agency       | 
| Delmarva Community Services, Inc                       | 185000 | 410-221-1920    | Eastern Shore          | 
```