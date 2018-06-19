# DYCD after-school programs: Healthy Families

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dycd-after-school-programs-healthy-families-85f7c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yqkf-i7a4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yqkf-i7a4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yqkf-i7a4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yqkf-i7a4 |
| Name | DYCD after-school programs: Healthy Families |
| Attribution | Department of Youth and Community Development (DYCD) |
| Category | Social Services |
| Tags | jobs and economic mobility, community, development, community development, school, child, children, after-school, after-school programs, programs, family, family support, housing assistance and ad... |
| Created | 2011-09-02T21:21:26Z |
| Publication Date | 2013-06-21T19:32:26Z |

## Description

Facilities in New York City, by agency and site, that offer ?Healthy Family? after-school Family Support Programs, such as programs in Housing Assistance and Advocacy, Adult Health Awareness and Prevention, HIV/AIDS Support Services, Young Parent Education and Family Support, Substance Abuse Education and Prevention, and the Fatherhood Initiative.
Update Frequency: Annually

## Columns

```ls
| Included | Schema Type | Field Name            | Name                    | Data Type | Render Type |
| ======== | =========== | ===================== | ======================= | ========= | =========== |
| No       | time        | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | program_type          | PROGRAM TYPE            | text      | text        |
| Yes      | series tag  | program               | PROGRAM                 | text      | text        |
| Yes      | series tag  | site_name             | SITE NAME               | text      | text        |
| Yes      | series tag  | borough_community     | BOROUGH / COMMUNITY     | text      | text        |
| Yes      | series tag  | agency                | AGENCY                  | text      | text        |
| Yes      | series tag  | contact_number        | Contact Number          | text      | text        |
| Yes      | series tag  | grade_level_age_group | Grade Level / Age Group | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yqkf-i7a4 d:2011-09-02T14:21:28.000Z t:contact_number="718 896-2500" t:program_type="Family Support" t:borough_community=Queens t:program="HIV/AIDS Support Services" t:agency="AIDS Center of Queens County, Inc." t:site_name="AIDS Center of Queens County, Inc." m:row_number.yqkf-i7a4=1

series e:yqkf-i7a4 d:2011-09-02T14:21:28.000Z t:contact_number=718.435.7585 t:program_type="Family Support" t:borough_community=Brooklyn t:program="Housing Assistance & Advocacy" t:agency="Brooklyn Housing and Family Services, Inc." t:grade_level_age_group=Adults t:site_name="Brooklyn Housing and Family Services, Inc." m:row_number.yqkf-i7a4=2

series e:yqkf-i7a4 d:2011-09-02T14:21:37.000Z t:contact_number=718.293.0727 t:program_type="Family Support" t:borough_community=Bronx t:program="Housing Assistance & Advocacy" t:agency="Citizens Advice Bureau, Inc." t:grade_level_age_group=Adults t:site_name="Bedford Park" m:row_number.yqkf-i7a4=3
```

## Meta Commands

```ls
metric m:row_number.yqkf-i7a4 p:long l:"Row Number"

entity e:yqkf-i7a4 l:"DYCD after-school programs: Healthy Families" t:attribution="Department of Youth and Community Development (DYCD)" t:url=https://data.cityofnewyork.us/api/views/yqkf-i7a4

property e:yqkf-i7a4 t:meta.view v:id=yqkf-i7a4 v:category="Social Services" v:averageRating=0 v:name="DYCD after-school programs: Healthy Families" v:attribution="Department of Youth and Community Development (DYCD)"

property e:yqkf-i7a4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yqkf-i7a4 t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| :updated_at | program_type   | program                             | site_name                                                  | borough_community | agency                                                     | contact_number | grade_level_age_group | 
| =========== | ============== | =================================== | ========================================================== | ================= | ========================================================== | ============== | ===================== | 
| 1314973288  | Family Support | HIV/AIDS Support Services           | AIDS Center of Queens County, Inc.                         | Queens            | AIDS Center of Queens County, Inc.                         | 718 896-2500   |                       | 
| 1314973288  | Family Support | Housing Assistance & Advocacy       | Brooklyn Housing and Family Services, Inc.                 | Brooklyn          | Brooklyn Housing and Family Services, Inc.                 | 718.435.7585   | Adults                | 
| 1314973297  | Family Support | Housing Assistance & Advocacy       | Bedford Park                                               | Bronx             | Citizens Advice Bureau, Inc.                               | 718.293.0727   | Adults                | 
| 1314973288  | Family Support | Housing Assistance & Advocacy       | Flatbush Development Corporation                           | Brooklyn          | Flatbush Development Corporation                           | 718.859.4763   | Adults                | 
| 1314973288  | Family Support | Older Adult Program                 | Pelham Parkway Senior Center                               | Bronx             | Conscientious Musical Revues                               | 800.624.8474   | Seniors               | 
| 1314973289  | Family Support | Domestic Violence Program           | Edith and Carl Marks Jewish Community House of Bensonhurst | Brooklyn          | Edith and Carl Marks Jewish Community House of Bensonhurst | 718.331.6800   |                       | 
| 1314973289  | Family Support | Domestic Violence Program           | Aging in America, Inc.                                     | Bronx             | Aging In America Community Services, Inc.                  | 718.409.7961   |                       | 
| 1314973289  | Family Support | Adult Health Awareness & Prevention | Kings Bay YM-YWHA, Inc.                                    | Brooklyn          | Kings Bay YM-YWHA, Inc.                                    | 718.648.7703   |                       | 
| 1314973289  | Family Support | Domestic Violence Program           | Fannie Lou Hammer High School                              | Bronx             | The Children?s Aid Society                                 | 212.503.6837   | MS/HS                 | 
| 1314973289  | Family Support | Domestic Violence Program           | I.S. 281                                                   | Brooklyn          | St. Rosalia-Regina Pacis Neighborhood Improvement          | 718.236.5266   | MS/HS                 | 
```