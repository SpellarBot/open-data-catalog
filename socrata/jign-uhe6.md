# Arches Organization Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arches-organization-information-a156d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jign-uhe6) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jign-uhe6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jign-uhe6/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jign-uhe6 |
| Name | Arches Organization Information |
| Attribution | Department of Probation (DOP) |
| Category | City Government |
| Tags | dop, probation, law, borough, address, locations, site, organization, arches |
| Created | 2013-02-12T16:55:32Z |
| Publication Date | 2013-06-21T20:05:36Z |

## Description

Contact details of Organizations determined eligible for Arches award.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | target_geographic_area | Target Geographic Area | text      | text        |
| Yes      | series tag  | organization_name      | Organization Name      | text      | text        |
| No       |             | site_address           | Address                | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = site_address
```

## Data Commands

```ls
series e:jign-uhe6 d:2013-02-12T08:55:33.000Z t:target_geographic_area="Bedford Stuyvesant" t:organization_name="Good Shepherd Services" m:row_number.jign-uhe6=1

series e:jign-uhe6 d:2013-02-12T08:55:33.000Z t:target_geographic_area="Bedford Stuyvesant" t:organization_name="Friends of Bedford, Inc" m:row_number.jign-uhe6=2

series e:jign-uhe6 d:2013-02-12T08:55:33.000Z t:target_geographic_area=Brownsville t:organization_name="Jewish Child Care Association" m:row_number.jign-uhe6=3
```

## Meta Commands

```ls
metric m:row_number.jign-uhe6 p:long l:"Row Number"

entity e:jign-uhe6 l:"Arches Organization  Information" t:attribution="Department of Probation (DOP)" t:url=https://data.cityofnewyork.us/api/views/jign-uhe6

property e:jign-uhe6 t:meta.view v:id=jign-uhe6 v:category="City Government" v:attributionLink=http://www.nyc.gov/html/prob/html/young_men/arches.shtml v:averageRating=0 v:name="Arches Organization  Information" v:attribution="Department of Probation (DOP)"

property e:jign-uhe6 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jign-uhe6 t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | target_geographic_area | organization_name                                                              | site_address                              | 
| =========== | ====================== | ============================================================================== | ========================================= | 
| 1360659333  | Bedford Stuyvesant     | Good Shepherd Services                                                         | 862 Park Avenue, Brooklyn, NY 11206       | 
| 1360659333  | Bedford Stuyvesant     | Friends of Bedford, Inc                                                        | 510 Gates Ave., Brooklyn, NY 11216        | 
| 1360659333  | Brownsville            | Jewish Child Care Association                                                  | 1555 Linden Blvd, Brooklyn, NY11212       | 
| 1360659333  | East New York          | Alpha School Center for Progressive Living                                     | 2400 Linden Blvd, Brooklyn, NU 11208      | 
| 1360659333  | Edenwald               | Fedcap Rehabilitation Services, Inc. (partnering with Bronx Clergy Roundtable) | Site address is being finalized           | 
| 1360659333  | Harlem                 | New York Mission Society                                                       | 646 Malcolm X Blvd, New York, NY 10037    | 
| 1360659333  | Harlem                 | Friends of Island Academy                                                      | 22 E 128th Street, New York, NY 10035     | 
| 1360659333  | Harlem                 | Exodus Transitional Community                                                  | 2271 Third Ave, New York, NY 10035        | 
| 1360659333  | Harlem                 | Harlem Commonwealth Council Inc                                                | 361 West 125th Street, New York, NY 10027 | 
| 1360659333  | Highbridge             | BronxWorks, Inc                                                                | 1130 Grand Concourse, Bronx, NY 10456     | 
```