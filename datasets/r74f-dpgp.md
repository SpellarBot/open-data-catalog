# Oregon Recovery and Reinvestment Act Data - June, 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oregon-recovery-and-reinvestment-act-data-june-2012-371c3) |
| Metadata | [Link](https://data.oregon.gov/api/views/r74f-dpgp) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/r74f-dpgp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/r74f-dpgp/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | r74f-dpgp |
| Name | Oregon Recovery and Reinvestment Act Data - June, 2012 |
| Category | Revenue & Expense |
| Created | 2012-08-08T20:56:38Z |
| Publication Date | 2012-08-08T21:00:58Z |
| Rows Updated | 2012-08-08T20:56:53Z |

## Description

This spreadsheet contains Oregon Recovery and Reinvestment Act (ARRA) Data reported on the State of Oregon Recovery site (http://oregon.gov/recovery/StimulusReporting/ARRA_Projects.shtml). Please note that this data reflects the preliminary data from the most recent reporting period of the American Recovery and Reinvestment Act of 2009, including data through March 30, 2011. This data available for viewing through an interactive map site. For this, and other information on ARRA projects, please visit Oregon's Economic Recovery site: http://www.oregon.gov/recovery. For the latest recovery award data, please visit http://www.recovery.gov.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | numeric metric | sort_order             | SORT ORDER             | number    | number      |
| Yes      | series tag     | award_description      | AWARD DESCRIPTION      | text      | text        |
| Yes      | series tag     | project_description    | PROJECT DESCRIPTION    | text      | text        |
| Yes      | series tag     | root_id                | ROOT ID                | text      | number      |
| Yes      | series tag     | prime_award            | PRIME AWARD #          | text      | text        |
| Yes      | series tag     | award_id               | AWARD ID               | text      | number      |
| Yes      | series tag     | award_number           | AWARD NUMBER           | text      | text        |
| Yes      | series tag     | project_id             | PROJECT ID             | text      | text        |
| Yes      | series tag     | award_instrument       | AWARD INSTRUMENT       | text      | text        |
| Yes      | series tag     | recipient_type         | RECIPIENT TYPE         | text      | text        |
| Yes      | series tag     | vendor                 | VENDOR                 | text      | text        |
| Yes      | series tag     | county                 | COUNTY                 | text      | text        |
| Yes      | series tag     | project_name           | PROJECT NAME           | text      | text        |
| Yes      | series tag     | award_recipient        | AWARD RECIPIENT        | text      | text        |
| Yes      | numeric metric | award_amount           | AWARD AMOUNT           | number    | number      |
| Yes      | numeric metric | amount_expended        | AMOUNT EXPENDED        | number    | number      |
| Yes      | numeric metric | jobs_created           | JOBS CREATED           | number    | number      |
| Yes      | series tag     | project_status         | PROJECT STATUS         | text      | text        |
| Yes      | series tag     | zipcode                | ZIPCODE                | text      | text        |
| Yes      | series tag     | congressional_district | CONGRESSIONAL DISTRICT | text      | number      |
| Yes      | series tag     | month_code             | MONTH CODE             | text      | text        |
| Yes      | series tag     | project                | Project                | text      | text        |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:r74f-dpgp d:2012-01-01T00:00:00.000Z t:award_number=OR-00J03801 t:project_name="Port of Newport's International Terminal Clean-up - Award ID#:6062" t:project_status=Completed t:vendor=NO t:award_instrument=Q10002 t:root_id=5 t:zipcode=97365-4338 t:recipient_type=SUB t:award_id=6062 t:congressional_district=5 t:project_description="Port of Newport's International Terminal Clean-up - Award ID: 6062" t:project="Port of Newport's International Terminal Clean-up - Award ID#:6062" t:month_code=1106 t:award_description="Brownfields Clean-up" t:county=Lincoln t:prime_award=00J03801 t:award_recipient="Port of Newport" m:amount_expended=200000 m:award_amount=200000 m:jobs_created=0 m:sort_order=2

series e:r74f-dpgp d:2012-01-01T00:00:00.000Z t:award_number=OR-00J03801 t:project_name="Grant Pass River Road Reserve Clean-up Project - Award ID#:9245" t:project_status=Completed t:vendor=NO t:award_instrument=Q10003 t:root_id=5 t:zipcode=97526-2000 t:recipient_type=SUB t:award_id=9245 t:congressional_district=2 t:project_description="Grant Pass River Road Reserve Clean-up Project - Award ID: 9245" t:project="Grant Pass River Road Reserve Clean-up Project - Award ID#:9245" t:month_code=1203 t:award_description="Brownfields Clean-up" t:county=Josephine t:prime_award=00J03801 t:award_recipient="City of Grants Pass" m:amount_expended=220938 m:award_amount=220938 m:jobs_created=0 m:sort_order=5

series e:r74f-dpgp d:2012-01-01T00:00:00.000Z t:award_number=OR-00J03801 t:project_name="Oakridge Industrial Park Clean-up project - Award ID#:9247" t:project_status=Completed t:vendor=NO t:award_instrument=Q10004 t:root_id=5 t:zipcode=97463 t:recipient_type=SUB t:award_id=9247 t:congressional_district=4 t:project_description="Oakridge Industrial Park Clean-up project - Award ID: 9247" t:project="Oakridge Industrial Park Clean-up project - Award ID#:9247" t:month_code=1112 t:award_description="Brownfields Clean-up" t:county=Lane t:prime_award=00J03801 t:award_recipient="City of Oakridge" m:amount_expended=160000 m:award_amount=160000 m:jobs_created=0 m:sort_order=9
```

## Meta Commands

```ls
metric m:sort_order p:integer l:"SORT ORDER" t:dataTypeName=number

metric m:award_amount p:double l:"AWARD AMOUNT" t:dataTypeName=number

metric m:amount_expended p:double l:"AMOUNT EXPENDED" t:dataTypeName=number

metric m:jobs_created p:float l:"JOBS CREATED" t:dataTypeName=number

entity e:r74f-dpgp l:"Oregon Recovery and Reinvestment Act Data - June, 2012" t:url=https://data.oregon.gov/api/views/r74f-dpgp

property e:r74f-dpgp t:meta.view v:id=r74f-dpgp v:category="Revenue & Expense" v:averageRating=0 v:name="Oregon Recovery and Reinvestment Act Data - June, 2012"

property e:r74f-dpgp t:meta.view.owner v:id=d6zz-js5q v:screenName="Paula N." v:displayName="Paula N."

property e:r74f-dpgp t:meta.view.tableauthor v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```