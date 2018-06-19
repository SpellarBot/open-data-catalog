# Baltimore Operating Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-operating-budget) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/g5wn-pq7y) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/g5wn-pq7y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/g5wn-pq7y/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | g5wn-pq7y |
| Name | Baltimore Operating Budget |
| Created | 2015-04-26T22:49:09Z |
| Publication Date | 2015-04-26T22:50:54Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | time           | fiscal_year               | Fiscal Year               | number    | number      |
| Yes      | series tag     | department                | Department                | text      | text        |
| Yes      | series tag     | fund_id                   | Fund Id                   | text      | number      |
| Yes      | series tag     | fund                      | Fund                      | text      | text        |
| Yes      | series tag     | fund_type                 | Fund Type                 | text      | text        |
| Yes      | series tag     | detailed_fund_id          | Detailed Fund Id          | text      | number      |
| Yes      | series tag     | detailed_fund_description | Detailed Fund Description | text      | text        |
| Yes      | series tag     | program_id                | Program Id                | text      | number      |
| Yes      | series tag     | service                   | Service                   | text      | text        |
| Yes      | series tag     | program                   | Program                   | text      | text        |
| Yes      | series tag     | activity_id               | Activity Id               | text      | number      |
| Yes      | series tag     | description               | Description               | text      | text        |
| Yes      | numeric metric | obj                       | Obj                       | number    | number      |
| Yes      | series tag     | expense_category          | Expense Category          | text      | text        |
| Yes      | series tag     | sub_object_id             | Sub Object Id             | text      | number      |
| Yes      | series tag     | expense_type              | Expense Type              | text      | text        |
| Yes      | numeric metric | approved_amount           | Approved Amount           | number    | number      |
| Yes      | numeric metric | recommended_amount        | Recommended Amount        | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g5wn-pq7y d:2015-01-01T00:00:00.000Z t:fund_id=1001 t:expense_type="Unallocable Credits (General)" t:detailed_fund_description=General t:activity_id=1 t:program="Benefits Administration" t:description=Transfers t:department="Human Resources" t:detailed_fund_id=1001 t:service="Innovative Government" t:sub_object_id=0 t:expense_category="Benefits Administration" t:fund=General t:program_id=771 m:approved_amount=-2339176 m:recommended_amount=0 m:obj=0

series e:g5wn-pq7y d:2015-01-01T00:00:00.000Z t:fund_id=1001 t:expense_type="Unallocable Credits (General)" t:detailed_fund_description=General t:activity_id=1 t:program="Civil Service Management" t:description=Transfers t:department="Human Resources" t:detailed_fund_id=1001 t:service="Innovative Government" t:sub_object_id=0 t:expense_category="Civil Service Management" t:fund=General t:program_id=772 m:approved_amount=-219300 m:recommended_amount=0 m:obj=0

series e:g5wn-pq7y d:2015-01-01T00:00:00.000Z t:fund_id=1001 t:expense_type="Unallocable Credits (General)" t:detailed_fund_description=General t:activity_id=1 t:program="COB University" t:description=Transfers t:department="Human Resources" t:detailed_fund_id=1001 t:service="Innovative Government" t:sub_object_id=0 t:expense_category="COB University" t:fund=General t:program_id=773 m:approved_amount=-634625 m:recommended_amount=0 m:obj=0
```

## Meta Commands

```ls
metric m:obj p:integer l:Obj t:dataTypeName=number

metric m:approved_amount p:integer l:"Approved Amount" t:dataTypeName=number

metric m:recommended_amount p:integer l:"Recommended Amount" t:dataTypeName=number

entity e:g5wn-pq7y l:"Baltimore Operating Budget" t:url=https://data.baltimorecity.gov/api/views/g5wn-pq7y

property e:g5wn-pq7y t:meta.view v:id=g5wn-pq7y v:averageRating=0 v:name="Baltimore Operating Budget"

property e:g5wn-pq7y t:meta.view.owner v:id=n97x-2qif v:screenName="Tim Wang" v:displayName="Tim Wang"

property e:g5wn-pq7y t:meta.view.tableauthor v:id=n97x-2qif v:screenName="Tim Wang" v:displayName="Tim Wang"
```

## Top Records

```ls
| fiscal_year | department            | fund_id | fund    | fund_type | detailed_fund_id | detailed_fund_description | program_id | service               | program                  | activity_id | description | obj | expense_category                     | sub_object_id | expense_type                  | approved_amount | recommended_amount | 
| =========== | ===================== | ======= | ======= | ========= | ================ | ========================= | ========== | ===================== | ======================== | =========== | =========== | === | ==================================== | ============= | ============================= | =============== | ================== | 
| 2015        | Human Resources       | 1001    | General |           | 1001             | General                   | 771        | Innovative Government | Benefits Administration  | 1           | Transfers   | 0   | Benefits Administration              | 0             | Unallocable Credits (General) | -2339176        | 0                  | 
| 2015        | Human Resources       | 1001    | General |           | 1001             | General                   | 772        | Innovative Government | Civil Service Management | 1           | Transfers   | 0   | Civil Service Management             | 0             | Unallocable Credits (General) | -219300         | 0                  | 
| 2015        | Human Resources       | 1001    | General |           | 1001             | General                   | 773        | Innovative Government | COB University           | 1           | Transfers   | 0   | COB University                       | 0             | Unallocable Credits (General) | -634625         | 0                  | 
| 2015        | Courts: Circuit Court | 1001    | General |           | 1001             | General                   | 110        | Safer Streets         | Circuit Court            | 1           | Transfers   | 0   | Adjudications                        | 0             | Unallocable Credits (General) | -150511         | 0                  | 
| 2015        | Finance               | 1001    | General |           | 1001             | General                   | 148        | Innovative Government | Revenue Collection       | 11          | Transfers   | 0   | Transfers - General Collections      | 0             | Unallocable Credits (General) | -2346000        | 0                  | 
| 2015        | Finance               | 1001    | General |           | 1001             | General                   | 148        | Innovative Government | Revenue Collection       | 12          | Transfers   | 0   | Transfers - Parking Fine Collections | 0             | Unallocable Credits (General) | -2901119        | 0                  | 
| 2015        | Finance               | 1001    | General |           | 1001             | General                   | 699        | Innovative Government | Procurement              | 1           | Transfers   | 0   | Procurement                          | 0             | Unallocable Credits (General) | -1221288        | 0                  | 
| 2015        | Finance               | 1001    | General |           | 1001             | General                   | 702        | Innovative Government | Accounts Payable         | 26          | Transfers   | 0   | Transfers                            | 0             | Unallocable Credits (General) | -165166         | 0                  | 
| 2015        | Finance               | 1001    | General |           | 1001             | General                   | 703        | Innovative Government | Payroll                  | 26          | Transfers   | 0   | Transfers                            | 0             | Unallocable Credits (General) | -489906         | 0                  | 
| 2015        | Finance               | 1001    | General |           | 1001             | General                   | 704        | Innovative Government | Accounting               | 26          | Transfers   | 0   | Transfers                            | 0             | Unallocable Credits (General) | -1512344        | 0                  | 
```