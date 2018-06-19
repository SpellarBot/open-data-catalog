# Vehicle, Snowmobile, and Boat Registrations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/vehicle-snowmobile-and-boat-registrations) |
| Metadata | [Link](https://data.ny.gov/api/views/w4pv-hbkt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/w4pv-hbkt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/w4pv-hbkt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | w4pv-hbkt |
| Name | Vehicle, Snowmobile, and Boat Registrations |
| Attribution | NYS DMV |
| Category | Transportation |
| Tags | registration, dmv, vehicle, sticker, boat, snowmobile, trailer |
| Created | 2013-05-13T20:02:52Z |
| Publication Date | 2017-03-21T19:12:46Z |

## Description

This dataset contains the file of vehicle, snowmobile and boat registrations in NYS. Registrations expired more than 2 years are excluded. Records that have a scofflaw, revocation and/or suspension are included with indicators specifying those kinds of records.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | record_type          | Record Type          | text          | text          |
| Yes      | series tag     | vin                  | VIN                  | text          | text          |
| Yes      | series tag     | registration_class   | Registration Class   | text          | text          |
| Yes      | series tag     | city                 | City                 | text          | text          |
| Yes      | series tag     | state                | State                | text          | text          |
| Yes      | series tag     | zip                  | Zip                  | text          | text          |
| Yes      | series tag     | county               | County               | text          | text          |
| No       |                | model_year           | Model Year           | number        | number        |
| Yes      | series tag     | make                 | Make                 | text          | text          |
| Yes      | series tag     | body_type            | Body Type            | text          | text          |
| Yes      | series tag     | fuel_type            | Fuel Type            | text          | text          |
| Yes      | numeric metric | unladen_weight       | Unladen Weight       | number        | number        |
| Yes      | numeric metric | maximum_gross_weight | Maximum Gross Weight | number        | number        |
| Yes      | numeric metric | passengers           | Passengers           | number        | number        |
| Yes      | time           | reg_valid_date       | Reg Valid Date       | calendar_date | calendar_date |
| No       |                | reg_expiration_date  | Reg Expiration Date  | calendar_date | calendar_date |
| Yes      | series tag     | color                | Color                | text          | text          |
| Yes      | series tag     | scofflaw_indicator   | Scofflaw Indicator   | text          | text          |
| Yes      | series tag     | suspension_indicator | Suspension Indicator | text          | text          |
| Yes      | series tag     | revocation_indicator | Revocation Indicator | text          | text          |
```

## Time Field

```ls
Value = reg_valid_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = reg_expiration_date,model_year
```

## Data Commands

```ls
series e:w4pv-hbkt d:2015-06-30T00:00:00.000Z t:zip=14739 t:body_type=PICK t:state=NY t:scofflaw_indicator=N t:city=FRIENDSHIP t:suspension_indicator=N t:fuel_type=GAS t:county=ALLEGANY t:record_type=VEH t:color=MR t:vin=1C6RR7ST6ES327972 t:revocation_indicator=N t:make=RAM t:registration_class=COM m:maximum_gross_weight=6200

series e:w4pv-hbkt d:2015-06-03T00:00:00.000Z t:zip=11951 t:body_type=4DSD t:state=NY t:scofflaw_indicator=N t:city="MASTIC BEACH" t:suspension_indicator=N t:fuel_type=GAS t:county=SUFFOLK t:record_type=VEH t:color=BL t:vin=3N1AB6AP6AL715787 t:revocation_indicator=N t:make=NISSA t:registration_class=PAS m:unladen_weight=2904

series e:w4pv-hbkt d:2015-05-29T00:00:00.000Z t:zip=11514 t:body_type=SUBN t:state=NY t:scofflaw_indicator=N t:city="CARLE PLACE" t:suspension_indicator=N t:fuel_type=GAS t:county=NASSAU t:record_type=VEH t:color=WH t:vin=1C4PJMCS8FW664777 t:revocation_indicator=N t:make=JEEP t:registration_class=PAS m:unladen_weight=3966
```

## Meta Commands

```ls
metric m:unladen_weight p:long l:"Unladen Weight" d:"The weight of a passenger vehicle without any load." t:dataTypeName=number

metric m:maximum_gross_weight p:integer l:"Maximum Gross Weight" d:"The maximum weight that a commercial vehicle is permitted to carry." t:dataTypeName=number

metric m:passengers p:integer l:Passengers d:"The number of passengers that a for-hire vehicle can transport, excluding the driver." t:dataTypeName=number

entity e:w4pv-hbkt l:"Vehicle, Snowmobile, and Boat Registrations" t:attribution="NYS DMV" t:url=https://data.ny.gov/api/views/w4pv-hbkt

property e:w4pv-hbkt t:meta.view v:id=w4pv-hbkt v:category=Transportation v:attributionLink=http://www.dmv.ny.gov/register.htm v:averageRating=0 v:name="Vehicle, Snowmobile, and Boat Registrations" v:attribution="NYS DMV"

property e:w4pv-hbkt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:w4pv-hbkt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:w4pv-hbkt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| record_type | vin               | registration_class | city           | state | zip   | county      | model_year | make  | body_type | fuel_type | unladen_weight | maximum_gross_weight | passengers | reg_valid_date      | reg_expiration_date | color | scofflaw_indicator | suspension_indicator | revocation_indicator | 
| =========== | ================= | ================== | ============== | ===== | ===== | =========== | ========== | ===== | ========= | ========= | ============== | ==================== | ========== | =================== | =================== | ===== | ================== | ==================== | ==================== | 
| VEH         | 1C6RR7ST6ES327972 | COM                | FRIENDSHIP     | NY    | 14739 | ALLEGANY    | 2014       | RAM   | PICK      | GAS       |                | 6200                 |            | 2015-06-30T00:00:00 | 2017-06-29T00:00:00 | MR    | N                  | N                    | N                    | 
| VEH         | 3N1AB6AP6AL715787 | PAS                | MASTIC BEACH   | NY    | 11951 | SUFFOLK     | 2010       | NISSA | 4DSD      | GAS       | 2904           |                      |            | 2015-06-03T00:00:00 | 2017-07-07T00:00:00 | BL    | N                  | N                    | N                    | 
| VEH         | 1C4PJMCS8FW664777 | PAS                | CARLE PLACE    | NY    | 11514 | NASSAU      | 2015       | JEEP  | SUBN      | GAS       | 3966           |                      |            | 2015-05-29T00:00:00 | 2017-06-21T00:00:00 | WH    | N                  | N                    | N                    | 
| VEH         | 1FTBF2B65CEB68700 | PSD                | JAMAICA        | NY    | 11451 | QUEENS      | 2012       | FORD  | PICK      | GAS       | 6125           |                      |            | 2014-10-15T00:00:00 |                     | DK BL | N                  | N                    | N                    | 
| VEH         | JF2SJAGC5FH572589 | PAS                | YORKTOWN HGTS  | NY    | 10598 | WESTCHESTER | 2015       | SUBAR | SUBN      | GAS       | 3397           |                      |            | 2015-05-12T00:00:00 | 2017-06-25T00:00:00 | RD    | N                  | N                    | N                    | 
| VEH         | KMHDU46D19U688986 | PAS                | EAST MEADOW    | NY    | 11554 | NASSAU      | 2009       | HYUND | 4DSD      | GAS       | 2895           |                      |            | 2015-03-06T00:00:00 | 2017-04-05T00:00:00 | GY    | N                  | N                    | N                    | 
| VEH         | SAJDA23C71LF25643 | SRF                | VESTAL         | NY    | 13850 | BROOME      | 2001       | JAGUA | 4DSD      | GAS       | 3900           |                      |            | 2015-08-19T00:00:00 | 2017-09-26T00:00:00 | RD    | N                  | N                    | N                    | 
| VEH         | WVWAP7AN9DE562331 | SRF                | CLAYTON        | NY    | 13624 | JEFFERSON   | 2013       | VOLKS | 4DSD      | GAS       | 3258           |                      |            | 2015-05-07T00:00:00 | 2017-07-29T00:00:00 | BK    | N                  | N                    | N                    | 
| VEH         | 1HGFA16536L135160 | PAS                | RIVERHEAD      | NY    | 11901 | SUFFOLK     | 2006       | HONDA | 4DSD      | GAS       | 2687           |                      |            | 2015-05-20T00:00:00 | 2017-05-19T00:00:00 | BL    | N                  | N                    | N                    | 
| VEH         | 1HGCP26409A186811 | PAS                | HUNTINGTON STA | NY    | 11746 | SUFFOLK     | 2009       | HONDA | 4DSD      | GAS       | 3221           |                      |            | 2015-07-09T00:00:00 | 2017-07-08T00:00:00 | GY    | N                  | N                    | N                    | 
```