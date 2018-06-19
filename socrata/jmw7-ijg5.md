# Family and Support Services Delegate Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/family-and-support-services-delegate-agencies) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/jmw7-ijg5) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/jmw7-ijg5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/jmw7-ijg5/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | jmw7-ijg5 |
| Name | Family and Support Services Delegate Agencies |
| Attribution | City of Chicago |
| Category | Health & Human Services |
| Tags | facilities, children, domestic violence, housing, homelessness, youth, seniors, workforce, human services, family and support services |
| Created | 2015-10-06T16:14:40Z |
| Publication Date | 2015-10-07T21:49:36Z |

## Description

A list of the delegate agencies with which the Department of Family and Support Services has contracted to provide services to residents of Chicago.  For more information on the department and its services, please see http://www.cityofchicago.org/city/en/depts/fss.html.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| No       | time        | :updated_at           | updated_at            | meta_data | meta_data   |
| Yes      | series tag  | agency                | Agency                | text      | text        |
| Yes      | series tag  | program_model         | Program Model         | text      | text        |
| Yes      | series tag  | division              | Division              | text      | text        |
| Yes      | series tag  | site_name             | Site Name             | text      | text        |
| No       |             | address               | Address               | text      | text        |
| Yes      | series tag  | street_number         | Street Number         | text      | number      |
| Yes      | series tag  | street_direction      | Street Direction      | text      | text        |
| Yes      | series tag  | street_name           | Street Name           | text      | text        |
| Yes      | series tag  | street_type           | Street Type           | text      | text        |
| No       |             | address_line_2        | Address Line 2        | text      | text        |
| Yes      | series tag  | city                  | City                  | text      | text        |
| Yes      | series tag  | state                 | State                 | text      | text        |
| Yes      | series tag  | zip                   | ZIP                   | text      | text        |
| Yes      | series tag  | phone_number          | Phone Number          | phone     | phone       |
| Yes      | series tag  | phone_extension       | Phone Extension       | text      | text        |
| Yes      | series tag  | ward                  | Ward                  | text      | number      |
| Yes      | series tag  | community_area        | Community Area        | text      | text        |
| Yes      | series tag  | community_area_number | Community Area Number | text      | number      |
| No       |             | x_coordinate          | X Coordinate          | number    | number      |
| No       |             | y_coordinate          | Y Coordinate          | number    | number      |
| No       |             | latitude              | Latitude              | number    | number      |
| No       |             | longitude             | Longitude             | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,address_line_2,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:jmw7-ijg5 d:2015-10-07T14:44:20.000Z t:zip=60620 t:community_area=ROSELAND t:street_direction=W t:agency="A.M. Bus Company" t:city=Chicago t:program_model="Head Start Support Services" t:ward=21 t:street_name=91ST t:division="Children Services" t:site_name="A.M. Bus Company" t:street_number=100 t:street_type=ST t:phone_number=7733965556 t:state=IL t:community_area_number=49 m:row_number.jmw7-ijg5=1

series e:jmw7-ijg5 d:2015-10-07T14:44:20.000Z t:zip=60649 t:community_area="SOUTH SHORE" t:street_direction=S t:agency="Ada S. McKinley Community Services, Inc." t:city=Chicago t:program_model="Child Care Only" t:ward=7 t:street_name=EXCHANGE t:division="Children Services" t:site_name="McKinley-Ersula Howard" t:street_number=7222 t:street_type=AVE t:phone_number=7732219711 t:state=IL t:community_area_number=43 m:row_number.jmw7-ijg5=2

series e:jmw7-ijg5 d:2015-10-07T14:44:20.000Z t:zip=60653 t:community_area="GRAND BOULEVARD" t:street_direction=S t:agency="Ada S. McKinley Community Services, Inc." t:city=Chicago t:program_model="Child Care Only" t:ward=3 t:street_name=WABASH t:division="Children Services" t:site_name="McKinley-Maggie Drummond" t:street_number=4301 t:street_type=AVE t:phone_number=7733738200 t:state=IL t:community_area_number=38 m:row_number.jmw7-ijg5=3
```

## Meta Commands

```ls
metric m:row_number.jmw7-ijg5 p:long l:"Row Number"

entity e:jmw7-ijg5 l:"Family and Support Services Delegate Agencies" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/jmw7-ijg5

property e:jmw7-ijg5 t:meta.view d:2017-09-25T07:25:28.060Z v:averageRating=0 v:name="Family and Support Services Delegate Agencies" v:attribution="City of Chicago" v:attributionLink=http://www.cityofchicago.org v:id=jmw7-ijg5 v:category="Health & Human Services"

property e:jmw7-ijg5 t:meta.view.owner d:2017-09-25T07:25:28.060Z v:displayName="Jonathan Levy" v:lastNotificationSeenAt=1505253103 v:id=vewm-vupz v:screenName="Jonathan Levy"

