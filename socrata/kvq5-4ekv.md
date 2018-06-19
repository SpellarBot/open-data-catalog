# Animal Control - Area Animal Shelters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/animal-control-area-animal-shelters) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/kvq5-4ekv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kvq5-4ekv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/kvq5-4ekv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | kvq5-4ekv |
| Name | Animal Control - Area Animal Shelters |
| Attribution | Cook County Animal and Rabies Control |
| Tags | animal shelter, pets, lost pet, found pet |
| Created | 2016-10-17T21:32:18Z |
| Publication Date | 2016-10-17T21:46:58Z |

## Description

Animal shelters located in and around Cook County.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | name           | Shelter Name   | text      | text        |
| Yes      | series tag  | street_address | Street Address | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | state          | State          | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | text        |
| Yes      | series tag  | hours          | Hours          | text      | text        |
| Yes      | series tag  | phone_number   | Phone Number   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kvq5-4ekv d:2016-10-17T21:46:36.000Z t:phone_number="708.848.8155 ex.122" t:zip_code=60304 t:hours="Mon-Fri, 9am-5pm" t:name="Animal Care League" t:state=IL t:street_address="1011 Garfield St." t:city="Oak Park" m:row_number.kvq5-4ekv=1

series e:kvq5-4ekv d:2016-10-17T21:46:36.000Z t:phone_number=708.636.8586 t:zip_code=60415 t:hours="Mon-Fri, 9am-9pm, | Sat. 9am-9pm, | Sun 9am-6pm. | 24hr Intake | Police escort required if after hours." t:name="Animal Welfare League (AWL)" t:state=IL t:street_address="10305 Southwest Hwy" t:city="Chicago Ridge" m:row_number.kvq5-4ekv=2

series e:kvq5-4ekv d:2016-10-17T21:46:36.000Z t:phone_number=312.744.5000 t:zip_code=60608 t:hours="Mon-Sun 7am-11pm" t:name="Chicago Animal Care & Control" t:state=IL t:street_address="2741 S. Western Ave." t:city=Chicago m:row_number.kvq5-4ekv=3
```

## Meta Commands

```ls
metric m:row_number.kvq5-4ekv p:long l:"Row Number"

entity e:kvq5-4ekv l:"Animal Control - Area Animal Shelters" t:attribution="Cook County Animal and Rabies Control" t:url=https://datacatalog.cookcountyil.gov/api/views/kvq5-4ekv

property e:kvq5-4ekv t:meta.view v:id=kvq5-4ekv v:averageRating=0 v:name="Animal Control - Area Animal Shelters" v:attribution="Cook County Animal and Rabies Control"

property e:kvq5-4ekv t:meta.view.license v:name="Public Domain"

property e:kvq5-4ekv t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:kvq5-4ekv t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| :updated_at | name                                     | street_address                | city            | state | zip_code | hours                                                                                                   | phone_number                                                                                                              | 
| =========== | ======================================== | ============================= | =============== | ===== | ======== | ======================================================================================================= | ========================================================================================================================= | 
| 1476740796  | Animal Care League                       | 1011 Garfield St.             | Oak Park        | IL    | 60304    | Mon-Fri, 9am-5pm                                                                                        | 708.848.8155 ex.122                                                                                                       | 
| 1476740796  | Animal Welfare League (AWL)              | 10305 Southwest Hwy           | Chicago Ridge   | IL    | 60415    | Mon-Fri, 9am-9pm, | Sat. 9am-9pm, | Sun 9am-6pm. | 24hr Intake | Police escort required if after hours. | 708.636.8586                                                                                                              | 
| 1476740796  | Chicago Animal Care & Control            | 2741 S. Western Ave.          | Chicago         | IL    | 60608    | Mon-Sun 7am-11pm                                                                                        | 312.744.5000                                                                                                              | 
| 1476740796  | Evanston Animal Shelter & Animal Control | 2310 Oakton                   | Evanston        | IL    | 60602    |                                                                                                         | Call contact number for shelter related inquiries. 847.866.5082 | If no answer call Evanston Police Dept. at 847.866.5000 | 
| 1476740796  | Golf Rose Animal Hospital                | 1375 N. Roselle Rd.           | Schaumburg      | IL    | 60195    | M-F 8am-7pm, | Sat 9am-2pm | Sun open for emergencies only                                              | 847.885.3344                                                                                                              | 
| 1476740796  | Skokie Animal Control                    | 5127 Oakton St.               | Skokie          | IL    | 60077    |                                                                                                         | If unable to reach Animal Control call: 847.933.8484 | Skokie Police Dept. non-emergency 847.982.5900                     | 
| 1476740796  | South Surburban Humane Society           | 1103 W. End Ave.              | Chicago Heights | IL    | 60411    | Mon, Weds, Fri. 1pm-7pm, | Tues Closed, | Sat/Sun 12pm-5pm                                              | 708.755.7387                                                                                                              | 
| 1476740796  | Waggin Tails                             | 1634 S. Laramie Ave., Bldg B. | Cicero          | IL    | 60804    | Mon-Fri, 1pm-6pm | Sat, 10am-2pm                                                                        | 708.652.0825                                                                                                              | 
| 1476740805  | Kings Kennel                             | 238 Saunders Rd.              | Riverwood       | IL    | 60015    | M-F , 8am-6pm | Sat, 8am-12                                                                             | 847.945.9592                                                                                                              | 
| 1476740805  | Paws Tinley Park                         | 8301 191st St.                | Tinley Park     | IL    | 60487    | M,W,F 7pm-9pm, | Tues,Thurs, Sat, Sun 12pm-4pm                                                          | Contact the local Police Department for lost pets, prior to contacting shelter 815.464.7298                               | 
```