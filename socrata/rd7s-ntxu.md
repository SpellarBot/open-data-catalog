# Parking Garage and Lot Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-garage-and-lot-inventory-6b68b) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/rd7s-ntxu) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/rd7s-ntxu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/rd7s-ntxu/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | rd7s-ntxu |
| Name | Parking Garage and Lot Inventory |
| Category | Transportation |
| Tags | parking, lot, garage |
| Created | 2013-08-07T14:23:09Z |
| Publication Date | 2015-08-05T15:45:33Z |

## Description

This dataset includes parking space inventory information for Montgomery County Public Parking Facilities. Update Frequency: Monthly

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | district                     | District                     | text          | text          |
| Yes      | series tag     | facilitynumber               | Facility Number              | text          | text          |
| No       |                | address_of_facility          | Address                      | text          | text          |
| Yes      | series tag     | hours_requiring_payment      | Hours Requiring Payment      | text          | text          |
| Yes      | series tag     | payment_options              | Payment Options              | text          | text          |
| Yes      | numeric metric | floors                       | Floors                       | number        | number        |
| Yes      | numeric metric | clearance_height_feet        | Clearance Height (Feet)      | number        | number        |
| Yes      | numeric metric | clearance_height_inch        | Clearance Height (Inches)    | number        | number        |
| Yes      | series tag     | facility_name                | Facility Name                | text          | text          |
| Yes      | numeric metric | total_capacity               | Total Capacity               | number        | number        |
| Yes      | numeric metric | ada_spaces                   | ADA Spaces                   | number        | number        |
| Yes      | numeric metric | ada_van_spaces               | ADA Van Spaces               | number        | number        |
| Yes      | numeric metric | bike_spaces                  | Bike Spaces                  | number        | number        |
| Yes      | numeric metric | car_spaces                   | Car Spaces                   | number        | number        |
| Yes      | numeric metric | motorcycle_spaces            | Motorcycle Spaces            | number        | number        |
| Yes      | numeric metric | motorcycle_area              | Motorcycle Area              | number        | text          |
| Yes      | series tag     | otherinformation             | Other Information            | text          | text          |
| No       |                | centroid_lat                 | Latitude                     | number        | number        |
| Yes      | numeric metric | centroid_lng                 | Longitude                    | number        | number        |
| Yes      | numeric metric | five_min_spaces              | 5 Minute Limit               | number        | number        |
| Yes      | numeric metric | thirty_min_limit             | 30 Minute Limit              | number        | number        |
| Yes      | numeric metric | one_hour_limit               | 1 Hour Limit                 | number        | number        |
| Yes      | numeric metric | two_hour_limit               | 2 Hour Limit                 | number        | number        |
| Yes      | numeric metric | three_hour_limit             | 3 Hour Limit                 | number        | number        |
| Yes      | numeric metric | four_hour_limit              | 4 Hour Limit                 | number        | number        |
| Yes      | numeric metric | nine_hour_limit              | 9 Hour Limit                 | number        | number        |
| Yes      | numeric metric | twelve_hour_limit            | 12 Hour Limit                | number        | number        |
| Yes      | numeric metric | fifteen_hour_limit           | 15 Hour Limit                | number        | number        |
| Yes      | numeric metric | pcs                          | Parking Convenience Stickers | number        | number        |
| Yes      | numeric metric | carpool                      | Carpool                      | number        | number        |
| Yes      | numeric metric | restricted                   | Restricted                   | number        | text          |
| Yes      | series tag     | inactive                     | Inactive                     | text          | text          |
| Yes      | series tag     | url_to_additionalinformation | Additional Information       | text          | text          |
| Yes      | time           | data_modified_datetime       | Last Update                  | calendar_date | calendar_date |
```

## Time Field

```ls
Value = data_modified_datetime
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_of_facility,centroid_lat
```

## Data Commands

```ls
series e:rd7s-ntxu d:2016-11-01T00:00:00.000Z t:inactive=false t:payment_options=Coins t:facility_name="Colonial Lane Lot" t:facilitynumber="LOT 20" t:url_to_additionalinformation="http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp" t:district="Silver Spring" t:hours_requiring_payment="7:00AM-7:00PM Monday through Friday" m:twelve_hour_limit=31 m:total_capacity=41 m:centroid_lng=-77.02775 m:three_hour_limit=8 m:fifteen_hour_limit=0 m:clearance_height_feet=0 m:restricted=39 m:five_min_spaces=0 m:carpool=0 m:motorcycle_area=0 m:nine_hour_limit=0 m:four_hour_limit=0 m:ada_van_spaces=2 m:one_hour_limit=0 m:floors=0 m:pcs=0 m:ada_spaces=0 m:clearance_height_inch=0 m:motorcycle_spaces=0 m:thirty_min_limit=0 m:car_spaces=39 m:bike_spaces=0 m:two_hour_limit=0

