# New York City Locations Providing Seasonal Flu Vaccinations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-locations-providing-seasonal-flu-vaccinations-5c001) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w9ei-idxz) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w9ei-idxz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w9ei-idxz/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w9ei-idxz |
| Name | New York City Locations Providing Seasonal Flu Vaccinations |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | flu, influenza, vaccine, location, health |
| Created | 2014-01-15T15:53:39Z |
| Publication Date | 2016-11-29T00:12:22Z |

## Description

Location and facility information for places in New York City providing seasonal flu vaccinations.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | objectid         | OBJECTID         | text      | text        |
| No       |             | a                | A                | number    | text        |
| Yes      | series tag  | service_category | Service Category | text      | text        |
| Yes      | series tag  | service_type     | Service Type     | text      | text        |
| Yes      | series tag  | walk_in          | Walk-in          | text      | text        |
| Yes      | series tag  | insurance        | Insurance        | text      | text        |
| Yes      | series tag  | children         | Children         | text      | text        |
| Yes      | series tag  | facility_name    | Facility Name    | text      | text        |
| No       |             | address          | Address          | text      | text        |
| Yes      | series tag  | city             | City             | text      | text        |
| Yes      | series tag  | borough          | Borough          | text      | text        |
| No       |             | latitude         | Latitude         | number    | number      |
| No       |             | longitude        | Longitude        | number    | number      |
| Yes      | series tag  | zip_code         | ZIP Code         | text      | text        |
| Yes      | series tag  | phone            | Phone            | text      | text        |
| Yes      | series tag  | website          | Website          | url       | url         |
| Yes      | series tag  | monday           | Monday           | text      | text        |
| Yes      | series tag  | tuesday          | Tuesday          | text      | text        |
| Yes      | series tag  | wednesday        | Wednesday        | text      | text        |
| Yes      | series tag  | thursday         | Thursday         | text      | text        |
| Yes      | series tag  | friday           | Friday           | text      | text        |
| Yes      | series tag  | saturday         | Saturday         | text      | text        |
| Yes      | series tag  | sunday           | Sunday           | text      | text        |
| Yes      | series tag  | more_information | More Information | text      | text        |
| Yes      | series tag  | dohmh_website    | DOHMH Website    | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = a,address,latitude,longitude
```

## Data Commands

```ls
series e:w9ei-idxz d:2016-11-29T00:09:53.000Z t:insurance=Yes t:phone=212-425-8460 t:walk_in=Yes t:more_information="Call location for hours" t:service_category=Vaccines t:facility_name="Duane Reade" t:zip_code=10006 t:website=https://www.walgreens.com/topic/duane-reade/duane-reade.jsp t:service_type="Flu Vaccine (Influenza)" t:dohmh_website=http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page t:children=No t:borough=Manhattan t:objectid=1 t:city="NEW YORK" m:row_number.w9ei-idxz=1

series e:w9ei-idxz d:2016-11-29T00:09:53.000Z t:insurance=Yes t:phone=212-571-4511 t:walk_in=Yes t:more_information="Call location for hours" t:service_category=Vaccines t:facility_name="Duane Reade" t:zip_code=10007 t:website=https://www.walgreens.com/topic/duane-reade/duane-reade.jsp t:service_type="Flu Vaccine (Influenza)" t:dohmh_website=http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page t:children=No t:borough=Manhattan t:objectid=2 t:city="NEW YORK" m:row_number.w9ei-idxz=2

series e:w9ei-idxz d:2016-11-29T00:09:53.000Z t:insurance=Yes t:phone=212-213-9730 t:walk_in=Yes t:more_information="Call location for hours" t:service_category=Vaccines t:facility_name="Duane Reade" t:zip_code=10016 t:website=https://www.walgreens.com/topic/duane-reade/duane-reade.jsp t:service_type="Flu Vaccine (Influenza)" t:dohmh_website=http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page t:children=No t:borough=Manhattan t:objectid=3 t:city="NEW YORK" m:row_number.w9ei-idxz=3
```

## Meta Commands

```ls
metric m:row_number.w9ei-idxz p:long l:"Row Number"

