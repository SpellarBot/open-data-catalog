# Transmission Facilities Application Status & Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/transmission-facilities-application-status-location-5a549) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/j2i5-vax9) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/j2i5-vax9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/j2i5-vax9/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | j2i5-vax9 |
| Name | Transmission Facilities Application Status & Location |
| Attribution | Montgomery County, MD Government |
| Category | Community/Recreation |
| Tags | cable, application, location |
| Created | 2012-08-08T20:39:32Z |
| Publication Date | 2015-07-20T19:08:24Z |

## Description

Information on all transmission facility applications (new tower or attachments) filed with the Montgomery County Cable Office for telecommunications and radio & TV transmission sites, including the location of the tower and the disposition of the application.  This dataset will be updated on a quarterly basis.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | applicationnumber | ApplicationNumber | text          | text          |
| Yes      | series tag  | carriername       | CarrierName       | text          | text          |
| Yes      | series tag  | description       | Description       | text          | text          |
| Yes      | series tag  | sitename          | SiteName          | text          | text          |
| Yes      | series tag  | propertynumber    | PropertyNumber    | text          | text          |
| Yes      | series tag  | propertystreet    | PropertyStreet    | text          | text          |
| Yes      | series tag  | propertycity      | PropertyCity      | text          | text          |
| Yes      | series tag  | zone              | Zone              | text          | text          |
| Yes      | series tag  | propertyowner     | PropertyOwner     | text          | text          |
| Yes      | time        | received          | Received          | calendar_date | calendar_date |
| Yes      | series tag  | action            | Action            | text          | text          |
| No       |             | actiondate        | ActionDate        | calendar_date | calendar_date |
| No       |             | latitude          | Latitude          | number        | number        |
| No       |             | longitude         | Longitude         | number        | number        |
| No       |             | dms_latitude      | DMS_Latitude      | number        | text          |
| No       |             | dms_longitude     | DMS_Longitude     | number        | text          |
| Yes      | series tag  | structure         | Structure         | text          | text          |
```

## Time Field

```ls
Value = received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = actiondate,latitude,longitude,dms_latitude,dms_longitude
```

## Data Commands

```ls
series e:j2i5-vax9 d:2015-07-20T12:06:30.000Z t:structure=Tower t:sitename="PEPCO #106-N" t:propertystreet="East Village Ave @ Doubleland Rd" t:zone=R-200 t:propertycity=Gaithersburg t:propertyowner=PEPCO m:row_number.j2i5-vax9=1

series e:j2i5-vax9 d:1996-07-02T00:00:00.000Z t:propertynumber=7806-A t:structure="Water Tank" t:carriername="APC/Sprint Spectrum" t:sitename="Cabin John Water Tank" t:description=Colocation t:action="For Info Only" t:propertystreet="Tomlinson Ave" t:zone=R-90 t:applicationnumber="199607-info only" t:propertycity="Cabin John" t:propertyowner=WSSC m:row_number.j2i5-vax9=2

series e:j2i5-vax9 d:1996-07-02T00:00:00.000Z t:propertynumber=8505 t:structure="Water Tank" t:carriername="APC/Sprint Spectrum" t:sitename="Falls Rd Tank" t:description=Colocation t:action="For Info Only" t:propertystreet="Aqueduct Rd" t:zone=R-90 t:applicationnumber="199607-info only" t:propertycity=Potomac t:propertyowner=WSSC m:row_number.j2i5-vax9=3
```

## Meta Commands

```ls
metric m:row_number.j2i5-vax9 p:long l:"Row Number"

entity e:j2i5-vax9 l:"Transmission Facilities Application Status & Location" t:attribution="Montgomery County, MD Government" t:url=https://data.montgomerycountymd.gov/api/views/j2i5-vax9

property e:j2i5-vax9 t:meta.view v:id=j2i5-vax9 v:category=Community/Recreation v:averageRating=0 v:name="Transmission Facilities Application Status & Location" v:attribution="Montgomery County, MD Government"

property e:j2i5-vax9 t:meta.view.license v:name="Public Domain"

property e:j2i5-vax9 t:meta.view.owner v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:displayName=Brian