series e:rd7s-ntxu d:2016-11-01T00:00:00.000Z t:inactive=false t:payment_options=Coins t:facility_name="Georgia Avenue Lot" t:facilitynumber="LOT 48" t:url_to_additionalinformation="http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp" t:district="Montgomery Hills" t:hours_requiring_payment="9:00AM-6:00PM Monday through Friday" m:twelve_hour_limit=0 m:total_capacity=38 m:centroid_lng=-77.03988 m:three_hour_limit=0 m:fifteen_hour_limit=0 m:clearance_height_feet=0 m:restricted=34 m:five_min_spaces=0 m:carpool=0 m:motorcycle_area=0 m:nine_hour_limit=13 m:four_hour_limit=0 m:ada_van_spaces=2 m:one_hour_limit=5 m:floors=0 m:pcs=0 m:ada_spaces=0 m:clearance_height_inch=0 m:motorcycle_spaces=2 m:thirty_min_limit=0 m:car_spaces=34 m:bike_spaces=0 m:two_hour_limit=16

series e:rd7s-ntxu d:2016-11-01T00:00:00.000Z t:inactive=false t:payment_options="Bills, Credit Cards, Coins" t:facility_name="Cameron-Second Garage" t:facilitynumber="GAR 07" t:url_to_additionalinformation="http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp" t:district="Silver Spring" t:hours_requiring_payment="7:00AM-7:00PM Monday through Friday" m:twelve_hour_limit=1242 m:total_capacity=1398 m:centroid_lng=-77.03095 m:three_hour_limit=0 m:fifteen_hour_limit=0 m:clearance_height_feet=7 m:restricted=1356 m:five_min_spaces=0 m:carpool=14 m:motorcycle_area=9 m:nine_hour_limit=0 m:four_hour_limit=2 m:ada_van_spaces=9 m:one_hour_limit=0 m:floors=6 m:pcs=0 m:ada_spaces=20 m:clearance_height_inch=0 m:motorcycle_spaces=0 m:thirty_min_limit=0 m:car_spaces=1358 m:bike_spaces=2 m:two_hour_limit=112
```

## Meta Commands

```ls
metric m:floors p:integer l:Floors d:"The existing number of levels in the facility including the basement, where applicable." t:dataTypeName=number

metric m:clearance_height_feet p:integer l:"Clearance Height (Feet)" d:"The maximum vertical clearance permitted within the facility." t:dataTypeName=number

metric m:clearance_height_inch p:integer l:"Clearance Height (Inches)" d:"The maximum vertical clearance permitted within the facility." t:dataTypeName=number

metric m:total_capacity p:integer l:"Total Capacity" d:"The total number of vehicular, motorcycle and bicycle spaces within the facility." t:dataTypeName=number

metric m:ada_spaces p:integer l:"ADA Spaces" d:"The total number of accessible parking spaces for cars within the facility. The total number of accessible parking spaces for vans within the facility." t:dataTypeName=number

metric m:ada_van_spaces p:integer l:"ADA Van Spaces" d:"The total number of accessible parking spaces for vans within the facility." t:dataTypeName=number

metric m:bike_spaces p:integer l:"Bike Spaces" d:"The total number of bicycle spaces found on bicycle-specific racks within the facility." t:dataTypeName=number

metric m:car_spaces p:integer l:"Car Spaces" d:"The total number of vehicular spaces, excluding ADA and ADA-Van spaces, within the facility." t:dataTypeName=number

metric m:motorcycle_spaces p:integer l:"Motorcycle Spaces" d:"The total number of individual motorcycle parking spaces within the facility." t:dataTypeName=number

