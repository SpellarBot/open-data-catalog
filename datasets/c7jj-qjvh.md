# CPS Schools 2013-2014 Academic Year

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cps-schools-2013-2014-academic-year-5c8c1) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/c7jj-qjvh) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/c7jj-qjvh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/c7jj-qjvh/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | c7jj-qjvh |
| Name | CPS Schools 2013-2014 Academic Year |
| Attribution | Chicago Public Schools |
| Category | Education |
| Tags | cps, education |
| Created | 2013-10-01T22:21:46Z |
| Publication Date | 2013-10-22T05:09:28Z |

## Description

List of CPS schools for the 2013-2014 academic year. This dataset includes various identifiers used to identify school districts, including names; local, state, and federal IDs; and geographic descriptions on the location of each school.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag     | schoolid                  | SchoolID                  | text      | number      |
| Yes      | series tag     | schoolname                | SchoolName                | text      | text        |
| Yes      | series tag     | fullname                  | FullName                  | text      | text        |
| Yes      | series tag     | schoolname2               | SchoolName2               | text      | text        |
| Yes      | series tag     | isbe_name                 | ISBE Name                 | text      | text        |
| Yes      | series tag     | street_number             | Street Number             | text      | number      |
| Yes      | series tag     | street_direction          | Street Direction          | text      | text        |
| Yes      | series tag     | street_name               | Street Name               | text      | text        |
| Yes      | series tag     | city                      | City                      | text      | text        |
| Yes      | series tag     | state                     | State                     | text      | text        |
| Yes      | series tag     | zip                       | ZIP                       | text      | text        |
| Yes      | series tag     | nces_id                   | NCES ID                   | text      | text        |
| Yes      | numeric metric | cps_unit                  | CPS Unit                  | number    | number      |
| Yes      | series tag     | isbe_id                   | ISBE ID                   | text      | text        |
| Yes      | series tag     | oracleid                  | OracleID                  | text      | number      |
| Yes      | series tag     | class                     | Class                     | text      | text        |
| Yes      | series tag     | school_type               | School Type               | text      | text        |
| Yes      | series tag     | s_type                    | S_Type                    | text      | text        |
| Yes      | series tag     | school_category           | School Category           | text      | text        |
| Yes      | series tag     | governance                | Governance                | text      | text        |
| Yes      | series tag     | charter_type              | Charter Type              | text      | text        |
| Yes      | series tag     | grade_structure           | Grade Structure           | text      | text        |
| Yes      | series tag     | attending_grades          | Attending Grades          | text      | text        |
| Yes      | series tag     | programtypes              | ProgramTypes              | text      | text        |
| Yes      | series tag     | ward                      | Ward                      | text      | number      |
| Yes      | series tag     | community_area_number     | Community Area Number     | text      | number      |
| Yes      | series tag     | community_area            | Community Area            | text      | text        |
| Yes      | series tag     | il_senate_district        | IL Senate District        | text      | number      |
| Yes      | series tag     | il_rep_district           | IL Rep District           | text      | number      |
| Yes      | series tag     | us_congressional_district | US Congressional District | text      | number      |
| Yes      | series tag     | geographicarea            | GeographicArea            | text      | text        |
| Yes      | series tag     | geographic_area_number    | Geographic Area Number    | text      | number      |
| Yes      | series tag     | cook_county_district      | Cook County District      | text      | number      |
| Yes      | numeric metric | census_block              | Census Block              | number    | number      |
| No       |                | latitude                  | Latitude                  | number    | number      |
| No       |                | longitude                 | Longitude                 | number    | number      |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:c7jj-qjvh d:2013-01-01T00:00:00.000Z t:school_type=Regular t:schoolid=609772 t:street_name="Avenue H" t:state=IL t:us_congressional_district=2.0 t:city=Chicago t:isbe_id=150162990252051 t:cook_county_district=4.0 t:nces_id=170993000884 t:street_number=10810 t:fullname="Jane Addams Elementary School" t:zip=60617 t:s_type="District, non-alternative" t:class=CPS t:il_rep_district=25.0 t:schoolname2=Addams t:attending_grades=PK-8th t:geographic_area_number=2.0 t:isbe_name="Addams Elem School" t:grade_structure=ES t:oracleid=22021.0 t:schoolname=Addams t:ward=10.0 t:geographicarea="Far East Side" t:street_direction=S t:community_area="East Side" t:programtypes=NA|| t:il_senate_district=13.0 t:community_area_number=52.0 t:school_category=ES t:governance=District m:census_block=170315205001002 m:cps_unit=2020

