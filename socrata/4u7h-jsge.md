# Public Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-facilities) |
| Metadata | [Link](https://data.brla.gov/api/views/4u7h-jsge) |
| Data: JSON | [100 Rows](https://data.brla.gov/api/views/4u7h-jsge/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.brla.gov/api/views/4u7h-jsge/rows.csv?max_rows=100) |
| Host | data.brla.gov |
| Id | 4u7h-jsge |
| Name | Public Facilities |
| Attribution | City-Parish Planning Commission |
| Category | Government |
| Tags | public facility, municipal office, government office, police, fire, ems, park, library, courthouse, community center, head start center, public works |
| Created | 2015-01-01T23:18:05Z |
| Publication Date | 2015-07-11T20:22:10Z |

## Description

This dataset contains information and addresses for all City-Parish facilities

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| No       |             | id            | ID            | text      | number      |
| Yes      | series tag  | description   | DESCRIPTION   | text      | text        |
| Yes      | series tag  | facility_type | FACILITY TYPE | text      | text        |
| Yes      | series tag  | agency        | AGENCY        | text      | text        |
| No       |             | full_address  | FULL ADDRESS  | text      | text        |
| Yes      | series tag  | city          | CITY          | text      | text        |
| Yes      | series tag  | state         | STATE         | text      | text        |
| Yes      | series tag  | zip           | ZIP           | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,full_address
```

## Data Commands

```ls
series e:4u7h-jsge d:2016-02-22T03:33:28.000Z t:zip=70808 t:description="BRFD Station 10" t:state=LA t:agency="BATON ROUGE FIRE DEPARTMENT" t:facility_type="FIRE PROTECTION" t:city="BATON ROUGE" m:row_number.4u7h-jsge=1

series e:4u7h-jsge d:2016-02-22T03:33:28.000Z t:zip=70816 t:description="BRFD Station 17" t:state=LA t:agency="BATON ROUGE FIRE DEPARTMENT" t:facility_type="FIRE PROTECTION" t:city="BATON ROUGE" m:row_number.4u7h-jsge=2

series e:4u7h-jsge d:2016-02-22T03:33:28.000Z t:zip=70802 t:description="Public Defender" t:state=LA t:agency="DISTRICT ATTORNEY" t:facility_type="MUNICIPAL OFFICES" t:city="BATON ROUGE" m:row_number.4u7h-jsge=3
```

## Meta Commands

```ls
metric m:row_number.4u7h-jsge p:long l:"Row Number"

entity e:4u7h-jsge l:"Public Facilities" t:attribution="City-Parish Planning Commission" t:url=https://data.brla.gov/api/views/4u7h-jsge

property e:4u7h-jsge t:meta.view v:id=4u7h-jsge v:category=Government v:attributionLink=http://brgov.com/dept/planning v:averageRating=0 v:name="Public Facilities" v:attribution="City-Parish Planning Commission"

property e:4u7h-jsge t:meta.view.license v:name="Public Domain"

property e:4u7h-jsge t:meta.view.owner v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:displayName="Open Data BR"

property e:4u7h-jsge t:meta.view.tableauthor v:id=mjn2-v86v v:profileImageUrlMedium=/api/users/mjn2-v86v/profile_images/THUMB v:profileImageUrlLarge=/api/users/mjn2-v86v/profile_images/LARGE v:screenName="Open Data BR" v:profileImageUrlSmall=/api/users/mjn2-v86v/profile_images/TINY v:roleName=viewer v:displayName="Open Data BR"
```

## Top Records

```ls
| :updated_at | id | description                | facility_type     | agency                                | full_address          | city        | state | zip   | 
| =========== | == | ========================== | ================= | ===================================== | ===================== | =========== | ===== | ===== | 
| 1456112008  | 16 | BRFD Station 10            | FIRE PROTECTION   | BATON ROUGE FIRE DEPARTMENT           | 7380 MENLO DR         | BATON ROUGE | LA    | 70808 | 
| 1456112008  | 24 | BRFD Station 17            | FIRE PROTECTION   | BATON ROUGE FIRE DEPARTMENT           | 14450 OLD HAMMOND HWY | BATON ROUGE | LA    | 70816 | 
| 1456112008  | 42 | Public Defender            | MUNICIPAL OFFICES | DISTRICT ATTORNEY                     | 300 LOUISIANA AVE     | BATON ROUGE | LA    | 70802 | 
| 1456112008  | 18 | BRFD Station 12            | FIRE PROTECTION   | BATON ROUGE FIRE DEPARTMENT           | 555 GOVERNMENT ST     | BATON ROUGE | LA    | 70802 | 
| 1456112008  | 34 | Central FD Station 35      | FIRE PROTECTION   | CENTRAL VOLUNTEER FIRE DEPARTMENT     | 10626 LOVETT RD       | CENTRAL     | LA    | 70818 | 
| 1456112008  | 0  | Baker FD Station 22        | FIRE PROTECTION   | BAKER FIRE DEPARTMENT                 | 6252 LAVEY LN         | BAKER       | LA    | 70714 | 
| 1456112008  | 17 | BRFD Station 11            | FIRE PROTECTION   | BATON ROUGE FIRE DEPARTMENT           | 3186 HIGHLAND RD      | BATON ROUGE | LA    | 70802 | 
| 1456112008  | 15 | BRFD Station 9             | FIRE PROTECTION   | BATON ROUGE FIRE DEPARTMENT           | 4025 PERKINS RD       | BATON ROUGE | LA    | 70808 | 
| 1456112008  | 26 | Brownsfield VFD Station 71 | FIRE PROTECTION   | BROWNSFIELD VOLUNTEER FIRE DEPARTMENT | 11420 PLANK RD        | BATON ROUGE | LA    | 70811 | 
| 1456112008  | 22 | BRFD Station 16            | FIRE PROTECTION   | BATON ROUGE FIRE DEPARTMENT           | 1200 ROSENWALD RD     | BATON ROUGE | LA    | 70807 | 
```