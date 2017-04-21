# Open Budget Application - Capital Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-budget-application-capital-budget) |
| Metadata | [Link](https://data.seattle.gov/api/views/makk-9r56) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/makk-9r56/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/makk-9r56/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | makk-9r56 |
| Name | Open Budget Application - Capital Budget |
| Attribution | Seattle City Budget Office |
| Category | Finance |
| Created | 2016-08-11T20:48:10Z |
| Publication Date | 2016-09-29T22:13:00Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | time           | fiscal_year  | Fiscal_Year  | number    | number      |
| Yes      | series tag     | deptname     | DeptName     | text      | text        |
| Yes      | series tag     | bclname      | BCLName      | text      | text        |
| Yes      | series tag     | projecttitle | ProjectTitle | text      | text        |
| Yes      | series tag     | projectcode  | ProjectCode  | text      | text        |
| Yes      | series tag     | fundname     | FundName     | text      | text        |
| Yes      | numeric metric | amount       | Amount       | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:makk-9r56 d:2017-01-01T00:00:00.000Z t:projecttitle="Debt Service - CRF" t:projectcode=TC320060 t:bclname="Debt Service Program" t:deptname="Seattle Department of Transportation" t:fundname="Cumulative Reserve Subfund - Real Estate Excise Tax II Subaccount" m:amount=1306000

series e:makk-9r56 d:2017-01-01T00:00:00.000Z t:projecttitle="Debt Service - CRF" t:projectcode=TC320060 t:bclname="Debt Service Program" t:deptname="Seattle Department of Transportation" t:fundname="2006 LTGO Capital Projects Fund" m:amount=0

series e:makk-9r56 d:2017-01-01T00:00:00.000Z t:projecttitle="Arterial Asphalt and Concrete Program" t:projectcode=TC365440 t:bclname="Major Maintenance/Replacement" t:deptname="Seattle Department of Transportation" t:fundname="Cumulative Reserve Subfund - Real Estate Excise Tax II Subaccount" m:amount=0
```

## Meta Commands

```ls
metric m:amount p:integer l:Amount t:dataTypeName=number

entity e:makk-9r56 l:"Open Budget Application - Capital Budget" t:attribution="Seattle City Budget Office" t:url=https://data.seattle.gov/api/views/makk-9r56

property e:makk-9r56 t:meta.view v:id=makk-9r56 v:category=Finance v:averageRating=0 v:name="Open Budget Application - Capital Budget" v:attribution="Seattle City Budget Office"

property e:makk-9r56 t:meta.view.owner v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:displayName="Kirk, Daniel"

property e:makk-9r56 t:meta.view.tableauthor v:id=wmx8-e5p7 v:screenName="Kirk, Daniel" v:roleName=administrator v:displayName="Kirk, Daniel"
```

## Top Records

```ls
| fiscal_year | deptname                             | bclname                       | projecttitle                          | projectcode | fundname                                                          | amount  | 
| =========== | ==================================== | ============================= | ===================================== | =========== | ================================================================= | ======= | 
| 2017        | Seattle Department of Transportation | Debt Service Program          | Debt Service - CRF                    | TC320060    | Cumulative Reserve Subfund - Real Estate Excise Tax II Subaccount | 1306000 | 
| 2017        | Seattle Department of Transportation | Debt Service Program          | Debt Service - CRF                    | TC320060    | 2006 LTGO Capital Projects Fund                                   | 0       | 
| 2017        | Seattle Department of Transportation | Major Maintenance/Replacement | Arterial Asphalt and Concrete Program | TC365440    | Cumulative Reserve Subfund - Real Estate Excise Tax II Subaccount | 0       | 
| 2017        | Seattle Department of Transportation | Major Maintenance/Replacement | Arterial Asphalt and Concrete Program | TC365440    | Cumulative Reserve Subfund - Real Estate Excise Tax I Subaccount  | 0       | 
| 2017        | Seattle Department of Transportation | Major Maintenance/Replacement | Arterial Asphalt and Concrete Program | TC365440    | Cumulative Reserve Subfund - Unrestricted Subaccount              | 0       | 
| 2017        | Seattle Department of Transportation | Major Maintenance/Replacement | Arterial Asphalt and Concrete Program | TC365440    | Cumulative Reserve Subfund - Street Vacation Subaccount           | 0       | 
| 2017        | Seattle Department of Transportation | Major Maintenance/Replacement | Arterial Asphalt and Concrete Program | TC365440    | Transportation Operating Fund                                     | 0       | 
| 2017        | Seattle Department of Transportation | Major Maintenance/Replacement | Arterial Asphalt and Concrete Program | TC365440    | Transportation Operating Fund                                     | 0       | 
| 2017        | Seattle Department of Transportation | Major Maintenance/Replacement | Arterial Asphalt and Concrete Program | TC365440    | Transportation Operating Fund                                     | 0       | 
| 2017        | Seattle Department of Transportation | Major Maintenance/Replacement | Arterial Asphalt and Concrete Program | TC365440    | Transportation Operating Fund                                     | 0       | 
```