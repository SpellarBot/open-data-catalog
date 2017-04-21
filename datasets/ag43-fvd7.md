# Procurement - Intent to Execute

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-intent-to-execute) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ag43-fvd7) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ag43-fvd7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ag43-fvd7/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ag43-fvd7 |
| Name | Procurement - Intent to Execute |
| Attribution | Office of the Chief Procurement Officer |
| Category | Finance & Administration |
| Tags | procurement, purchase, contract, bid, rfp, rfi, award |
| Created | 2016-05-31T18:22:54Z |
| Publication Date | 2017-04-10T20:32:11Z |

## Description

This dataset provides the list of vendors and contracts to be executed by the Office of the Chief Procurement Officer and is updated 3 days before award.

M/W/DBE Participation Types
MBE = Minority Business Enterprise
WBE = Women Business Enterprise
DBE = Disadvantaged Business Enterprise
Native American (4)
African American (5)
Female (7)
Asian (8)
Hispanic (9)

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | time           | posting_date              | Posting Date              | calendar_date | calendar_date |
| Yes      | series tag     | contract_number           | Contract Number           | text          | text          |
| Yes      | series tag     | department                | Department                | text          | text          |
| Yes      | series tag     | description               | Description               | text          | text          |
| Yes      | numeric metric | contract_amount           | Contract Amount           | money         | money         |
| Yes      | series tag     | recommended_vendor        | Recommended Vendor        | text          | text          |
| Yes      | series tag     | mbe_wbe_dbe_participation | MBE/WBE/DBE Participation | text          | text          |
| Yes      | series tag     | mbe_wbe_dbe_type          | MBE/WBE/DBE type          | text          | text          |
| Yes      | numeric metric | direct_participation      | Direct Participation      | percent       | percent       |
| Yes      | numeric metric | indirect_participation    | Indirect Participation    | percent       | percent       |
```

## Time Field

```ls
Value = posting_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ag43-fvd7 d:2017-04-10T00:00:00.000Z t:description="Medical Grade Gases" t:department="Medical Examiner - 259" t:recommended_vendor="Chicago United Industries, Ltd." t:contract_number=1635-15845 t:mbe_wbe_dbe_participation=N/A t:mbe_wbe_dbe_type=0% m:contract_amount=63235

series e:ag43-fvd7 d:2017-04-07T00:00:00.000Z t:description="Illinois Civil Law Citation Tickets" t:department="Circuit Clerk of the Court" t:recommended_vendor="Cherokee Printing" t:contract_number=1726-16195 t:mbe_wbe_dbe_participation=N/A t:mbe_wbe_dbe_type="No Goal Set - Contract < $25,000" m:contract_amount=15081

series e:ag43-fvd7 d:2017-03-31T00:00:00.000Z t:description=Uniforms t:department="Clerk of the Crct Crt Off.of Clerk - 335" t:recommended_vendor="Uniforms Manufacturing, Inc." t:contract_number=1626-15723 t:mbe_wbe_dbe_participation=N/A t:mbe_wbe_dbe_type="No Goal Set - Contract < $25,000" m:contract_amount=4996
```

## Meta Commands

```ls
metric m:contract_amount p:double l:"Contract Amount" t:dataTypeName=money

metric m:direct_participation p:integer l:"Direct Participation" t:dataTypeName=percent

metric m:indirect_participation p:double l:"Indirect Participation" t:dataTypeName=percent

entity e:ag43-fvd7 l:"Procurement - Intent to Execute" t:attribution="Office of the Chief Procurement Officer" t:url=https://datacatalog.cookcountyil.gov/api/views/ag43-fvd7

property e:ag43-fvd7 t:meta.view v:id=ag43-fvd7 v:category="Finance & Administration" v:attributionLink=http://www.cookcountyil.gov/procurement v:averageRating=0 v:name="Procurement - Intent to Execute" v:attribution="Office of the Chief Procurement Officer"

property e:ag43-fvd7 t:meta.view.license v:name="Public Domain"

property e:ag43-fvd7 t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:ag43-fvd7 t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| posting_date        | contract_number | department                               | description                                   | contract_amount | recommended_vendor                  | mbe_wbe_dbe_participation | mbe_wbe_dbe_type                 | direct_participation | indirect_participation | 
| =================== | =============== | ======================================== | ============================================= | =============== | =================================== | ========================= | ================================ | ==================== | ====================== | 
| 2017-04-10T00:00:00 | 1635-15845      | Medical Examiner - 259                   | Medical Grade Gases                           | 63235.00        | Chicago United Industries, Ltd.     | N/A                       | 0%                               |                      |                        | 
| 2017-04-07T00:00:00 | 1726-16195      | Circuit Clerk of the Court               | Illinois Civil Law Citation Tickets           | 15081.00        | Cherokee Printing                   | N/A                       | No Goal Set - Contract < $25,000 |                      |                        | 
| 2017-03-31T00:00:00 | 1626-15723      | Clerk of the Crct Crt Off.of Clerk - 335 | Uniforms                                      | 4996.00         | Uniforms Manufacturing, Inc.        | N/A                       | No Goal Set - Contract < $25,000 |                      |                        | 
| 2017-03-22T00:00:00 | 1611-15825      | Office of the Sheriff - 210              | Aftermarket Vehicle Equipment                 | 20813.14        | Chicago Parts and Sounds, LLC       | N/A                       | 0%                               |                      |                        | 
| 2017-02-24T00:00:00 | 1626-15833      | Office of the Sheriff - 210              | Portable Restrooms                            | 18842.00        | Comforts of Home Services, Inc.     | N/A                       | No Goal Set - Contract < $25,000 |                      |                        | 
| 2017-02-24T00:00:00 | 1626-15850      | Dept. of Facilities/Mgmt - 200           | Acorn Mirrors                                 | 2687.50         | Cornestone Detention Products, Inc. | N/A                       | No Goal Set - Contract < $25,000 |                      |                        | 
| 2017-02-24T00:00:00 | 1623-15542      | Depart. Of Environmental Ctrl - 161      | Phase I and II Environmental Site Assessments | 53257.00        | Terracon Consultants, Inc.          | N/A                       | 0%                               |                      |                        | 
| 2017-02-24T00:00:00 | 1626-15680      | Clerk of the Crct Crt Off.of Clerk - 335 | Fileprint 470 Toner                           | 5500.00         | Atlas & Associates, Inc.            | N/A                       | No Goal Set - Contract < $25,000 |                      |                        | 
| 2017-02-21T00:00:00 | 1726-16123      | Dept. of Human Rights and Ethics - 002   | Breakfast Catering Services                   | 4085.00         | Twomaytoz, Inc.                     |                           | No Goal Set - Contract < $25,000 |                      |                        | 
| 2017-02-16T00:00:00 | 1614-15742      | Juvenile Temporary Detent. Ctr - 440     | Resident Gym Shoes                            | 75810.60        | Victory Supply, Inc.                |                           | N/A                              |                      |                        | 
```