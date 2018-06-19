# AAQOL Community Comments Oct 27 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/aaqol-community-comments-oct-27-2016) |
| Metadata | [Link](https://data.austintexas.gov/api/views/75gm-hb4x) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/75gm-hb4x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/75gm-hb4x/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 75gm-hb4x |
| Name | AAQOL Community Comments Oct 27 2016 |
| Attribution | Marion Sanchez: City of Austin, City Manager's Office, Communications & Public Information Office, Community Engagement |
| Category | Government |
| Tags | asian, asian american, quality of life, aaqol, austin, multicultural, asia, 20131024-084, city manager, marion, marion sanchez, city council, community conversations, conversations over tea, visio... |
| Created | 2016-10-27T15:34:02Z |
| Publication Date | 2016-10-27T15:52:02Z |

## Description

Resolution No. 20131024-084 directed the City Manager to ? . . . conduct facilitated discussions . . . about Asian American quality of life issues in Austin; to produce a Community Scorecard; to develop strategies to address the findings of Asian-American Health Assessment, the facilitated discussions, and the Community Scorecard; and to report back . . . with recommendations for enhanced or new City programs and practices.?  For more information: marion.sanchez@AustinTexas.gov., https://asianlifeatx.bloomfire.com/, http://austintexas.gov/asianlifeaustin, https://www.facebook.com/AsianLifeATX.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type     | Render Type   |
| ======== | ============== | ============= | ============= | ============= | ============= |
| Yes      | numeric metric | total         | TOTAL         | number        | number        |
| Yes      | time           | date_of_event | Date of Event | calendar_date | calendar_date |
| Yes      | series tag     | location      | Location      | text          | text          |
| Yes      | series tag     | topic         | Topic         | text          | text          |
| Yes      | series tag     | question      | Question      | text          | text          |
| Yes      | numeric metric | of_comments   | # of Comments | number        | number        |
| Yes      | series tag     | code          | Code          | text          | text          |
| Yes      | series tag     | comment       | Comment       | text          | text          |
| Yes      | series tag     | zip_code      | Zip Code      | text          | text          |
| Yes      | series tag     | department_1  | Department 1  | text          | text          |
| Yes      | series tag     | department_2  | Department 2  | text          | text          |
| Yes      | series tag     | theme_1       | Theme 1       | text          | text          |
| Yes      | series tag     | theme_2       | Theme 2       | text          | text          |
| Yes      | series tag     | theme_3       | Theme 3       | text          | text          |
| Yes      | series tag     | theme_4       | Theme 4       | text          | text          |
| Yes      | series tag     | theme_5       | Theme 5       | text          | text          |
| Yes      | series tag     | theme_6       | Theme 6       | text          | text          |
```

## Time Field

```ls
Value = date_of_event
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:75gm-hb4x d:2016-01-20T00:00:00.000Z t:topic=HHS t:theme_1=affordability t:location=GAACC t:question="What is your Austin experience? Where am I today?" t:code=0120-HHS-Q1-0001 t:comment="""high"" + ""low"" groups of income/ some struggle" t:department_2="Human Resources" t:department_1="Neighborhood Housing & Community Development" m:total=1 m:of_comments=1

series e:75gm-hb4x d:2016-01-20T00:00:00.000Z t:topic=HHS t:theme_1="recreational activities" t:location=GAACC t:question="What is your Austin experience? Where am I today?" t:code=0120-HHS-Q1-0002 t:comment="Capacity to be involved in different activities" t:department_1="Parks & Recreation" m:total=2 m:of_comments=2

series e:75gm-hb4x d:2016-01-20T00:00:00.000Z t:topic=HHS t:theme_1="cultural events, arts, and/or music" t:location=GAACC t:question="What is your Austin experience? Where am I today?" t:code=0120-HHS-Q1-0003 t:comment="listen to music for free or cheap" t:department_2="Economic Development" t:department_1="Parks & Recreation" m:total=3 m:of_comments=3
```

## Meta Commands

```ls
metric m:total p:integer l:TOTAL t:dataTypeName=number

metric m:of_comments p:integer l:"# of Comments" t:dataTypeName=number

entity e:75gm-hb4x l:"AAQOL Community Comments Oct 27 2016" t:attribution="Marion Sanchez: City of Austin, City Manager's Office, Communications & Public Information Office, Community Engagement" t:url=https://data.austintexas.gov/api/views/75gm-hb4x

property e:75gm-hb4x t:meta.view v:id=75gm-hb4x v:category=Government v:attributionLink=http://www.austintexas.gov/asianlifeaustin v:averageRating=0 v:name="AAQOL Community Comments Oct 27 2016" v:attribution="Marion Sanchez: City of Austin, City Manager's Office, Communications & Public Information Office, Community Engagement"

property e:75gm-hb4x t:meta.view.owner v:id=5h2x-93y4 v:profileImageUrlMedium=/api/users/5h2x-93y4/profile_images/THUMB v:profileImageUrlLarge=/api/users/5h2x-93y4/profile_images/LARGE v:screenName=marion3sanchez v:profileImageUrlSmall=/api/users/5h2x-93y4/profile_images/TINY v:displayName=marion3sanchez

property e:75gm-hb4x t:meta.view.tableauthor v:id=5h2x-93y4 v:profileImageUrlMedium=/api/users/5h2x-93y4/profile_images/THUMB v:profileImageUrlLarge=/api/users/5h2x-93y4/profile_images/LARGE v:screenName=marion3sanchez v:profileImageUrlSmall=/api/users/5h2x-93y4/profile_images/TINY v:roleName=editor v:displayName=marion3sanchez
```

## Top Records

```ls
| total | date_of_event       | location | topic | question                                          | of_comments | code             | comment                                                                               | zip_code | department_1                                 | department_2         | theme_1                             | theme_2 | theme_3 | theme_4 | theme_5 | theme_6 | 
| ===== | =================== | ======== | ===== | ================================================= | =========== | ================ | ===================================================================================== | ======== | ============================================ | ==================== | =================================== | ======= | ======= | ======= | ======= | ======= | 
| 1     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 1           | 0120-HHS-Q1-0001 | "high" + "low" groups of income/ some struggle                                        |          | Neighborhood Housing & Community Development | Human Resources      | affordability                       |         |         |         |         |         | 
| 2     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 2           | 0120-HHS-Q1-0002 | Capacity to be involved in different activities                                       |          | Parks & Recreation                           |                      | recreational activities             |         |         |         |         |         | 
| 3     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 3           | 0120-HHS-Q1-0003 | listen to music for free or cheap                                                     |          | Parks & Recreation                           | Economic Development | cultural events, arts, and/or music |         |         |         |         |         | 
| 4     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 4           | 0120-HHS-Q1-0004 | Hustle                                                                                |          | Economic Development                         |                      | miscellaneous                       |         |         |         |         |         | 
| 5     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 5           | 0120-HHS-Q1-0005 | Music                                                                                 |          | Parks & Recreation                           | Economic Development | cultural events, arts, and/or music |         |         |         |         |         | 
| 6     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 6           | 0120-HHS-Q1-0006 | WEIRD & FUN                                                                           |          | Parks & Recreation                           |                      | miscellaneous                       |         |         |         |         |         | 
| 7     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 7           | 0120-HHS-Q1-0007 | HIGHER EDUCATION -> WORKFORCE (I'M SURE THIS IS A COMMON "AUSTIN EXPERIENCE")         |          | Economic Development                         | Human Resources      | education                           |         |         |         |         |         | 
| 8     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 8           | 0120-HHS-Q1-0008 | Many community experiences.../Witness to many great efforts w/ lack of infrastructure |          | Equity Office                                | Planning & Zoning    | development                         |         |         |         |         |         | 
| 9     | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 9           | 0120-HHS-Q1-0009 | amazing recreational options and activities making Austin unique                      |          | Parks & Recreation                           | Economic Development | recreational activites              |         |         |         |         |         | 
| 10    | 2016-01-20T00:00:00 | GAACC    | HHS   | What is your Austin experience? Where am I today? | 10          | 0120-HHS-Q1-0010 | Enjoy Live Music with local Talent                                                    |          | Parks & Recreation                           | Economic Development | cultural events, arts, and/or music |         |         |         |         |         | 
```