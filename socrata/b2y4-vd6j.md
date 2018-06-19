# Baltimore City Employee Residency by Agency

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-city-employee-residency-by-agency-b4228) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/b2y4-vd6j) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/b2y4-vd6j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/b2y4-vd6j/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | b2y4-vd6j |
| Name | Baltimore City Employee Residency by Agency |
| Attribution | Finance / Accounting & Payroll |
| Category | City Government |
| Tags | residency, agencies |
| Created | 2011-12-01T15:47:05Z |
| Publication Date | 2014-03-27T23:55:30Z |

## Description

This dataset captures city employee residency as of 6/30/2012.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | deptname       | deptName       | text      | text        |
| Yes      | numeric metric | totalemployees | totalEmployees | number    | number      |
| Yes      | numeric metric | baltcity       | baltCity       | number    | number      |
| Yes      | numeric metric | allegany       | allegany       | number    | number      |
| Yes      | numeric metric | annearundel    | anneArundel    | number    | number      |
| Yes      | numeric metric | baltimoreco    | baltimoreCo    | number    | number      |
| Yes      | numeric metric | calvert        | calvert        | number    | number      |
| Yes      | numeric metric | caroline       | caroline       | number    | number      |
| Yes      | numeric metric | carroll        | carroll        | number    | number      |
| Yes      | numeric metric | cecil          | cecil          | number    | number      |
| Yes      | numeric metric | charles        | charles        | number    | number      |
| Yes      | numeric metric | dorchester     | dorchester     | number    | number      |
| Yes      | numeric metric | frederick      | frederick      | number    | number      |
| Yes      | numeric metric | garrett        | garrett        | number    | number      |
| Yes      | numeric metric | harford        | harford        | number    | number      |
| Yes      | numeric metric | howard         | howard         | number    | number      |
| Yes      | numeric metric | kent           | kent           | number    | number      |
| Yes      | numeric metric | talbot         | talbot         | number    | number      |
| Yes      | numeric metric | montgomery     | montgomery     | number    | number      |
| Yes      | numeric metric | princegeorges  | princeGeorges  | number    | number      |
| Yes      | numeric metric | queenannes     | queenAnnes     | number    | number      |
| Yes      | numeric metric | somerset       | somerset       | number    | number      |
| Yes      | numeric metric | stmarys        | stMarys        | number    | number      |
| Yes      | numeric metric | washington     | washington     | number    | number      |
| Yes      | numeric metric | wicomico       | wicomico       | number    | number      |
| Yes      | numeric metric | worcester      | worcester      | number    | number      |
| Yes      | numeric metric | outofstate     | outOfState     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:b2y4-vd6j d:2012-07-18T07:09:13.000Z t:deptname="Circuit Court" m:wicomico=0 m:outofstate=2 m:calvert=0 m:charles=0 m:queenannes=0 m:washington=0 m:somerset=0 m:talbot=0 m:cecil=0 m:annearundel=10 m:dorchester=0 m:howard=4 m:stmarys=0 m:princegeorges=0 m:montgomery=1 m:kent=0 m:harford=11 m:frederick=1 m:carroll=0 m:baltimoreco=40 m:allegany=1 m:baltcity=76 m:caroline=0 m:garrett=0 m:worcester=0 m:totalemployees=146

series e:b2y4-vd6j d:2012-07-18T07:09:13.000Z t:deptname="City Council" m:wicomico=0 m:outofstate=2 m:calvert=0 m:charles=0 m:queenannes=0 m:washington=0 m:somerset=0 m:talbot=0 m:cecil=0 m:annearundel=0 m:dorchester=0 m:howard=1 m:stmarys=0 m:princegeorges=1 m:montgomery=0 m:kent=0 m:harford=4 m:frederick=0 m:carroll=1 m:baltimoreco=17 m:allegany=0 m:baltcity=62 m:caroline=0 m:garrett=0 m:worcester=0 m:totalemployees=88

series e:b2y4-vd6j d:2012-07-18T07:09:13.000Z t:deptname="Community Relations" m:wicomico=0 m:outofstate=0 m:calvert=0 m:charles=0 m:queenannes=0 m:washington=0 m:somerset=0 m:talbot=0 m:cecil=0 m:annearundel=1 m:dorchester=0 m:howard=0 m:stmarys=0 m:princegeorges=0 m:montgomery=0 m:kent=0 m:harford=1 m:frederick=0 m:carroll=0 m:baltimoreco=4 m:allegany=0 m:baltcity=6 m:caroline=0 m:garrett=0 m:worcester=0 m:totalemployees=12
```

## Meta Commands

```ls
metric m:totalemployees p:integer l:totalEmployees t:dataTypeName=number

metric m:baltcity p:integer l:baltCity t:dataTypeName=number

metric m:allegany p:integer l:allegany t:dataTypeName=number

metric m:annearundel p:integer l:anneArundel t:dataTypeName=number

metric m:baltimoreco p:integer l:baltimoreCo t:dataTypeName=number

metric m:calvert p:integer l:calvert t:dataTypeName=number

metric m:caroline p:integer l:caroline t:dataTypeName=number

metric m:carroll p:integer l:carroll t:dataTypeName=number

metric m:cecil p:integer l:cecil t:dataTypeName=number

metric m:charles p:integer l:charles t:dataTypeName=number

metric m:dorchester p:integer l:dorchester t:dataTypeName=number

