# ARRA Grant Revenue as of COB March 31, 2016

## Dataset

* [Dataset URL](https://data.mo.gov/api/views/h3pg-sm3a/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/arra-grant-revenue-as-of-cob-march-31-2016)
* [Metadata URL](https://data.mo.gov/api/views/h3pg-sm3a)
* Id = h3pg-sm3a
* Name = ARRA Grant Revenue as of COB March 31, 2016
* Category = Government Administration
* Created = 2016-04-04T18:04:09Z
* Publication Date = 2016-04-04T18:05:02Z
* Rows Updated = 2016-04-04T18:04:17Z

## Description

Data that shows every dollar received by the State of Missouri to date under the American Reinvestment and Recovery Act of 2009 including the receiving state agency and the federal funding source or program.

## Columns

```ls
| Name            | Field Name      | Data Type | Render Type | Schema Type    | Included | 
| =============== | =============== | ========= | =========== | ============== | ======== | 
| updated_at      | :updated_at     | meta_data | meta_data   | time           | No       | 
| Agency Name     | agency_name     | text      | text        | series tag     | Yes      | 
| Program Name    | program_name    | text      | text        | series tag     | Yes      | 
| Amount Received | amount_received | money     | money       | numeric metric | Yes      | 
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
series e:h3pg-sm3a d:2016-04-04T11:04:12.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:h3pg-sm3a d:2016-04-04T11:04:12.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=5000000

series e:h3pg-sm3a d:2016-04-04T11:04:12.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
entity e:h3pg-sm3a l:"ARRA Grant Revenue as of COB March 31, 2016" t:url=https://data.mo.gov/api/views/h3pg-sm3a

property e:h3pg-sm3a t:meta.view d:2017-03-07T18:49:18.057Z v:id=h3pg-sm3a v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Revenue as of COB March 31, 2016"

property e:h3pg-sm3a t:meta.view.owner d:2017-03-07T18:49:18.057Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight

property e:h3pg-sm3a t:meta.view.tableauthor d:2017-03-07T18:49:18.057Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```