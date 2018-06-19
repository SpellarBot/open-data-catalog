# For Hire Vehicles (FHV) - Active and Inactive Vehicles

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/for-hire-vehicles-fhv-active-and-inactive-vehicles) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8wbx-tsch) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8wbx-tsch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8wbx-tsch/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8wbx-tsch |
| Name | For Hire Vehicles (FHV) - Active and Inactive Vehicles |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | fhv, for hire, for-hire, for-hire-vehicles, drivers, taxi, active, inactive |
| Created | 2015-07-16T17:33:32Z |
| Publication Date | 2017-04-20T19:02:42Z |

## Description

TLC authorized For-Hire vehicles that are active or inactive. This list is accurate to the date and time represented in the Last Date Updated and Last Time Updated fields. For inquiries about the contents of this dataset, please email licensinginquiries@tlc.nyc.gov.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag  | active                   | Active                   | text          | text          |
| Yes      | series tag  | vehicle_license_number   | Vehicle License Number   | text          | text          |
| Yes      | series tag  | name                     | Name                     | text          | text          |
| Yes      | series tag  | license_type             | License Type             | text          | text          |
| Yes      | time        | expiration_date          | Expiration Date          | calendar_date | calendar_date |
| Yes      | series tag  | permit_license_number    | Permit License Number    | text          | text          |
| Yes      | series tag  | dmv_license_plate_number | DMV License Plate Number | text          | text          |
| Yes      | series tag  | vehicle_vin_number       | Vehicle VIN Number       | text          | text          |
| Yes      | series tag  | wheelchair_accessible    | Wheelchair Accessible    | text          | text          |
| No       |             | certification_date       | Certification Date       | calendar_date | calendar_date |
| No       |             | hack_up_date             | Hack Up Date             | calendar_date | calendar_date |
| Yes      | series tag  | vehicle_year             | Vehicle Year             | text          | number        |
| Yes      | series tag  | base_number              | Base Number              | text          | text          |
| Yes      | series tag  | base_name                | Base Name                | text          | text          |
| Yes      | series tag  | base_type                | Base Type                | text          | text          |
| Yes      | series tag  | veh                      | VEH                      | text          | text          |
| Yes      | series tag  | base_telephone_number    | Base Telephone Number    | text          | text          |
| Yes      | series tag  | website                  | Website                  | text          | text          |
| No       |             | base_address             | Base Address             | text          | text          |
| Yes      | series tag  | reason                   | Reason                   | text          | text          |
| No       |             | order_date               | Order Date               | calendar_date | calendar_date |
| No       |             | last_date_updated        | Last Date Updated        | calendar_date | calendar_date |
| Yes      | series tag  | last_time_updated        | Last Time Updated        | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = certification_date,hack_up_date,base_address,order_date,last_date_updated
```

## Data Commands

```ls
series e:8wbx-tsch d:2018-04-09T00:00:00.000Z t:vehicle_license_number=C37255 t:license_type="FOR HIRE VEHICLE" t:base_telephone_number=(212)666-3939 t:reason=G t:last_time_updated=13:25 t:name="LOPEZ, CECILIO" t:vehicle_year=2008 t:active=YES t:dmv_license_plate_number=T432999C t:base_type=LIVERY t:base_number=B02228 t:base_name="SPECIAL RADIO DISP.CORP." t:vehicle_vin_number=4T1BE46K18U240801 m:row_number.8wbx-tsch=1

series e:8wbx-tsch d:2019-04-20T00:00:00.000Z t:vehicle_license_number=C37386 t:license_type="FOR HIRE VEHICLE" t:base_telephone_number=(718)846-4500 t:reason=G t:last_time_updated=13:25 t:name=VILLANUEVA,,RAMON,,O t:vehicle_year=2012 t:active=YES t:dmv_license_plate_number=T428156C t:base_type=LIVERY t:base_number=B00900 t:base_name="BIG Q CAR SVC. INC." t:vehicle_vin_number=4T1BF1FK7CU162870 m:row_number.8wbx-tsch=2

series e:8wbx-tsch d:2019-04-24T00:00:00.000Z t:vehicle_license_number=C37350 t:license_type="FOR HIRE VEHICLE" t:base_telephone_number=(718)805-4500 t:reason=G t:last_time_updated=13:25 t:name="DIALLO, SALIMON" t:vehicle_year=2011 t:active=YES t:dmv_license_plate_number=T432862C t:base_type=LIVERY t:base_number=B02338 t:base_name="DESTINY CAR & LIMO SERVICE INC." t:vehicle_vin_number=2LNBL8CV6BX756003 m:row_number.8wbx-tsch=3
```

## Meta Commands

```ls
metric m:row_number.8wbx-tsch p:long l:"Row Number"

entity e:8wbx-tsch l:"For Hire Vehicles (FHV) - Active and Inactive Vehicles" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/8wbx-tsch

property e:8wbx-tsch t:meta.view v:id=8wbx-tsch v:category=Transportation v:averageRating=0 v:name="For Hire Vehicles (FHV) - Active and Inactive Vehicles" v:attribution="Taxi and Limousine Commission (TLC)"

