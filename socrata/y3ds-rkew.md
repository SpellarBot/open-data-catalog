# Annual Salary 2010 thru 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-salary-2010-thru-2013-fda95) |
| Metadata | [Link](https://data.wa.gov/api/views/y3ds-rkew) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/y3ds-rkew/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/y3ds-rkew/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | y3ds-rkew |
| Name | Annual Salary 2010 thru 2013 |
| Attribution | fiscal.wa.gov |
| Category | Labor |
| Tags | salary, employees |
| Created | 2015-01-22T19:48:15Z |
| Publication Date | 2015-01-22T21:39:55Z |

## Description

State Employee Salaries by Calendar Year

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| Yes      | series tag     | agency       | Agency       | text      | number      |
| Yes      | series tag     | agencytitle  | AgencyTitle  | text      | text        |
| Yes      | series tag     | employeename | EmployeeName | text      | text        |
| Yes      | series tag     | jobtitle     | JobTitle     | text      | text        |
| Yes      | numeric metric | salary2010   | Salary2010   | number    | number      |
| Yes      | numeric metric | salary2011   | Salary2011   | number    | number      |
| Yes      | numeric metric | salary2012   | Salary2012   | number    | number      |
| Yes      | numeric metric | salary2013   | Salary2013   | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:y3ds-rkew d:2010-01-01T00:00:00.000Z t:jobtitle="FORMS & RECORDS ANALYST 2" t:agencytitle=Accountancy t:employeename="ASMATH, MOSAR" t:agency=165 m:salary2010=0 m:salary2011=0 m:salary2012=0 m:salary2013=32272

series e:y3ds-rkew d:2010-01-01T00:00:00.000Z t:jobtitle="BOARD MEMBER" t:agencytitle=Accountancy t:employeename="AUBREY, DONALD F" t:agency=165 m:salary2010=0 m:salary2011=950 m:salary2012=1450 m:salary2013=0

series e:y3ds-rkew d:2010-01-01T00:00:00.000Z t:jobtitle="WMS BAND 3" t:agencytitle=Accountancy t:employeename="BREN, DIANE MARIE" t:agency=165 m:salary2010=15004 m:salary2011=0 m:salary2012=0 m:salary2013=0
```

## Meta Commands

```ls
metric m:salary2010 p:integer l:Salary2010 t:dataTypeName=number

metric m:salary2011 p:integer l:Salary2011 t:dataTypeName=number

metric m:salary2012 p:integer l:Salary2012 t:dataTypeName=number

metric m:salary2013 p:integer l:Salary2013 t:dataTypeName=number

entity e:y3ds-rkew l:"Annual Salary 2010 thru 2013" t:attribution=fiscal.wa.gov t:url=https://data.wa.gov/api/views/y3ds-rkew

property e:y3ds-rkew t:meta.view v:id=y3ds-rkew v:category=Labor v:attributionLink=http://fiscal.wa.gov/Salaries.aspx v:averageRating=0 v:name="Annual Salary 2010 thru 2013" v:attribution=fiscal.wa.gov

property e:y3ds-rkew t:meta.view.license v:name="Public Domain"

property e:y3ds-rkew t:meta.view.owner v:id=bjfs-pe5a v:screenName=justinb.ocio v:displayName=justinb.ocio

property e:y3ds-rkew t:meta.view.tableauthor v:id=bjfs-pe5a v:screenName=justinb.ocio v:roleName=publisher v:displayName=justinb.ocio
```

## Top Records

```ls
| agency | agencytitle | employeename       | jobtitle                      | salary2010 | salary2011 | salary2012 | salary2013 | 
| ====== | =========== | ================== | ============================= | ========== | ========== | ========== | ========== | 
| 165    | Accountancy | ASMATH, MOSAR      | FORMS & RECORDS ANALYST 2     | 0          | 0          | 0          | 32272      | 
| 165    | Accountancy | AUBREY, DONALD F   | BOARD MEMBER                  | 0          | 950        | 1450       | 0          | 
| 165    | Accountancy | BREN, DIANE MARIE  | WMS BAND 3                    | 15004      | 0          | 0          | 0          | 
| 165    | Accountancy | CLARK, ROBIN       | BOARD MEMBER                  | 550        | 0          | 0          | 0          | 
| 165    | Accountancy | DONOVAN, KIRSTEN M | ADMINISTRATIVE TRAINEE 3      | 0          | 0          | 0          | 15182      | 
| 165    | Accountancy | EDDY, MICHELLE S   | CUST SVS SPEC 4               | 42142      | 0          | 0          | 0          | 
| 165    | Accountancy | EDDY, MICHELLE S   | CUSTOMER SERVICE SPECIALIST 4 | 0          | 39369      | 5421       | 4323       | 
| 165    | Accountancy | EDDY, MICHELLE S   | FORMS & RECORDS ANALYST 3     | 0          | 3800       | 39682      | 0          | 
| 165    | Accountancy | HUTCHINS, ROBERT G | BOARD MEMBER                  | 550        | 550        | 350        | 0          | 
| 165    | Accountancy | JASSNY, LAUREN     | BOARD MEMBER                  | 350        | 350        | 150        | 0          | 
```