series e:c7jj-qjvh d:2013-01-01T00:00:00.000Z t:school_type=Regular t:schoolid=609773 t:street_name="Seminary Ave" t:state=IL t:us_congressional_district=5.0 t:city=Chicago t:isbe_id=150162990252052 t:cook_county_district=10.0 t:nces_id=170993000763 t:street_number=2851 t:fullname="Louis A Agassiz Elementary School" t:zip=60657 t:s_type="District, non-alternative" t:class=CPS t:il_rep_district=12.0 t:schoolname2=Agassiz t:attending_grades=PK-8th t:geographic_area_number=29.0 t:isbe_name="Agassiz Elem School" t:grade_structure=ES t:oracleid=22031.0 t:schoolname=Agassiz t:ward=44.0 t:geographicarea="Lincoln Park" t:street_direction=N t:community_area="Lake View" t:programtypes=NA|| t:il_senate_district=6.0 t:community_area_number=6.0 t:school_category=ES t:governance=District m:census_block=170310629002002 m:cps_unit=2030

series e:c7jj-qjvh d:2013-01-01T00:00:00.000Z t:school_type=Regular t:schoolid=610513 t:street_name="Wells St" t:state=IL t:us_congressional_district=3.0 t:city=Chicago t:isbe_id=150162990250848 t:cook_county_district=2.0 t:nces_id=170993006055 t:street_number=3630 t:fullname="Air Force Academy High School" t:zip=60609 t:s_type="District, non-alternative" t:class=CPS t:il_rep_district=6.0 t:schoolname2="Air Force HS" t:attending_grades=9th-12th t:geographic_area_number=18.0 t:isbe_name="Air Force Acad High School" t:grade_structure=HS t:oracleid=45231.0 t:schoolname="Air Force HS" t:ward=11.0 t:geographicarea="Bridgeport - Chinatown" t:street_direction=S t:community_area="Armour Square" t:programtypes=Military|| t:il_senate_district=3.0 t:community_area_number=34.0 t:school_category=HS t:governance=District m:census_block=170313406001012 m:cps_unit=1055
```

## Meta Commands

```ls
metric m:cps_unit p:float l:"CPS Unit" t:dataTypeName=number

metric m:census_block p:long l:"Census Block" t:dataTypeName=number

entity e:c7jj-qjvh l:"CPS Schools 2013-2014 Academic Year" t:attribution="Chicago Public Schools" t:url=https://data.cityofchicago.org/api/views/c7jj-qjvh

property e:c7jj-qjvh t:meta.view v:id=c7jj-qjvh v:category=Education v:attributionLink=http://www.cps.edu/Schools/Pages/Schools.aspx v:averageRating=0 v:name="CPS Schools 2013-2014 Academic Year" v:attribution="Chicago Public Schools"

