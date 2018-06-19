# SFO Gate and Stand Assignment Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfo-gate-and-stand-assignment-information) |
| Metadata | [Link](https://data.sfgov.org/api/views/chfu-j7tc) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/chfu-j7tc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/chfu-j7tc/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | chfu-j7tc |
| Name | SFO Gate and Stand Assignment Information |
| Category | Transportation |
| Tags | sfo, airport, flight |
| Created | 2015-12-01T16:20:14Z |
| Publication Date | 2017-03-10T16:54:19Z |

## Description

This data provides information related to actual departure and arrival time of all airline flights arriving and departing out of assigned gates and stands at San Francisco International Airport.  Additional remarks for delayed or cancelled flight operations are included in this dataset. Airport finance and operations collects this data for statistical and billing purposes. The data starts 1/1/2015 and is updated monthly.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | time        | time          | TIME          | calendar_date | calendar_date |
| Yes      | series tag  | airline       | AIRLINE       | text          | text          |
| Yes      | series tag  | flight_number | FLIGHT_NUMBER | text          | text          |
| Yes      | series tag  | transaction   | TRANSACTION   | text          | text          |
| Yes      | series tag  | terminal      | TERMINAL      | text          | text          |
| Yes      | series tag  | gate          | GATE          | text          | text          |
| Yes      | series tag  | remark        | REMARK        | text          | text          |
```

## Time Field

```ls
Value = time
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:chfu-j7tc d:2015-01-01T00:00:00.000Z t:terminal=3 t:transaction=ARR t:flight_number=UA263 t:airline="United Airlines" t:gate=75 m:row_number.chfu-j7tc=1

series e:chfu-j7tc d:2015-01-01T00:01:00.000Z t:terminal=2 t:transaction=ARR t:flight_number=AA243 t:airline="American Airlines" t:gate=57 m:row_number.chfu-j7tc=2

series e:chfu-j7tc d:2015-01-01T00:05:00.000Z t:terminal=I t:transaction=DEP t:flight_number=SQ1 t:airline="Singapore Airlines" t:gate=G96 m:row_number.chfu-j7tc=3
```

## Meta Commands

```ls
metric m:row_number.chfu-j7tc p:long l:"Row Number"

entity e:chfu-j7tc l:"SFO Gate and Stand Assignment Information" t:url=https://data.sfgov.org/api/views/chfu-j7tc

property e:chfu-j7tc t:meta.view v:id=chfu-j7tc v:category=Transportation v:averageRating=0 v:name="SFO Gate and Stand Assignment Information"

property e:chfu-j7tc t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:chfu-j7tc t:meta.view.owner v:id=h9yb-8z9n v:screenName="Thant Hein" v:displayName="Thant Hein"

property e:chfu-j7tc t:meta.view.tableauthor v:id=h9yb-8z9n v:screenName="Thant Hein" v:roleName=editor v:displayName="Thant Hein"
```

## Top Records

```ls
| time                | airline            | flight_number | transaction | terminal | gate | remark | 
| =================== | ================== | ============= | =========== | ======== | ==== | ====== | 
| 2015-01-01T00:00:00 | United Airlines    | UA263         | ARR         | 3        | 75   |        | 
| 2015-01-01T00:01:00 | American Airlines  | AA243         | ARR         | 2        | 57   |        | 
| 2015-01-01T00:05:00 | Singapore Airlines | SQ1           | DEP         | I        | G96  |        | 
| 2015-01-01T00:18:00 | US Airways         | US840         | DEP         | 1        | 26   |        | 
| 2015-01-01T00:19:00 | American Airlines  | AA1112        | DEP         | 2        | 56B  |        | 
| 2015-01-01T00:20:00 | Delta Airlines     | DL806         | DEP         | 1        | 40   |        | 
| 2015-01-01T00:27:00 | EVA Airways        | BR17          | DEP         | I        | G99  |        | 
| 2015-01-01T00:32:00 | Avianca            | AV561         | DEP         | I        | A4   |        | 
| 2015-01-01T00:33:00 | China Airlines     | CI3           | DEP         | I        | A9   |        | 
| 2015-01-01T00:35:00 | AeroMexico         | AM665         | DEP         | I        | A1B  |        | 
```