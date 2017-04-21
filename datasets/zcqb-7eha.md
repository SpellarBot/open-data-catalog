# Boundary Board Members Roster

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boundary-board-members-roster-1caf2) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/zcqb-7eha) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/zcqb-7eha/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/zcqb-7eha/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | zcqb-7eha |
| Name | Boundary Board Members Roster |
| Attribution | King County Boundary Review Board |
| Category | Operations |
| Tags | boundary review, board, annexations |
| Created | 2011-05-17T18:06:01Z |
| Publication Date | 2015-06-17T17:36:04Z |

## Description

Washington State Boundary Board for King County - Membership Profile: Board Members Roster

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | firstname         | FirstName         | text          | text          |
| Yes      | series tag     | lastname          | LastName          | text          | text          |
| Yes      | series tag     | office            | Office            | text          | text          |
| Yes      | series tag     | sex               | Sex               | text          | text          |
| Yes      | series tag     | ethnicity         | Ethnicity         | text          | text          |
| Yes      | numeric metric | kc_dist           | KC Dist.          | number        | number        |
| Yes      | series tag     | skill_affiliation | Skill/Affiliation | text          | text          |
| Yes      | time           | first_appointed   | First appointed   | calendar_date | calendar_date |
| No       |                | term_expires      | Term Expires      | calendar_date | calendar_date |
| Yes      | numeric metric | term              | Term #            | number        | number        |
| Yes      | series tag     | other             | Appointed by      | text          | text          |
| Yes      | series tag     | details_2         | Details 2         | text          | text          |
| Yes      | series tag     | details_3         | Details 3         | text          | text          |
| Yes      | series tag     | details_4         | Details 4         | text          | text          |
| Yes      | series tag     | details_5         | Details 5         | text          | text          |
| Yes      | series tag     | details_6         | Details 6         | text          | text          |
| Yes      | series tag     | details_7         | Details 7         | text          | text          |
```

## Time Field

```ls
Value = first_appointed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = term_expires
```

## Data Commands

```ls
series e:zcqb-7eha d:2001-02-01T00:00:00.000Z t:skill_affiliation="Real Estate Agent" t:sex=F t:other="Special Purpose District" t:details_5="Bellevue resident" t:details_3="Real Estate Sales Person" t:details_4="Director of National Association of Realtors" t:lastname=Anderson t:firstname=Evangeline t:details_2="Real Estate Instructor, Renton Technical College" t:ethnicity=Caucasian m:term=3 m:kc_dist=6

series e:zcqb-7eha d:2012-09-28T00:00:00.000Z t:skill_affiliation="Civil Engineer" t:sex=M t:other="K.C. Executive" t:details_3="City of Seattle resident" t:lastname=Beltran t:firstname=Miguel t:details_2="Senior Program Administrator" t:ethnicity=Hispanic m:term=1 m:kc_dist=4

series e:zcqb-7eha d:2009-01-31T00:00:00.000Z t:skill_affiliation="Community Volunteer; Retired Businesswoman" t:sex=F t:other="K.C. Executive" t:details_3="Former liaison to King County Records and Elections" t:details_4="Seattle (West Hill) resident" t:lastname=Bushnell t:firstname=Sylvia t:details_2="Retired Businesswoman" t:ethnicity=African-American m:term=1 m:kc_dist=5
```

## Meta Commands

```ls
metric m:kc_dist p:integer l:"KC Dist." t:dataTypeName=number

metric m:term p:integer l:"Term #" t:dataTypeName=number

entity e:zcqb-7eha l:"Boundary Board Members Roster" t:attribution="King County Boundary Review Board" t:url=https://data.kingcounty.gov/api/views/zcqb-7eha

property e:zcqb-7eha t:meta.view v:id=zcqb-7eha v:category=Operations v:attributionLink=http://www.kingcounty.gov/property/annexations/ v:averageRating=0 v:name="Boundary Board Members Roster" v:attribution="King County Boundary Review Board"

property e:zcqb-7eha t:meta.view.license v:name="Public Domain"

