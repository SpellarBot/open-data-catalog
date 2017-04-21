# San Francisco Department of Public Health Flu Shot Locations 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-department-of-public-health-flu-shot-locations-2013-81188) |
| Metadata | [Link](https://data.sfgov.org/api/views/yg87-cd6v) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/yg87-cd6v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/yg87-cd6v/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | yg87-cd6v |
| Name | San Francisco Department of Public Health Flu Shot Locations 2013 |
| Attribution | San Francisco Department of Public Health |
| Category | Health and Social Services |
| Tags | phes, public health, flu, influenza, vaccines, vaccination, san francisco, environmental health, sfdph, sfphes |
| Created | 2013-10-03T17:10:15Z |
| Publication Date | 2013-10-03T17:52:40Z |

## Description

List of San Francisco Department of Public Health clinics offering flu vaccinations throughout the city in fall 2013.This dataset complies with the  emerging Data Specification for Flu Shot Locations. For information about the specification, please see https://github.com/CityOfPhiladelphia/flu-shot-spec.For more information about SFDPH's Influenza Program  www.sfcdcp.org/flu or call 311For more information about SFDPH's Open data Initiatives http://www.sfphes.org/resources/health-data or Contact Cyndy.comerford@sfdph.org

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | facility_name   | facility_name   | text          | text          |
| Yes      | series tag     | facility_id     | facility_id     | text          | number        |
| Yes      | series tag     | facility_type   | facility_type   | text          | text          |
| Yes      | series tag     | street1         | street1         | text          | text          |
| Yes      | series tag     | street2         | street2         | text          | text          |
| Yes      | series tag     | city            | city            | text          | text          |
| Yes      | series tag     | state           | state           | text          | text          |
| Yes      | series tag     | postal_code     | postal_code     | text          | text          |
| Yes      | series tag     | country         | country         | text          | text          |
| No       |                | latitude        | latitude        | number        | number        |
| No       |                | longitude       | longitude       | number        | number        |
| Yes      | series tag     | phone           | phone           | text          | text          |
| Yes      | series tag     | contact         | contact         | text          | text          |
| Yes      | series tag     | url             | url             | text          | text          |
| Yes      | time           | begin_date      | begin_date      | calendar_date | calendar_date |
| No       |                | end_date        | end_date        | calendar_date | calendar_date |
| No       |                | begin_time      | begin_time      | text          | text          |
| No       |                | end_time        | end_time        | text          | text          |
| Yes      | series tag     | eligibility     | eligibility     | text          | text          |
| Yes      | series tag     | documents       | documents       | text          | text          |
| Yes      | numeric metric | cost            | cost            | number        | number        |
| Yes      | series tag     | currency_code   | currency_code   | text          | text          |
| Yes      | series tag     | notes           | notes           | text          | text          |
| No       |                | file_start_date | file_start_date | text          | text          |
| No       |                | file_end_date   | file_end_date   | text          | text          |
```

## Time Field

```ls
Value = begin_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = latitude,longitude,end_date,begin_time,end_time,file_start_date,file_end_date
```

## Data Commands

```ls
series e:yg87-cd6v d:2013-10-12T00:00:00.000Z t:street1="1490 Mason Street" t:phone="(415) 364-7934" t:state=California t:facility_type="Health Center" t:facility_id=904 t:contact="Erin M. Bachus, MPH" t:url=www.sfcdcp.org/flu t:city="San Francisco" t:country="United States" t:facility_name="Chinatown Public Health Center" t:postal_code=94133 t:eligibility="Adults 18 and Over" t:notes="No Medicare or Insurance accepted." t:currency_code=USD m:cost=10

series e:yg87-cd6v d:2013-10-12T00:00:00.000Z t:street1="1490 Mason Street" t:phone="(415) 364-7934" t:state=California t:facility_type="Health Center" t:facility_id=904 t:contact="Erin M. Bachus, MPH" t:url=www.sfcdcp.org/flu t:city="San Francisco" t:country="United States" t:facility_name="Chinatown Public Health Center" t:postal_code=94133 t:eligibility="Adults 18 and Over" t:notes="No Medicare or Insurance accepted." t:currency_code=USD m:cost=10

series e:yg87-cd6v d:2013-10-18T00:00:00.000Z t:street1="1490 Mason Street" t:phone="(415) 364-7934" t:state=California t:facility_type="Health Center" t:facility_id=904 t:contact="Erin M. Bachus, MPH" t:url=www.sfcdcp.org/flu t:city="San Francisco" t:country="United States" t:facility_name="Chinatown Public Health Center" t:postal_code=94133 t:eligibility="Adults 18 and Over" t:notes="No Medicare or Insurance accepted." t:currency_code=USD m:cost=10
```

## Meta Commands

```ls
metric m:cost p:integer l:cost t:dataTypeName=number

entity e:yg87-cd6v l:"San Francisco Department of Public Health Flu Shot Locations 2013" t:attribution="San Francisco Department of Public Health" t:url=https://data.sfgov.org/api/views/yg87-cd6v

property e:yg87-cd6v t:meta.view v:id=yg87-cd6v v:category="Health and Social Services" v:averageRating=0 v:name="San Francisco Department of Public Health Flu Shot Locations 2013" v:attribution="San Francisco Department of Public Health"

property e:yg87-cd6v t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:yg87-cd6v t:meta.view.owner v:id=5w65-feqy v:profileImageUrlMedium=/api/users/5w65-feqy/profile_images/THUMB v:profileImageUrlLarge=/api/users/5w65-feqy/profile_images/LARGE v:screenName="SFDPH Open Data" v:profileImageUrlSmall=/api/users/5w65-feqy/profile_images/TINY v:displayName="SFDPH Open Data"

property e:yg87-cd6v t:meta.view.tableauthor v:id=5w65-feqy v:profileImageUrlMedium=/api/users/5w65-feqy/profile_images/THUMB v:profileImageUrlLarge=/api/users/5w65-feqy/profile_images/LARGE v:screenName="SFDPH Open Data" v:profileImageUrlSmall=/api/users/5w65-feqy/profile_images/TINY v:roleName=editor v:displayName="SFDPH Open Data"
```

## Top Records

```ls
| facility_name                  | facility_id | facility_type | street1           | street2 | city          | state      | postal_code | country       | latitude  | longitude   | phone          | contact             | url                | begin_date          | end_date            | begin_time    | end_time      | eligibility        | documents | cost | currency_code | notes                              | file_start_date | file_end_date | 
| ============================== | =========== | ============= | ================= | ======= | ============= | ========== | =========== | ============= | ========= | =========== | ============== | =================== | ================== | =================== | =================== | ============= | ============= | ================== | ========= | ==== | ============= | ================================== | =============== | ============= | 
| Chinatown Public Health Center | 904         | Health Center | 1490 Mason Street |         | San Francisco | California | 94133       | United States | 37.797205 | -122.411792 | (415) 364-7934 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-12T00:00:00 | 2013-10-12T00:00:00 | 08:30:00-0500 | 11:30:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Chinatown Public Health Center | 904         | Health Center | 1490 Mason Street |         | San Francisco | California | 94133       | United States | 37.797205 | -122.411792 | (415) 364-7934 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-12T00:00:00 | 2013-10-12T00:00:00 | 13:30:00-0500 | 16:30:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Chinatown Public Health Center | 904         | Health Center | 1490 Mason Street |         | San Francisco | California | 94133       | United States | 37.797205 | -122.411792 | (415) 364-7934 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-18T00:00:00 | 2013-10-18T00:00:00 | 13:30:00-0500 | 16:30:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Chinatown Public Health Center | 904         | Health Center | 1490 Mason Street |         | San Francisco | California | 94133       | United States | 37.797205 | -122.411792 | (415) 364-7934 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-25T00:00:00 | 2013-10-25T00:00:00 | 13:30:00-0500 | 16:30:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Chinatown Public Health Center | 904         | Health Center | 1490 Mason Street |         | San Francisco | California | 94133       | United States | 37.797205 | -122.411792 | (415) 364-7934 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-19T00:00:00 | 2013-10-19T00:00:00 | 08:30:00-0500 | 11:30:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Chinatown Public Health Center | 904         | Health Center | 1490 Mason Street |         | San Francisco | California | 94133       | United States | 37.797205 | -122.411792 | (415) 364-7934 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-19T00:00:00 | 2013-10-19T00:00:00 | 13:30:00-0500 | 16:30:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Chinatown Public Health Center | 904         | Health Center | 1490 Mason Street |         | San Francisco | California | 94133       | United States | 37.797205 | -122.411792 | (415) 364-7934 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-26T00:00:00 | 2013-10-26T00:00:00 | 08:30:00-0500 | 11:30:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Chinatown Public Health Center | 904         | Health Center | 1490 Mason Street |         | San Francisco | California | 94133       | United States | 37.797205 | -122.411792 | (415) 364-7934 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-26T00:00:00 | 2013-10-26T00:00:00 | 13:30:00-0500 | 16:30:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Southeast Health Center        | 938         | Health Center | 2401 Keith Street |         | San Francisco | California | 94124       | United States | 37.72572  | -122.391891 | (415) 671-7000 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-18T00:00:00 | 2013-10-18T00:00:00 | 08:00:00-0500 | 10:00:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
| Southeast Health Center        | 938         | Health Center | 2401 Keith Street |         | San Francisco | California | 94124       | United States | 37.72572  | -122.391891 | (415) 671-7000 | Erin M. Bachus, MPH | www.sfcdcp.org/flu | 2013-10-21T00:00:00 | 2013-10-21T00:00:00 | 08:00:00-0500 | 10:00:00-0500 | Adults 18 and Over |           | 10   | USD           | No Medicare or Insurance accepted. |                 |               | 
```