metric m:frederick p:integer l:frederick t:dataTypeName=number

metric m:garrett p:integer l:garrett t:dataTypeName=number

metric m:harford p:integer l:harford t:dataTypeName=number

metric m:howard p:integer l:howard t:dataTypeName=number

metric m:kent p:integer l:kent t:dataTypeName=number

metric m:talbot p:integer l:talbot t:dataTypeName=number

metric m:montgomery p:integer l:montgomery t:dataTypeName=number

metric m:princegeorges p:integer l:princeGeorges t:dataTypeName=number

metric m:queenannes p:integer l:queenAnnes t:dataTypeName=number

metric m:somerset p:integer l:somerset t:dataTypeName=number

metric m:stmarys p:integer l:stMarys t:dataTypeName=number

metric m:washington p:integer l:washington t:dataTypeName=number

metric m:wicomico p:integer l:wicomico t:dataTypeName=number

metric m:worcester p:integer l:worcester t:dataTypeName=number

metric m:outofstate p:integer l:outOfState t:dataTypeName=number

entity e:b2y4-vd6j l:"Baltimore City Employee Residency by Agency" t:attribution="Finance / Accounting & Payroll" t:url=https://data.baltimorecity.gov/api/views/b2y4-vd6j

property e:b2y4-vd6j t:meta.view v:id=b2y4-vd6j v:category="City Government" v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Finance/AccountingPayroll.aspx v:averageRating=0 v:name="Baltimore City Employee Residency by Agency" v:attribution="Finance / Accounting & Payroll"

property e:b2y4-vd6j t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:b2y4-vd6j t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:b2y4-vd6j t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | deptname                    | totalemployees | baltcity | allegany | annearundel | baltimoreco | calvert | caroline | carroll | cecil | charles | dorchester | frederick | garrett | harford | howard | kent | talbot | montgomery | princegeorges | queenannes | somerset | stmarys | washington | wicomico | worcester | outofstate | 
| =========== | =========================== | ============== | ======== | ======== | =========== | =========== | ======= | ======== | ======= | ===== | ======= | ========== | ========= | ======= | ======= | ====== | ==== | ====== | ========== | ============= | ========== | ======== | ======= | ========== | ======== | ========= | ========== | 
| 1342595353  | Circuit Court               | 146            | 76       | 1        | 10          | 40          | 0       | 0        | 0       | 0     | 0       | 0          | 1         | 0       | 11      | 4      | 0    | 0      | 1          | 0             | 0          | 0        | 0       | 0          | 0        | 0         | 2          | 
| 1342595353  | City Council                | 88             | 62       | 0        | 0           | 17          | 0       | 0        | 1       | 0     | 0       | 0          | 0         | 0       | 4       | 1      | 0    | 0      | 0          | 1             | 0          | 0        | 0       | 0          | 0        | 0         | 2          | 
| 1342595353  | Community Relations         | 12             | 6        | 0        | 1           | 4           | 0       | 0        | 0       | 0     | 0       | 0          | 0         | 0       | 1       | 0      | 0    | 0      | 0          | 0             | 0          | 0        | 0       | 0          | 0        | 0         | 0          | 
| 1342595353  | COMP-Audits                 | 37             | 11       | 0        | 2           | 22          | 0       | 0        | 0       | 0     | 0       | 0          | 0         | 0       | 0       | 1      | 0    | 0      | 0          | 0             | 0          | 0        | 0       | 0          | 0        | 0         | 1          | 
| 1342595353  | COMP-Communication Services | 31             | 22       | 0        | 0           | 5           | 0       | 0        | 0       | 0     | 0       | 0          | 0         | 0       | 2       | 1      | 0    | 0      | 1          | 0             | 0          | 0        | 0       | 0          | 0        | 0         | 0          | 
| 1342595353  | COMP-Comptroller's Office   | 9              | 7        | 0        | 0           | 1           | 0       | 0        | 0       | 0     | 0       | 0          | 0         | 0       | 0       | 0      | 0    | 0      | 0          | 0             | 0          | 0        | 0       | 0          | 0        | 0         | 1          | 
| 1342595353  | COMP-Real Estate            | 11             | 7        | 0        | 0           | 3           | 0       | 0        | 0       | 0     | 0       | 0          | 0         | 0       | 1       | 0      | 0    | 0      | 0          | 0             | 0          | 0        | 0       | 0          | 0        | 0         | 0          | 
| 1342595353  | Council Services            | 6              | 4        | 0        | 0           | 1           | 0       | 0        | 0       | 0     | 0       | 0          | 0         | 0       | 0       | 0      | 0    | 0      | 0          | 0             | 0          | 0        | 0       | 0          | 0        | 0         | 1          | 
| 1342595353  | DPW-Administration          | 96             | 57       | 0        | 4           | 21          | 0       | 0        | 2       | 0     | 0       | 0          | 0         | 0       | 7       | 1      | 0    | 0      | 1          | 0             | 1          | 0        | 0       | 0          | 0        | 0         | 2          | 
| 1342595353  | DPW-Solid Waste             | 741            | 622      | 0        | 3           | 94          | 2       | 0        | 1       | 0     | 1       | 0          | 0         | 0       | 5       | 6      | 0    | 1      | 2          | 0             | 0          | 0        | 0       | 0          | 0        | 0         | 4          | 
```