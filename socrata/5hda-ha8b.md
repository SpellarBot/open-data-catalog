# 4th Ward Alderman Applicants - 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/4th-ward-alderman-applicants-2016) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/5hda-ha8b) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/5hda-ha8b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/5hda-ha8b/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 5hda-ha8b |
| Name | 4th Ward Alderman Applicants - 2016 |
| Attribution | http://www.cityofchicago.org |
| Category | Administration & Finance |
| Tags | elections |
| Created | 2016-05-05T18:25:46Z |
| Publication Date | 2016-05-05T20:59:33Z |

## Description

Applicants to the 4th Ward Alderman vacancy in 2016 with links to applications.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| Yes      | series tag  | full_name   | FULL NAME   | text      | text        |
| Yes      | series tag  | last_name   | LAST NAME   | text      | text        |
| Yes      | series tag  | first_name  | FIRST NAME  | text      | text        |
| Yes      | series tag  | middle_name | MIDDLE NAME | text      | text        |
| Yes      | series tag  | suffix      | SUFFIX      | text      | text        |
| Yes      | series tag  | appointed   | APPOINTED   | text      | text        |
| Yes      | series tag  | url         | URL         | url       | url         |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5hda-ha8b d:2016-01-01T00:00:00.000Z t:first_name=Marcellus t:middle_name=H. t:last_name=Moore t:suffix=Jr. t:url=http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/MooreJrMarcellusApplicationMaterials.pdf t:full_name="Marcellus H. Moore, Jr." m:row_number.5hda-ha8b=1

series e:5hda-ha8b d:2016-01-01T00:00:00.000Z t:first_name=Gloria t:middle_name=J. t:last_name=Hanna t:url=http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/HannaGloriaApplicationMaterials.pdf t:full_name="Gloria J Hanna" m:row_number.5hda-ha8b=2

series e:5hda-ha8b d:2016-01-01T00:00:00.000Z t:first_name=Jeannette t:middle_name=Leann t:last_name=Hoyt t:url=http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/HoytJeannetteApplicationMaterials.pdf t:full_name="Jeannette Leann Hoyt" m:row_number.5hda-ha8b=3
```

## Meta Commands

```ls
metric m:row_number.5hda-ha8b p:long l:"Row Number"

entity e:5hda-ha8b l:"4th Ward Alderman Applicants - 2016" t:attribution=http://www.cityofchicago.org t:url=https://data.cityofchicago.org/api/views/5hda-ha8b

property e:5hda-ha8b t:meta.view v:id=5hda-ha8b v:category="Administration & Finance" v:averageRating=0 v:name="4th Ward Alderman Applicants - 2016" v:attribution=http://www.cityofchicago.org

property e:5hda-ha8b t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:5hda-ha8b t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| full_name                     | last_name     | first_name | middle_name | suffix | appointed | url                                                                                                                                               | 
| ============================= | ============= | ========== | =========== | ====== | ========= | ================================================================================================================================================= | 
| Marcellus H. Moore, Jr.       | Moore         | Marcellus  | H.          | Jr.    |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/MooreJrMarcellusApplicationMaterials.pdf, null]   | 
| Gloria J Hanna                | Hanna         | Gloria     | J.          |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/HannaGloriaApplicationMaterials.pdf, null]        | 
| Jeannette Leann Hoyt          | Hoyt          | Jeannette  | Leann       |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/HoytJeannetteApplicationMaterials.pdf, null]      | 
| Akilah Shani Halley           | Halley        | Akilah     | Shani       |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/HalleyAkilahApplicationMaterials.pdf, null]       | 
| Tracey Y. Bey                 | Bey           | Tracey     | Y.          |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/BeyTraceyApplicationMaterials.pdf, null]          | 
| Joshua James Law              | Law           | Joshua     | James       |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/LawJoshuaApplicationMaterials.pdf, null]          | 
| Shay Tyrone Allen             | Allen         | Shay       | Tyrone      |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/AllenTyroneApplicationMaterials.pdf, null]        | 
| Tameka Vaundril Walton Lawson | Walton-Lawson | Tameka     | Vaundril    |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/WaltonLawsonTamekaApplicationMaterials.pdf, null] | 
| Jesus Manuel Ozaeta           | Ozaeta        | Jesus      | Manuel      |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/OzaetaJesusManuelApplicationMaterials.pdf, null]  | 
| Isaac Roland Monroe           | Monroe        | Isaac      | Roland      |        |           | [http://www.cityofchicago.org/content/dam/city/depts/mayor/4th%20Ward%20Aldermanic%20Applicants/MonroeIsaacApplicationMaterials.pdf, null]        | 
```