property e:c7jj-qjvh t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:c7jj-qjvh t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| schoolid | schoolname      | fullname                              | schoolname2     | isbe_name                      | street_number | street_direction | street_name  | city    | state | zip   | nces_id      | cps_unit | isbe_id         | oracleid | class | school_type | s_type                    | school_category | governance | charter_type             | grade_structure | attending_grades | programtypes              | ward | community_area_number | community_area | il_senate_district | il_rep_district | us_congressional_district | geographicarea         | geographic_area_number | cook_county_district | census_block    | latitude         | longitude         | 
| ======== | =============== | ===================================== | =============== | ============================== | ============= | ================ | ============ | ======= | ===== | ===== | ============ | ======== | =============== | ======== | ===== | =========== | ========================= | =============== | ========== | ======================== | =============== | ================ | ========================= | ==== | ===================== | ============== | ================== | =============== | ========================= | ====================== | ====================== | ==================== | =============== | ================ | ================= | 
| 609772   | Addams          | Jane Addams Elementary School         | Addams          | Addams Elem School             | 10810         | S                | Avenue H     | Chicago | IL    | 60617 | 170993000884 | 2020.0   | 150162990252051 | 22021.0  | CPS   | Regular     | District, non-alternative | ES              | District   |                          | ES              | PK-8th           | NA||                      | 10.0 | 52.0                  | East Side      | 13.0               | 25.0            | 2.0                       | Far East Side          | 2.0                    | 4.0                  | 170315205001002 | 41.7935651919    | -87.6414185840999 | 
| 609773   | Agassiz         | Louis A Agassiz Elementary School     | Agassiz         | Agassiz Elem School            | 2851          | N                | Seminary Ave | Chicago | IL    | 60657 | 170993000763 | 2030.0   | 150162990252052 | 22031.0  | CPS   | Regular     | District, non-alternative | ES              | District   |                          | ES              | PK-8th           | NA||                      | 44.0 | 6.0                   | Lake View      | 6.0                | 12.0            | 5.0                       | Lincoln Park           | 29.0                   | 10.0                 | 170310629002002 | 41.8496748576    | -87.6253515103    | 
| 610513   | Air Force HS    | Air Force Academy High School         | Air Force HS    | Air Force Acad High School     | 3630          | S                | Wells St     | Chicago | IL    | 60609 | 170993006055 | 1055.0   | 150162990250848 | 45231.0  | CPS   | Regular     | District, non-alternative | HS              | District   |                          | HS              | 9th-12th         | Military||                | 11.0 | 34.0                  | Armour Square  | 3.0                | 6.0             | 3.0                       | Bridgeport - Chinatown | 18.0                   | 2.0                  | 170313406001012 | 41.8277744098    | -87.6775785338    | 
| 610212   | Albany Park     | Albany Park Multicultural Academy     | Albany Park     | Albany Park Multicultural Elem | 4929          | N                | Sawyer Ave   | Chicago | IL    | 60625 | 170993004962 | 6290.0   | 150162990252850 | 32011.0  | CPS   | Regular     | District, non-alternative | MS              | District   |                          | ES              | 7th-8th          | NA||                      | 39.0 | 14.0                  | Albany Park    | 8.0                | 15.0            | 5.0                       | Albany Irving          | 27.0                   | 12.0                 | 170311402001008 | 41.6962349093999 | -87.6271470318999 | 
| 609774   | Alcott ES       | Louisa May Alcott Elementary School   | Alcott ES       | Alcott Elem School             | 2625          | N                | Orchard St   | Chicago | IL    | 60614 | 170993000804 | 2040.0   | 150162990252053 | 22041.0  | CPS   | Regular     | District, non-alternative | ES              | District   |                          | ES              | PK-8th           | NA||                      | 43.0 | 7.0                   | Lincoln Park   | 6.0                | 11.0            | 5.0                       | Lincoln Park           | 29.0                   | 10.0                 | 170310702001011 | 41.6987389279    | -87.532939427     | 
| 610524   | Alcott HS       | Alcott High School for the Humanities | Alcott HS       | Alcott Humanities High School  | 2957          | N                | Hoyne Ave    | Chicago | IL    | 60618 | 170993006072 | 8035.0   | 150162990250849 | 22041.0  | CPS   | Regular     | District, non-alternative | HS              | District   |                          | ES-HS           | 9th-12th         | AVID||                    | 1.0  | 5.0                   | North Center   | 6.0                | 11.0            | 5.0                       | Lincoln Park           | 29.0                   | 8.0                  | 170310514002003 | 41.7712216704    | -87.6664932336999 | 
| 609848   | Aldridge        | Ira F Aldridge Elementary School      | Aldridge        | Aldridge Elem School           | 630           | E                | 131st St     | Chicago | IL    | 60827 | 170993001168 | 2710.0   | 150162990252054 | 22641.0  | CPS   | Regular     | District, non-alternative | ES              | District   |                          | ES              | PK-8th           | Early_Childhood_Program|| | 9.0  | 54.0                  | Riverdale      | 15.0               | 29.0            | 2.0                       | Far South Side         | 22.0                   | 5.0                  | 170315401022010 | 41.7898283982    | -87.6224160902    | 
| 400012   | Amandla Chtr HS | Amandla Charter High School           | Amandla Chtr HS | Amandla Elem Charter Sch       | 6800          | S                | Stewart Ave  | Chicago | IL    | 60621 | 170993005986 | 2035.0   | 15016299025227C | 66551.0  | CPS   | Charter     | Charter                   | HS              | Charter    | Non-replicating Charters | ES-HS           | 5th-10th         | NA||                      | 6.0  | 68.0                  | Englewood      | 16.0               | 32.0            | 1.0                       | Englewood              | 4.0                    | 3.0                  | 170316812003013 | 41.7707911322999 | -87.6352295467    | 
| 609780   | Ames            | Ames Middle School                    | Ames            | Ames Middle School             | 1920          | N                | Hamlin Ave   | Chicago | IL    | 60647 | 170993002618 | 2090.0   | 150162990252912 | 41111.0  | CPS   | Regular     | District, non-alternative | MS              | District   |                          | ES              | 7th-8th          | NA||                      | 26.0 | 22.0                  | Logan Square   | 2.0                | 4.0             | 4.0                       | Logan                  | 9.0                    | 8.0                  | 170312229001004 | 41.8338264794999 | -87.6506520970999 | 
| 609695   | Amundsen HS     | Roald Amundsen High School            | Amundsen HS     | Amundsen High School           | 5110          | N                | Damen Ave    | Chicago | IL    | 60625 | 170993000587 | 1210.0   | 150162990250001 | 46031.0  | CPS   | Regular     | District, non-alternative | HS              | District   |                          | HS              | 9th-12th         | IB||AVID||                | 47.0 | 4.0                   | Lincoln Square | 7.0                | 13.0            | 5.0                       | Ravenswood             | 30.0                   | 12.0                 | 170310404022002 | 41.8900046421    | -87.7073328694999 | 
```