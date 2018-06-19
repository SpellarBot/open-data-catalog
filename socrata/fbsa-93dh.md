# Directory Of Zoning Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-zoning-details-464a5) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fbsa-93dh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fbsa-93dh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fbsa-93dh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fbsa-93dh |
| Name | Directory Of Zoning Details |
| Attribution | Department of City Planning (DCP) |
| Category | Housing & Development |
| Tags | dcp, city, planning, zone, dwelling, unit |
| Created | 2013-02-13T19:48:11Z |
| Publication Date | 2013-06-21T20:45:38Z |

## Description

Details about different zones and corresponding dwelling unit limit

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                           | Data Type | Render Type |
| ======== | =========== | ============================== | ============================== | ========= | =========== |
| No       | time        | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag  | zone                           | Zone                           | text      | text        |
| Yes      | series tag  | description                    | Description                    | text      | text        |
| Yes      | series tag  | maximumdwelling_units_per_acre | MaximumDwelling units per acre | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fbsa-93dh d:2013-02-13T11:48:13.000Z t:description="Single-family detached residences" t:maximumdwelling_units_per_acre="4 to 7" t:zone=R1 m:row_number.fbsa-93dh=1

series e:fbsa-93dh d:2013-02-13T11:48:13.000Z t:description="Single-family detached residences" t:maximumdwelling_units_per_acre="11 to 15" t:zone=R2 m:row_number.fbsa-93dh=2

series e:fbsa-93dh d:2013-02-13T11:48:13.000Z t:description="Two-family detached, semi-detached, 
and general residence districts" t:maximumdwelling_units_per_acre="26 to 42" t:zone=R3 m:row_number.fbsa-93dh=3
```

## Meta Commands

```ls
metric m:row_number.fbsa-93dh p:long l:"Row Number"

entity e:fbsa-93dh l:"Directory Of Zoning Details" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/fbsa-93dh

property e:fbsa-93dh t:meta.view v:id=fbsa-93dh v:category="Housing & Development" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/pub/conplan12_amended_vol2.pdf v:averageRating=0 v:name="Directory Of Zoning Details" v:attribution="Department of City Planning (DCP)"

property e:fbsa-93dh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fbsa-93dh t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | zone | description                                                                                             | maximumdwelling_units_per_acre | 
| =========== | ==== | ======================================================================================================= | ============================== | 
| 1360756093  | R1   | Single-family detached residences                                                                       | 4 to 7                         | 
| 1360756093  | R2   | Single-family detached residences                                                                       | 11 to 15                       | 
| 1360756093  | R3   | Two-family detached, semi-detached, and general residence districts                                     | 26 to 42                       | 
| 1360756093  | R4   | Two-family detached, semi-detached, and general residence districts                                     | 30 to 65                       | 
| 1360756093  | R5   | General residence districts (provides a transition between lower and higher density neighborhoods)      | 65 to 80                       | 
| 1360756093  | R6   | General residence districts (medium density housing between 3 and 12 stories)                           | 129 to 192                     | 
| 1360756093  | R7   | General residence districts (medium density apartment houses with good access to public transportation) | 192 to 322                     | 
| 1360756093  | R8   | General residence districts (high density residential districts)                                        | 258 to 427                     | 
| 1360756093  | R9   | General residence districts (high density residential districts)                                        | 444 to 495                     | 
| 1360756093  | R10  | General residence districts (highest density residential district)                                      | 551 to 700                     | 
```