metric m:motorcycle_area p:integer l:"Motorcycle Area" d:"The total number of motorcycles designed to park in the motorcycle area within the facility." t:dataTypeName=number

metric m:centroid_lng p:float l:Longitude d:"Depicts a digital representation of the facility's location expressed in longitudinal degrees." t:dataTypeName=number

metric m:five_min_spaces p:integer l:"5 Minute Limit" d:"The total number of spaces within the facility whose posted duration is 5 minutes." t:dataTypeName=number

metric m:thirty_min_limit p:integer l:"30 Minute Limit" d:"The total number of spaces within the facility whose posted duration is 30 minutes." t:dataTypeName=number

metric m:one_hour_limit p:integer l:"1 Hour Limit" d:"The total number of spaces within the facility whose posted duration is 1 hour." t:dataTypeName=number

metric m:two_hour_limit p:integer l:"2 Hour Limit" d:"The total number of spaces within the facility whose posted duration is 2 hours." t:dataTypeName=number

metric m:three_hour_limit p:integer l:"3 Hour Limit" d:"The total number of spaces within the facility whose posted duration is 3 hours." t:dataTypeName=number

metric m:four_hour_limit p:integer l:"4 Hour Limit" d:"The total number of spaces within the facility whose posted duration is 4 hours." t:dataTypeName=number

metric m:nine_hour_limit p:integer l:"9 Hour Limit" d:"The total number of spaces within the facility whose posted duration is 9 hours." t:dataTypeName=number

metric m:twelve_hour_limit p:integer l:"12 Hour Limit" d:"The total number of spaces within the facility whose posted duration is 12 hours." t:dataTypeName=number

metric m:fifteen_hour_limit p:integer l:"15 Hour Limit" d:"The total number of spaces within the facility whose posted duration is 15 hours." t:dataTypeName=number

metric m:pcs p:integer l:"Parking Convenience Stickers" d:"The total number of spaces within the facility allocated to Parking Convenience Sticker (PCS) users." t:dataTypeName=number

metric m:carpool p:integer l:Carpool d:"The total number of spaces within the facility allocated to Carpool users." t:dataTypeName=number

metric m:restricted p:integer l:Restricted d:"The total number of spaces within the facility whose use is restricted to specified groups and is not open to the public." t:dataTypeName=number

entity e:rd7s-ntxu l:"Parking Garage and Lot Inventory" t:url=https://data.montgomerycountymd.gov/api/views/rd7s-ntxu

property e:rd7s-ntxu t:meta.view v:id=rd7s-ntxu v:category=Transportation v:averageRating=0 v:name="Parking Garage and Lot Inventory"

property e:rd7s-ntxu t:meta.view.license v:name="Public Domain"

