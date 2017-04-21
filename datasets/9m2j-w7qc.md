# Disciplinary Actions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dob-disciplinary-action) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9m2j-w7qc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9m2j-w7qc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9m2j-w7qc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9m2j-w7qc |
| Name | Disciplinary Actions |
| Attribution | Department of Buildings (DOB) |
| Category | Business |
| Created | 2017-02-06T21:31:25Z |
| Publication Date | 2017-02-06T21:45:45Z |

## Description

The Department of Buildings investigates and takes disciplinary action against construction professionals when their conduct violates standards set forth in the New York City Construction Codes. Actions may be taken against individuals who are accused of abusing filing privileges; violating laws, rules, and regulations; performing work that requires a license or registration without a license or registration.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | time        | year           | Year           | number    | number      |
| Yes      | series tag  | licence_type   | Licence type   | text      | text        |
| Yes      | series tag  | licence_number | Licence number | text      | text        |
| Yes      | series tag  | name           | Name           | text      | text        |
| Yes      | series tag  | company        | Company        | text      | text        |
| Yes      | series tag  | disposition    | Disposition    | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:9m2j-w7qc l:"Disciplinary Actions" t:attribution="Department of Buildings (DOB)" t:url=https://data.cityofnewyork.us/api/views/9m2j-w7qc

property e:9m2j-w7qc t:meta.view v:id=9m2j-w7qc v:category=Business v:averageRating=0 v:name="Disciplinary Actions" v:attribution="Department of Buildings (DOB)"

property e:9m2j-w7qc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9m2j-w7qc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| year | licence_type          | licence_number | name                | company                              | disposition                                                                    | 
| ==== | ===================== | ============== | =================== | ==================================== | ============================================================================== | 
| 2016 | Registered Architect  | #025804        | Gaskin, Robert      | RCGA Architects                      | Voluntary Surrender of Professional Certification and Directive 14 privileges. | 
| 2016 | Professional Engineer | #086577        | Choi, Samuel        | S & K Building System Solutions, LLC | Voluntary Surrender of Professional Certification and Directive 14 privileges. | 
| 2016 | Registered Architect  | #034339        | Arjune, Nischal     | Arjune Design Studio, LLC            | Voluntary Surrender of Professional Certification and Directive 14 privileges. | 
| 2016 | Professional Engineer | #087737        | So, Keng Lee        | S&K Building System Solutions        | Voluntary Surrender of Professional Certification and Directive 14 privileges. | 
| 2016 | Professional Engineer | #083278        | Hoque, Akm Ashraful | Ashraf Corporation                   | Voluntary Surrender of Professional Certification and Directive 14 privileges. | 
| 2016 | Professional Engineer | #090429        | Ekwaneen, Ziad      | AA Building & Inspections Services   | Four year Voluntary Surrender of all filing privileges.                        | 
| 2016 | Registered Architect  | #023734        | Conard, Jon Michael | Design + Urbanism Architectural, LLC | Voluntary Surrender of Professional Certification and Directive 14 privileges. | 
| 2016 | Professional Engineer | #065736        | Ken, Theeshiun      | Theeshiun Ken, P.E.                  | Voluntary surrender of Professional Certification and Directive 14 privileges. | 
| 2016 | Registered Architect  | #020919        | Rowland, Steven     | SRA Group, LLC                       | Voluntary Surrender of Professional Certification and Directive 14 privileges. | 
| 2016 | Registered Architect  | #018459        | Vail, Thomas        | Vail Associates, Architects          | Voluntary Surrender of Professional Certification and Directive 14 privileges. | 
```