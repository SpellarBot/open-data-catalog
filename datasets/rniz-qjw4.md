# IDOL 2014 Registered Day and Temporary Labor Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2014-registered-day-and-temporary-labor-agencies-7b01c) |
| Metadata | [Link](https://data.illinois.gov/api/views/rniz-qjw4) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/rniz-qjw4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/rniz-qjw4/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | rniz-qjw4 |
| Name | IDOL 2014 Registered Day and Temporary Labor Agencies |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | labor, dtlsa, 820 ilcs 175, jobs, work |
| Created | 2014-01-22T23:05:02Z |
| Publication Date | 2015-01-27T19:12:21Z |

## Description

This is the list of current and approved Day and Temporary Labor Agencies, under the Illinois Day and Temporary Labor Services Act, 820 ILCS 175.

## Columns

```ls
| Included | Schema Type | Field Name | Name     | Data Type | Render Type |
| ======== | =========== | ========== | ======== | ========= | =========== |
| Yes      | series tag  | company    | Company  | text      | text        |
| No       |             | address    | Address  | text      | text        |
| Yes      | series tag  | city       | City     | text      | text        |
| Yes      | series tag  | state      | State    | text      | text        |
| Yes      | series tag  | zip_code   | ZIP Code | text      | text        |
| Yes      | series tag  | type       | Type     | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:rniz-qjw4 d:2014-01-01T00:00:00.000Z t:zip_code=60106 t:company="Clearstaff, Inc." t:state=IL t:type=Office/Branch t:city=Bensenville m:row_number.rniz-qjw4=1

series e:rniz-qjw4 d:2014-01-01T00:00:00.000Z t:zip_code=92868 t:company="Roth Staffing Companies, L.P." t:state=CA t:type=Corporate t:city=Orange m:row_number.rniz-qjw4=2

series e:rniz-qjw4 d:2014-01-01T00:00:00.000Z t:zip_code=61021 t:company="Manpower US Inc." t:state=IL t:type=Office/Branch t:city=Dixon m:row_number.rniz-qjw4=3
```

## Meta Commands

```ls
metric m:row_number.rniz-qjw4 p:long l:"Row Number"

entity e:rniz-qjw4 l:"IDOL 2014 Registered Day and Temporary Labor Agencies" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/rniz-qjw4

property e:rniz-qjw4 t:meta.view v:id=rniz-qjw4 v:category=Labor v:attributionLink=http://labor.illinois.gov/ v:averageRating=0 v:name="IDOL 2014 Registered Day and Temporary Labor Agencies" v:attribution="Illinois Department of Labor"

property e:rniz-qjw4 t:meta.view.license v:name="Public Domain"

property e:rniz-qjw4 t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:rniz-qjw4 t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| company                                        | address                        | city          | state | zip_code | type          | 
| ============================================== | ============================== | ============= | ===== | ======== | ============= | 
| Clearstaff, Inc.                               | 718 - A West Irving Park Rd    | Bensenville   | IL    | 60106    | Office/Branch | 
| Roth Staffing Companies, L.P.                  | 333 City Blvd. West, Suite 100 | Orange        | CA    | 92868    | Corporate     | 
| Manpower US Inc.                               | 1678 S. Galena Ave., Ste. C100 | Dixon         | IL    | 61021    | Office/Branch | 
| Real Time Staffing Services, Inc./Selectremedy | 1789 Norwood Ave.              | Itasca        | IL    | 60143    | Office/Branch | 
| Kelly Services                                 | 2025 Windsor Dr.               | Oak Brook     | IL    | 60523    | Office/Branch | 
| Peoplelink Staffing Solutions, LLC             | 323 Front St.                  | Mc Henry      | IL    | 60050    | Office/Branch | 
| Accurate Personnel, LLC                        | 822 S. Buffalo Grove Rd        | Buffalo Grove | IL    | 60089    | Office/Branch | 
| Real Time Staffing Services, Inc./Selectremedy | 1005 101St Street, Suite A     | Lemont        | IL    | 60439    | Office/Branch | 
| Surestaff, Inc.                                | 14142 S. Cicero Ave.           | Crestwood     | IL    | 60445    | Office/Branch | 
| Associated Labor Corp Of America               | 1622 S. Blue Island            | Chicago       | IL    | 60608    | Office/Branch | 
```