# ARRA Grant Expenditures As Of COB May 31, 2016

## Dataset

* [Dataset URL](https://data.mo.gov/api/views/4nzm-we3m/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/arra-grant-expenditures-as-of-cob-may-31-2016)
* Id = 4nzm-we3m
* Name = ARRA Grant Expenditures As Of COB May 31, 2016
* Category = Government Administration
* Created = 2016-06-02T20:05:41Z
* Publication Date = 2016-06-02T20:08:27Z
* Rows Updated = 2016-06-02T20:07:53Z

## Description

Data that shows how every dollar received by the State of Missouri under the American Reinvestment and Recovery Act of 2009 has been spent including the name of the state agency that made the expenditure, category of expenditure and the names of vendors receiving payments.

## Columns

```ls
| Name           | Field Name     | Data Type | Render Type | Schema Type    | Included | 
| ============== | ============== | ========= | =========== | ============== | ======== | 
| updated_at     | :updated_at    | meta_data | meta_data   | time           | Yes      | 
| Agency Name    | agency_name    | text      | text        | series tag     | Yes      | 
| Program Name   | program_name   | text      | text        | series tag     | Yes      | 
| Vendor Name    | vendor_name    | text      | text        | series tag     | Yes      | 
| Payments Total | payments_total | number    | number      | numeric metric | Yes      | 
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
series e:4nzm-we3m d:2016-06-02T13:06:45.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="CRYSTAL LAKE FISHERIES INC" m:payments_total=52809.14

series e:4nzm-we3m d:2016-06-02T13:06:45.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FLOWERS FISH FARM LLC" m:payments_total=37285.06

series e:4nzm-we3m d:2016-06-02T13:06:45.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FRENCH FARMS" m:payments_total=21755.01
```

## Meta Commands

```ls
metric m:payments_total l:"Payments Total" t:dataTypeName=number

entity e:4nzm-we3m l:"ARRA Grant Expenditures As Of COB May 31, 2016" t:url=https://data.mo.gov/api/views/4nzm-we3m

property e:4nzm-we3m t:meta.view d:2017-03-03T14:15:02.523Z v:id=4nzm-we3m v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Expenditures As Of COB May 31, 2016"

property e:4nzm-we3m t:meta.view.owner d:2017-03-03T14:15:02.523Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight

property e:4nzm-we3m t:meta.view.tableauthor d:2017-03-03T14:15:02.523Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```