# Employee Reimbursements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/employee-reimbursements-d3216) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/g5h3-jkgt) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/g5h3-jkgt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/g5h3-jkgt/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | g5h3-jkgt |
| Name | Employee Reimbursements |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | personnel, reimbursements |
| Created | 2011-10-28T03:57:05Z |
| Publication Date | 2015-12-18T21:01:19Z |

## Description

This information is derived from payments made to City of Chicago employees from January 1 of the previous calendar year to the present.  Payments are initiated by City Departments and issued by the Department of Finance. Descriptions of each attribute follow:

-	Voucher Number:  This is a unique number assigned to each payment and is used for identifying that particular payment.

-	Amount:  This is the dollar amount of the payment made.

-	Payment Date:  This is the date payment was issued.

-	Vendor Name:  This is the name of the person or entity to which payment was made.  

-	Description:  This is an optional field that indicates the reason payment was made.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | voucher_number | VOUCHER NUMBER | text          | text          |
| Yes      | numeric metric | amount         | AMOUNT         | money         | money         |
| Yes      | time           | payment_date   | PAYMENT DATE   | calendar_date | calendar_date |
| Yes      | series tag     | vendor_name    | VENDOR NAME    | text          | text          |
| Yes      | series tag     | description    | DESCRIPTION    | text          | text          |
| Yes      | series tag     | department     | DEPARTMENT     | text          | text          |
```

## Time Field

```ls
Value = payment_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:g5h3-jkgt d:2016-12-28T00:00:00.000Z t:department="CHICAGO DEPARTMENT OF TRANSPORTATION" t:description="2016 SAFETY SHOE REIMBURSEMENT" t:vendor_name="COOGAN, JAMES M" t:voucher_number=PV84168406182 m:amount=75

series e:g5h3-jkgt d:2016-12-28T00:00:00.000Z t:department="CHICAGO DEPARTMENT OF TRANSPORTATION" t:description="2016 SAFETY SHOE REIMBURSEMENT" t:vendor_name="CHAVEZ, JOSE C" t:voucher_number=PV84168406158 m:amount=75

series e:g5h3-jkgt d:2016-12-28T00:00:00.000Z t:department="CHICAGO DEPARTMENT OF TRANSPORTATION" t:description="2016 SAFETY SHOE REIMBURSEMENT" t:vendor_name="JOYCE, JAMES M" t:voucher_number=PV84168406149 m:amount=75
```

## Meta Commands

```ls
metric m:amount p:double l:AMOUNT t:dataTypeName=money

entity e:g5h3-jkgt l:"Employee Reimbursements" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/g5h3-jkgt

property e:g5h3-jkgt t:meta.view v:id=g5h3-jkgt v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Employee Reimbursements" v:attribution="City of Chicago"

property e:g5h3-jkgt t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:g5h3-jkgt t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| voucher_number | amount | payment_date        | vendor_name       | description                    | department                           | 
| ============== | ====== | =================== | ================= | ============================== | ==================================== | 
| PV84168406182  | 75     | 2016-12-28T00:00:00 | COOGAN, JAMES M   | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406158  | 75     | 2016-12-28T00:00:00 | CHAVEZ, JOSE C    | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406149  | 75     | 2016-12-28T00:00:00 | JOYCE, JAMES M    | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406146  | 75     | 2016-12-28T00:00:00 | SAMANO, MICHAEL J | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406173  | 75     | 2016-12-28T00:00:00 | HALL, ADAM P      | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406155  | 75     | 2016-12-28T00:00:00 | VYHNANEK, JOHN I  | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406150  | 69.99  | 2016-12-28T00:00:00 | PATANO, VITO      | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406151  | 75     | 2016-12-28T00:00:00 | HAYWOOD, MICHAEL  | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406172  | 75     | 2016-12-28T00:00:00 | FANUCCHI, CORY    | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
| PV84168406157  | 40     | 2016-12-28T00:00:00 | CASTILLO, MARK A  | 2016 SAFETY SHOE REIMBURSEMENT | CHICAGO DEPARTMENT OF TRANSPORTATION | 
```