# Hartford Family Resources Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hartford-family-resources-inventory) |
| Metadata | [Link](https://data.hartford.gov/api/views/qu2v-7rbh) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/qu2v-7rbh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/qu2v-7rbh/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | qu2v-7rbh |
| Name | Hartford Family Resources Inventory |
| Created | 2015-12-22T20:31:32Z |
| Publication Date | 2015-12-22T20:33:41Z |

## Description

Hartford Family Resources Inventory

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | objectid                  | OBJECTID                  | text      | number      |
| Yes      | series tag  | organization_name         | Organization_Name         | text      | text        |
| No       |             | address                   | Address                   | text      | text        |
| Yes      | series tag  | apt_suite                 | Apt_Suite                 | text      | text        |
| Yes      | series tag  | city                      | City                      | text      | text        |
| Yes      | series tag  | zipcode                   | ZipCode                   | text      | text        |
| Yes      | series tag  | telephone                 | Telephone                 | text      | text        |
| Yes      | series tag  | email_address             | Email_Address             | text      | text        |
| Yes      | series tag  | website                   | Website                   | text      | text        |
| Yes      | series tag  | simbology                 | Simbology                 | text      | text        |
| Yes      | series tag  | civic_engagement          | Civic_Engagement          | text      | text        |
| Yes      | series tag  | early_childhood_education | Early_Childhood_Education | text      | text        |
| Yes      | series tag  | home_day_care             | Home_Day_Care             | text      | text        |
| Yes      | series tag  | government_agencies       | Government_Agencies       | text      | text        |
| Yes      | series tag  | schools                   | Schools                   | text      | text        |
| Yes      | series tag  | higher_education          | Higher_Education          | text      | text        |
| Yes      | series tag  | support_services          | Support_Services          | text      | text        |
| Yes      | series tag  | workforce_development     | Workforce_Development     | text      | text        |
| Yes      | series tag  | youth_family_enrichment   | Youth_Family_Enrichment   | text      | text        |
| Yes      | series tag  | other                     | OTHER                     | text      | text        |
| Yes      | series tag  | mission                   | Mission                   | text      | text        |
| Yes      | series tag  | field20                   | Field20                   | text      | text        |
| Yes      | series tag  | school_type               | School_Type               | text      | text        |
| Yes      | series tag  | school_grades             | School_Grades             | text      | text        |
| Yes      | series tag  | name                      | NAME                      | text      | text        |
| Yes      | time        | updated                   | Updated                   | date      | date        |
| No       |             | xcoord                    | xcoord                    | number    | number      |
| No       |             | ycoord                    | ycoord                    | number    | number      |
```

## Time Field

```ls
Value = updated
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,xcoord,ycoord
```

## Data Commands

```ls
series e:qu2v-7rbh d:2015-02-17T00:00:00.000Z t:school_type=Elementary t:website=http://www.hasdas.com/ t:zipcode=6112 t:simbology=Schools t:city=HARTFORD t:schools=Schools t:mission="Serve pre-kindergarten through grade eight children with a quality Christian education." t:field20=Schools t:name="UPPER ALBANY" t:objectid=1 t:telephone="(860) 724-5777" t:organization_name="HARTFORD AREA SEVENTH DAY ADVENTISTE PRE-SCHOOL (PK-9)" t:school_grades=PK-9 t:email_address=office@hasdas.com m:row_number.qu2v-7rbh=1

series e:qu2v-7rbh d:2015-02-17T00:00:00.000Z t:school_type=Elementary t:website=http://www.hartfordschools.org t:zipcode=6114 t:simbology=Schools t:city=HARTFORD t:schools=Schools t:mission="Create a challenging, stimulating, and safe environment that promotes attainment of Academic Standards of the State of Connecticut, and that gives students the ability to effectively participate in the global economy." t:field20=Schools t:name="BARRY SQUARE" t:objectid=2 t:telephone="(860) 695-3080" t:organization_name="ALFRED E. BURR ELEMENTARY SCHOOL (PK 4-8)" t:school_grades=PK-8 t:email_address=welcomecenter@hartfordschools.org m:row_number.qu2v-7rbh=2

series e:qu2v-7rbh d:2015-02-17T00:00:00.000Z t:school_type=Elementary t:other="Mandarin Chinese language study for students" t:website=http://www.hartfordschools.org t:zipcode=6114 t:simbology=Schools t:city=HARTFORD t:schools=Schools t:mission="Provide our students with an intensive, comprehensive education focusing on Chinese Mandarin language and East Asian cultures." t:field20=Schools t:name="SOUTH END" t:objectid=3 t:telephone="(860) 695-2400" t:organization_name="ASIAN STUDIES ACADEMY AT BELLIZZI SCHOOL (PK 4-8)" t:school_grades=PK-8 t:email_address=welcomecenter@hartfordschools.org m:row_number.qu2v-7rbh=3
```

## Meta Commands

```ls
metric m:row_number.qu2v-7rbh p:long l:"Row Number"

entity e:qu2v-7rbh l:"Hartford Family Resources Inventory" t:url=https://data.hartford.gov/api/views/qu2v-7rbh

property e:qu2v-7rbh t:meta.view v:id=qu2v-7rbh v:averageRating=0 v:name="Hartford Family Resources Inventory"

property e:qu2v-7rbh t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:qu2v-7rbh t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| objectid | organization_name                                                | address             | apt_suite | city     | zipcode | telephone      | email_address                     | website                        | simbology | civic_engagement | early_childhood_education | home_day_care | government_agencies | schools | higher_education | support_services | workforce_development | youth_family_enrichment | other                                        | mission                                                                                                                                                                                                                       | field20 | school_type | school_grades | name             | updated    | xcoord  | ycoord | 
| ======== | ================================================================ | =================== | ========= | ======== | ======= | ============== | ================================= | ============================== | ========= | ================ | ========================= | ============= | =================== | ======= | ================ | ================ | ===================== | ======================= | ============================================ | ============================================================================================================================================================================================================================= | ======= | =========== | ============= | ================ | ========== | ======= | ====== | 
| 1        | HARTFORD AREA SEVENTH DAY ADVENTISTE PRE-SCHOOL (PK-9)           | 474 WOODLAND ST     |           | HARTFORD | 6112    | (860) 724-5777 | office@hasdas.com                 | http://www.hasdas.com/         | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | Serve pre-kindergarten through grade eight children with a quality Christian education.                                                                                                                                       | Schools | Elementary  | PK-9          | UPPER ALBANY     | 1424131200 | 1014837 | 846008 | 
| 2        | ALFRED E. BURR ELEMENTARY SCHOOL (PK 4-8)                        | 400 WETHERSFIELD AV |           | HARTFORD | 6114    | (860) 695-3080 | welcomecenter@hartfordschools.org | http://www.hartfordschools.org | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | Create a challenging, stimulating, and safe environment that promotes attainment of Academic Standards of the State of Connecticut, and that gives students the ability to effectively participate in the global economy.     | Schools | Elementary  | PK-8          | BARRY SQUARE     | 1424131200 | 1021092 | 832173 | 
| 3        | ASIAN STUDIES ACADEMY AT BELLIZZI SCHOOL (PK 4-8)                | 215 SOUTH ST        |           | HARTFORD | 6114    | (860) 695-2400 | welcomecenter@hartfordschools.org | http://www.hartfordschools.org | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         | Mandarin Chinese language study for students | Provide our students with an intensive, comprehensive education focusing on Chinese Mandarin language and East Asian cultures.                                                                                                | Schools | Elementary  | PK-8          | SOUTH END        | 1424131200 | 1018877 | 828295 | 
| 4        | L.W. BATCHELDER ELEMENTARY (PK 4-8)                              | 757 NEW BRITAIN AV  |           | HARTFORD | 6106    | (860) 695-2720 | welcomecenter@hartfordschools.org | http://www.hartfordschools.org | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | Create a community of active learners, where we all interact collaboratively with parents and community organizations to develop and implement educational programs ensuring academic and social excellence for all           | Schools | Elementary  | PK-8          | SOUTH WEST       | 1424131200 | 1011557 | 827729 | 
| 5        | BREAKTHROUGH II ELEMETARY SCHOOL (PK 3-6)                        | 395 LYME ST         |           | HARTFORD | 6112    | (860) 695-6380 | info@breakthroughnorth.org        | http://www.hartfordschools.org | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | For staff, families, and community members of diverse backgrounds to work in partnership to develop students as models of outstanding character.                                                                              | Schools | Elementary  | PK-8          | BLUE HILLS       | 1424131200 | 1012426 | 853665 | 
| 6        | BREAKTHROUGH MAGNET SCHOOL (PK3-8)                               | 290 BROOKFIELD ST   |           | HARTFORD | 6106    | (860) 695-5700 | welcomecenter@hartfordschools.org | http://www.hartfordschools.org | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | For staff, families, and community members of diverse backgrounds to work in partnership to develop students as models of outstanding character.                                                                              | Schools | Elementary  | PK-8          | BEHIND THE ROCKS | 1424131200 | 1011754 | 832424 | 
| 7        | JOHN C CLARK, JR. ELEMENTARY & MIDDLE SCHOOL (PK 4-8)            | 75 CLARK ST         |           | HARTFORD | 6120    | (860) 695-3240 | welcomecenter@hartfordschools.org | http://www.hartfordschools.org | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | Hartford?s system of schools exists to provide all students with access to participation in a global economy through attainment of Academic Standards of the State of Connecticut and readiness for post-secondary education. | Schools | Elementary  | PK-8          | NORTHEAST        | 1424131200 | 1019643 | 847497 | 
| 8        | E.B. KENNELLY ELEMENTARY SCHOOL (PK 4-8)                         | 180 WHITE ST        |           | HARTFORD | 6114    | (860) 695-3860 | welcomecenter@hartfordschools.org | http://www.hartfordschools.org | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | Provide a dynamic learning community, with teachers and parents partnering to create a positive, high- achieving environment, where differences are valued.                                                                   | Schools | Elementary  | PK-8          | SOUTH WEST       | 1424131200 | 1015116 | 828563 | 
| 9        | ENVIRONMENTAL SCIENCES MAGNET SCHOOL AT MARY HOOKER (PK 3-8)     | 440 BROADVIEW TER   |           | HARTFORD | 6106    | (860) 695-3760 | welcomecenter@hartfordschools.org | http://www.hartfordschools.org | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | Serve students from Pre-Kindergarten (age 4) through Grade 8 and ensure that all students attain high academic achievement through theme-based instruction in a safe, responsive learning community.                          | Schools | Elementary  | PK-8          | BEHIND THE ROCKS | 1424131200 | 1013125 | 830961 | 
| 10       | THELMA ELLIS DICKERSON'S JUMOKE ACADEMY ELEMENTARY SCHOOL (PK-4) | 250 BLUE HILLS AV   |           | HARTFORD | 6112    | (860) 527-0575 | Unlisted/Unavailable              | http://www.jumokeacademy.org   | Schools   |                  |                           |               |                     | Schools |                  |                  |                       |                         |                                              | Prepare children to successfully compete in the global marketplace and to overcome cultural, social, and/or economic challenges.                                                                                              | Schools | Elementary  | PK-4          | UPPER ALBANY     | 1424131200 | 1014229 | 848950 | 
```