property e:j2i5-vax9 t:meta.view.tableauthor v:id=rykt-6e5x v:profileImageUrlMedium=/api/users/rykt-6e5x/profile_images/THUMB v:profileImageUrlLarge=/api/users/rykt-6e5x/profile_images/LARGE v:screenName=Brian v:profileImageUrlSmall=/api/users/rykt-6e5x/profile_images/TINY v:roleName=editor v:displayName=Brian
```

## Top Records

```ls
| applicationnumber | carriername            | description               | sitename                    | propertynumber | propertystreet                   | propertycity  | zone     | propertyowner      | received            | action        | actiondate          | latitude | longitude | dms_latitude     | dms_longitude      | structure  | 
| ================= | ====================== | ========================= | =========================== | ============== | ================================ | ============= | ======== | ================== | =================== | ============= | =================== | ======== | ========= | ================ | ================== | ========== | 
|                   |                        |                           | PEPCO #106-N                |                | East Village Ave @ Doubleland Rd | Gaithersburg  | R-200    | PEPCO              |                     |               |                     |          |           | 77.1686111111111 | 39.186111111111103 | Tower      | 
| 199607-info only  | APC/Sprint Spectrum    | Colocation                | Cabin John Water Tank       | 7806-A         | Tomlinson Ave                    | Cabin John    | R-90     | WSSC               | 1996-07-02T00:00:00 | For Info Only |                     |          |           | 77.159839        | 38.978222000000002 | Water Tank | 
| 199607-info only  | APC/Sprint Spectrum    | Colocation                | Falls Rd Tank               | 8505           | Aqueduct Rd                      | Potomac       | R-90     | WSSC               | 1996-07-02T00:00:00 | For Info Only |                     |          |           | 77.174403        | 39.059818999999997 | Water Tank | 
| 199608-004        | APC/Sprint Spectrum    | Existing Obsv. Tower Bldg | Public Svc Training Academy | 10025          | Darnestown Rd                    | Rockville     | R-90/TDR | Montgomery County  | 1996-07-18T00:00:00 | Recommended   | 1996-08-12T00:00:00 |          |           | 77.2077777777778 | 39.099166666666697 | Bldg       | 
| 199607-001        | Bell Atl. NYNEX Mobile | Existing water tank       | Woodside Water Tank         | 1945           | Seminary Place                   | Silver Spring | R-60     | WSSC               | 1996-07-19T00:00:00 | Recommended   | 1996-07-31T00:00:00 |          |           | 77.0422222222222 | 39.009722222222202 | Water Tank | 
| 199607-002        | Cellular One           | Existing water tank       | Wall Lane Water Tank        | 11400          | Woodglen Dr & Executive Blvd     | Rockville     | R-90     | WSSC               | 1996-07-22T00:00:00 | Recommended   | 1996-07-31T00:00:00 |          |           | 77.1141666666667 | 39.043333333333301 | Water Tank | 
| 199607-003        | Cellular One           | Existing water tank       | Bradley Water Tank #2       | 7005B          | Radnor Rd                        | Bethesda      | R-90     | WSSC               | 1996-07-22T00:00:00 | Recommended   | 1996-07-31T00:00:00 |          |           | 77.113742        | 38.980367000000001 | Water Tank | 
| 199607-005        | Bell Atl. NYNEX Mobile | New 180' monopole         | Sears Service Center        | 16401          | Shady Grove Rd                   | Gaithersburg  |          | Sears              | 1996-07-27T00:00:00 | Withdrawn     | 1996-09-01T00:00:00 |          |           | 0                | 0                  | Monopole   | 
| 199608-001        | AT&T Wireless          | New 110' AT&T monopole    | Silver Spring YMCA          | 9800           | Hastings Drive                   | Silver Spring | R-60     | Silver Spring YMCA | 1996-08-01T00:00:00 | Recommended   | 1996-10-22T00:00:00 |          |           | 77.0133333333333 | 39.015833333333298 | Monopole   | 
| 199607-004        | APC/Sprint Spectrum    | New 190' Sprint monopole  | Oakmont Monopole            | 16801          | Oakmont Avene                    | Gaithersburg  | I-1      | Douglas Dillard    | 1996-08-06T00:00:00 | Recommended   | 1996-09-19T00:00:00 |          |           | 77.1738888888889 | 39.1313888888889   | Monopole   | 
```