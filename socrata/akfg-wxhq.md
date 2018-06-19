# IDOL 2015 Registered Day and Temporary Labor Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idol-2015-registered-day-and-temporary-labor-agencies-e7a78) |
| Metadata | [Link](https://data.illinois.gov/api/views/akfg-wxhq) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/akfg-wxhq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/akfg-wxhq/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | akfg-wxhq |
| Name | IDOL 2015 Registered Day and Temporary Labor Agencies |
| Attribution | Illinois Department of Labor |
| Category | Labor |
| Tags | labor, dtlsa, 820 ilcs 175, jobs, work |
| Created | 2015-02-25T17:34:43Z |
| Publication Date | 2015-11-30T15:40:04Z |

## Description

This is the list of current and approved Day and Temporary Labor Agencies, under the Illinois Day and Temporary Labor Services Act, 820 ILCS 175.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| Yes      | series tag  | company       | Company       | text      | text        |
| Yes      | series tag  | dba           | DBA           | text      | text        |
| Yes      | series tag  | location_type | Location Type | text      | text        |
| No       |             | address       | Address       | text      | text        |
| Yes      | series tag  | city          | City          | text      | text        |
| Yes      | series tag  | state         | State         | text      | text        |
| Yes      | series tag  | zip_code      | ZIP Code      | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:akfg-wxhq d:2015-01-01T00:00:00.000Z t:location_type=Office/Branch t:zip_code=61554 t:dba="Advanced Employment Services, Inc." t:company="Advance Services, Inc." t:state=IL t:city=Pekin m:row_number.akfg-wxhq=1

series e:akfg-wxhq d:2015-01-01T00:00:00.000Z t:location_type=Office/Branch t:zip_code=60015 t:dba="Aerotek Of Marylend, Inc." t:company="Aerotek, Inc." t:state=IL t:city=Deerfield m:row_number.akfg-wxhq=2

series e:akfg-wxhq d:2015-01-01T00:00:00.000Z t:location_type=Corporate t:zip_code=60949 t:company="Ag Temps, LLC" t:state=IL t:city=Ludlow m:row_number.akfg-wxhq=3
```

## Meta Commands

```ls
metric m:row_number.akfg-wxhq p:long l:"Row Number"

entity e:akfg-wxhq l:"IDOL 2015 Registered Day and Temporary Labor Agencies" t:attribution="Illinois Department of Labor" t:url=https://data.illinois.gov/api/views/akfg-wxhq

property e:akfg-wxhq t:meta.view v:id=akfg-wxhq v:category=Labor v:attributionLink=http://labor.illinois.gov/ v:averageRating=0 v:name="IDOL 2015 Registered Day and Temporary Labor Agencies" v:attribution="Illinois Department of Labor"

property e:akfg-wxhq t:meta.view.license v:name="Public Domain"

property e:akfg-wxhq t:meta.view.owner v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:displayName="IL Department of Labor"

property e:akfg-wxhq t:meta.view.tableauthor v:id=qz2n-kjc9 v:screenName="IL Department of Labor" v:roleName=publisher v:displayName="IL Department of Labor"
```

## Top Records

```ls
| company                | dba                                | location_type | address                         | city             | state | zip_code | 
| ====================== | ================================== | ============= | =============================== | ================ | ===== | ======== | 
| Advance Services, Inc. | Advanced Employment Services, Inc. | Office/Branch | 18356 Route 9                   | Pekin            | IL    | 61554    | 
| Aerotek, Inc.          | Aerotek Of Marylend, Inc.          | Office/Branch | Nine Parkway North, Ste. 100E   | Deerfield        | IL    | 60015    | 
| Ag Temps, LLC          |                                    | Corporate     | 100 W. Thomas, Suite B          | Ludlow           | IL    | 60949    | 
| Agente Staffing, Inc   |                                    | Corporate     | 750 Almar Pkwy., Suite 203      | Bourbonnais      | IL    | 60914    | 
| Anchor Staffing, Inc.  | Pyramid Staffing, Inc              | Corporate     | 39209 W Six Mile Rd, Suite 250  | Livonia          | MI    | 48152    | 
| ASG Staffing, Inc.     |                                    | Office/Branch | 546 E. North Ave.               | Glendale Heights | IL    | 60139    | 
| ASG Staffing, Inc.     |                                    | Office/Branch | 1200 Orchard Gateway Blvd.      | North Aurora     | IL    | 60542    | 
| CFA, Inc.              | CFA Staffing, Inc.                 | Corporate     | 977 State Road 46 East, Suite C | Batesville       | IN    | 47006    | 
| Clearstaff, Inc.       |                                    | Corporate     | 7501 S. Lemont Road, Suite 220  | Woodridge        | IL    | 60517    | 
| Cortech LLC            | Cortech International, LLC         | Corporate     | 10 Glenlake Pkwy., Suite 800    | Atlanta          | GA    | 30328    | 
```