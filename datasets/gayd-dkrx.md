# State Polling Locations2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-polling-locations2014) |
| Metadata | [Link](https://data.ct.gov/api/views/gayd-dkrx) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/gayd-dkrx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/gayd-dkrx/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | gayd-dkrx |
| Name | State Polling Locations2014 |
| Category | Government |
| Tags | stamford, ct, election, voting, state polling locations |
| Created | 2014-11-13T21:37:02Z |
| Publication Date | 2014-11-13T21:39:32Z |

## Description

City of Stamford, CT State Polling Locations for 2014.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag  | statepollingdistrictid | StatePollingDistrictID | text      | number      |
| Yes      | series tag  | statepollinglocation   | StatePollingLocation   | text      | text        |
| No       |             | fullsiteaddress        | FullSiteAddress        | text      | text        |
| Yes      | series tag  | sitenotes              | SiteNotes              | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = fullsiteaddress
```

## Data Commands

```ls
series e:gayd-dkrx d:2014-01-01T00:00:00.000Z t:statepollinglocation="Our Lady Star of the Sea" t:statepollingdistrictid=1 m:row_number.gayd-dkrx=1

series e:gayd-dkrx d:2014-01-01T00:00:00.000Z t:sitenotes="Frank Street Entrance" t:statepollinglocation="Domus (Old Rogers School)" t:statepollingdistrictid=2 m:row_number.gayd-dkrx=2

series e:gayd-dkrx d:2014-01-01T00:00:00.000Z t:sitenotes="George Street Entrance" t:statepollinglocation="K. T. Murphy School (rear)" t:statepollingdistrictid=3 m:row_number.gayd-dkrx=3
```

## Meta Commands

```ls
metric m:row_number.gayd-dkrx p:long l:"Row Number"

entity e:gayd-dkrx l:"State Polling Locations2014" t:url=https://data.ct.gov/api/views/gayd-dkrx

property e:gayd-dkrx t:meta.view v:id=gayd-dkrx v:category=Government v:averageRating=0 v:name="State Polling Locations2014"

property e:gayd-dkrx t:meta.view.owner v:id=d2jw-b5qp v:screenName="City of Stamford" v:displayName="City of Stamford"

property e:gayd-dkrx t:meta.view.tableauthor v:id=d2jw-b5qp v:screenName="City of Stamford" v:roleName=publisher v:displayName="City of Stamford"
```

## Top Records

```ls
| statepollingdistrictid | statepollinglocation         | fullsiteaddress        | sitenotes                  | 
| ====================== | ============================ | ====================== | ========================== | 
| 1                      | Our Lady Star of the Sea     | 1170 Shippan Av        |                            | 
| 2                      | Domus (Old Rogers School)    | 83 Lockwood Av         | Frank Street Entrance      | 
| 3                      | K. T. Murphy School (rear)   | 19 Horton St           | George Street Entrance     | 
| 4                      | Julia A. Stark School (rear) | 398 Glenbrook Rd       | Oscar Street Entrance Only | 
| 5                      | Stamford High School (rear)  | 55 Strawberry Hill Av  | Hillandale Avenue Entrance | 
| 6                      | Agudath Sholom               | 301 Strawberry Hill Av |                            | 
| 7                      | First Presbyterian Church    | 1101 Bedford St        |                            | 
| 8                      | Westover School              | 412 Stillwater Av      |                            | 
| 9                      | Neighbors Link               | 75 Selleck St          |                            | 
| 10                     | Westover School              | 412 Stillwater Av      |                            | 
```