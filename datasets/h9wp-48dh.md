# Materials Innovation and Recycling Authority Checkbook Financial Data FY 2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/materials-innovation-and-recycling-authority-checkbook-financial-data-fy-2015) |
| Metadata | [Link](https://data.ct.gov/api/views/h9wp-48dh) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/h9wp-48dh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/h9wp-48dh/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | h9wp-48dh |
| Name | Materials Innovation and Recycling Authority Checkbook Financial Data FY 2015 |
| Attribution | Materials Innovation and Recycling Authority |
| Category | Environment and Natural Resources |
| Tags | mira, transparency, financial data, vendors |
| Created | 2016-04-28T18:54:53Z |
| Publication Date | 2016-04-28T18:57:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | time           | date             | Date             | calendar_date | calendar_date |
| Yes      | series tag     | vendor_name      | Vendor Name      | text          | text          |
| Yes      | series tag     | vendor_number    | Vendor Number    | text          | text          |
| Yes      | numeric metric | amount_paid      | Amount Paid      | money         | money         |
| Yes      | series tag     | expense_category | Expense Category | text          | text          |
| Yes      | series tag     | fund             | Fund             | text          | text          |
| Yes      | series tag     | program          | Program          | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:h9wp-48dh d:2014-08-14T00:00:00.000Z t:vendor_number=VN2271 t:program="General Fund" t:expense_category="Printing services" t:fund=Operating t:vendor_name="4IMPRINT, INC." m:amount_paid=462.05

series e:h9wp-48dh d:2014-08-14T00:00:00.000Z t:vendor_number=VN2271 t:program="General Fund" t:expense_category="Printing services" t:fund=Operating t:vendor_name="4IMPRINT, INC." m:amount_paid=464.1

series e:h9wp-48dh d:2014-09-18T00:00:00.000Z t:vendor_number=VN2271 t:program="General Fund" t:expense_category="Printing services" t:fund=Operating t:vendor_name="4IMPRINT, INC." m:amount_paid=261.14
```

## Meta Commands

```ls
metric m:amount_paid p:double l:"Amount Paid" t:dataTypeName=money

entity e:h9wp-48dh l:"Materials Innovation and Recycling Authority Checkbook Financial Data FY 2015" t:attribution="Materials Innovation and Recycling Authority" t:url=https://data.ct.gov/api/views/h9wp-48dh

property e:h9wp-48dh t:meta.view v:id=h9wp-48dh v:category="Environment and Natural Resources" v:attributionLink=http://www.ctmira.org/ v:averageRating=0 v:name="Materials Innovation and Recycling Authority Checkbook Financial Data FY 2015" v:attribution="Materials Innovation and Recycling Authority"

property e:h9wp-48dh t:meta.view.owner v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:displayName="Office of the State Comptroller"

property e:h9wp-48dh t:meta.view.tableauthor v:id=xhf5-s5a4 v:screenName="Office of the State Comptroller" v:roleName=publisher v:displayName="Office of the State Comptroller"
```

## Top Records

```ls
| date                | vendor_name                             | vendor_number | amount_paid | expense_category                      | fund      | program                        | 
| =================== | ======================================= | ============= | =========== | ===================================== | ========= | ============================== | 
| 2014-08-14T00:00:00 | 4IMPRINT, INC.                          | VN2271        | 462.05      | Printing services                     | Operating | General Fund                   | 
| 2014-08-14T00:00:00 | 4IMPRINT, INC.                          | VN2271        | 464.10      | Printing services                     | Operating | General Fund                   | 
| 2014-09-18T00:00:00 | 4IMPRINT, INC.                          | VN2271        | 261.14      | Printing services                     | Operating | General Fund                   | 
| 2014-07-24T00:00:00 | A & A OFFICE SYSTEMS INC.               | VN1908        | 7.47        | Copier Services                       | Operating | General Fund                   | 
| 2014-07-31T00:00:00 | A J BELLIVEAU RAILROAD CONSTRUCTION INC | VN27          | 9450.50     | Project equipment maintenance         | operating | Connecticut Solid waste System | 
| 2015-05-07T00:00:00 | A J BELLIVEAU RAILROAD CONSTRUCTION INC | VN27          | 440.00      | Maintenance Services                  | Operating | Property Division              | 
| 2014-07-31T00:00:00 | A M BEST COMPANY INC                    | VN635         | 171.25      | Subscriptions and Reference materials | Operating | General Fund                   | 
| 2015-03-27T00:00:00 | A M BEST COMPANY INC                    | VN635         | 175.75      | Subscriptions and Reference materials | Operating | General Fund                   | 
| 2014-07-03T00:00:00 | ACCURATE TERMITE AND PEST CONTROL CO.   | VN1847        | 144.00      | Building Operations                   | Operating | Property Division              | 
| 2014-08-07T00:00:00 | ACCURATE TERMITE AND PEST CONTROL CO.   | VN1847        | 144.00      | Building Operations                   | Operating | Property Division              | 
```