property e:jmw7-ijg5 t:meta.view.tableauthor d:2017-09-25T07:25:28.060Z v:displayName="Jonathan Levy" v:lastNotificationSeenAt=1505253103 v:roleName=administrator v:id=vewm-vupz v:screenName="Jonathan Levy"
```

## Top Records

```ls
| :updated_at | agency                                   | program_model                             | division          | site_name                      | address               | street_number | street_direction | street_name | street_type | address_line_2 | city    | state | zip   | phone_number       | phone_extension | ward | community_area  | community_area_number | x_coordinate    | y_coordinate    | latitude   | longitude   | 
| =========== | ======================================== | ========================================= | ================= | ============================== | ===================== | ============= | ================ | =========== | =========== | ============== | ======= | ===== | ===== | ================== | =============== | ==== | =============== | ===================== | =============== | =============== | ========== | =========== | 
| 1444229060  | A.M. Bus Company                         | Head Start Support Services               | Children Services | A.M. Bus Company               | 100 W 91ST ST         | 100           | W                | 91ST        | ST          |                | Chicago | IL    | 60620 | [7733965556, null] |                 | 21   | ROSELAND        | 49                    | 1177171.4675969 | 1844670.948724  | 41.7291099 | -87.6265663 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Child Care Only                           | Children Services | McKinley-Ersula Howard         | 7222 S EXCHANGE AVE   | 7222          | S                | EXCHANGE    | AVE         |                | Chicago | IL    | 60649 | [7732219711, null] |                 | 7    | SOUTH SHORE     | 43                    | 1193938.4160504 | 1857455.5996721 | 41.7637978 | -87.5647275 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Child Care Only                           | Children Services | McKinley-Maggie Drummond       | 4301 S WABASH AVE     | 4301          | S                | WABASH      | AVE         |                | Chicago | IL    | 60653 | [7733738200, null] |                 | 3    | GRAND BOULEVARD | 38                    | 1177471.7477859 | 1876492.6834015 | 41.8164254 | -87.6245056 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Early Head Start                          | Children Services | Children's Center (Halsted)    | 12803 S HALSTED ST    | 12803         | S                | HALSTED     | ST          |                | Chicago | IL    | 60628 | [7732645171, null] |                 | 34   | WEST PULLMAN    | 53                    | 1173373.3538352 | 1819917.5693245 | 41.6612676 | -87.6412084 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Early Head Start                          | Children Services | Children's Center (Western)    | 7956 S WESTERN AVE    | 7956          | S                | WESTERN     | AVE         |                | Chicago | IL    | 60620 | [7734768805, null] |                 | 18   | ASHBURN         | 70                    | 1161726.7759037 | 1851575.7208388 | 41.7483918 | -87.6829531 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Early Head Start                          | Children Services | Montessori Academy             | 11025 S HALSTED ST    | 11025         | S                | HALSTED     | ST          |                | Chicago | IL    | 60628 | [7734680033, null] |                 | 34   | ROSELAND        | 49                    | 1172990.7188443 | 1831627.7101645 | 41.6934105 | -87.6422649 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Early Head Start – Child Care Partnership | Children Services | Children's Center (Halsted)    | 12803 S HALSTED ST    | 12803         | S                | HALSTED     | ST          |                | Chicago | IL    | 60628 | [7732645171, null] |                 | 34   | WEST PULLMAN    | 53                    | 1173373.3538352 | 1819917.5693245 | 41.6612676 | -87.6412084 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Early Head Start – Child Care Partnership | Children Services | Children's Center (Western)    | 7956 S WESTERN AVE    | 7956          | S                | WESTERN     | AVE         |                | Chicago | IL    | 60620 | [7734768805, null] |                 | 18   | ASHBURN         | 70                    | 1161726.7759037 | 1851575.7208388 | 41.7483918 | -87.6829531 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Early Head Start – Child Care Partnership | Children Services | J & L Family Learning Day Care | 11640 S WENTWORTH AVE | 11640         | S                | WENTWORTH   | AVE         |                | Chicago | IL    | 60628 | [7738211808, null] |                 | 34   | WEST PULLMAN    | 53                    | 1176992.3104918 | 1827574.1163402 | 41.6821978 | -87.6277358 | 
| 1444229060  | Ada S. McKinley Community Services, Inc. | Early Head Start – Child Care Partnership | Children Services | Little Hands                   | 7146 S ASHLAND AVE    | 7146          | S                | ASHLAND     | AVE         |                | Chicago | IL    | 60636 | [7734710662, null] |                 | 17   | WEST ENGLEWOOD  | 67                    | 1166884.9951001 | 1857124.9398149 | 41.763511  | -87.6638933 | 
```