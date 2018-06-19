# Public Right-of-Way Use Permits - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-right-of-way-use-permits-c1cef) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/hwmb-iu8j) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/hwmb-iu8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/hwmb-iu8j/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | hwmb-iu8j |
| Name | Public Right-of-Way Use Permits - Historical |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | permits, historical |
| Created | 2012-03-30T19:38:09Z |
| Publication Date | 2014-06-05T18:12:27Z |

## Description

As described in http://bit.ly/cdotpermitspost, the function of this dataset was replaced by https://data.cityofchicago.org/d/pubx-yq2d on 12/7/2015.  This dataset is historical-only.

The Chicago Department of Transportation (CDOT) reviews applications for permits for the temporary use of the public way for construction projects, parades, festivals, block parties, athletic events, etc.This dataset includes permits applied for, issued, amended and expired with permit start dates beginning January 1, 2011. Note a permit may be amended if any details are changed after the initial issuance. For more information about Public Right-of-Way Use Permits, go to http://bit.ly/15ypkkL.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| No       |             | id                        | ID                        | text          | text          |
| Yes      | series tag  | permit_number             | PERMIT NUMBER             | text          | text          |
| Yes      | series tag  | permit_type_code          | PERMIT TYPE CODE          | text          | text          |
| Yes      | series tag  | permit_type_description   | PERMIT TYPE DESCRIPTION   | text          | text          |
| Yes      | series tag  | company                   | COMPANY                   | text          | text          |
| No       |             | address                   | ADDRESS                   | text          | text          |
| Yes      | series tag  | location_details          | LOCATION DETAILS          | text          | text          |
| Yes      | time        | effective_date            | EFFECTIVE DATE            | calendar_date | calendar_date |
| No       |             | expiration_date           | EXPIRATION DATE           | calendar_date | calendar_date |
| Yes      | series tag  | permit_status_code        | PERMIT STATUS CODE        | text          | text          |
| Yes      | series tag  | permit_status_description | PERMIT STATUS DESCRIPTION | text          | text          |
| No       |             | last_modified_date        | LAST MODIFIED DATE        | calendar_date | calendar_date |
| No       |             | latitude                  | LATITUDE                  | number        | number        |
| No       |             | longitude                 | LONGITUDE                 | number        | number        |
| Yes      | series tag  | location                  | LOCATION                  | text          | text          |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,address,expiration_date,last_modified_date,latitude,longitude
```

## Data Commands

```ls
series e:hwmb-iu8j d:2011-01-04T00:00:00.000Z t:permit_number=777358687 t:permit_status_code=IEXPIRE t:permit_type_description="Street Opening (Curb Lane, Parkway, Sidewalk)" t:location=(41.99340537374761,-87.66051935979738) t:company="PEOPLES GAS LIGHT & COKE CO" t:permit_type_code=PKCSOPEN t:permit_status_description=Expired m:row_number.hwmb-iu8j=1

series e:hwmb-iu8j d:2011-01-04T00:00:00.000Z t:permit_number=777358687 t:permit_status_code=IEXPIRE t:permit_type_description="Street Opening (Curb Lane, Parkway, Sidewalk)" t:location=(41.993674733493634,-87.66023318180571) t:company="PEOPLES GAS LIGHT & COKE CO" t:permit_type_code=PKCSOPEN t:permit_status_description=Expired m:row_number.hwmb-iu8j=2

series e:hwmb-iu8j d:2011-01-04T00:00:00.000Z t:permit_number=777358699 t:permit_status_code=IEXPIRE t:permit_type_description="Street Opening (Curb Lane, Parkway, Sidewalk)" t:location=(42.01219414595151,-87.67471606126013) t:company="PEOPLES GAS LIGHT & COKE CO" t:permit_type_code=PKCSOPEN t:location_details="AMENDED ON JAN 31, 2011 TO EXTEND TO FEB 28, 2011" t:permit_status_description=Expired m:row_number.hwmb-iu8j=3
```

## Meta Commands

```ls
metric m:row_number.hwmb-iu8j p:long l:"Row Number"

entity e:hwmb-iu8j l:"Public Right-of-Way Use Permits - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/hwmb-iu8j

property e:hwmb-iu8j t:meta.view v:id=hwmb-iu8j v:category=Transportation v:attributionLink=http://www.cityofchicago.org/content/city/en/depts/cdot/provdrs/permit/svcs/public_right_of_wayusepermit.html v:averageRating=0 v:name="Public Right-of-Way Use Permits - Historical" v:attribution="City of Chicago"

