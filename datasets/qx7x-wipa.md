# Hospice CASPER/ASPEN Contacts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospice-casper-aspen-contacts) |
| Metadata | [Link](https://data.medicare.gov/api/views/qx7x-wipa) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/qx7x-wipa/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/qx7x-wipa/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | qx7x-wipa |
| Name | Hospice CASPER/ASPEN Contacts |
| Category | Hospice Data Directory |
| Tags | hospice care, hospice, care |
| Created | 2016-06-13T23:26:03Z |
| Publication Date | 2016-10-19T11:28:05Z |

## Description

A list of Regional Office (RO) and State coordinators.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | region      | Region     | text      | html        |
| Yes      | series tag  | state       | State      | text      | text        |
| Yes      | series tag  | name        | Contact    | text      | text        |
| Yes      | series tag  | email       | Email      | email     | email       |
| Yes      | series tag  | phone       | Phone      | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qx7x-wipa d:2016-10-03T17:55:09.000Z t:region=Boston t:phone_number=860-509-7400 t:email=Loan.nguyen@ct.gov t:name="Loan Nguyen" t:state=Connecticut m:row_number.qx7x-wipa=1

series e:qx7x-wipa d:2016-10-03T17:55:09.000Z t:region=Boston t:phone_number=207-287-4462 t:email=William.montejo@maine.gov t:name="William Montejo" t:state=Maine m:row_number.qx7x-wipa=2

series e:qx7x-wipa d:2016-10-03T17:55:09.000Z t:region=Boston t:phone_number=617-753-8222 t:email=paul.dinatale@state.ma.us t:name="Paul DiNatale" t:state=Massachusetts m:row_number.qx7x-wipa=3
```

## Meta Commands

```ls
metric m:row_number.qx7x-wipa p:long l:"Row Number"

entity e:qx7x-wipa l:"Hospice CASPER/ASPEN Contacts" t:url=https://data.medicare.gov/api/views/qx7x-wipa

property e:qx7x-wipa t:meta.view v:id=qx7x-wipa v:category="Hospice Data Directory" v:averageRating=0 v:name="Hospice CASPER/ASPEN Contacts"

property e:qx7x-wipa t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:qx7x-wipa t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:qx7x-wipa t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| :updated_at | region   | state         | name                    | email                        | phone                               | 
| =========== | ======== | ============= | ======================= | ============================ | =================================== | 
| 1475517309  | Boston   | Connecticut   | Loan Nguyen             | Loan.nguyen@ct.gov           | [860-509-7400, null]                | 
| 1475517309  | Boston   | Maine         | William Montejo         | William.montejo@maine.gov    | [207-287-4462, null]                | 
| 1475517309  | Boston   | Massachusetts | Paul DiNatale           | paul.dinatale@state.ma.us    | [617-753-8222, null]                | 
| 1475517309  | Boston   | New Hampshire | Darlene Laro            | Darlene.laro@dhhs.nh.gov     | [603-271-9059, null]                | 
| 1475517309  | Boston   | Rhode Island  | Adele Renzulli          | adele.renzulli@health.ri.gov | [401-222-4536, null]                | 
| 1475517309  | Boston   | Vermont       | Susan Emmons            | susan.emmons@vermont.gov     | [802-793-0997, null]                | 
| 1475517309  | New York | New Jersey    | Janet Diaz              | Janet.diaz@doh.nj.gov        | [609-292-5636, null]                | 
| 1475517309  | New York | New York      | Curtis Rogers           | curtis.rogers@health.ny.gov  | [518-402-0926, null]                | 
| 1475517309  | New York | Puerto Rico   | Carmen M. Rivera-Rosado | carivera@salud.gov.pr        | [787-782-0120, ext 4727/4728, null] | 
| 1475517309  | Texas    | Oklahoma      | Rachael Battles         | rachelMB@health.ok.gov       | [405-271-9444, null]                | 
```