# 7th Ward Alderman Applicants - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/7th-ward-alderman-applicants-2013-c6e5a) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2b3m-wnm2) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2b3m-wnm2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2b3m-wnm2/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2b3m-wnm2 |
| Name | 7th Ward Alderman Applicants - 2013 |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | elections |
| Created | 2013-01-31T15:06:50Z |
| Publication Date | 2013-08-15T16:59:13Z |

## Description

Applicants to the 7th Ward Alderman vacancy in 2013 with links to applications.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | full_name        | FULL NAME        | text      | text        |
| Yes      | series tag  | last_name        | LAST NAME        | text      | text        |
| Yes      | series tag  | first_name       | FIRST NAME       | text      | text        |
| Yes      | series tag  | middle_name      | MIDDLE NAME      | text      | text        |
| Yes      | series tag  | suffix           | SUFFIX           | text      | text        |
| Yes      | series tag  | met_requirements | MET REQUIREMENTS | text      | text        |
| Yes      | series tag  | appointed        | APPOINTED        | text      | text        |
| Yes      | series tag  | url              | URL              | url       | url         |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:2b3m-wnm2 d:2013-01-01T00:00:00.000Z t:first_name=Benjamin t:middle_name=D. t:last_name=Boone t:met_requirements=Y t:url="http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Benjamin_D._Boone.pdf" t:full_name="Benjamin D. Boone" m:row_number.2b3m-wnm2=1

series e:2b3m-wnm2 d:2013-01-01T00:00:00.000Z t:first_name=Bernard t:last_name=Riley t:met_requirements=Y t:url="http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Bernie_Riley.pdf" t:full_name="Bernie Riley" m:row_number.2b3m-wnm2=2

series e:2b3m-wnm2 d:2013-01-01T00:00:00.000Z t:first_name=Brittney t:middle_name=Diane t:last_name=Stinson t:met_requirements=Y t:url="http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Brittney_Diane_Stinson.pdf" t:full_name="Brittney Diane Stinson" m:row_number.2b3m-wnm2=3
```

## Meta Commands

```ls
metric m:row_number.2b3m-wnm2 p:long l:"Row Number"

entity e:2b3m-wnm2 l:"7th Ward Alderman Applicants - 2013" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/2b3m-wnm2

property e:2b3m-wnm2 t:meta.view v:id=2b3m-wnm2 v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="7th Ward Alderman Applicants - 2013" v:attribution="City of Chicago"

property e:2b3m-wnm2 t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:2b3m-wnm2 t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| full_name                   | last_name       | first_name | middle_name | suffix | met_requirements | appointed | url                                                                                                                                 | 
| =========================== | =============== | ========== | =========== | ====== | ================ | ========= | =================================================================================================================================== | 
| Benjamin D. Boone           | Boone           | Benjamin   | D.          |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Benjamin_D._Boone.pdf, null]           | 
| Bernie Riley                | Riley           | Bernard    |             |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Bernie_Riley.pdf, null]                | 
| Brittney Diane Stinson      | Stinson         | Brittney   | Diane       |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Brittney_Diane_Stinson.pdf, null]      | 
| Carlos Maxwell              | Maxwell         | Carlos     |             |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Carlos_Maxwell.pdf, null]              | 
| Change Hamilton-Hayyim      | Hamilton-Hayyim | Change     |             |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Change_Hamilton-Hayyim.pdf, null]      | 
| Charles Edwin McMillan      | McMillan        | Charles    | Edwin       |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Charles_Edwin_McMillan.PDF, null]      | 
| David Lee                   | Lee             | David      |             |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/David_Lee.PDF, null]                   | 
| Dennis McCullum             | McCullum        | Dennis     |             |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Dennis_McCullum.PDF, null]             | 
| Deveree Susan Greenwood     | Greenwood       | Deveree    | Susan       |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Deveree_Susan_Greenwood.PDF, null]     | 
| Dorian Christopher Myrickes | Myrickes        | Dorian     | Christopher |        | Y                |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/7th ward alderman applicants data/Dorian_Christopher_Myrickes.PDF, null] | 
```