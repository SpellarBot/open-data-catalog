# ARRA Grant Revenues As Of COB November 30, 2014

## Dataset

* [Dataset URL](https://data.mo.gov/api/views/2xyd-uph9/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/arra-grant-revenues-as-of-cob-november-30-2014-1007e)
* [Metadata URL](https://data.mo.gov/api/views/2xyd-uph9)
* Id = 2xyd-uph9
* Name = ARRA Grant Revenues As Of COB November 30, 2014
* Category = Government Administration
* Created = 2014-12-02T18:50:15Z
* Publication Date = 2014-12-02T18:51:04Z
* Rows Updated = 2014-12-02T18:50:22Z

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
series e:2xyd-uph9 d:2014-12-02T10:50:18.000Z t:program_name="AQUACULTURE ASSISTANCE PROGRAM" t:agency_name=AGRICULTURE m:amount_received=111849.21

series e:2xyd-uph9 d:2014-12-02T10:50:18.000Z t:program_name="ENERGY EFFIC/RENEW ENERGY - CONS BLO" t:agency_name=AGRICULTURE m:amount_received=5000000

series e:2xyd-uph9 d:2014-12-02T10:50:18.000Z t:program_name="FISH AND WILDLIFE SERVICE" t:agency_name=CONSERVATION m:amount_received=144900
```

## Meta Commands

```ls
entity e:2xyd-uph9 l:"ARRA Grant Revenues As Of COB November 30, 2014" t:url=https://data.mo.gov/api/views/2xyd-uph9

property e:2xyd-uph9 t:meta.view d:2017-03-08T00:52:41.563Z v:id=2xyd-uph9 v:category="Government Administration" v:averageRating=0 v:name="ARRA Grant Revenues As Of COB November 30, 2014"

property e:2xyd-uph9 t:meta.view.owner d:2017-03-08T00:52:41.563Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight

property e:2xyd-uph9 t:meta.view.tableauthor d:2017-03-08T00:52:41.563Z v:id=4cdh-4my4 v:screenName=Dwight v:roleName=editor v:displayName=Dwight
```