property e:hwmb-iu8j t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:hwmb-iu8j t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| id                             | permit_number | permit_type_code | permit_type_description                       | company                     | address              | location_details                                                  | effective_date      | expiration_date     | permit_status_code | permit_status_description | last_modified_date  | latitude           | longitude          | location                                | 
| ============================== | ============= | ================ | ============================================= | =========================== | ==================== | ================================================================= | =================== | =================== | ================== | ========================= | =================== | ================== | ================== | ======================================= | 
| 518323496651832349695183235031 | 777358687     | PKCSOPEN         | Street Opening (Curb Lane, Parkway, Sidewalk) | PEOPLES GAS LIGHT & COKE CO | 6136-6146 N BROADWAY |                                                                   | 2011-01-04T00:00:00 | 2011-01-31T00:00:00 | IEXPIRE            | Expired                   | 2011-01-04T15:59:26 | 41.99340537374761  | -87.66051935979738 | (41.99340537374761,-87.66051935979738)  | 
| 518323496651832349695183235045 | 777358687     | PKCSOPEN         | Street Opening (Curb Lane, Parkway, Sidewalk) | PEOPLES GAS LIGHT & COKE CO | 6147-6155 N BROADWAY |                                                                   | 2011-01-04T00:00:00 | 2011-01-31T00:00:00 | IEXPIRE            | Expired                   | 2011-01-04T15:59:26 | 41.993674733493634 | -87.66023318180571 | (41.993674733493634,-87.66023318180571) | 
| 518323507751832350845183235146 | 777358699     | PKCSOPEN         | Street Opening (Curb Lane, Parkway, Sidewalk) | PEOPLES GAS LIGHT & COKE CO | 7124-7199 N CLARK ST | AMENDED ON JAN 31, 2011 TO EXTEND TO FEB 28, 2011                 | 2011-01-04T00:00:00 | 2011-02-28T00:00:00 | IEXPIRE            | Expired                   | 2011-01-31T11:12:10 | 42.01219414595151  | -87.67471606126013 | (42.01219414595151,-87.67471606126013)  | 
| 518448863551844886745184488831 | 781973067     | VEHPARWC         | Parking of Vehicles Citywide (Annual)         | SBC ILLINOIS                |                      | 2011 PARK WORK VEHICLES WORK TO BE PERFORMED BY AT&T VEH#9222639  | 2011-01-01T00:00:00 | 2011-12-31T00:00:00 | IEXPIRE            | Expired                   | 2010-11-15T11:51:26 |                    |                    |                                         | 
| 518448912651844891435184489211 | 781973144     | VEHPARWC         | Parking of Vehicles Citywide (Annual)         | SBC ILLINOIS                |                      | 2011 PARK WORK VEHICLES WORK TO BE PERFORMED BY AT&T VEH#4006009M | 2011-01-01T00:00:00 | 2011-12-31T00:00:00 | IEXPIRE            | Expired                   | 2010-11-15T11:57:56 |                    |                    |                                         | 
| 518448936351844894245184489488 | 781973182     | VEHPARWC         | Parking of Vehicles Citywide (Annual)         | SBC ILLINOIS                |                      | 2011 PARK WORK VEHICLES WORK TO BE PERFORMED BY AT&T VEH#1106418Q | 2011-01-01T00:00:00 | 2011-12-31T00:00:00 | IEXPIRE            | Expired                   | 2010-11-15T12:00:57 |                    |                    |                                         | 
| 518448953851844896715184489768 | 781973221     | VEHPARWC         | Parking of Vehicles Citywide (Annual)         | SBC ILLINOIS                |                      | 2011 PARK WORK VEHICLES WORK TO BE PERFORMED BY AT&T VEH#2076292Q | 2011-01-01T00:00:00 | 2011-12-31T00:00:00 | IEXPIRE            | Expired                   | 2010-11-15T12:04:35 |                    |                    |                                         | 
| 518448992651844899395184489972 | 781973271     | VEHPARWC         | Parking of Vehicles Citywide (Annual)         | SBC ILLINOIS                |                      | 2011 PARK WORK VEHICLES WORK TO BE PERFORMED BY AT&T VEH#2006542Q | 2011-01-01T00:00:00 | 2011-12-31T00:00:00 | IEXPIRE            | Expired                   | 2010-11-15T12:09:22 |                    |                    |                                         | 
| 518449011251844901175184490157 | 781973308     | VEHPARWC         | Parking of Vehicles Citywide (Annual)         | SBC ILLINOIS                |                      | 2011 PARK WORK VEHICLES WORK TO BE PERFORMED BY AT&T VEH#4202021  | 2011-01-01T00:00:00 | 2011-12-31T00:00:00 | IEXPIRE            | Expired                   | 2010-11-15T12:12:30 |                    |                    |                                         | 
| 518449027651844902795184490347 | 781973322     | VEHPARWC         | Parking of Vehicles Citywide (Annual)         | SBC ILLINOIS                |                      | 2011 PARK WORK VEHICLES WORK TO BE PERFORMED BY AT&T VEH#2030838  | 2011-01-01T00:00:00 | 2011-12-31T00:00:00 | IEXPIRE            | Expired                   | 2010-11-15T12:14:56 |                    |                    |                                         | 
```