# Montgomery College Enrollment Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/montgomery-college-enrollment-data) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/wmr2-6hn6) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/wmr2-6hn6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/wmr2-6hn6/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | wmr2-6hn6 |
| Name | Montgomery College Enrollment Data |
| Attribution | Montgomery County, MD |
| Category | Education |
| Tags | community college education higher learning |
| Created | 2016-05-17T20:46:38Z |
| Publication Date | 2016-05-17T20:48:19Z |

## Description

Montgomery College Student Enrollment Data Update Frequency: Annually

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| No       | time           | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | numeric metric | fall_term                | Fall Term                | number    | number      |
| Yes      | series tag     | student_type             | Student Type             | text      | text        |
| Yes      | series tag     | student_status           | Student Status           | text      | text        |
| Yes      | series tag     | gender                   | Gender                   | text      | text        |
| Yes      | series tag     | ethnicity                | Ethnicity                | text      | text        |
| Yes      | series tag     | race                     | Race                     | text      | text        |
| Yes      | series tag     | attending_germantown     | Attending Germantown     | text      | text        |
| Yes      | series tag     | attending_rockville      | Attending Rockville      | text      | text        |
| Yes      | series tag     | attending_takoma_park_ss | Attending Takoma Park/SS | text      | text        |
| Yes      | series tag     | attend_day_or_evening    | Attend Day or Evening    | text      | text        |
| Yes      | series tag     | mc_program_description   | MC Program Description   | text      | text        |
| Yes      | series tag     | age_group                | Age Group                | text      | text        |
| Yes      | series tag     | hs_category              | HS Category              | text      | text        |
| Yes      | series tag     | mcps_high_school         | MCPS High School         | text      | text        |
| Yes      | series tag     | city_in_md               | City in MD               | text      | text        |
| Yes      | series tag     | state                    | State                    | text      | text        |
| Yes      | series tag     | zip                      | ZIP                      | text      | number      |
| Yes      | series tag     | county_in_md             | County in MD             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wmr2-6hn6 d:2016-05-18T08:33:08.000Z t:zip=20816 t:mc_program_description="Health Sciences (Pre-Clinical Studies)" t:county_in_md=Montgomery t:attending_rockville=Yes t:state=MD t:race=White t:student_status=Full-Time t:city_in_md=Bethesda t:age_group="25 - 29" t:attending_takoma_park_ss=No t:gender=Female t:attend_day_or_evening="Day Only" t:student_type=Continuing t:ethnicity="Not Hispanic" t:hs_category="Foreign Country" t:attending_germantown=Yes m:fall_term=2015

series e:wmr2-6hn6 d:2016-05-18T08:33:08.000Z t:zip=20832 t:mc_program_description="Building Trades Technology (AA & AAS)" t:county_in_md=Montgomery t:attending_rockville=Yes t:state=MD t:race=White t:student_status=Part-Time t:city_in_md=Olney t:age_group="21 - 24" t:attending_takoma_park_ss=No t:gender=Male t:attend_day_or_evening="Evening Only" t:student_type=Continuing t:ethnicity="Not Hispanic" t:hs_category=MCPS t:attending_germantown=No t:mcps_high_school="Sherwood High School" m:fall_term=2015

series e:wmr2-6hn6 d:2016-05-18T08:33:08.000Z t:zip=20877 t:mc_program_description="Computer Gaming & Simulation (AA - All Tracks)" t:county_in_md=Montgomery t:attending_rockville=Yes t:state=MD t:race=Black t:student_status=Part-Time t:city_in_md=Gaithersburg t:age_group="20 or Younger" t:attending_takoma_park_ss=No t:gender=Male t:attend_day_or_evening="Day & Evening" t:student_type=Continuing t:ethnicity="Not Hispanic" t:hs_category=MCPS t:attending_germantown=No t:mcps_high_school="Quince Orchard Sr High School" m:fall_term=2015
```

## Meta Commands

```ls
metric m:fall_term p:integer l:"Fall Term" d:"Year of the School Term reported." t:dataTypeName=number

entity e:wmr2-6hn6 l:"Montgomery College Enrollment Data" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/wmr2-6hn6

