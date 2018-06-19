# New York City Farmers Markets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-city-farmers-markets-574c2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/j8gx-kc43) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/j8gx-kc43/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/j8gx-kc43/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | j8gx-kc43 |
| Name | New York City Farmers Markets |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | farmers market, location, health |
| Created | 2013-10-25T16:21:22Z |
| Publication Date | 2017-03-21T19:33:16Z |

## Description

Location and facility information for New York City farmers markets.

## Columns

```ls
| Included | Schema Type | Field Name         | Name                   | Data Type | Render Type |
| ======== | =========== | ================== | ====================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | facilityname       | Farmers Market Name    | text      | text        |
| Yes      | series tag  | facilityaddinfo    | Additional Information | text      | text        |
| Yes      | series tag  | facilitystreetname | Street Address         | text      | text        |
| Yes      | series tag  | facilitycity       | Borough                | text      | text        |
| Yes      | series tag  | facilitystate      | State                  | text      | text        |
| Yes      | series tag  | facilityzipcode    | Zip Code               | text      | text        |
| No       |             | latitude           | Latitude               | number    | number      |
| No       |             | longitude          | Longitude              | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = latitude,longitude
```

## Data Commands

```ls
series e:j8gx-kc43 d:2017-03-21T19:33:05.000Z t:facilityaddinfo="Spend $5 in EBT and get a $2 Health Buck coupon.<br><br><b>Program Website:</b> <a  href=''http://bisselgardens.org/thegardens/farmersmarket/'' target=''_blank''>http://www.grownyc.org.</a>" t:facilitystate=NY t:facilityname="Bissel Gardens Farmers' Market" t:facilitystreetname="Baychester Ave & E 241st St" t:facilitycity=Bronx t:facilityzipcode=10470 m:row_number.j8gx-kc43=1

series e:j8gx-kc43 d:2017-03-21T19:33:05.000Z t:facilityaddinfo="Spend $5 in EBT and get a $2 Health Buck coupon.<br><br><b>Program Website:</b> <a  href=''http://www.grownyc.org.'' target=''_blank''>http://www.grownyc.org.</a>" t:facilitystate=NY t:facilityname="Bronx Borough Hall Greenmarket" t:facilitystreetname="Grand Concourse bet 161st & 162nd Sts" t:facilitycity=Bronx t:facilityzipcode=10451 m:row_number.j8gx-kc43=2

series e:j8gx-kc43 d:2017-03-21T19:33:05.000Z t:facilityaddinfo="Spend $5 in EBT and get a $2 Health Buck coupon.<br><br><b>Program Website:</b> <a  href=''http://www.harvesthomefm.org'' target=''_blank''>http://www.harvesthomefm.org</a>" t:facilitystate=NY t:facilityname="Harvest Home Forest Avenue Farmers' Market" t:facilitystreetname="Forest Ave bet Westchester Ave & 156th St" t:facilitycity=Bronx t:facilityzipcode=10455 m:row_number.j8gx-kc43=3
```

## Meta Commands

```ls
metric m:row_number.j8gx-kc43 p:long l:"Row Number"

entity e:j8gx-kc43 l:"New York City Farmers Markets" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/j8gx-kc43

property e:j8gx-kc43 t:meta.view v:id=j8gx-kc43 v:category=Health v:averageRating=0 v:name="New York City Farmers Markets" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:j8gx-kc43 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:j8gx-kc43 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | facilityname                               | facilityaddinfo                                                                                       | facilitystreetname                        | facilitycity | facilitystate | facilityzipcode | latitude | longitude | 
| =========== | ========================================== | ===================================================================================================== | ========================================= | ============ | ============= | =============== | ======== | ========= | 
| 1490124785  | Bissel Gardens Farmers' Market             | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.grownyc.org.            | Baychester Ave & E 241st St               | Bronx        | NY            | 10470           | 41       | -74       | 
| 1490124785  | Bronx Borough Hall Greenmarket             | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.grownyc.org.            | Grand Concourse bet 161st & 162nd Sts     | Bronx        | NY            | 10451           | 41       | -74       | 
| 1490124785  | Harvest Home Forest Avenue Farmers' Market | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.harvesthomefm.org       | Forest Ave bet Westchester Ave & 156th St | Bronx        | NY            | 10455           | 41       | -74       | 
| 1490124785  | Harvest Home Mt. Eden Farmers' Market      | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.harvesthomefm.org       | Mt. Eden & Morris Aves, at Claremont Park | Bronx        | NY            | 10457           | 41       | -74       | 
| 1490124785  | Harvest Home Sunday Farmers' Market        | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.harvesthomefm.org       | Grand Concourse                           | Bronx        | NY            | 10456           | 41       | -74       | 
| 1490124785  | La Familia Verde Farmers' Market           | Spend $5 in EBT and get a $2 Health Buck coupon.                                                      | Tremont Avenue                            | Bronx        | NY            | 10457           | 41       | -74       | 
| 1490124785  | Learn It, Grow It, Eat It Youthmarket      | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.grownyc.org/youthmarket | 169th St & Boston Rd, at McKinley Park    | Bronx        | NY            | 10456           | 41       | -74       | 
| 1490124785  | Lincoln Hospital Greenmarket               | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.grownyc.org.            | 149th St bet Park & Morris Aves           | Bronx        | NY            | 10451           | 41       | -74       | 
| 1490124785  | Marble Hill Youthmarket                    | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.grownyc.org/youthmarket | 225th St bet Broadway & Exterior St.      | Bronx        | NY            | 10034           | 41       | -74       | 
| 1490124785  | New York Botanical Gardens Greenmarket     | Spend $5 in EBT and get a $2 Health Buck coupon.

Program Website: http://www.grownyc.org.            | Southern Blvd                             | Bronx        | NY            | 10467           | 41       | -74       | 
```