# ARRA Grant Expenditures As Of COB January 31, 2013

## Dataset

* [Dataset URL](https://data.mo.gov/api/views/bzg7-8yqk/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/arra-grant-expenditures-as-of-cob-january-31-2013-51d18)
* Id = bzg7-8yqk
* Name = ARRA Grant Expenditures As Of COB January 31, 2013
* Category = Government Administration
* Created = 2013-02-01T16:57:56Z
* Publication Date = 2013-02-01T16:59:04Z
* Rows Updated = 2013-02-01T16:58:05Z

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
| Payments Total | payments_total | money     | money       | numeric metric | Yes      | 
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
series e:bzg7-8yqk d:2013-02-01T08:57:58.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="CRYSTAL LAKE FISHERIES INC" m:payments_total=52809.14

series e:bzg7-8yqk d:2013-02-01T08:57:58.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FLOWERS FISH FARM LLC" m:payments_total=37285.06

series e:bzg7-8yqk d:2013-02-01T08:57:58.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE t:vendor_name="FRENCH FARMS" m:payments_total=21755.01
```

## Meta Commands

```ls
entity e:bzg7-8yqk l:"ARRA Grant Expenditures As Of COB January 31, 2013" t:url=https://data.mo.gov/api/views/bzg7-8yqk

property e:bzg7-8yqk t:meta.view d:2017-03-03T14:08:47.989Z v:id=bzg7-8yqk v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Expenditures As Of COB January 31, 2013"

property e:bzg7-8yqk t:meta.view.owner d:2017-03-03T14:08:47.989Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight

property e:bzg7-8yqk t:meta.view.tableauthor d:2017-03-03T14:08:47.989Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```