property e:wmr2-6hn6 t:meta.view v:id=wmr2-6hn6 v:category=Education v:averageRating=0 v:name="Montgomery College Enrollment Data" v:attribution="Montgomery County, MD"

property e:wmr2-6hn6 t:meta.view.license v:name="Public Domain"

property e:wmr2-6hn6 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:wmr2-6hn6 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| :updated_at | fall_term | student_type | student_status | gender | ethnicity    | race     | attending_germantown | attending_rockville | attending_takoma_park_ss | attend_day_or_evening | mc_program_description                         | age_group     | hs_category       | mcps_high_school               | city_in_md    | state | zip   | county_in_md | 
| =========== | ========= | ============ | ============== | ====== | ============ | ======== | ==================== | =================== | ======================== | ===================== | ============================================== | ============= | ================= | ============================== | ============= | ===== | ===== | ============ | 
| 1463560388  | 2015      | Continuing   | Full-Time      | Female | Not Hispanic | White    | Yes                  | Yes                 | No                       | Day Only              | Health Sciences (Pre-Clinical Studies)         | 25 - 29       | Foreign Country   |                                | Bethesda      | MD    | 20816 | Montgomery   | 
| 1463560388  | 2015      | Continuing   | Part-Time      | Male   | Not Hispanic | White    | No                   | Yes                 | No                       | Evening Only          | Building Trades Technology (AA & AAS)          | 21 - 24       | MCPS              | Sherwood High School           | Olney         | MD    | 20832 | Montgomery   | 
| 1463560388  | 2015      | Continuing   | Part-Time      | Male   | Not Hispanic | Black    | No                   | Yes                 | No                       | Day & Evening         | Computer Gaming & Simulation (AA - All Tracks) | 20 or Younger | MCPS              | Quince Orchard Sr High School  | Gaithersburg  | MD    | 20877 | Montgomery   | 
| 1463560388  | 2015      | New          | Full-Time      | Male   | Not Hispanic | Asian    | No                   | Yes                 | No                       | Day Only              | Graphic Design (AA, AAS, & AFA - All Tracks)   | 20 or Younger | MCPS              | Thomas Sprigg Wootton High Sch | North Potomac | MD    | 20878 | Montgomery   | 
| 1463560388  | 2015      | New          | Full-Time      | Female | Hispanic     | White    | No                   | Yes                 | No                       | Day & Evening         | General Studies (AA - All Tracks)              | 20 or Younger | MCPS              | Montgomery Blair High School   | Silver Spring | MD    | 20906 | Montgomery   | 
| 1463560388  | 2015      | Continuing   | Full-Time      | Female | Hispanic     | Hispanic | Yes                  | No                  | No                       | Day Only              | General Studies (AA - All Tracks)              | 20 or Younger | MCPS              | Clarksburg High School         | Germantown    | MD    | 20876 | Montgomery   | 
| 1463560388  | 2015      | Continuing   | Full-Time      | Female | Hispanic     | Hispanic | Yes                  | No                  | No                       | Day Only              | General Studies (AA - All Tracks)              | 20 or Younger | MCPS              | Clarksburg High School         | Germantown    | MD    | 20876 | Montgomery   | 
| 1463560388  | 2015      | New          | Full-Time      | Male   | Hispanic     | Black    | No                   | No                  | Yes                      | Day Only              | Engineering Science (AA & AS - All Tracks)     | 20 or Younger | Mont.County Other |                                | Silver Spring | MD    | 20903 | Montgomery   | 
| 1463560388  | 2015      | Continuing   | Part-Time      | Female | Not Hispanic | Black    | No                   | No                  | Yes                      | Day Only              | Education / Teacher Education (AA & AAT)       | 21 - 24       | Foreign Country   |                                | Silver Spring | MD    | 20901 | Montgomery   | 
| 1463560388  | 2015      | Continuing   | Part-Time      | Male   | Not Hispanic | White    | No                   | Yes                 | No                       | Day Only              | Business / International Business (AA)         | 25 - 29       | Other State       |                                | Rockville     | MD    | 20851 | Montgomery   | 
```