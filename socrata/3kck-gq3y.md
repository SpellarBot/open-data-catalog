# Iowa Juvenile Detention Secure Placements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-juvenile-detention-secure-placements) |
| Metadata | [Link](https://data.iowa.gov/api/views/3kck-gq3y) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/3kck-gq3y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/3kck-gq3y/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | 3kck-gq3y |
| Name | Iowa Juvenile Detention Secure Placements |
| Attribution | Iowa Department of Human Rights, Iowa Justice Data Warehouse, Juvenile Detention Center Data |
| Category | Public Safety |
| Tags | juvenile detention |
| Created | 2014-11-24T13:48:09Z |
| Publication Date | 2017-02-09T18:10:33Z |

## Description

This dataset contains de-identified individual data for youth placed in a juvenile detention center in Iowa. The dataset includes information regarding age, gender, race/ethnicity, placement facility, month and year of release, and offense class and type. Please note that the Month of Release reflects the first day in the month the placement was released.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | numeric metric | admission_age     | Admission Age     | number        | number        |
| Yes      | series tag     | charge_class_code | Charge Class Code | text          | text          |
| Yes      | series tag     | charge_type       | Charge Type       | text          | text          |
| Yes      | series tag     | charge_subtype    | Charge Subtype    | text          | text          |
| Yes      | series tag     | sex               | Sex               | text          | text          |
| Yes      | series tag     | race_desc         | Race Desc         | text          | text          |
| Yes      | series tag     | county            | County            | text          | text          |
| Yes      | time           | month_of_release  | Month of Release  | calendar_date | calendar_date |
| Yes      | numeric metric | year_of_release   | Year of Release   | number        | number        |
| Yes      | series tag     | facility_name     | Facility Name     | text          | text          |
| Yes      | numeric metric | days_held         | Days Held         | number        | number        |
```

## Time Field

```ls
Value = month_of_release
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:3kck-gq3y d:2004-04-01T00:00:00.000Z t:sex=MALE t:facility_name="Linn County Juvenile Detention Center" t:county=Johnson t:charge_type=VIOLENT t:charge_class_code="Aggravated Misdemeanor" t:charge_subtype=ASSAULT t:race_desc="AFRICAN AMERICAN" m:days_held=2 m:year_of_release=2004 m:admission_age=9

series e:3kck-gq3y d:2003-08-01T00:00:00.000Z t:sex=MALE t:facility_name="Linn County Juvenile Detention Center" t:county=Johnson t:charge_type=VIOLENT t:charge_class_code="Aggravated Misdemeanor" t:charge_subtype=ASSAULT t:race_desc=CAUCASIAN m:days_held=2 m:year_of_release=2003 m:admission_age=9

series e:3kck-gq3y d:2011-01-01T00:00:00.000Z t:sex=MALE t:facility_name="North Iowa Juvenile Detention Services" t:county="Black Hawk" t:charge_type=VIOLENT t:charge_class_code="Simple Misdemeanor" t:charge_subtype=ASSAULT t:race_desc="AFRICAN AMERICAN" m:days_held=38 m:year_of_release=2011 m:admission_age=9
```

## Meta Commands

```ls
metric m:admission_age p:integer l:"Admission Age" d:"The age of the youth when admitted to the juvenile detention facility" t:dataTypeName=number

metric m:year_of_release p:integer l:"Year of Release" d:"Year the individual was released from placement" t:dataTypeName=number

metric m:days_held p:integer l:"Days Held" d:"Number of days the individual was in placement" t:dataTypeName=number

entity e:3kck-gq3y l:"Iowa Juvenile Detention Secure Placements" t:attribution="Iowa Department of Human Rights, Iowa Justice Data Warehouse, Juvenile Detention Center Data" t:url=https://data.iowa.gov/api/views/3kck-gq3y

property e:3kck-gq3y t:meta.view v:id=3kck-gq3y v:category="Public Safety" v:averageRating=0 v:name="Iowa Juvenile Detention Secure Placements" v:attribution="Iowa Department of Human Rights, Iowa Justice Data Warehouse, Juvenile Detention Center Data"

property e:3kck-gq3y t:meta.view.license v:name="Public Domain"

property e:3kck-gq3y t:meta.view.owner v:id=e8jt-thfe v:profileImageUrlMedium=/api/users/e8jt-thfe/profile_images/THUMB v:profileImageUrlLarge=/api/users/e8jt-thfe/profile_images/LARGE v:screenName="Iowa Department of Human Rights" v:profileImageUrlSmall=/api/users/e8jt-thfe/profile_images/TINY v:displayName="Iowa Department of Human Rights"

property e:3kck-gq3y t:meta.view.tableauthor v:id=e8jt-thfe v:profileImageUrlMedium=/api/users/e8jt-thfe/profile_images/THUMB v:profileImageUrlLarge=/api/users/e8jt-thfe/profile_images/LARGE v:screenName="Iowa Department of Human Rights" v:profileImageUrlSmall=/api/users/e8jt-thfe/profile_images/TINY v:roleName=editor v:displayName="Iowa Department of Human Rights"
```

## Top Records

```ls
| admission_age | charge_class_code      | charge_type | charge_subtype | sex  | race_desc        | county      | month_of_release    | year_of_release | facility_name                          | days_held | 
| ============= | ====================== | =========== | ============== | ==== | ================ | =========== | =================== | =============== | ====================================== | ========= | 
| 9             | Aggravated Misdemeanor | VIOLENT     | ASSAULT        | MALE | AFRICAN AMERICAN | Johnson     | 2004-04-01T00:00:00 | 2004            | Linn County Juvenile Detention Center  | 2         | 
| 9             | Aggravated Misdemeanor | VIOLENT     | ASSAULT        | MALE | CAUCASIAN        | Johnson     | 2003-08-01T00:00:00 | 2003            | Linn County Juvenile Detention Center  | 2         | 
| 9             | Simple Misdemeanor     | VIOLENT     | ASSAULT        | MALE | AFRICAN AMERICAN | Black Hawk  | 2011-01-01T00:00:00 | 2011            | North Iowa Juvenile Detention Services | 38        | 
| 9             | Simple Misdemeanor     | VIOLENT     | ASSAULT        | MALE | AFRICAN AMERICAN | Black Hawk  | 2010-11-01T00:00:00 | 2010            | North Iowa Juvenile Detention Services | 7         | 
| 9             | Simple Misdemeanor     | VIOLENT     | ASSAULT        | MALE | AFRICAN AMERICAN | Johnson     | 2004-04-01T00:00:00 | 2004            | Linn County Juvenile Detention Center  | 3         | 
| 9             | Simple Misdemeanor     | VIOLENT     | ASSAULT        | MALE | CAUCASIAN        | Cerro Gordo | 2010-03-01T00:00:00 | 2010            | North Iowa Juvenile Detention Services | 2         | 
| 9             | Simple Misdemeanor     | VIOLENT     | ASSAULT        | MALE | CAUCASIAN        | Wright      | 2005-08-01T00:00:00 | 2005            | North Iowa Juvenile Detention Services | 3         | 
| 10            | Aggravated Misdemeanor | PROPERTY    | ARSON          | MALE | AFRICAN AMERICAN | Webster     | 2003-07-01T00:00:00 | 2003            | Central Iowa Juvenile Detention Center | 4         | 
| 10            | Aggravated Misdemeanor | PROPERTY    | THEFT          | MALE | CAUCASIAN        | Madison     | 2011-08-01T00:00:00 | 2011            | Central Iowa Juvenile Detention Center | 14        | 
| 10            | Aggravated Misdemeanor | PROPERTY    | THEFT          | MALE | CAUCASIAN        | Madison     | 2011-11-01T00:00:00 | 2011            | Central Iowa Juvenile Detention Center | 88        | 
```