# Neighborhood Health Clinics - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/neighborhood-health-clinics-historical-76c5d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/mw69-m6xi) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/mw69-m6xi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/mw69-m6xi/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | mw69-m6xi |
| Name | Neighborhood Health Clinics - Historical |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | facilities, gis, historical |
| Created | 2010-12-22T21:27:16Z |
| Publication Date | 2013-07-23T19:20:30Z |

## Description

Former neighborhood health clinic locations, hours of operation and contact information. These clinics were closed or transferred to private management in July 2012.  See https://data.cityofchicago.org/d/kcki-hnch for current public health clinics.

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | site_name          | SITE NAME          | text      | text        |
| Yes      | series tag  | hours_of_operation | HOURS OF OPERATION | text      | text        |
| No       |             | address            | ADDRESS            | text      | text        |
| Yes      | series tag  | city               | CITY               | text      | text        |
| Yes      | series tag  | state              | STATE              | text      | text        |
| Yes      | series tag  | zip                | ZIP                | text      | text        |
| Yes      | series tag  | phone              | PHONE              | text      | text        |
| Yes      | series tag  | website            | WEBSITE            | url       | url         |
| Yes      | series tag  | services           | SERVICES           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:mw69-m6xi d:2011-01-04T07:14:52.000Z t:zip=60628 t:services="Adults, Family Case Management, Medication Assistance" t:phone=312-747-9500 t:website=http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html t:hours_of_operation="Mon, Wed, Fri: 8:00 am ? 4:00 pm; Tue, and Thurs: 9:00 am - 5:00pm" t:state=IL t:site_name="Roseland Neighborhood Health Clinic" t:city=Chicago m:row_number.mw69-m6xi=1

series e:mw69-m6xi d:2011-01-04T07:14:52.000Z t:zip=60621 t:services="Adults, Children, Family Case Management, Medication Assistance, Pregnancy Testing, Pregnant Women, Women seeking Birth Control" t:phone=312-747-7831 t:website=http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html t:hours_of_operation="Mon, Wed, Fri: 8:00 am ? 4:00 pm; Tue, and Thurs: 10:00 am - 6:00pm" t:state=IL t:site_name="Englewood Neighborhood Health Clinic" t:city=Chicago m:row_number.mw69-m6xi=2

series e:mw69-m6xi d:2011-01-04T07:14:52.000Z t:zip=60640 t:services="Adult, Children, Family Case Management, Immigration Physicals, Medication Assistance, Pregnancy Testing, Pregnant Women, Refugee, Women seeking Birth Control" t:phone=312-744-1938 t:website=http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html t:hours_of_operation="Mon, Wed, Fri: 8:00 am ? 4:00 pm; Tue, and Thurs: 10:00 am - 6:00pm" t:state=IL t:site_name="Uptown Neighborhood Health Center" t:city=Chicago m:row_number.mw69-m6xi=3
```

## Meta Commands

```ls
metric m:row_number.mw69-m6xi p:long l:"Row Number"

entity e:mw69-m6xi l:"Neighborhood Health Clinics - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/mw69-m6xi

property e:mw69-m6xi t:meta.view v:id=mw69-m6xi v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Neighborhood Health Clinics - Historical" v:attribution="City of Chicago"

property e:mw69-m6xi t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:mw69-m6xi t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | site_name                                     | hours_of_operation                                                  | address              | city    | state | zip   | phone        | website                                                                                                        | services                                                                                                                                                       | 
| =========== | ============================================= | =================================================================== | ==================== | ======= | ===== | ===== | ============ | ============================================================================================================== | ============================================================================================================================================================== | 
| 1294125292  | Roseland Neighborhood Health Clinic           | Mon, Wed, Fri: 8:00 am ? 4:00 pm; Tue, and Thurs: 9:00 am - 5:00pm  | 200 E. 115th St.     | Chicago | IL    | 60628 | 312-747-9500 | [http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html, null] | Adults, Family Case Management, Medication Assistance                                                                                                          | 
| 1294125292  | Englewood Neighborhood Health Clinic          | Mon, Wed, Fri: 8:00 am ? 4:00 pm; Tue, and Thurs: 10:00 am - 6:00pm | 641 W. 63rd St.      | Chicago | IL    | 60621 | 312-747-7831 | [http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html, null] | Adults, Children, Family Case Management, Medication Assistance, Pregnancy Testing, Pregnant Women, Women seeking Birth Control                                | 
| 1294125292  | Uptown Neighborhood Health Center             | Mon, Wed, Fri: 8:00 am ? 4:00 pm; Tue, and Thurs: 10:00 am - 6:00pm | 845 W. Wilson Ave.   | Chicago | IL    | 60640 | 312-744-1938 | [http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html, null] | Adult, Children, Family Case Management, Immigration Physicals, Medication Assistance, Pregnancy Testing, Pregnant Women, Refugee, Women seeking Birth Control | 
| 1294125292  | West Town Neighborhood Health Center          | Mon, Wed, Fri: 8:00 am ? 4:00 pm; Tue, and Thurs: 10:00 am - 6:00pm | 2418 W. Division St. | Chicago | IL    | 60622 | 312-744-0943 | [http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html, null] | Adult, Children, Family Case Management, Immigration Physicals, Medication Assistance, Pregnancy Testing, Pregnant Women, Women seeking Birth Control          | 
| 1294125292  | Lower West Neighborhood Health Clinic         | Mon - Fri: 8:00 am ? 4:00 pm.                                       | 1713 S. Ashland Ave. | Chicago | IL    | 60608 | 312-746-5157 | [http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html, null] | Adults, Children, Family Case Management, Immigration Physicals, Medication Assistance, Pregnancy Testing, Pregnant Women, Women seeking Birth Control         | 
| 1294125292  | South Chicago Women & Children Health Center  | Mon - Fri: 8:00 am ? 4:00 pm.                                       | 2938 E. 89th St.     | Chicago | IL    | 60617 | 312-747-5285 | [http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html, null] | Children, Family Case Management, Pregnancy Testing, Pregnant Women, Women seeking Birth Control                                                               | 
| 1294125292  | South Lawndale Women & Children Health Center | Mon - Fri: 8:00 am ? 4:00 pm.                                       | 3059 W. 26th St.     | Chicago | IL    | 60623 | 312-747-0066 | [http://www.cityofchicago.org/city/en/depts/cdph/supp_info/clinical_health/community_healthclinics.html, null] | Children, Family Case Management, Pregnancy Testing, Pregnant Women, Women seeking Birth Control                                                               | 
```