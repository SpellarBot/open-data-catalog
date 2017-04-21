# Building and Safety Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/building-and-safety-inspections-f6000) |
| Metadata | [Link](https://data.lacity.org/api/views/9w5z-rg2h) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/9w5z-rg2h/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/9w5z-rg2h/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | 9w5z-rg2h |
| Name | Building and Safety Inspections |
| Attribution | LADBS |
| Category | A Safe City |
| Tags | ladbs, department of building and safety, building and safety, building, safety, construction services, construction, permit, permit number, inspection, permit status, inspection type, inspection ... |
| Created | 2014-04-21T17:28:46Z |
| Publication Date | 2017-01-04T01:36:59Z |

## Description

All permitted construction work are subject to inspection by authorized Building and Safety inspectors. The permit applicant notifies Building and Safety when the work is ready for inspection. Common items inspected include foundation excavations, concrete work, wood framing, ventilation equipment, plumbing, electrical, and so forth. Upon completion, there will be a final inspection and approval of the completed project.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| No       |             | address           | ADDRESS           | text          | text          |
| Yes      | series tag  | permit            | PERMIT            | text          | text          |
| Yes      | series tag  | permit_status     | Permit Status     | text          | text          |
| Yes      | time        | inspection_date   | Inspection Date   | calendar_date | calendar_date |
| Yes      | series tag  | inspection        | Inspection Type   | text          | text          |
| Yes      | series tag  | inspection_result | Inspection Result | text          | text          |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:9w5z-rg2h d:2013-06-18T00:00:00.000Z t:inspection_result=Approved t:permit_status=Issued t:permit=13020-10000-00260 t:inspection="Deputy Reinf. Concrete" m:row_number.9w5z-rg2h=1

series e:9w5z-rg2h d:2013-10-08T00:00:00.000Z t:inspection_result="Conditional Approval" t:permit_status=Issued t:permit=12010-10000-02776 t:inspection="Deputy Shotcrete" m:row_number.9w5z-rg2h=2

series e:9w5z-rg2h d:2013-09-16T00:00:00.000Z t:inspection_result="Conditional Approval" t:permit_status=Issued t:permit=12010-10000-02776 t:inspection="Deputy Reinf. Concrete" m:row_number.9w5z-rg2h=3
```

## Meta Commands

```ls
metric m:row_number.9w5z-rg2h p:long l:"Row Number"

entity e:9w5z-rg2h l:"Building and Safety Inspections" t:attribution=LADBS t:url=https://data.lacity.org/api/views/9w5z-rg2h

property e:9w5z-rg2h t:meta.view v:id=9w5z-rg2h v:category="A Safe City" v:averageRating=0 v:name="Building and Safety Inspections" v:attribution=LADBS

property e:9w5z-rg2h t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:9w5z-rg2h t:meta.view.owner v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:displayName="Building and Safety OpenData"

property e:9w5z-rg2h t:meta.view.tableauthor v:id=tdwf-cih6 v:profileImageUrlMedium=/api/users/tdwf-cih6/profile_images/THUMB v:profileImageUrlLarge=/api/users/tdwf-cih6/profile_images/LARGE v:screenName="Building and Safety OpenData" v:profileImageUrlSmall=/api/users/tdwf-cih6/profile_images/TINY v:roleName=publisher v:displayName="Building and Safety OpenData"
```

## Top Records

```ls
| address    | permit            | permit_status | inspection_date     | inspection                     | inspection_result    | 
| ========== | ================= | ============= | =================== | ============================== | ==================== | 
| 1 S LMU DR | 13020-10000-00260 | Issued        | 2013-06-18T00:00:00 | Deputy Reinf. Concrete         | Approved             | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-10-08T00:00:00 | Deputy Shotcrete               | Conditional Approval | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-09-16T00:00:00 | Deputy Reinf. Concrete         | Conditional Approval | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-09-17T00:00:00 | Deputy Reinf. Concrete         | Conditional Approval | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-09-18T00:00:00 | Deputy Reinf. Concrete         | Conditional Approval | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-09-19T00:00:00 | Deputy Reinf. Concrete         | Conditional Approval | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-09-20T00:00:00 | Deputy Reinf. Concrete         | Conditional Approval | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-10-17T00:00:00 | Deputy Shotcrete               | Conditional Approval | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-10-24T00:00:00 | Excavation/Setback/Form/Re-Bar | Partial Approval     | 
| 1 S LMU DR | 12010-10000-02776 | Issued        | 2013-10-25T00:00:00 | Excavation/Setback/Form/Re-Bar | Partial Approval     | 
```