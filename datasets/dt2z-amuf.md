# Financial Empowerment Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/financial-empowerment-centers-d56fe) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/dt2z-amuf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/dt2z-amuf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/dt2z-amuf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | dt2z-amuf |
| Name | Financial Empowerment Centers |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | Business |
| Tags | big apps, bigapps, nycofe, socialservices, department of consumer affairs, empowerment, finance, financial empowerment, empowerment center, consumer, financial empowerment centers, city government... |
| Created | 2013-02-25T15:23:08Z |
| Publication Date | 2016-02-09T17:44:20Z |

## Description

This is a list of the Department of Consumer Affairs' Financial Empowerment Centers. It includes the Financial Empowerment Center site name/partners, site location, hours, and languages spoken.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | provider              | Provider              | text      | text        |
| Yes      | series tag  | host_organization     | Host Organization     | text      | text        |
| No       |             | site_location_address | Site Location Address | text      | text        |
| Yes      | series tag  | city                  | City                  | text      | text        |
| Yes      | series tag  | zip_code              | Zip Code              | text      | number      |
| Yes      | series tag  | days_open             | Days Open             | text      | text        |
| Yes      | series tag  | hours                 | Hours                 | text      | text        |
| Yes      | series tag  | language_s            | Language(s)           | text      | text        |
| Yes      | series tag  | telephone             | Telephone             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = site_location_address
```

## Data Commands

```ls
series e:dt2z-amuf d:2016-02-09T09:42:34.000Z t:language_s="English and Spanish" t:days_open="Tuesday, Wednesday & Saturday" t:zip_code=11237 t:host_organization="Brooklyn Cooperative Federal Credit Union" t:hours="Tues 9am-4pm, Wed 9am-5pm, Sat 10am-2pm" t:provider="Bedford Stuyvesant Restoration Corporation" t:telephone="(718) 636-6900" t:city=Brooklyn m:row_number.dt2z-amuf=1

series e:dt2z-amuf d:2016-02-09T09:42:34.000Z t:language_s="English, Spanish and Yoruba" t:days_open=Monday-Friday t:zip_code=11216 t:host_organization="Bedford Stuyvesant Restoration Corporation" t:hours="M-W & F 10am-6pm, Th 12pm-8pm" t:provider="Bedford Stuyvesant Restoration Corporation" t:telephone="(718) 636-6900" t:city=Brooklyn m:row_number.dt2z-amuf=2

series e:dt2z-amuf d:2016-02-09T09:42:34.000Z t:language_s="English, Spanish and Yoruba" t:days_open="Tuesday, Thursday and Saturday" t:zip_code=11238 t:host_organization="Brooklyn Central Library" t:hours="Tues 9am-4pm, Thursday 12pm-8pm, Saturday 10am-2pm" t:provider="Bedford Stuyvesant Restoration Corporation" t:telephone="(718) 636-6900" t:city=Brooklyn m:row_number.dt2z-amuf=3
```

## Meta Commands

```ls
metric m:row_number.dt2z-amuf p:long l:"Row Number"

entity e:dt2z-amuf l:"Financial Empowerment Centers" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/dt2z-amuf

property e:dt2z-amuf t:meta.view v:id=dt2z-amuf v:category=Business v:attributionLink=http://www.nyc.gov/html/ofe/html/find/find.shtml v:averageRating=0 v:name="Financial Empowerment Centers" v:attribution="Department of Consumer Affairs (DCA)"

property e:dt2z-amuf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:dt2z-amuf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | provider                                   | host_organization                                        | site_location_address                                | city      | zip_code | days_open                       | hours                                              | language_s                  | telephone      | 
| =========== | ========================================== | ======================================================== | ==================================================== | ========= | ======== | =============================== | ================================================== | =========================== | ============== | 
| 1455010954  | Bedford Stuyvesant Restoration Corporation | Brooklyn Cooperative Federal Credit Union                | 1474 Myrtle Avenue                                   | Brooklyn  | 11237    | Tuesday, Wednesday & Saturday   | Tues 9am-4pm, Wed 9am-5pm, Sat 10am-2pm            | English and Spanish         | (718) 636-6900 | 
| 1455010954  | Bedford Stuyvesant Restoration Corporation | Bedford Stuyvesant Restoration Corporation               | 1368 Fulton Street                                   | Brooklyn  | 11216    | Monday-Friday                   | M-W & F 10am-6pm, Th 12pm-8pm                      | English, Spanish and Yoruba | (718) 636-6900 | 
| 1455010954  | Bedford Stuyvesant Restoration Corporation | Brooklyn Central Library                                 | 10 Grand Army Plaza                                  | Brooklyn  | 11238    | Tuesday, Thursday and Saturday  | Tues 9am-4pm, Thursday 12pm-8pm, Saturday 10am-2pm | English, Spanish and Yoruba | (718) 636-6900 | 
| 1455010954  | Bedford Stuyvesant Restoration Corporation | Brownsville Multi-Service Family Health Center           | 592 Rockaway Avenue                                  | Brooklyn  | 11212    | Tuesday and Thursday            | Tues 10am-6pm, Th 12-8pm                           | English and Spanish         | (718) 636-6900 | 
| 1455010954  | Neighborhood Trust Financial Partners      | Neighborhood Housing Services of South Bronx             | 848 Concourse Village West                           | Bronx     | 10451    | Monday and Wednesday            | 9am-6pm                                            | English and Spanish         | (212) 927-5771 | 
| 1455010954  | Neighborhood Trust Financial Partners      | CAMBA                                                    | 885 Flatbush Ave, 2nd Floor                          | Brooklyn  | 11226    | Monday-Thursday                 | 9am-6pm                                            | English and Spanish         | (212) 927-5772 | 
| 1455010954  | Neighborhood Trust Financial Partners      | Northern Manhattan Improvement Corporation               | 45 Wadsworth Avenue                                  | Manhattan | 10033    | Monday-Friday                   | M, W-F 9am-6pm, Tuesday 11am-8pm                   | English and Spanish         | (212) 927-5773 | 
| 1455010954  | Neighborhood Trust Financial Partners      | Neighborhood Housing Services of New York City (Midtown) | 307 West 36th Street, 12th Floor (at 8th Ave)        | Manhattan | 10018    | M, T, Th, F                     | 9am-6pm                                            | English and Spanish         | (212) 927-5774 | 
| 1455010954  | Neighborhood Trust Financial Partners      | Midtown Community Court                                  | 314 West 54th Street                                 | Manhattan | 10019    | Wednesday, Thursday, and Friday | W, TH 9am - 6pm F 9am - 1pm                        | English and Spanish         | (212) 927-5775 | 
| 1455010954  | Neighborhood Trust Financial Partners      | Lower East Side People's Federal Credit Union            | 2052 Adam Clayton Powell Jr. Blvd New York, NY 10027 | Manhattan | 10027    | Monday                          | 9am-5pm                                            | English and Spanish         | (212) 927-5776 | 
```