property e:rd7s-ntxu t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:rd7s-ntxu t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| district         | facilitynumber | address_of_facility                | hours_requiring_payment               | payment_options            | floors | clearance_height_feet | clearance_height_inch | facility_name             | total_capacity | ada_spaces | ada_van_spaces | bike_spaces | car_spaces | motorcycle_spaces | motorcycle_area | otherinformation | centroid_lat | centroid_lng | five_min_spaces | thirty_min_limit | one_hour_limit | two_hour_limit | three_hour_limit | four_hour_limit | nine_hour_limit | twelve_hour_limit | fifteen_hour_limit | pcs | carpool | restricted | inactive | url_to_additionalinformation                                                      | data_modified_datetime | 
| ================ | ============== | ================================== | ===================================== | ========================== | ====== | ===================== | ===================== | ========================= | ============== | ========== | ============== | =========== | ========== | ================= | =============== | ================ | ============ | ============ | =============== | ================ | ============== | ============== | ================ | =============== | =============== | ================= | ================== | === | ======= | ========== | ======== | ================================================================================= | ====================== | 
| Silver Spring    | LOT 20         | 8212 Colonial Lane                 | 7:00AM-7:00PM Monday through Friday   | Coins                      | 0      | 0                     | 0                     | Colonial Lane Lot         | 41             | 0          | 2              | 0           | 39         | 0                 | 0               |                  | 38.99173     | -77.02775    | 0               | 0                | 0              | 0              | 8                | 0               | 0               | 31                | 0                  | 0   | 0       | 39         | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Montgomery Hills | LOT 48         | 9401 Georgia Avenue                | 9:00AM-6:00PM Monday through Friday   | Coins                      | 0      | 0                     | 0                     | Georgia Avenue Lot        | 38             | 0          | 2              | 0           | 34         | 2                 | 0               |                  | 39.00896     | -77.03988    | 0               | 0                | 5              | 16             | 0                | 0               | 13              | 0                 | 0                  | 0   | 0       | 34         | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Silver Spring    | GAR 07         | 8530 Cameron Street (Fenwick Lane) | 7:00AM-7:00PM Monday through Friday   | Bills, Credit Cards, Coins | 6      | 7                     | 0                     | Cameron-Second Garage     | 1398           | 20         | 9              | 2           | 1358       | 0                 | 9               |                  | 38.99671     | -77.03095    | 0               | 0                | 0              | 112            | 0                | 2               | 0               | 1242              | 0                  | 0   | 14      | 1356       | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Silver Spring    | LOT 09         | 8040 Kennett Street                | 7:00AM-7:00PM Monday through Friday   | Coins                      | 0      | 0                     | 0                     | Kennett Street Garage Lot | 67             | 0          | 0              | 0           | 67         | 0                 | 0               |                  | 38.98816     | -77.02877    | 0               | 0                | 0              | 4              | 0                | 0               | 0               | 62                | 0                  | 0   | 0       | 66         | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Silver Spring    | GAR 16         | 8005 13th Street                   | 7:00AM-7:00PM Monday through Friday   | Bills, Credit Cards, Coins | 2      | 8                     | 2                     | King - 13th Street Garage | 170            | 4          | 4              | 4           | 152        | 6                 | 0               |                  | 38.98694     | -77.02821    | 0               | 0                | 0              | 0              | 0                | 0               | 0               | 152               | 0                  | 0   | 0       | 152        | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Bethesda         | GAR 49         | 7601 Woodmont Avenue               | 7:00AM-10:00PM Monday through Friday  | Bills, Credit Cards, Coins | 5      | 6                     | 8                     | Metropolitan Garage       | 999            | 24         | 0              | 4           | 961        | 0                 | 10              |                  | 38.98815     | -77.09862    | 0               | 0                | 0              | 0              | 106              | 0               | 0               | 4                 | 828                | 0   | 4       | 938        | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Wheaton          | LOT 13         | 11219 Grandview Avenue             | 9:00AM-6:00PM Monday through Saturday | Coins                      | 0      | 0                     | 0                     | Wheaton Market Place Lot  | 164            | 4          | 4              | 0           | 152        | 4                 | 0               |                  | 39.03933     | -77.05211    | 0               | 0                | 13             | 70             | 33               | 0               | 35              | 0                 | 0                  | 0   | 0       | 151        | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Silver Spring    | GAR 21         | 1000 Spring Street                 | 7:00AM-7:00PM Monday through Friday   | Bills, Credit Cards, Coins | 1      | 7                     | 0                     | Spring-Colesville Garage  | 49             | 4          | 0              | 0           | 45         | 0                 | 0               |                  | 38.99903     | -77.02701    | 0               | 0                | 0              | 0              | 0                | 0               | 0               | 0                 | 0                  | 0   | 0       | 0          | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Bethesda         | LOT 43         | 8009 Woodmont Avenue               | 7:00AM-10:00PM Monday through Friday  | Coins                      | 0      | 0                     | 0                     | Woodmont Avenue           | 39             | 0          | 2              | 0           | 37         | 0                 | 0               |                  | 38.99034     | -77.09631    | 0               | 0                | 11             | 26             | 0                | 0               | 0               | 0                 | 0                  | 0   | 0       | 37         | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
| Bethesda         | GAR 49         | 7601 Woodmont Avenue               | 7:00AM-10:00PM Monday through Friday  | Bills, Credit Cards, Coins | 5      | 6                     | 8                     | Metropolitan Garage       | 999            | 24         | 0              | 4           | 961        | 0                 | 10              |                  | 38.98521     | -77.09681    | 0               | 0                | 0              | 0              | 106              | 0               | 0               | 4                 | 828                | 0   | 4       | 938        | false    | http://www6.montgomerycountymd.gov/dpktmpl.asp?url=/content/DOT/parking/index.asp | 2016-11-01T00:00:00    | 
```