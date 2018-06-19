# Flu Shot Clinic Locations - 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/flu-shot-clinic-locations-2013-f55c2) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/g5vx-5vqf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/g5vx-5vqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/g5vx-5vqf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | g5vx-5vqf |
| Name | Flu Shot Clinic Locations - 2013 |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | health, flu, 2013 |
| Created | 2013-09-24T17:46:07Z |
| Publication Date | 2013-09-24T17:54:44Z |

## Description

List of Chicago Department of Public Health free flu clinics offered throughout the city. For more information about the flu, go to http://bit.ly/9uNhqG.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | =========== | ===================== | ===================== | ============= | ============= |
| Yes      | time        | date                  | Date                  | calendar_date | calendar_date |
| No       |             | start_time            | Start Time            | text          | text          |
| No       |             | end_time              | End Time              | text          | text          |
| Yes      | series tag  | day                   | Day                   | text          | text          |
| Yes      | series tag  | event                 | Event                 | text          | text          |
| Yes      | series tag  | event_type            | Event Type            | text          | text          |
| No       |             | address               | Address               | text          | text          |
| Yes      | series tag  | city                  | City                  | text          | text          |
| Yes      | series tag  | state                 | State                 | text          | text          |
| Yes      | series tag  | zip                   | Zip                   | text          | number        |
| Yes      | series tag  | phone                 | Phone                 | text          | text          |
| Yes      | series tag  | community_area_number | Community Area Number | text          | number        |
| Yes      | series tag  | community_area_name   | Community Area Name   | text          | text          |
| Yes      | series tag  | ward                  | Ward                  | text          | number        |
| No       |             | latitude              | Latitude              | number        | number        |
| No       |             | longitude             | Longitude             | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_time,end_time,address,latitude,longitude
```

## Data Commands

```ls
series e:g5vx-5vqf d:2013-10-25T00:00:00.000Z t:zip=60617 t:phone="(773) 721-1999" t:ward=10 t:event="10th Ward-Knights of Columbus" t:community_area_name="EAST SIDE" t:event_type=Alderman t:state=IL t:day=Friday t:community_area_number=52 t:city=Chicago m:row_number.g5vx-5vqf=1

series e:g5vx-5vqf d:2013-10-22T00:00:00.000Z t:zip=60608 t:phone="(773) 254-6677" t:ward=11 t:event="11th Ward-McGuane Park" t:community_area_name=BRIDGEPORT t:event_type=Alderman t:state=IL t:day=Tuesday t:community_area_number=60 t:city=Chicago m:row_number.g5vx-5vqf=2

series e:g5vx-5vqf d:2013-11-01T00:00:00.000Z t:zip=60608 t:phone="(773) 523-8250" t:ward=12 t:event="12th Ward-Boys and Girls Club" t:community_area_name="SOUTH LAWNDALE" t:event_type=Alderman t:state=IL t:day=Friday t:community_area_number=30 t:city=Chicago m:row_number.g5vx-5vqf=3
```

## Meta Commands

```ls
metric m:row_number.g5vx-5vqf p:long l:"Row Number"

entity e:g5vx-5vqf l:"Flu Shot Clinic Locations - 2013" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/g5vx-5vqf

property e:g5vx-5vqf t:meta.view v:id=g5vx-5vqf v:category="Health & Human Services" v:attributionLink=http://www.cityofchicago.org/city/en/depts/cdph/provdrs/flu.html v:averageRating=0 v:name="Flu Shot Clinic Locations - 2013" v:attribution="City of Chicago"

property e:g5vx-5vqf t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:g5vx-5vqf t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| date                | start_time | end_time | day       | event                         | event_type | address             | city    | state | zip   | phone          | community_area_number | community_area_name | ward | latitude      | longitude      | 
| =================== | ========== | ======== | ========= | ============================= | ========== | =================== | ======= | ===== | ===== | ============== | ===================== | =================== | ==== | ============= | ============== | 
| 2013-10-25T00:00:00 | 9am        | 3pm      | Friday    | 10th Ward-Knights of Columbus | Alderman   | 11207 S. Ewing      | Chicago | IL    | 60617 | (773) 721-1999 | 52                    | EAST SIDE           | 10   | 41.6915835405 | -87.5351333203 | 
| 2013-10-22T00:00:00 | 9am        | 3pm      | Tuesday   | 11th Ward-McGuane Park        | Alderman   | 2901 S. Poplar Ave. | Chicago | IL    | 60608 | (773) 254-6677 | 60                    | BRIDGEPORT          | 11   | 41.8413489899 | -87.6495076896 | 
| 2013-11-01T00:00:00 | 9am        | 2pm      | Friday    | 12th Ward-Boys and Girls Club | Alderman   | 2950 W. 25th        | Chicago | IL    | 60608 | (773) 523-8250 | 30                    | SOUTH LAWNDALE      | 12   | 41.8465081508 | -87.6997507706 | 
| 2013-10-11T00:00:00 | 10am       | 3pm      | Friday    | 12th Ward-McKinley Park       | Alderman   | 2210 W. Pershing Rd | Chicago | IL    | 60608 | (773) 523-8250 | 59                    | MCKINLEY PARK       | 11   | 41.8231525443 | -87.6805621474 | 
| 2013-11-04T00:00:00 | 10am       | 1pm      | Monday    | 13th Ward-West Lawn Park      | Alderman   | 4233 W. 65th        | Chicago | IL    | 60629 | (773) 581-8000 | 65                    | WEST LAWN           | 13   | 41.7748650121 | -87.7288422505 | 
| 2013-11-15T00:00:00 | 9am        | 3pm      | Friday    | 14th Ward-Polish Highlanders  | Alderman   | 4808 S. Archer Ave. | Chicago | IL    | 60632 | (773) 471-1414 | 57                    | ARCHER HEIGHTS      | 14   | 41.8061421882 | -87.7174279038 | 
| 2013-12-14T00:00:00 | 10am       | 1pm      | Saturday  | 15th Ward Office              | Alderman   | 3045 W. 63rd St.    | Chicago | IL    | 60629 | (773) 863-0220 | 66                    | CHICAGO LAWN        | 15   | 41.7789090127 | -87.7000480109 | 
| 2013-10-19T00:00:00 | 10am       | 1pm      | Saturday  | 16th Ward-Hope Presbyterian   | Alderman   | 1354 W. 61st St.    | Chicago | IL    | 60609 | (773) 434-3399 | 67                    | WEST ENGLEWOOD      | 16   | 41.7832894663 | -87.6593057019 | 
| 2013-11-16T00:00:00 | 10am       | 1pm      | Saturday  | 17th Ward Office              | Alderman   | 7811 S. Racine      | Chicago | IL    | 60620 | (312) 744-7738 | 71                    | AUBURN GRESHAM      | 17   | 41.7520003511 | -87.6536309698 | 
| 2013-11-13T00:00:00 | 10am       | 1pm      | Wednesday | 18th Ward Office              | Alderman   | 8108 S. Western     | Chicago | IL    | 60620 | (773) 471-1991 | 70                    | ASHBURN             | 18   | 41.7461788457 | -87.6829022633 | 
```