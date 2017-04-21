# Fire Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-violations) |
| Metadata | [Link](https://data.sfgov.org/api/views/4zuq-2cbe) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4zuq-2cbe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4zuq-2cbe/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4zuq-2cbe |
| Name | Fire Violations |
| Category | Housing and Buildings |
| Created | 2015-12-21T18:52:58Z |
| Publication Date | 2016-02-05T01:03:55Z |

## Description

Information on Fire Violations issued by the Fire Department for a particular location. Key fields include Violation Number, Violation Type, Address, Fire Code Reference, Violation Date, Violation Status.

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | =========== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag  | violation_id               | Violation Id               | text          | text          |
| Yes      | series tag  | violation_number           | Violation Number           | text          | number        |
| Yes      | time        | violation_date             | Violation Date             | calendar_date | calendar_date |
| Yes      | series tag  | violation_item             | Violation Item             | text          | text          |
| Yes      | series tag  | violation_item_description | Violation Item Description | text          | text          |
| Yes      | series tag  | citation_number            | Citation Number            | text          | text          |
| Yes      | series tag  | corrective_action          | Corrective Action          | text          | text          |
| Yes      | series tag  | inspection_number          | Inspection Number          | text          | number        |
| No       |             | address                    | Address                    | text          | text          |
| Yes      | series tag  | zipcode                    | Zipcode                    | text          | text          |
| Yes      | series tag  | battalion                  | Battalion                  | text          | text          |
| Yes      | series tag  | station                    | Station Area               | text          | text          |
| Yes      | series tag  | bfp_district               | Fire Prevention District   | text          | text          |
| Yes      | series tag  | status                     | Status                     | text          | text          |
| No       |             | close_date                 | Close Date                 | calendar_date | calendar_date |
| Yes      | series tag  | supervisor_district        | Supervisor District        | text          | text          |
| Yes      | series tag  | neighborhood_district      | Neighborhood District      | text          | text          |
```

## Time Field

```ls
Value = violation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,close_date
```

## Data Commands

```ls
series e:4zuq-2cbe d:2007-08-27T00:00:00.000Z t:violation_item_description="fire systems certified" t:inspection_number=296051 t:violation_id=3460391 t:status=closed t:station=07 t:bfp_district=02S t:violation_number=3460 t:zipcode=94110 t:battalion=02 t:neighborhood_district=Mission t:corrective_action="correct - no permit" t:supervisor_district=9 t:violation_item=391 m:row_number.4zuq-2cbe=1

series e:4zuq-2cbe d:2016-07-25T00:00:00.000Z t:violation_item_description="permit / general" t:inspection_number=291201 t:violation_id=1799413PER01 t:status=open t:station=01 t:bfp_district=03N t:violation_number=17994 t:zipcode=94105 t:battalion=03 t:neighborhood_district="Financial District/South Beach" t:corrective_action="correct - no permit" t:supervisor_district=6 t:violation_item=13PER01 m:row_number.4zuq-2cbe=2

series e:4zuq-2cbe d:2016-11-30T00:00:00.000Z t:violation_item_description="extinguisher / required" t:inspection_number=297107 t:violation_id=1870213EXT15 t:status=abated t:station=44 t:bfp_district=10 t:violation_number=18702 t:zipcode=94134 t:battalion=10 t:neighborhood_district=Portola t:corrective_action="correct - no permit" t:supervisor_district=9 t:violation_item=13EXT15 m:row_number.4zuq-2cbe=3
```

## Meta Commands

```ls
metric m:row_number.4zuq-2cbe p:long l:"Row Number"

entity e:4zuq-2cbe l:"Fire Violations" t:url=https://data.sfgov.org/api/views/4zuq-2cbe

property e:4zuq-2cbe t:meta.view v:id=4zuq-2cbe v:category="Housing and Buildings" v:averageRating=0 v:name="Fire Violations"

property e:4zuq-2cbe t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4zuq-2cbe t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:4zuq-2cbe t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| violation_id | violation_number | violation_date      | violation_item | violation_item_description         | citation_number | corrective_action   | inspection_number | address                 | zipcode | battalion | station | bfp_district | status | close_date          | supervisor_district | neighborhood_district          | 
| ============ | ================ | =================== | ============== | ================================== | =============== | =================== | ================= | ======================= | ======= | ========= | ======= | ============ | ====== | =================== | =================== | ============================== | 
| 3460391      | 3460             | 2007-08-27T00:00:00 | 391            | fire systems certified             |                 | correct - no permit | 296051            | 2195 - 2199 Mission St  | 94110   | 02        | 07      | 02S          | closed | 2016-11-16T00:00:00 | 9                   | Mission                        | 
| 1799413PER01 | 17994            | 2016-07-25T00:00:00 | 13PER01        | permit / general                   |                 | correct - no permit | 291201            | 101 02nd St             | 94105   | 03        | 01      | 03N          | open   | 2016-07-27T02:02:37 | 6                   | Financial District/South Beach | 
| 1870213EXT15 | 18702            | 2016-11-30T00:00:00 | 13EXT15        | extinguisher / required            |                 | correct - no permit | 297107            | 3190 San Bruno Ave      | 94134   | 10        | 44      | 10           | abated | 2016-12-05T00:00:00 | 9                   | Portola                        | 
| 2844999      | 2844             | 2006-11-03T00:00:00 | 999            | other violations                   |                 |                     | 30008             | 635 Ellis St            | 94109   | 02        | 03      | 02N          | closed | 2007-11-08T00:00:00 | 6                   | Tenderloin                     | 
| 3648390      | 3648             | 2007-12-11T00:00:00 | 390            | fire alarms maintained             |                 | correct - no permit | 90679             | 935 Geary St            | 94109   | 04        | 03      | 04           | closed | 2011-07-25T00:00:00 | 6                   | Tenderloin                     | 
| 1612113EXT04 | 16121            | 2015-04-02T00:00:00 | 13EXT04        | extinguisher / service required    |                 | correct - no permit | 210785            | 1 Pier 2                | 94111   | 03        | 60      | 03S          | closed | 2015-04-17T00:00:00 | 3                   | Financial District/South Beach | 
| 3646181      | 3646             | 2007-12-06T00:00:00 | 181            | approved occupant load sign posted |                 | correct - no permit | 45661             | 2175 - 2185 Chestnut St | 94123   | 04        | 16      | 04           | closed | 2007-12-17T00:00:00 | 2                   | Marina                         | 
| 3102999      | 3102             | 2007-04-25T00:00:00 | 999            | other violations                   |                 |                     | 37021             | 3154 Fillmore St        | 94123   | 04        | 16      | 04           | closed | 2007-05-17T00:00:00 | 2                   | Marina                         | 
| 2314465      | 2314             | 2006-05-02T00:00:00 | 465            | fire haz not permitted in any occ  |                 |                     | 23524             | 3310 - 3316 Mission St  | 94110   | 06        | 32      | 06           | closed | 2006-05-16T00:00:00 | 9                   | Bernal Heights                 | 
| 847910SPR08  | 8479             | 2011-02-01T00:00:00 | 10SPR08        | sprinkler / 5-year service         |                 | correct - no permit | 111433            | 327 - 333 Grant Ave     | 94108   | 01        | 01      | 01W          | closed | 2011-02-28T00:00:00 | 3                   | Financial District/South Beach | 
```