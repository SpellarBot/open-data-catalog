# Budget - 2015 Budget Recommendations - Appropriations

## Dataset

* [Dataset URL](https://data.cityofchicago.org/api/views/kzbi-spm5/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/budget-2015-budget-recommendations-appropriations-68f61)
* [Metadata URL](https://data.cityofchicago.org/api/views/kzbi-spm5)
* Id = kzbi-spm5
* Name = Budget - 2015 Budget Recommendations - Appropriations
* Attribution = City of Chicago
* [Attribution Link](http://www.cityofchicago.org/budget)
* Category = Administration & Finance
* Tags = [budget, 2015]
* Created = 2014-10-15T15:06:10Z
* Publication Date = 2014-10-15T15:41:22Z
* Rows Updated = 2014-10-15T15:40:17Z

## Description

The dataset details 2015 Budget Recommendations, which is the line-item budget document proposed by the Mayor to the City Council for approval. Budgeted expenditures are identified by department, appropriation account, and funding type: Local, Community Development Block Grant Program (CDBG), and other Grants. ?Local? funds refer to those line items that are balanced with locally-generated revenue sources, including but not limited to the Corporate Fund, Water Fund, Midway and O?Hare Airport funds, Vehicle Tax Fund, Library Fund and General Obligation Bond funds. Owner: Budget and Management. Frequency: Data are updated annually. For more information about the budget process, visit the Budget Documents page: http://j.mp/lPotWf.

## Columns

```ls
| Name                                | Field Name                          | Data Type | Render Type | Schema Type    | Included | 
| =================================== | =================================== | ========= | =========== | ============== | ======== | 
| updated_at                          | :updated_at                         | meta_data | meta_data   | time           | No       | 
| FUND TYPE                           | fund_type                           | text      | text        | series tag     | Yes      | 
| FUND CODE                           | fund_code                           | text      | text        | series tag     | Yes      | 
| FUND DESCRIPTION                    | fund_description                    | text      | text        | series tag     | Yes      | 
| DEPARTMENT NUMBER                   | department_number                   | number    | number      | numeric metric | Yes      | 
| DEPARTMENT DESCRIPTION              | department_description              | text      | text        | series tag     | Yes      | 
| APPROPRIATION AUTHORITY             | appropriation_authority             | number    | number      | numeric metric | Yes      | 
| APPROPRIATION AUTHORITY DESCRIPTION | appropriation_authority_description | text      | text        | series tag     | Yes      | 
| APPROPRIATION ACCOUNT               | appropriation_account               | number    | number      | numeric metric | Yes      | 
| APPROPRIATION ACCOUNT DESCRIPTION   | appropriation_account_description   | text      | text        | series tag     | Yes      | 
| 2014 APPROPRATION                   | appropration                        | money     | money       | numeric metric | Yes      | 
| 2014 REVISED APPROPRIATION          | revised_appropriation               | money     | money       | numeric metric | Yes      | 
| 2015 RECOMMENDATION                 | recommendation                      | money     | money       | numeric metric | Yes      | 
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
series e:kzbi-spm5 d:2014-10-15T08:40:01.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_type=LOCAL t:fund_code=0100 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_account_description="SALARIES AND WAGES - ON PAYROLL" t:fund_description="CORPORATE FUND" m:appropriation_account=5 m:appropration=5511957 m:appropriation_authority=2005 m:department_number=1 m:revised_appropriation=5511957 m:recommendation=5550657

series e:kzbi-spm5 d:2014-10-15T08:40:01.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_type=LOCAL t:fund_code=0100 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_account_description="OFFICE CONVENIENCES" t:fund_description="CORPORATE FUND" m:appropriation_account=126 m:appropration=1200 m:appropriation_authority=2005 m:department_number=1 m:revised_appropriation=1200 m:recommendation=1000

series e:kzbi-spm5 d:2014-10-15T08:40:01.000Z t:department_description="OFFICE OF THE MAYOR" t:fund_type=LOCAL t:fund_code=0100 t:appropriation_authority_description="OFFICE OF THE MAYOR" t:appropriation_account_description=POSTAGE t:fund_description="CORPORATE FUND" m:appropriation_account=130 m:appropration=10000 m:appropriation_authority=2005 m:department_number=1 m:revised_appropriation=10000 m:recommendation=5019
```

## Meta Commands

```ls
metric m:department_number p:integer l:"DEPARTMENT NUMBER" t:dataTypeName=number

metric m:appropriation_authority p:integer l:"APPROPRIATION AUTHORITY" t:dataTypeName=number

metric m:appropriation_account p:integer l:"APPROPRIATION ACCOUNT" t:dataTypeName=number

entity e:kzbi-spm5 l:"Budget - 2015 Budget Recommendations - Appropriations" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/kzbi-spm5

property e:kzbi-spm5 t:meta.view d:2017-03-08T00:40:07.617Z v:id=kzbi-spm5 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/budget v:averageRating=0 v:name="Budget - 2015 Budget Recommendations - Appropriations" v:attribution="City of Chicago"

property e:kzbi-spm5 t:meta.view.owner d:2017-03-08T00:40:07.617Z v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"

property e:kzbi-spm5 t:meta.view.tableauthor d:2017-03-08T00:40:07.617Z v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```