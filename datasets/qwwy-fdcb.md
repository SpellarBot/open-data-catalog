# List of Pre-Qualified Architects, Engineers and Contractors for Swimming Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/list-of-pre-qualified-architects-engineers-and-contractors-for-swimming-facilities-10f9c) |
| Metadata | [Link](https://data.illinois.gov/api/views/qwwy-fdcb) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/qwwy-fdcb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/qwwy-fdcb/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | qwwy-fdcb |
| Name | List of Pre-Qualified Architects, Engineers and Contractors for Swimming Facilities |
| Attribution | Swimming Facilities Program |
| Category | Public Health |
| Tags | pre-qualified, engineers, architects, contractors |
| Created | 2014-01-29T17:52:50Z |
| Publication Date | 2017-03-21T14:38:03Z |

## Description

Last Updated March 2017.
This list contains those individuals and companies that are deemed to be pre-qualified for the design and construction of swimming facilities in Illinois.  Renewal of this certification is required annually.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | company_name         | Company Name         | text      | text        |
| Yes      | series tag  | profession           | Profession           | text      | text        |
| Yes      | series tag  | first_name           | First Name           | text      | text        |
| Yes      | series tag  | last_name            | Last Name            | text      | text        |
| Yes      | series tag  | middle_initial       | Middle Initial       | text      | text        |
| No       |             | company_address      | Company Address      | text      | text        |
| Yes      | series tag  | city                 | City                 | text      | text        |
| Yes      | series tag  | state                | State                | text      | text        |
| Yes      | series tag  | zip_code             | ZIP Code             | text      | number      |
| Yes      | series tag  | phone                | Phone                | phone     | phone       |
| Yes      | series tag  | email                | Email                | email     | email       |
| Yes      | series tag  | qualification_status | Qualification Status | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = company_address
```

## Data Commands

```ls
series e:qwwy-fdcb d:2017-01-19T19:23:52.000Z t:first_name=Christopher t:phone_number=847-277-9840 t:zip_code=60078 t:company_name="Aqua-Guard Management, Inc." t:email=chris@aquaguardmanagement.com t:qualification_status=Active t:middle_initial=J t:profession=Contractor t:last_name=Strzalka t:state=IL t:city=Palatine m:row_number.qwwy-fdcb=1

series e:qwwy-fdcb d:2017-01-19T19:23:52.000Z t:first_name=Donald t:phone_number=847-277-9840 t:zip_code=60078 t:company_name="Aqua-Guard Management, Inc." t:email=patrick@aquaguardmanagement.com t:qualification_status=Active t:middle_initial=J t:profession=Contractor t:last_name=Wilke t:state=IL t:city=Palatine m:row_number.qwwy-fdcb=2

series e:qwwy-fdcb d:2017-01-19T19:23:52.000Z t:first_name=Andrew t:phone_number=630-774-4515 t:zip_code=60554 t:company_name="Aquajoy Spa & Pool, Inc." t:email=Aquajoy@aol.com t:qualification_status=Active t:middle_initial=J t:profession=Contractor t:last_name=Limbrick t:state=IL t:city="Sugar Grove" m:row_number.qwwy-fdcb=3
```

## Meta Commands

```ls
metric m:row_number.qwwy-fdcb p:long l:"Row Number"

entity e:qwwy-fdcb l:"List of Pre-Qualified Architects, Engineers and Contractors for Swimming Facilities" t:attribution="Swimming Facilities Program" t:url=https://data.illinois.gov/api/views/qwwy-fdcb

property e:qwwy-fdcb t:meta.view v:id=qwwy-fdcb v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/swimming-facilities v:averageRating=0 v:name="List of Pre-Qualified Architects, Engineers and Contractors for Swimming Facilities" v:attribution="Swimming Facilities Program"

property e:qwwy-fdcb t:meta.view.license v:name="Public Domain"

property e:qwwy-fdcb t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:qwwy-fdcb t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| :updated_at | company_name                | profession | first_name  | last_name  | middle_initial | company_address    | city          | state | zip_code | phone                | email                           | qualification_status | 
| =========== | =========================== | ========== | =========== | ========== | ============== | ================== | ============= | ===== | ======== | ==================== | =============================== | ==================== | 
| 1484853832  | Aqua-Guard Management, Inc. | Contractor | Christopher | Strzalka   | J              | P.O. Box 1325      | Palatine      | IL    | 60078    | [847-277-9840, null] | chris@aquaguardmanagement.com   | Active               | 
| 1484853832  | Aqua-Guard Management, Inc. | Contractor | Donald      | Wilke      | J              | P.O. Box 1325      | Palatine      | IL    | 60078    | [847-277-9840, null] | patrick@aquaguardmanagement.com | Active               | 
| 1484853832  | Aquajoy Spa & Pool, Inc.    | Contractor | Andrew      | Limbrick   | J              | P.O. Box 636       | Sugar Grove   | IL    | 60554    | [630-774-4515, null] | Aquajoy@aol.com                 | Active               | 
| 1484853832  | Barrington Pools, Inc.      | Contractor | Dale        | Overson    |                | P.O. Box 3906      | Barrington    | IL    | 60011    | [847-381-1245, null] | apacey@barrington-pools.com     | Active               | 
| 1484853832  | S & K Pool Services, Inc.   | Contractor | Steve       | Sowa       | J              | P.O. Box 88036     | Carol Stream  | IL    | 60188    | [630-690-3942, null] | ssowa@skpool.com                | Active               | 
| 1484853832  | Spear Corporation, Inc.     | Contractor | Brian       | Spear      | H              | P.O. Box 3906      | Roachdale     | IN    | 46172    | [765-522-1126, null] | bspear@spearcorp.com            | Active               | 
| 1484853832  | K.C. Mechanical Inc.        | Contractor | Kevin       | Cunningham |                | 5 S. 473 Vest Ave. | Naperville    | IL    | 60563    | [630-835-4498, null] | kcmechanicalinc@gmail.com       | Active               | 
| 1484853832  | J.V. Pools & Spas           | Contractor | Jerald      | Kirkwood   | L              | 10801 Porter Lane  | Lawrenceville | IL    | 62439    | [618-943-3404, null] | JVPools@frontier.com            | Initial              | 
| 1484853832  | J.V. Pools & Spas           | Contractor | Tyler       | Kirkwood   | L              | 10801 Porter Lane  | Lawrenceville | IL    | 62439    | [618-943-3404, null] | JVPools@frontier.com            | Initial              | 
| 1484853832  | JnT Pool Service            | Contractor | Thomas      | Girardin   | J              | P.O. Box 7540      | Rockford      | IL    | 61126    | [815-262-4532, null] | service@jntpoolservice.com      | Active               | 
```