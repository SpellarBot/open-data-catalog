# Major Recurring Federal Awards

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/major-recurring-federal-awards) |
| Metadata | [Link](https://data.hawaii.gov/api/views/wncs-jpqq) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/wncs-jpqq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/wncs-jpqq/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | wncs-jpqq |
| Name | Major Recurring Federal Awards |
| Created | 2015-02-03T00:21:04Z |
| Publication Date | 2015-02-04T17:26:51Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | letter_code            | Letter Code            | text      | text        |
| Yes      | series tag     | department_code        | Department Code        | text      | text        |
| Yes      | series tag     | state_expending_agency | State Expending Agency | text      | text        |
| Yes      | numeric metric | cfda                   | CFDA                   | number    | text        |
| Yes      | series tag     | program                | Program                | text      | text        |
| Yes      | time           | fiscal_year            | Fiscal Year            | number    | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wncs-jpqq d:2015-01-01T00:00:00.000Z t:state_expending_agency="Department of Business, Economic Development and Tourism" t:program="State Energy Program" t:letter_code=B t:department_code=BED m:cfda=81.041

series e:wncs-jpqq d:2015-01-01T00:00:00.000Z t:state_expending_agency="Department of Business, Economic Development and Tourism" t:program="EDA - Economic Adjustment" t:letter_code=B t:department_code=BED m:cfda=11.307

series e:wncs-jpqq d:2015-01-01T00:00:00.000Z t:state_expending_agency="Department of Business, Economic Development and Tourism" t:program="Coastal Zone Management" t:letter_code=B t:department_code=BED m:cfda=11.419
```

## Meta Commands

```ls
metric m:cfda p:float l:CFDA t:dataTypeName=number

entity e:wncs-jpqq l:"Major Recurring Federal Awards" t:url=https://data.hawaii.gov/api/views/wncs-jpqq

property e:wncs-jpqq t:meta.view v:id=wncs-jpqq v:averageRating=0 v:name="Major Recurring Federal Awards"

property e:wncs-jpqq t:meta.view.owner v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:displayName="Open Data Portal Administrator"

property e:wncs-jpqq t:meta.view.tableauthor v:id=q99n-k47h v:screenName="Open Data Portal Administrator" v:roleName=administrator v:displayName="Open Data Portal Administrator"
```

## Top Records

```ls
| letter_code | department_code | state_expending_agency                                   | cfda   | program                                                | fiscal_year | 
| =========== | =============== | ======================================================== | ====== | ====================================================== | =========== | 
| B           | BED             | Department of Business, Economic Development and Tourism | 81.041 | State Energy Program                                   | 2015        | 
| B           | BED             | Department of Business, Economic Development and Tourism | 11.307 | EDA - Economic Adjustment                              | 2015        | 
| B           | BED             | Department of Business, Economic Development and Tourism | 11.419 | Coastal Zone Management                                | 2015        | 
| B           | BED             | Department of Business, Economic Development and Tourism | 14.239 | HOME Investment Partnerships - Nonentitlement (States) | 2015        | 
| C           | LNR             | Department of Land and Natural Resources                 | 15.605 | Fish & Wildlife - Fish Restoration                     | 2015        | 
| C           | LNR             | Department of Land and Natural Resources                 | 15.611 | Fish & Wildlife - Wildlife Restoration                 | 2015        | 
| C           | LNR             | Department of Land and Natural Resources                 | 15.634 | State Wildlife Grants                                  | 2015        | 
| C           | LNR             | Department of Land and Natural Resources                 | 15.611 | Fish & Wildlife - Hunter Safety                        | 2015        | 
| C           | LNR             | Department of Land and Natural Resources                 | 15.904 | Historic Preservation fund                             | 2015        | 
| C           | LNR             | Department of Land and Natural Resources                 | 20.219 | FHWA - Recreational Trails                             | 2015        | 
```