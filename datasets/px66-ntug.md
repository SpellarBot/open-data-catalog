# City of Jackson 311 - Action Line

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-jackson-311-action-line) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/px66-ntug) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/px66-ntug/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/px66-ntug/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | px66-ntug |
| Name | City of Jackson 311 - Action Line |
| Attribution | City of Jackson - 311 Center |
| Category | City Services |
| Tags | 311, action line, mayor's action line, city services, jackson service center |
| Created | 2015-10-02T21:35:28Z |
| Publication Date | 2016-08-08T15:01:12Z |

## Description

The 311 Action Line is the single point of contact for all non-emergency City service requests.  This data provides information on the City's major departments (Public Works, Police, Fire, Parks and Recreation, and Planning and Development) and how the City responds to various citizen requests.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | numeric metric | requestid      | Request ID     | number        | number        |
| Yes      | time           | date_initiated | Date Initiated | calendar_date | calendar_date |
| Yes      | series tag     | description    | Description    | text          | text          |
| Yes      | series tag     | category       | Category       | text          | text          |
| Yes      | series tag     | submit_to      | Submit To      | text          | text          |
| Yes      | series tag     | dispatch_to    | Dispatch To    | text          | text          |
| Yes      | series tag     | incident_city  | Incident City  | text          | text          |
| Yes      | series tag     | incident_state | Incident State | text          | text          |
| Yes      | series tag     | zip_code       | Zip Code       | text          | text          |
| Yes      | numeric metric | ward           | Ward           | number        | text          |
| Yes      | series tag     | precinct       | Precinct       | text          | text          |
| Yes      | series tag     | status         | Status         | text          | text          |
| Yes      | series tag     | cancel         | Cancel         | text          | text          |
| No       |                | date_cancelled | Date Cancelled | calendar_date | calendar_date |
| Yes      | series tag     | cancel_reason  | Cancel Reason  | text          | text          |
```

## Time Field

```ls
Value = date_initiated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_cancelled
```

## Data Commands

```ls
series e:px66-ntug d:2012-05-17T00:00:00.000Z t:precinct=4 t:incident_state=MS t:category=POLICE t:zip_code=39211 t:status=CLOSED t:description="ABANDONED VEHICLE" t:cancel=N t:incident_city=JACKSON m:ward=1 m:requestid=32110

series e:px66-ntug d:2012-09-10T00:00:00.000Z t:precinct=4 t:submit_to="PAVEDSTREETS, SUBMIT" t:incident_state=MS t:category=STREETS t:zip_code=39211 t:status=CLOSED t:description="DRIVEWAY ENTRANCE REPAIR" t:cancel=N t:incident_city=JACKSON m:ward=1 m:requestid=44904

series e:px66-ntug d:2012-09-17T00:00:00.000Z t:submit_to=JFD_FIREMARSHAL, t:category=JFD t:status=CLOSED t:description="PAINT FIRE HYDRANT" t:cancel=N m:ward=4 m:requestid=45765
```

## Meta Commands

```ls
metric m:requestid p:integer l:"Request ID" d:"Cityworks System generated unique request ID number" t:dataTypeName=number

metric m:ward p:integer l:Ward d:"City of Jackson Ward to which the Service Request pertains" t:dataTypeName=number

entity e:px66-ntug l:"City of Jackson 311 - Action Line" t:attribution="City of Jackson - 311 Center" t:url=https://data.jacksonms.gov/api/views/px66-ntug

property e:px66-ntug t:meta.view v:id=px66-ntug v:category="City Services" v:attributionLink=http://www.jacksonms.gov v:averageRating=0 v:name="City of Jackson 311 - Action Line" v:attribution="City of Jackson - 311 Center"

property e:px66-ntug t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:px66-ntug t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| requestid | date_initiated      | description              | category  | submit_to             | dispatch_to    | incident_city | incident_state | zip_code | ward | precinct | status | cancel | date_cancelled | cancel_reason | 
| ========= | =================== | ======================== | ========= | ===================== | ============== | ============= | ============== | ======== | ==== | ======== | ====== | ====== | ============== | ============= | 
| 32110     | 2012-05-17T00:00:00 | ABANDONED VEHICLE        | POLICE    |                       |                | JACKSON       | MS             | 39211    | 1    | 4        | CLOSED | N      |                |               | 
| 44904     | 2012-09-10T00:00:00 | DRIVEWAY ENTRANCE REPAIR | STREETS   | PAVEDSTREETS, SUBMIT  |                | JACKSON       | MS             | 39211    | 1    | 4        | CLOSED | N      |                |               | 
| 45765     | 2012-09-17T00:00:00 | PAINT FIRE HYDRANT       | JFD       | JFD_FIREMARSHAL,      |                |               |                |          | 4    |          | CLOSED | N      |                |               | 
| 47384     | 2012-10-01T00:00:00 | MOSQUITO SPRAYING        | IFM       |                       |                | JACKSON       | MS             | 39209    | 5    | 2        | CLOSED | N      |                |               | 
| 48805     | 2012-10-11T00:00:00 | LITTER COMPLAINT         | SW        | SOLIDWASTE,           | HOLMES, ANDREA | JACKSON       | MS             | 39209    | 5    | 2        | CLOSED | N      |                |               | 
| 49423     | 2012-10-18T00:00:00 | LITTER COMPLAINT         | SW        | SOLIDWASTE,           |                | JACKSON       | MS             | 39212    | 6    | 1        | CLOSED | N      |                |               | 
| 49776     | 2012-10-23T00:00:00 | LITTER COMPLAINT         | SW        | SOLIDWASTE,           |                |               |                |          | 6    | 1        | CLOSED | N      |                |               | 
| 59182     | 2013-02-05T00:00:00 | LITTER COMPLAINT         | SW        | SOLIDWASTE,           | HOLMES, ANDREA | JACKSON       | MS             | 39206    | 1    | 4        | CLOSED | N      |                |               | 
| 60585     | 2013-02-14T00:00:00 | SMOKE DETECTOR REQUEST   | JFD       | JFD_FIRESAFETY,       |                | JACKSON       | MS             | 39213    |      |          | CLOSED | N      |                |               | 
| 63229     | 2013-03-11T00:00:00 | HEATING / COOLING        | CAREMAINT | SUPERVISOR, CAREMAINT | HVAC,          |               |                |          |      |          | CLOSED | N      |                |               | 
```