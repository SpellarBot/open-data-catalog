# Job Applicants by Gender and Ethnicity

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/applicant-information-from-7-1-2014-to-9-30-2014-7835b) |
| Metadata | [Link](https://data.lacity.org/api/views/mkf9-fagf) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/mkf9-fagf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/mkf9-fagf/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | mkf9-fagf |
| Name | Job Applicants by Gender and Ethnicity |
| Attribution | Personnel Department |
| Category | A Prosperous City |
| Tags | employment, jobs, equity, equal opportunity |
| Created | 2014-10-10T18:06:12Z |
| Publication Date | 2016-12-01T17:07:09Z |

## Description

City of LA job applicants by the job they applied for and demographic information. 

We are currently undergoing a data inventory to improve usability on the site. We're aware that this dataset is out of date but wanted to err on the side of making incomplete data available. Thank you for your patience, please contact the dataset owner or mayor.opendata@lacity.org with questions or ideas.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                            | Data Type | Render Type |
| ======== | ============== | ============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | fiscal_year                    | Fiscal Year                     | text      | text        |
| Yes      | series tag     | job_number                     | Job Number                      | text      | text        |
| Yes      | series tag     | job_description                | Job Description                 | text      | text        |
| Yes      | numeric metric | apps_received                  | Apps Received                   | number    | number      |
| Yes      | numeric metric | female                         | Female                          | number    | number      |
| Yes      | numeric metric | male                           | Male                            | number    | number      |
| Yes      | numeric metric | unknown_gender                 | Unknown_Gender                  | number    | number      |
| Yes      | numeric metric | black                          | Black                           | number    | number      |
| Yes      | numeric metric | hispanic                       | Hispanic                        | number    | number      |
| Yes      | numeric metric | asian                          | Asian                           | number    | number      |
| Yes      | numeric metric | caucasian                      | Caucasian                       | number    | number      |
| Yes      | numeric metric | american_indian_alaskan_native | American Indian/ Alaskan Native | number    | number      |
| Yes      | numeric metric | filipino                       | Filipino                        | number    | number      |
| Yes      | numeric metric | unknown_ethnicity              | Unknown_Ethnicity               | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mkf9-fagf d:2016-12-01T17:06:47.000Z t:fiscal_year=2013-2014 t:job_number="9206 OP 2014/04/18" t:job_description="311 DIRECTOR 9206" m:female=20 m:unknown_ethnicity=4 m:male=31 m:unknown_gender=3 m:american_indian_alaskan_native=0 m:filipino=0 m:hispanic=18 m:black=25 m:apps_received=54 m:caucasian=6 m:asian=1

series e:mkf9-fagf d:2016-12-01T17:06:47.000Z t:fiscal_year=2013-2014 t:job_number="1223 P 2013/08/09" t:job_description="ACCOUNTING CLERK 1223" m:female=488 m:unknown_ethnicity=26 m:male=152 m:unknown_gender=8 m:american_indian_alaskan_native=3 m:filipino=79 m:hispanic=204 m:black=151 m:apps_received=648 m:caucasian=62 m:asian=123

series e:mkf9-fagf d:2016-12-01T17:06:47.000Z t:fiscal_year=2013-2014 t:job_number="7260 OP 2014/02/14" t:job_description="AIRPORT MANAGER 7260" m:female=13 m:unknown_ethnicity=2 m:male=37 m:unknown_gender=1 m:american_indian_alaskan_native=0 m:filipino=0 m:hispanic=12 m:black=8 m:apps_received=51 m:caucasian=20 m:asian=9
```

## Meta Commands

```ls
metric m:apps_received p:integer l:"Apps Received" t:dataTypeName=number

metric m:female p:integer l:Female t:dataTypeName=number

metric m:male p:integer l:Male t:dataTypeName=number

metric m:unknown_gender p:integer l:Unknown_Gender t:dataTypeName=number

metric m:black p:integer l:Black t:dataTypeName=number

metric m:hispanic p:integer l:Hispanic t:dataTypeName=number

metric m:asian p:integer l:Asian t:dataTypeName=number

metric m:caucasian p:integer l:Caucasian t:dataTypeName=number

metric m:american_indian_alaskan_native p:integer l:"American Indian/ Alaskan Native" t:dataTypeName=number

metric m:filipino p:integer l:Filipino t:dataTypeName=number

metric m:unknown_ethnicity p:integer l:Unknown_Ethnicity t:dataTypeName=number

entity e:mkf9-fagf l:"Job Applicants by Gender and Ethnicity" t:attribution="Personnel Department" t:url=https://data.lacity.org/api/views/mkf9-fagf

property e:mkf9-fagf t:meta.view v:id=mkf9-fagf v:category="A Prosperous City" v:averageRating=0 v:name="Job Applicants by Gender and Ethnicity" v:attribution="Personnel Department"

property e:mkf9-fagf t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:mkf9-fagf t:meta.view.owner v:id=agii-8fjm v:profileImageUrlMedium=/api/users/agii-8fjm/profile_images/THUMB v:profileImageUrlLarge=/api/users/agii-8fjm/profile_images/LARGE v:screenName="Personnel OpenData" v:profileImageUrlSmall=/api/users/agii-8fjm/profile_images/TINY v:displayName="Personnel OpenData"

property e:mkf9-fagf t:meta.view.tableauthor v:id=agii-8fjm v:profileImageUrlMedium=/api/users/agii-8fjm/profile_images/THUMB v:profileImageUrlLarge=/api/users/agii-8fjm/profile_images/LARGE v:screenName="Personnel OpenData" v:profileImageUrlSmall=/api/users/agii-8fjm/profile_images/TINY v:roleName=publisher v:displayName="Personnel OpenData"
```

## Top Records

```ls
| :updated_at | fiscal_year | job_number         | job_description                            | apps_received | female | male | unknown_gender | black | hispanic | asian | caucasian | american_indian_alaskan_native | filipino | unknown_ethnicity | 
| =========== | =========== | ================== | ========================================== | ============= | ====== | ==== | ============== | ===== | ======== | ===== | ========= | ============================== | ======== | ================= | 
| 1480612007  | 2013-2014   | 9206 OP 2014/04/18 | 311 DIRECTOR 9206                          | 54            | 20     | 31   | 3              | 25    | 18       | 1     | 6         | 0                              | 0        | 4                 | 
| 1480612007  | 2013-2014   | 1223 P 2013/08/09  | ACCOUNTING CLERK 1223                      | 648           | 488    | 152  | 8              | 151   | 204      | 123   | 62        | 3                              | 79       | 26                | 
| 1480612007  | 2013-2014   | 7260 OP 2014/02/14 | AIRPORT MANAGER 7260                       | 51            | 13     | 37   | 1              | 8     | 12       | 9     | 20        | 0                              | 0        | 2                 | 
| 1480612007  | 2013-2014   | 3227 P 2013/11/15  | AIRPORT POLICE LIEUTENANT 2013             | 48            | 9      | 38   | 1              | 21    | 14       | 3     | 7         | 0                              | 1        | 2                 | 
| 1480612007  | 2013-2014   | 2400 O 2014/05/02  | AQUARIST 2400                              | 40            | 15     | 24   | 1              | 3     | 7        | 7     | 19        | 1                              | 1        | 2                 | 
| 1480612007  | 2013-2014   | 1191               | ARCHIVIST1191                              | 161           | 89     | 66   | 6              | 12    | 36       | 20    | 73        | 0                              | 6        | 14                | 
| 1480612007  | 2013-2014   | 2478 OP 2014/05/30 | ART CENTER DIRECTOR 2478                   | 102           | 53     | 48   | 1              | 22    | 18       | 14    | 37        | 2                              | 4        | 5                 | 
| 1480612007  | 2013-2014   | 2454 O 2014/04/11  | ARTS ASSOCIATE 2454                        | 702           | 430    | 240  | 32             | 96    | 173      | 84    | 211       | 5                              | 40       | 93                | 
| 1480612007  | 2013-2014   | 3808 P 2014/05/30  | ASSISTANT COMMUNICATIONS CABLE WORKER 3808 | 105           | 3      | 101  | 1              | 24    | 44       | 2     | 27        | 0                              | 6        | 2                 | 
| 1480612007  | 2013-2014   | 1860 O 2013/10/25  | ASSISTANT UTILITY BUYER 1860               | 897           | 467    | 411  | 19             | 197   | 229      | 197   | 116       | 3                              | 103      | 52                | 
```