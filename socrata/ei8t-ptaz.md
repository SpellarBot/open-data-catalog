# IDOL 2013 Registered Day and Temporary Labor Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2013-registered-day-and-temporary-labor-agencies-e3ef3) |
| Metadata | [Link](https://data.illinois.gov/api/views/ei8t-ptaz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ei8t-ptaz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ei8t-ptaz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ei8t-ptaz |
| Name | IDOL 2013 Registered Day and Temporary Labor Agencies |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | labor, dtlsa, 820 ilcs 175, jobs, work |
| Created | 2013-05-24T20:56:36Z |
| Publication Date | 2013-12-31T23:25:10Z |

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
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:ei8t-ptaz d:2013-01-01T00:00:00.000Z t:zip_code=60515 t:company="KELLY SERVICES" t:state=IL t:city="DOWNERS GROVE" m:row_number.ei8t-ptaz=1

series e:ei8t-ptaz d:2013-01-01T00:00:00.000Z t:zip_code=62208 t:company="KELLY SERVICES" t:state=IL t:city="FAIRVIEW HEIGHTS" m:row_number.ei8t-ptaz=2

series e:ei8t-ptaz d:2013-01-01T00:00:00.000Z t:zip_code=60123 t:company="METROSTAFF, INC." t:state=IL t:city=ELGIN m:row_number.ei8t-ptaz=3
```

## Meta Commands

```ls
metric m:row_number.ei8t-ptaz p:long l:"Row Number"

entity e:ei8t-ptaz l:"IDOL 2013 Registered Day and Temporary Labor Agencies" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/ei8t-ptaz

property e:ei8t-ptaz t:meta.view v:id=ei8t-ptaz v:category=Labor v:attributionLink=http://labor.illinois.gov/ v:averageRating=0 v:name="IDOL 2013 Registered Day and Temporary Labor Agencies" v:attribution="Illinois Department of Labor"

property e:ei8t-ptaz t:meta.view.license v:name="Public Domain"

property e:ei8t-ptaz t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:ei8t-ptaz t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| company                            | address                          | city             | state | zip_code | 
| ================================== | ================================ | ================ | ===== | ======== | 
| KELLY SERVICES                     | 2225 CURTISS ST.                 | DOWNERS GROVE    | IL    | 60515    | 
| KELLY SERVICES                     | 8 EXECUTIVE DR., SUITE 110       | FAIRVIEW HEIGHTS | IL    | 62208    | 
| METROSTAFF, INC.                   | 302 S MCLEAN BLVD.               | ELGIN            | IL    | 60123    | 
| KANE COUNTY PERSONNEL,INC/MANPOWER | 1415 CORPORATE BLVD              | AURORA           | IL    | 60502    | 
| MASTERSON PERSONNEL, INC.          | 505 HIGHWAY 169 NORTH, SUITE 700 | PLYMOUTH         | MN    | 55441    | 
| LABOR TEMPS II, LLC                | 3 N. SMITH STREET                | AURORA           | IL    | 60505    | 
| USCADEN CORPORATION/MANPOWER       | 3333 WARRENVILLE RD.             | LISLE            | IL    | 60532    | 
| RELIABLE STAFFING GROUP, INC.      | 14422 EDISON DR.                 | NEW LENOX        | IL    | 60451    | 
| ROCK RIVER TEMP./MANPOWER          | 50 W. DOUGLAS ST., #902          | FREEPORT         | IL    | 61032    | 
| ATLAS EMPLOYMENT SERVICES          | 9458 W. IRVING PARK RD.          | SCHILLER PARK    | IL    | 60176    | 
```