entity e:w9ei-idxz l:"New York City Locations Providing Seasonal Flu Vaccinations" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/w9ei-idxz

property e:w9ei-idxz t:meta.view v:id=w9ei-idxz v:category=Health v:averageRating=0 v:name="New York City Locations Providing Seasonal Flu Vaccinations" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:w9ei-idxz t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:w9ei-idxz t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | objectid | a   | service_category | service_type            | walk_in | insurance | children | facility_name     | address              | city      | borough   | latitude           | longitude           | zip_code | phone          | website                                                             | monday | tuesday | wednesday | thursday | friday | saturday | sunday | more_information        | dohmh_website                                                               | 
| =========== | ======== | === | ================ | ======================= | ======= | ========= | ======== | ================= | ==================== | ========= | ========= | ================== | =================== | ======== | ============== | =================================================================== | ====== | ======= | ========= | ======== | ====== | ======== | ====== | ======================= | =========================================================================== | 
| 1480378193  | 1        | 1   | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Duane Reade       | 37 BROADWAY          | NEW YORK  | Manhattan | 40.70619086        | -74.013032219999999 | 10006    | 212-425-8460   | [https://www.walgreens.com/topic/duane-reade/duane-reade.jsp, null] |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 2        | 2   | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Duane Reade       | 250 BROADWAY         | NEW YORK  | Manhattan | 40.712791080000002 | -74.007474849999994 | 10007    | 212-571-4511   | [https://www.walgreens.com/topic/duane-reade/duane-reade.jsp, null] |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 3        | 3   | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Duane Reade       | 401 PARK AVE S       | NEW YORK  | Manhattan | 40.743112089999997 | -73.984114329999997 | 10016    | 212-213-9730   | [https://www.walgreens.com/topic/duane-reade/duane-reade.jsp, null] |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 4        | 301 | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Rite Aid Pharmacy | 2833 Broadway        | Manhattan | Manhattan | 40.803952299999999 | -73.967018679999995 | 10025    | (212) 663-3135 | [https://www.riteaid.com/, null]                                    |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 5        | 4   | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Duane Reade       | 1430 BROADWAY        | NEW YORK  | Manhattan | 40.754009709999998 | -73.986926729999993 | 10018    | 212-768-0201   | [https://www.walgreens.com/topic/duane-reade/duane-reade.jsp, null] |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 6        | 201 | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Duane Reade       | 245 1st Ave.         | NEW YORK  | Manhattan | 40.73169291        | -73.982374320000005 | 10003    | 212-529-0091   | [https://www.walgreens.com/topic/duane-reade/duane-reade.jsp, null] |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 7        | 302 | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Rite Aid Pharmacy | 3823 Nostrand Avenue | Brooklyn  | Brooklyn  | 40.590569270000003 | -73.93994155        | 11235    | (718) 743-8933 | [https://www.riteaid.com/, null]                                    |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 8        | 5   | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Duane Reade       | 485 LEXINGTON AVE    | NEW YORK  | Manhattan | 40.754231160000003 | -73.973974299999995 | 10017    | 212-682-5338   | [https://www.walgreens.com/topic/duane-reade/duane-reade.jsp, null] |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 9        | 202 | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Duane Reade       | 300 E 23rd St.       | NEW YORK  | Manhattan | 40.73774487        | -73.980590960000001 | 10010    | 212-677-2014   | [https://www.walgreens.com/topic/duane-reade/duane-reade.jsp, null] |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
| 1480378193  | 10       | 303 | Vaccines         | Flu Vaccine (Influenza) | Yes     | Yes       | No       | Rite Aid Pharmacy | 741 Columbus Avenue  | Manhattan | Manhattan | 40.792940090000002 | -73.967458829999998 | 10025    | (212) 316-0436 | [https://www.riteaid.com/, null]                                    |        |         |           |          |        |          |        | Call location for hours | [http://www1.nyc.gov/site/doh/health/health-topics/flu-seasonal.page, null] | 
```