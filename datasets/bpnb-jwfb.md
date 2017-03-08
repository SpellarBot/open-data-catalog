# Spending And Revenue

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/bpnb-jwfb/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/spending-and-revenue-8cc3d)
* [Metadata URL](https://data.sfgov.org/api/views/bpnb-jwfb)
* Id = bpnb-jwfb
* Name = Spending And Revenue
* Attribution = SF Controller's Office
* [Attribution Link](http://openbook.sfgov.org)
* Category = City Management and Ethics
* Tags = [spending, revenue, amount, sfopenbook, open book, openbook]
* Created = 2013-04-02T20:46:47Z
* Publication Date = 2014-10-07T16:15:22Z
* Rows Updated = 2017-03-06T09:59:29Z

## Description

The San Francisco Controller's Office maintains a database of spending and revenue data sourced from it's citywide financial system. This data is presented on the Spending and Revenue report hosted at http://openbook.sfgov.org, and is also available in this dataset in CSV format. New data is added on a weekly basis, and is available from fiscal year 2000 forward.

## Columns

```ls
| Name                    | Field Name              | Data Type | Render Type | Schema Type    | Included | 
| ======================= | ======================= | ========= | =========== | ============== | ======== | 
| Fiscal Year             | fiscal_year             | number    | number      | time           | Yes      | 
| Revenue or Spending     | revenue_or_spending     | text      | text        | series tag     | Yes      | 
| Related Gov?t Units     | related_gov_t_units     | text      | text        | series tag     | Yes      | 
| Organization Group Code | organization_group_code | text      | text        | series tag     | Yes      | 
| Organization Group      | organization_group      | text      | text        | series tag     | Yes      | 
| Department Code         | department_code         | text      | text        | series tag     | Yes      | 
| Department              | department              | text      | text        | series tag     | Yes      | 
| Program Code            | program_code            | text      | text        | series tag     | Yes      | 
| Program                 | program                 | text      | text        | series tag     | Yes      | 
| Character Code          | character_code          | text      | text        | series tag     | Yes      | 
| Character               | character               | text      | text        | series tag     | Yes      | 
| Object Code             | object_code             | text      | text        | series tag     | Yes      | 
| Object                  | object                  | text      | text        | series tag     | Yes      | 
| Sub-object Code         | sub_object_code         | text      | text        | series tag     | Yes      | 
| Sub-object              | sub_object              | text      | text        | series tag     | Yes      | 
| Fund Type Code          | fund_type_code          | text      | text        | series tag     | Yes      | 
| Fund Type               | fund_type               | text      | text        | series tag     | Yes      | 
| Fund Code               | fund_code               | text      | text        | series tag     | Yes      | 
| Fund                    | fund                    | text      | text        | series tag     | Yes      | 
| Fund Category Code      | fund_category_code      | text      | text        | series tag     | Yes      | 
| Fund Category           | fund_category           | text      | text        | series tag     | Yes      | 
| Amount                  | amount                  | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
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
series e:bpnb-jwfb d:1999-01-01T00:00:00.000Z t:organization_group="Public Protection" t:fund_type="General Fund" t:fund_code=1GAGF t:program_code=AKB t:department="Adult Probation" t:revenue_or_spending=Revenue t:sub_object="Court Fines" t:object="Court Fines-Non Traffic" t:object_code=252 t:fund_type_code=1G t:character="Fines, Forfeitures & Penalties" t:character_code=250 t:fund_category_code=1 t:program="Community Services" t:fund_category=Operating t:sub_object_code=25210 t:fund="General Fund" t:department_code=ADP t:organization_group_code=01 t:related_gov_t_units=No m:amount=22409.06

series e:bpnb-jwfb d:1999-01-01T00:00:00.000Z t:organization_group="Public Protection" t:fund_type="General Fund" t:fund_code=1GAGF t:program_code=AKB t:department="Adult Probation" t:revenue_or_spending=Revenue t:sub_object="Court Fines Superior" t:object="Court Fines-Non Traffic" t:object_code=252 t:fund_type_code=1G t:character="Fines, Forfeitures & Penalties" t:character_code=250 t:fund_category_code=1 t:program="Community Services" t:fund_category=Operating t:sub_object_code=25220 t:fund="General Fund" t:department_code=ADP t:organization_group_code=01 t:related_gov_t_units=No m:amount=8027.68

series e:bpnb-jwfb d:1999-01-01T00:00:00.000Z t:organization_group="Public Protection" t:fund_type="Special Revenue Funds" t:fund_code=2SPPF t:program_code=AKB t:department="Adult Probation" t:revenue_or_spending=Revenue t:sub_object="Federal Grants Pass-Through State/Other" t:object=Federal-Other t:object_code=449 t:fund_type_code=2S t:character="Intergovernmental Revenues-Federal" t:character_code=400 t:fund_category_code=4 t:program="Community Services" t:fund_category=Grants t:sub_object_code=44931 t:fund="Public Protection Fund" t:department_code=ADP t:organization_group_code=01 t:related_gov_t_units=No m:amount=131977.11
```

## Meta Commands

```ls
metric m:amount l:Amount d:"The amount earned (Revenue) or spent (Spending) by the City and County of San Francisco." t:dataTypeName=number

entity e:bpnb-jwfb l:"Spending And Revenue" t:attribution="SF Controller's Office" t:url=https://data.sfgov.org/api/views/bpnb-jwfb

property e:bpnb-jwfb t:meta.view d:2017-03-08T01:42:06.873Z v:id=bpnb-jwfb v:category="City Management and Ethics" v:attributionLink=http://openbook.sfgov.org v:averageRating=0 v:name="Spending And Revenue" v:attribution="SF Controller's Office"

property e:bpnb-jwfb t:meta.view.license d:2017-03-08T01:42:06.873Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:bpnb-jwfb t:meta.view.owner d:2017-03-08T01:42:06.873Z v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"

property e:bpnb-jwfb t:meta.view.tableauthor d:2017-03-08T01:42:06.873Z v:id=9ufn-6bwh v:screenName="Jeff Pera" v:roleName=editor v:displayName="Jeff Pera"
```