# Oregon Recovery and Reinvestment Act Data - June, 2012

## Dataset

* [Dataset URL](https://data.oregon.gov/api/views/r74f-dpgp/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/oregon-recovery-and-reinvestment-act-data-june-2012-371c3)
* [Metadata URL](https://data.oregon.gov/api/views/r74f-dpgp)
* Id = r74f-dpgp
* Name = Oregon Recovery and Reinvestment Act Data - June, 2012
* Category = Revenue & Expense
* Created = 2012-08-08T20:56:38Z
* Publication Date = 2012-08-08T21:00:58Z
* Rows Updated = 2012-08-08T20:56:53Z

## Description

This spreadsheet contains Oregon Recovery and Reinvestment Act (ARRA) Data reported on the State of Oregon Recovery site (http://oregon.gov/recovery/StimulusReporting/ARRA_Projects.shtml). Please note that this data reflects the preliminary data from the most recent reporting period of the American Recovery and Reinvestment Act of 2009, including data through March 30, 2011. This data available for viewing through an interactive map site. For this, and other information on ARRA projects, please visit Oregon's Economic Recovery site: http://www.oregon.gov/recovery. For the latest recovery award data, please visit http://www.recovery.gov.

## Columns

```ls
| Name                   | Field Name             | Data Type | Render Type | Schema Type    | Included | 
| ====================== | ====================== | ========= | =========== | ============== | ======== | 
| updated_at             | :updated_at            | meta_data | meta_data   | time           | No       | 
| SORT ORDER             | sort_order             | number    | number      | numeric metric | Yes      | 
| AWARD DESCRIPTION      | award_description      | text      | text        | series tag     | Yes      | 
| PROJECT DESCRIPTION    | project_description    | text      | text        | series tag     | Yes      | 
| ROOT ID                | root_id                | text      | number      | series tag     | Yes      | 
| PRIME AWARD #          | prime_award            | text      | text        | series tag     | Yes      | 
| AWARD ID               | award_id               | text      | number      | series tag     | Yes      | 
| AWARD NUMBER           | award_number           | text      | text        | series tag     | Yes      | 
| PROJECT ID             | project_id             | text      | text        | series tag     | Yes      | 
| AWARD INSTRUMENT       | award_instrument       | text      | text        | series tag     | Yes      | 
| RECIPIENT TYPE         | recipient_type         | text      | text        | series tag     | Yes      | 
| VENDOR                 | vendor                 | text      | text        | series tag     | Yes      | 
| COUNTY                 | county                 | text      | text        | series tag     | Yes      | 
| PROJECT NAME           | project_name           | text      | text        | series tag     | Yes      | 
| AWARD RECIPIENT        | award_recipient        | text      | text        | series tag     | Yes      | 
| AWARD AMOUNT           | award_amount           | number    | number      | numeric metric | Yes      | 
| AMOUNT EXPENDED        | amount_expended        | number    | number      | numeric metric | Yes      | 
| JOBS CREATED           | jobs_created           | number    | number      | numeric metric | Yes      | 
| PROJECT STATUS         | project_status         | text      | text        | series tag     | Yes      | 
| ZIPCODE                | zipcode                | text      | text        | series tag     | Yes      | 
| CONGRESSIONAL DISTRICT | congressional_district | text      | number      | series tag     | Yes      | 
| MONTH CODE             | month_code             | text      | text        | series tag     | Yes      | 
| Project                | project                | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:r74f-dpgp d:2012-08-08T13:56:41.000Z t:award_number=OR-00J03801 t:project_name="Port of Newport's International Terminal Clean-up - Award ID#:6062" t:project_status=Completed t:vendor=NO t:award_instrument=Q10002 t:root_id=5 t:zipcode=97365-4338 t:recipient_type=SUB t:award_id=6062 t:congressional_district=5 t:project_description="Port of Newport's International Terminal Clean-up - Award ID: 6062" t:project="Port of Newport's International Terminal Clean-up - Award ID#:6062" t:month_code=1106 t:award_description="Brownfields Clean-up" t:county=Lincoln t:prime_award=00J03801 t:award_recipient="Port of Newport" m:amount_expended=200000 m:award_amount=200000 m:jobs_created=0 m:sort_order=2

series e:r74f-dpgp d:2012-08-08T13:56:41.000Z t:award_number=OR-00J03801 t:project_name="Grant Pass River Road Reserve Clean-up Project - Award ID#:9245" t:project_status=Completed t:vendor=NO t:award_instrument=Q10003 t:root_id=5 t:zipcode=97526-2000 t:recipient_type=SUB t:award_id=9245 t:congressional_district=2 t:project_description="Grant Pass River Road Reserve Clean-up Project - Award ID: 9245" t:project="Grant Pass River Road Reserve Clean-up Project - Award ID#:9245" t:month_code=1203 t:award_description="Brownfields Clean-up" t:county=Josephine t:prime_award=00J03801 t:award_recipient="City of Grants Pass" m:amount_expended=220938 m:award_amount=220938 m:jobs_created=0 m:sort_order=5

series e:r74f-dpgp d:2012-08-08T13:56:41.000Z t:award_number=OR-00J03801 t:project_name="Oakridge Industrial Park Clean-up project - Award ID#:9247" t:project_status=Completed t:vendor=NO t:award_instrument=Q10004 t:root_id=5 t:zipcode=97463 t:recipient_type=SUB t:award_id=9247 t:congressional_district=4 t:project_description="Oakridge Industrial Park Clean-up project - Award ID: 9247" t:project="Oakridge Industrial Park Clean-up project - Award ID#:9247" t:month_code=1112 t:award_description="Brownfields Clean-up" t:county=Lane t:prime_award=00J03801 t:award_recipient="City of Oakridge" m:amount_expended=160000 m:award_amount=160000 m:jobs_created=0 m:sort_order=9
```

## Meta Commands

```ls
metric m:sort_order p:integer l:"SORT ORDER" t:dataTypeName=number

metric m:award_amount l:"AWARD AMOUNT" t:dataTypeName=number

metric m:amount_expended l:"AMOUNT EXPENDED" t:dataTypeName=number

metric m:jobs_created l:"JOBS CREATED" t:dataTypeName=number

entity e:r74f-dpgp l:"Oregon Recovery and Reinvestment Act Data - June, 2012" t:url=https://data.oregon.gov/api/views/r74f-dpgp

property e:r74f-dpgp t:meta.view d:2017-03-07T16:48:33.609Z v:id=r74f-dpgp v:category="Revenue & Expense" v:averageRating=0 v:name="Oregon Recovery and Reinvestment Act Data - June, 2012"

property e:r74f-dpgp t:meta.view.owner d:2017-03-07T16:48:33.609Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."

property e:r74f-dpgp t:meta.view.tableauthor d:2017-03-07T16:48:33.609Z v:id=d6zz-js5q v:screenName="Paula N." v:roleName=administrator v:displayName="Paula N."
```