property e:zcqb-7eha t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:zcqb-7eha t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| firstname  | lastname  | office        | sex | ethnicity        | kc_dist | skill_affiliation                                                      | first_appointed     | term_expires        | term | other                    | details_2                                                          | details_3                                           | details_4                                    | details_5         | details_6          | details_7 | 
| ========== | ========= | ============= | === | ================ | ======= | ====================================================================== | =================== | =================== | ==== | ======================== | ================================================================== | =================================================== | ============================================ | ================= | ================== | ========= | 
| Evangeline | Anderson  |               | F   | Caucasian        | 6       | Real Estate Agent                                                      | 2001-02-01T00:00:00 | 2017-01-31T00:00:00 | 3    | Special Purpose District | Real Estate Instructor, Renton Technical College                   | Real Estate Sales Person                            | Director of National Association of Realtors | Bellevue resident |                    |           | 
| Miguel     | Beltran   |               | M   | Hispanic         | 4       | Civil Engineer                                                         | 2012-09-28T00:00:00 | 2017-01-31T00:00:00 | 1    | K.C. Executive           | Senior Program Administrator                                       | City of Seattle resident                            |                                              |                   |                    |           | 
| Sylvia     | Bushnell  |               | F   | African-American | 5       | Community Volunteer; Retired Businesswoman                             | 2009-01-31T00:00:00 | 2017-01-31T00:00:00 | 1    | K.C. Executive           | Retired Businesswoman                                              | Former liaison to King County Records and Elections | Seattle (West Hill) resident                 |                   |                    |           | 
| Robert     | Cook      |               | M   | Caucasian        | 8       | Fire District Commissioner; Business Owner                             | 2005-02-01T00:00:00 | 2017-03-01T00:00:00 | 2    | Special District         | Former Official Special Purpose District                           | Business Owner                                      | SeaTac resident                              |                   |                    |           | 
| Mary Lynne | Evans     |               | F   | Caucasian        | 2       | Retired Community Planner; Educator; Management Consultant             | 2010-02-01T00:00:00 | 2019-01-31T00:00:00 | 1    | K.C. Executive           | Community Planner (Retired)                                        | Educator                                            | Management Consultant                        | Seattle resident  |                    |           | 
| Claudia    | Hirschey  |               | F   | Caucasian        | 9       | Former Newcastle City Council Member; Transportation Planning Engineer | 2003-02-01T00:00:00 | 2019-01-31T00:00:00 | 3    | Cities of King County    | Transportation Planner/Engineer                                    | Former Member Newcastle City Council                | Member Institute of Transportation Engineers | Board Member YMCA | Newcastle resident |           | 
| Laura      | Kisielius | (Chair)       | F   | Caucasian        | 2       | Attorney at Law                                                        | 2011-05-18T00:00:00 | 2019-01-31T00:00:00 | 1    | Governor                 | Snohomish County - Deputy Prosecuting Attorney                     | Seattle resident                                    |                                              |                   |                    |           | 
| Ronald     | Little    |               | M   | Caucasian        | 3       | Retired Water District Commissioner                                    | 2011-03-10T00:00:00 | 2017-03-01T00:00:00 | 1    | Special District         | Retired Sammamish Plateau Water & Sewer District - General Manager | Sammamish Resident                                  |                                              |                   |                    |           | 
| Paul       | MacCready |               | M   | Caucasian        | 2       | Geographer, Land Use Planner                                           | 2011-08-24T00:00:00 | 2017-01-31T00:00:00 | 1    | Cities of King County    | Geographer                                                         | Land Use Planner (Snohomish)                        | Seattle resident                             |                   |                    |           | 
| Stephen    | Toy       | (Chair-elect) | M   | Caucasian        | 2       | Demographer - Snohomish County                                         | 2012-02-29T00:00:00 | 2019-01-31T00:00:00 | 1    | K.C. Executive           | Demographer--Snohomish County                                      | Seattle resident                                    |                                              |                   |                    |           | 
```