# City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department

## Dataset

* [Dataset URL](https://data.seattle.gov/api/views/k3hs-aykd/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/city-of-seattle-wages-comparison-by-gender-discretionary-pay-titles-by-department-eafb4)
* Id = k3hs-aykd
* Name = City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department
* Attribution Link = http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-4-EEO-Final.pdf
* Category = City Business
* Tags = [wages, salary, salaries, job, classifications, government, gender, comparison by gender, gender wage study]
* Created = 2013-07-16T20:42:14Z
* Publication Date = 2013-07-16T20:48:20Z
* Rows Updated = 2013-07-16T20:42:29Z

## Description



## Columns

```ls
| Name                                       | Field Name                                 | Data Type | Render Type | Schema Type    | Included | 
| ========================================== | ========================================== | ========= | =========== | ============== | ======== | 
| updated_at                                 | :updated_at                                | meta_data | meta_data   | time           | Yes      | 
| DEPARTMENT                                 | department                                 | text      | text        | series tag     | Yes      | 
| DESCR                                      | descr                                      | text      | text        | series tag     | Yes      | 
| GENDER DESCR                               | gender_descr                               | text      | text        | series tag     | Yes      | 
| Admin Support # EE                         | admin_support_ee                           | number    | number      | numeric metric | Yes      | 
| Admin Support % Gender                     | admin_support_gender                       | percent   | percent     | numeric metric | Yes      | 
| Admin Support Avg Hrly                     | admin_support_avg_hrly                     | number    | number      | numeric metric | Yes      | 
| Admin Support Avg Yrs in Current Job       | admin_support_avg_yrs_in_current_job       | number    | number      | numeric metric | Yes      | 
| Officials/Admin # EE                       | officials_admin_ee                         | number    | number      | numeric metric | Yes      | 
| Officials/Admin % Gender                   | officials_admin_gender                     | percent   | percent     | numeric metric | Yes      | 
| Officials/Admin Avg Hrly                   | officials_admin_avg_hrly                   | number    | number      | numeric metric | Yes      | 
| Officials/Admin Avg Yrs in Current Job     | officials_admin_avg_yrs_in_current_job     | number    | number      | numeric metric | Yes      | 
| Para-Professionals # EE                    | para_professionals_ee                      | number    | number      | numeric metric | Yes      | 
| Para-Professionals % Gender                | para_professionals_gender                  | percent   | percent     | numeric metric | Yes      | 
| Para-Professionals Avg Hrly                | para_professionals_avg_hrly                | number    | number      | numeric metric | Yes      | 
| Para-Professionals Avg Yrs in Current Job  | para_professionals_avg_yrs_in_current_job  | number    | number      | numeric metric | Yes      | 
| Professionals # EE                         | professionals_ee                           | number    | number      | numeric metric | Yes      | 
| Professionals % Gender                     | professionals_gender                       | percent   | percent     | numeric metric | Yes      | 
| Professionals Avg Hrly                     | professionals_avg_hrly                     | number    | number      | numeric metric | Yes      | 
| Professionals Avg Yrs in Current Job       | professionals_avg_yrs_in_current_job       | number    | number      | numeric metric | Yes      | 
| Protected Services # EE                    | protected_services_ee                      | number    | number      | numeric metric | Yes      | 
| Protected Services % Gender                | protected_services_gender                  | percent   | percent     | numeric metric | Yes      | 
| Protected Services Avg Hrly                | protected_services_avg_hrly                | number    | number      | numeric metric | Yes      | 
| Protected Services Avg Yrs in Current Job  | protected_services_avg_yrs_in_current_job  | number    | number      | numeric metric | Yes      | 
| Service/Maintenance # EE                   | service_maintenance_ee                     | number    | number      | numeric metric | Yes      | 
| Service/Maintenance % Gender               | service_maintenance_gender                 | percent   | percent     | numeric metric | Yes      | 
| Service/Maintenance Avg Hrly               | service_maintenance_avg_hrly               | number    | number      | numeric metric | Yes      | 
| Service/Maintenance Avg Yrs in Current Job | service_maintenance_avg_yrs_in_current_job | number    | number      | numeric metric | Yes      | 
| Skilled Craft # EE                         | skilled_craft_ee                           | number    | number      | numeric metric | Yes      | 
| Skilled Craft % Gender                     | skilled_craft_gender                       | percent   | percent     | numeric metric | Yes      | 
| Skilled Craft Avg Hrly                     | skilled_craft_avg_hrly                     | number    | number      | numeric metric | Yes      | 
| Skilled Craft Avg Yrs in Current Job       | skilled_craft_avg_yrs_in_current_job       | number    | number      | numeric metric | Yes      | 
| Technicians # EE                           | technicians_ee                             | number    | number      | numeric metric | Yes      | 
| Technicians % Gender                       | technicians_gender                         | percent   | percent     | numeric metric | Yes      | 
| Technicians Avg Hrly                       | technicians_avg_hrly                       | number    | number      | numeric metric | Yes      | 
| Technicians Avg Yrs in Current Job         | technicians_avg_yrs_in_current_job         | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:gender_descr=Female t:department="Arts and Cultural Affairs" m:technicians_gender=0 m:service_maintenance_ee=1 m:professionals_avg_hrly=35 m:admin_support_avg_hrly=26.53 m:protected_services_ee=0 m:service_maintenance_avg_hrly=27.78 m:professionals_gender=79 m:service_maintenance_gender=33 m:technicians_ee=0 m:professionals_ee=15 m:skilled_craft_ee=0 m:para_professionals_ee=0 m:officials_admin_avg_hrly=49.97 m:officials_admin_ee=2 m:officials_admin_gender=67 m:admin_support_ee=2 m:admin_support_gender=100

series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:gender_descr=Male t:department="Arts and Cultural Affairs" m:technicians_gender=100 m:service_maintenance_ee=2 m:professionals_avg_hrly=32.64 m:protected_services_ee=0 m:service_maintenance_avg_hrly=20.73 m:professionals_gender=21 m:service_maintenance_gender=67 m:technicians_ee=1 m:professionals_ee=4 m:skilled_craft_ee=0 m:para_professionals_ee=0 m:technicians_avg_hrly=29.04 m:officials_admin_avg_hrly=51.95 m:officials_admin_ee=1 m:officials_admin_gender=33 m:admin_support_ee=0 m:admin_support_gender=0

series e:k3hs-aykd d:2013-07-16T13:42:18.000Z t:department="Arts and Cultural Affairs" t:descr="Total Employees" m:technicians_ee=1 m:professionals_ee=19 m:service_maintenance_ee=3 m:officials_admin_ee=3 m:admin_support_ee=2
```

## Meta Commands

```ls
metric m:admin_support_ee p:integer l:"Admin Support # EE" t:dataTypeName=number

metric m:admin_support_avg_hrly l:"Admin Support Avg Hrly" t:dataTypeName=number

metric m:admin_support_avg_yrs_in_current_job l:"Admin Support Avg Yrs in Current Job" t:dataTypeName=number

metric m:officials_admin_ee p:integer l:"Officials/Admin # EE" t:dataTypeName=number

metric m:officials_admin_avg_hrly l:"Officials/Admin Avg Hrly" t:dataTypeName=number

metric m:officials_admin_avg_yrs_in_current_job l:"Officials/Admin Avg Yrs in Current Job" t:dataTypeName=number

metric m:para_professionals_ee p:integer l:"Para-Professionals # EE" t:dataTypeName=number

metric m:para_professionals_avg_hrly l:"Para-Professionals Avg Hrly" t:dataTypeName=number

metric m:para_professionals_avg_yrs_in_current_job l:"Para-Professionals Avg Yrs in Current Job" t:dataTypeName=number

metric m:professionals_ee p:integer l:"Professionals # EE" t:dataTypeName=number

metric m:professionals_avg_hrly l:"Professionals Avg Hrly" t:dataTypeName=number

metric m:professionals_avg_yrs_in_current_job l:"Professionals Avg Yrs in Current Job" t:dataTypeName=number

metric m:protected_services_ee p:integer l:"Protected Services # EE" t:dataTypeName=number

metric m:protected_services_avg_hrly l:"Protected Services Avg Hrly" t:dataTypeName=number

metric m:protected_services_avg_yrs_in_current_job l:"Protected Services Avg Yrs in Current Job" t:dataTypeName=number

metric m:service_maintenance_ee p:integer l:"Service/Maintenance # EE" t:dataTypeName=number

metric m:service_maintenance_avg_hrly l:"Service/Maintenance Avg Hrly" t:dataTypeName=number

metric m:service_maintenance_avg_yrs_in_current_job l:"Service/Maintenance Avg Yrs in Current Job" t:dataTypeName=number

metric m:skilled_craft_ee p:integer l:"Skilled Craft # EE" t:dataTypeName=number

metric m:skilled_craft_avg_hrly l:"Skilled Craft Avg Hrly" t:dataTypeName=number

metric m:skilled_craft_avg_yrs_in_current_job l:"Skilled Craft Avg Yrs in Current Job" t:dataTypeName=number

metric m:technicians_ee p:integer l:"Technicians # EE" t:dataTypeName=number

metric m:technicians_avg_hrly l:"Technicians Avg Hrly" t:dataTypeName=number

metric m:technicians_avg_yrs_in_current_job l:"Technicians Avg Yrs in Current Job" t:dataTypeName=number

entity e:k3hs-aykd l:"City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department" t:url=https://data.seattle.gov/api/views/k3hs-aykd

property e:k3hs-aykd t:meta.view d:2017-03-03T14:16:17.536Z v:id=k3hs-aykd v:category="City Business" v:attributionLink=http://mayormcginn.wpengine.netdna-cdn.com/wp-content/uploads/2013/07/Appendix-4-EEO-Final.pdf v:averageRating=0 v:name="City of Seattle Wages: Comparison by Gender - Discretionary Pay Titles by Department"

property e:k3hs-aykd t:meta.view.license d:2017-03-03T14:16:17.536Z v:name="Public Domain"

property e:k3hs-aykd t:meta.view.owner d:2017-03-03T14:16:17.536Z v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"

property e:k3hs-aykd t:meta.view.tableauthor d:2017-03-03T14:16:17.536Z v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```