property e:8wbx-tsch t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8wbx-tsch t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| active | vehicle_license_number | name                   | license_type     | expiration_date     | permit_license_number | dmv_license_plate_number | vehicle_vin_number | wheelchair_accessible | certification_date  | hack_up_date        | vehicle_year | base_number | base_name                           | base_type | veh | base_telephone_number | website                 | base_address                             | reason | order_date | last_date_updated   | last_time_updated | 
| ====== | ====================== | ====================== | ================ | =================== | ===================== | ======================== | ================== | ===================== | =================== | =================== | ============ | =========== | =================================== | ========= | === | ===================== | ======================= | ======================================== | ====== | ========== | =================== | ================= | 
| YES    | C37255                 | LOPEZ, CECILIO         | FOR HIRE VEHICLE | 2018-04-09T00:00:00 |                       | T432999C                 | 4T1BE46K18U240801  |                       |                     |                     | 2008         | B02228      | SPECIAL RADIO DISP.CORP.            | LIVERY    |     | (212)666-3939         |                         | 72 WEST 109 STREET NEW YORK NY 10025     | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37386                 | VILLANUEVA,,RAMON,,O   | FOR HIRE VEHICLE | 2019-04-20T00:00:00 |                       | T428156C                 | 4T1BF1FK7CU162870  |                       |                     |                     | 2012         | B00900      | BIG Q CAR SVC. INC.                 | LIVERY    |     | (718)846-4500         |                         | 86-29 102 STREET RICHMOND HILL NY 11418  | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37350                 | DIALLO, SALIMON        | FOR HIRE VEHICLE | 2019-04-24T00:00:00 |                       | T432862C                 | 2LNBL8CV6BX756003  |                       |                     |                     | 2011         | B02338      | DESTINY CAR & LIMO SERVICE INC.     | LIVERY    |     | (718)805-4500         |                         | 110-01 101 AVENUE RICHMONDHILL NY 11419  | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37355                 | XIE,,JOSEPH            | FOR HIRE VEHICLE | 2018-04-18T00:00:00 |                       | T434963C                 | 2C3CCAAG5EH263291  |                       |                     |                     | 2014         | B00887      | DIAL 7 CAR & LIMOUSINE SERVICE INC. | LIVERY    |     | (212)777-7777         | DIAL7.COM               | 43-23 35 STREET LONG ISLANDCITY NY 11101 | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37457                 | MOUGHAL,AJAZ,P         | FOR HIRE VEHICLE | 2018-04-22T00:00:00 | AE395                 | T440708C                 | 1LNHM84W66Y645987  |                       | 2014-01-31T00:00:00 | 2014-03-25T00:00:00 | 2006         | B00653      | ROYAL CAR & LIMO SERVICE INC.       | LIVERY    |     | (718)323-3333         |                         | 104-09 109 STREET RICHMOND HILL NY 11419 | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37460                 | BORHANE,,KAOUACHE,,M.  | FOR HIRE VEHICLE | 2017-04-24T00:00:00 |                       | T434481C                 | 2LNBL8CV1BX764154  |                       |                     |                     | 2011         | B00412      | NYC 2 WAY INTERNATIONAL LTD         | BLACK-CAR |     | (718)643-3900         | WWW.NYC2WAY.COM         | 335 BOND STREET BROOKLYN NY 11231        | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37548                 | GUAMAN,,ALFREDO,,J     | FOR HIRE VEHICLE | 2019-04-24T00:00:00 |                       | T415705C                 | 2LNHM82V69X624023  |                       |                     |                     | 2009         | B02876      | VIERZEHN-NY, LLC                    | BLACK-CAR |     | (646)665-7584         |                         | 636 WEST 28 STREET NEW YORK NY 10001     | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37553                 | BARRY, IBRAHIMA, DIOGO | FOR HIRE VEHICLE | 2018-04-01T00:00:00 |                       | T425357C                 | 4T1BK36B18U294523  |                       |                     |                     | 2008         | B02533      | VITAL PLATINUM SERVICES, INC.       | LUXURY    |     | (718)472-2500         |                         | 41-24 38 STREET LIC NY 11101             | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37653                 | HOSSAIN,,MAHBUB        | FOR HIRE VEHICLE | 2018-04-22T00:00:00 |                       | ELITE034                 | 2LNHM82V49X624022  |                       |                     |                     | 2009         | B01087      | ELITE LIMO PLUS INC                 | BLACK-CAR |     | (718)472-2300         |                         | 32-72 GALE AVENUE LIC NY 11101           | G      |            | 2017-04-19T00:00:00 | 13:25             | 
| YES    | C37728                 | ALI,MUHAMMAD           | FOR HIRE VEHICLE | 2019-04-22T00:00:00 |                       | T426263C                 | JTEBW3EH2A2046874  |                       |                     |                     | 2010         | B00888      | ACE C/L SVCE INC                    | BLACK-CAR |     | (718)438-1100         | WWW.EXECUTIVECHARGE.COM | 1440 39 STREET BROOKLYN NY 11218         | G      |            | 2017-04-19T00:00:00 | 13:25             | 
```