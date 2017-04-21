# Bulk Storage Facilities in New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bulk-storage-facilities-in-new-york-state) |
| Metadata | [Link](https://data.ny.gov/api/views/pteg-c78n) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pteg-c78n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pteg-c78n/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pteg-c78n |
| Name | Bulk Storage Facilities in New York State |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | petroleum, chemical, oil, storage |
| Created | 2016-12-16T18:02:27Z |
| Publication Date | 2017-04-20T11:42:30Z |

## Description

The dataset shows status information for:
?	Chemical Bulk Storage (CBS) Facilities pursuant to the Hazardous Substance Bulk Storage Law, Article 40 of ECL; and 6 NYCRR 596-599.
?	Major Oil Storage Facilities (MOSF) pursuant to Article 12 of the Navigation Law and 6 NYCRR Part 610
?	Petroleum Bulk Storage (PBS) Facilities registered pursuant to title 10 of Article 17 and 6 NYCRR Part 613.

Information may include: Program Number; Program Type; Site Type Name; Program Facility Name; Address; Locality; County; NYSDEC Region; Tank Number; Tank Location; Tank Status; Install Date; Capacity in Gallons; Tank Type; Close Date; Material Name (of substance in tank); Percent (of material in tank - if hazardous substance - CBS tanks only); Expiration Date; (of license or registration); Site Status Name; UTMX and UTMY location coordinates.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | program_number        | Program Number        | text          | text          |
| Yes      | series tag     | program_type          | Program Type          | text          | text          |
| Yes      | series tag     | site_type_name        | Site Type Name        | text          | text          |
| Yes      | series tag     | program_facility_name | Program Facility Name | text          | text          |
| No       |                | address_1             | Address 1             | text          | text          |
| No       |                | address_2             | Address 2             | text          | text          |
| Yes      | series tag     | locality              | Locality              | text          | text          |
| Yes      | series tag     | zip_code              | ZIP Code              | text          | text          |
| Yes      | series tag     | county                | County                | text          | text          |
| Yes      | numeric metric | nysdec_region         | NYSDEC Region         | number        | number        |
| Yes      | series tag     | tank_number           | Tank Number           | text          | text          |
| Yes      | series tag     | tank_location         | Tank Location         | text          | text          |
| Yes      | series tag     | tank_status           | Tank Status           | text          | text          |
| Yes      | time           | install_date          | Install Date          | calendar_date | calendar_date |
| Yes      | numeric metric | capacity_in_gallons   | Capacity in Gallons   | number        | number        |
| Yes      | series tag     | tank_type             | Tank Type             | text          | text          |
| No       |                | close_date            | Close Date            | calendar_date | calendar_date |
| Yes      | series tag     | material_name         | Material Name         | text          | text          |
| Yes      | numeric metric | percent               | Percent               | percent       | percent       |
| No       |                | expiration_date       | Expiration Date       | calendar_date | calendar_date |
| Yes      | series tag     | site_status_name      | Site Status Name      | text          | text          |
| Yes      | numeric metric | utmx                  | UTMX                  | number        | number        |
| Yes      | numeric metric | utmy                  | UTMY                  | number        | number        |
```

## Time Field

```ls
Value = install_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_1,address_2,close_date,expiration_date
```

## Data Commands

```ls
series e:pteg-c78n d:1965-12-01T00:00:00.000Z t:material_name=gasoline t:site_status_name=Unregulated/Closed t:program_type=PBS t:program_number=4-133159 t:tank_number=1 t:zip_code=12206 t:county=Albany t:locality=ALBANY t:tank_status="Closed Prior to 03/1991" t:tank_type="Steel/Carbon Steel/Iron" t:site_type_name=Unknown t:program_facility_name="CHARLES FREIHOFER BAKING CO" t:tank_location="Underground including vaulted with no access for inspection" m:percent=100 m:capacity_in_gallons=10000 m:utmy=4723673 m:nysdec_region=4 m:utmx=601432

series e:pteg-c78n d:2001-05-01T00:00:00.000Z t:material_name=gasoline t:site_status_name=Active t:program_type=PBS t:program_number=4-135151 t:tank_number=8 t:zip_code=12029 t:county=Columbia t:locality=CANAAN t:tank_status="In Service" t:tank_type="Steel/Carbon Steel/Iron" t:site_type_name="Retail Gasoline Sales" t:program_facility_name="CANAAN TRUCK STOP" t:tank_location="Aboveground on saddles, legs, stilts, rack or cradle" m:percent=100 m:capacity_in_gallons=500 m:utmy=4691173.08457 m:nysdec_region=4 m:utmx=629394.12093

series e:pteg-c78n d:1986-07-01T00:00:00.000Z t:material_name=gasoline t:site_status_name=Active t:program_type=PBS t:program_number=4-135585 t:tank_number=2 t:zip_code=12144 t:county=Rensselaer t:locality=RENSSELAER t:tank_status="Closed - Removed" t:tank_type="Steel/Carbon Steel/Iron" t:site_type_name="Retail Gasoline Sales" t:program_facility_name="STEWART'S SHOP # 262" t:tank_location="Underground including vaulted with no access for inspection" m:percent=100 m:capacity_in_gallons=4000 m:utmy=4722252.60631 m:nysdec_region=4 m:utmx=603421.57821
```

## Meta Commands

```ls
metric m:nysdec_region p:long l:"NYSDEC Region" d:"NYSDEC Region where facility is located: Region 0: Is reserved for Vessels/Barges which have no fixed location; Region 1: (Long Island) Nassau* and Suffolk* counties; Region 2: (New York City) Brooklyn, Bronx, Manhattan, Queens and Staten Island; Region 3: (Lower Hudson Valley) Dutchess, Orange, Putnam, Rockland*, Sullivan, Ulster and Westchester* counties; Region 4: (Capital Region/Northern Catskills) Albany, Columbia, Delaware, Greene, Montgomery, Otsego, Rensselaer, Schenectady and Schoharie counties; Region 5: (Eastern Adirondacks/Lake Champlain) Clinton, Essex, Franklin, Fulton, Hamilton, Saratoga, Warren and Washington counties; Region 6: (Western Adirondacks/Eastern Lake Ontario) Herkimer, Jefferson, Lewis, Oneida and St. Lawrence counties; Region 7: (Central New York) Broome, Cayuga, Chenango, Cortland*, Madison, Onondaga, Oswego, Tioga and Tompkins counties; Region 8: (Western Finger Lakes) Chemung, Genesee, Livingston, Monroe, Ontario, Orleans, Schuyler, Seneca, Steuben, Wayne and Yates counties; Region 9: (Western New York) Allegany, Chautauqua, Cattaraugus, Erie, Niagara and Wyoming counties. *NYSDEC does not maintain the PBS registration records for the following five counties which are delegated to manage their own records: Cortland, Nassau, Rockland, Suffolk, and Westchester." t:dataTypeName=number

metric m:capacity_in_gallons p:long l:"Capacity in Gallons" d:"Total design or maximum capacity of a tank, in gallons." t:dataTypeName=number

metric m:percent p:float l:Percent d:"The percentage of hazardous substance material in tank. (Applies to Chemical Bulk Storage (CBS) tanks only) (There is the capacity to input multi - material percentages for each tank.)" t:dataTypeName=percent

metric m:utmx p:long l:UTMX d:"X coordinate (latitude), represented in UTM (Universal Transverse Mercator) units. (Note: NYS is zone 18 for UTM)" t:dataTypeName=number

metric m:utmy p:long l:UTMY d:"Y coordinate (longitude), represented in UTM (Universal Transverse Mercator) units. (Note: NYS is zone 18 for UTM)" t:dataTypeName=number

entity e:pteg-c78n l:"Bulk Storage Facilities in New York State" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/pteg-c78n

property e:pteg-c78n t:meta.view v:id=pteg-c78n v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/287.html v:averageRating=0 v:name="Bulk Storage Facilities in New York State" v:attribution="New York State Department of Environmental Conservation"

property e:pteg-c78n t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pteg-c78n t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| program_number | program_type | site_type_name                          | program_facility_name          | address_1             | address_2 | locality   | zip_code | county     | nysdec_region | tank_number | tank_location                                               | tank_status             | install_date        | capacity_in_gallons | tank_type                           | close_date          | material_name                     | percent | expiration_date     | site_status_name   | utmx         | utmy          | 
| ============== | ============ | ======================================= | ============================== | ===================== | ========= | ========== | ======== | ========== | ============= | =========== | =========================================================== | ======================= | =================== | =================== | =================================== | =================== | ================================= | ======= | =================== | ================== | ============ | ============= | 
| 4-133159       | PBS          | Unknown                                 | CHARLES FREIHOFER BAKING CO    | 252 SPRUCE ST         |           | ALBANY     | 12206    | Albany     | 4             | 1           | Underground including vaulted with no access for inspection | Closed Prior to 03/1991 | 1965-12-01T00:00:00 | 10000               | Steel/Carbon Steel/Iron             |                     | gasoline                          | 100.00  | 1992-03-24T00:00:00 | Unregulated/Closed | 601432.00000 | 4723673.00000 | 
| 4-135151       | PBS          | Retail Gasoline Sales                   | CANAAN TRUCK STOP              | 12816 ROUTE 22        |           | CANAAN     | 12029    | Columbia   | 4             | 8           | Aboveground on saddles, legs, stilts, rack or cradle        | In Service              | 2001-05-01T00:00:00 | 500                 | Steel/Carbon Steel/Iron             |                     | gasoline                          | 100.00  | 2022-03-19T00:00:00 | Active             | 629394.12093 | 4691173.08457 | 
| 4-135585       | PBS          | Retail Gasoline Sales                   | STEWART'S SHOP # 262           | 12 PARTITION STREET   |           | RENSSELAER | 12144    | Rensselaer | 4             | 2           | Underground including vaulted with no access for inspection | Closed - Removed        | 1986-07-01T00:00:00 | 4000                | Steel/Carbon Steel/Iron             | 1998-04-01T00:00:00 | gasoline                          | 100.00  | 2022-03-24T00:00:00 | Active             | 603421.57821 | 4722252.60631 | 
| 4-134597       | PBS          | Trucking/Transportation/Fleet Operation | VANAUKEN EXPRESS INC           | 1485 RED MILL RD      |           | GREENVILLE | 12083    | Greene     | 4             | 5           | Underground including vaulted with no access for inspection | In Service              | 1998-10-01T00:00:00 | 4000                | Fiberglass Reinforced Plastic (FRP) |                     | diesel                            | 100.00  | 2022-03-24T00:00:00 | Active             | 578934.62653 | 4695793.93562 | 
| 4-134058       | PBS          | Other                                   | NYS DOT                        | 941 ROUTE 23          |           | CLAVERACK  | 12513    | Columbia   | 4             | 8112        | Aboveground on saddles, legs, stilts, rack or cradle        | Closed - Removed        | 2000-11-01T00:00:00 | 40                  | Steel/Carbon Steel/Iron             | 2011-03-01T00:00:00 | biodiesel                         | 10.00   | 2017-03-24T00:00:00 | Active             | 612541.44625 | 4673790.04579 | 
| 4-134147       | PBS          | Other                                   | NYS DOT                        | 310 MINERAL SPRING RD |           | COBLESKILL | 12043    | Schoharie  | 4             | 9604        | Aboveground on saddles, legs, stilts, rack or cradle        | In Service              | 2008-07-07T00:00:00 | 275                 | Steel/Carbon Steel/Iron             |                     | #2 fuel oil (on-site consumption) | 100.00  | 2017-03-24T00:00:00 | Active             | 541404.68763 | 4723831.15427 | 
| 4-133329       | PBS          | Trucking/Transportation/Fleet Operation | R M LILL INC                   | 1263 ROUTE 9          |           | CASTLETON  | 12033    | Rensselaer | 4             | 3           | Underground including vaulted with no access for inspection | Closed - Removed        | 1985-01-01T00:00:00 | 2000                | Fiberglass Coated Steel             | 1992-04-01T00:00:00 | gasoline                          | 100.00  | 1992-03-19T00:00:00 | Unregulated/Closed | 608618.17427 | 4707535.25639 | 
| 4-135070       | PBS          | Retail Gasoline Sales                   | SUPERMART, INC.                | 69 COLUMBIA ST        |           | RENSSELAER | 12144    | Rensselaer | 4             | W0          | Aboveground on saddles, legs, stilts, rack or cradle        | Closed - Removed        | 1978-12-01T00:00:00 | 275                 | Steel/Carbon Steel/Iron             |                     | #2 fuel oil (on-site consumption) | 100.00  | 2022-03-24T00:00:00 | Active             | 602764.10854 | 4721053.13276 | 
| 4-135089       | PBS          | Retail Gasoline Sales                   | POLSINELLO FUELS, INC          | 241 RIVERSIDE AVE     |           | RENSSELAER | 12144    | Rensselaer | 4             | 2-A         | Underground including vaulted with no access for inspection | Closed - Removed        | 1976-07-01T00:00:00 | 2000                | Steel/Carbon Steel/Iron             | 1992-05-01T00:00:00 | diesel                            | 100.00  | 2022-03-24T00:00:00 | Active             | 602510.11688 | 4720877.70958 | 
| 4-134031       | PBS          | Other                                   | NYS DOT - OFFICE OF OPERATIONS | 1373 ROUTE 203        |           | CHATHAM    | 12534    | Columbia   | 4             | 8110        | Aboveground on saddles, legs, stilts, rack or cradle        | In Service              | 1999-12-13T00:00:00 | 2000                | Steel/Carbon Steel/Iron             |                     | #2 fuel oil (on-site consumption) | 100.00  | 2017-03-24T00:00:00 | Active             | 617227.93108 | 4690073.88798 | 
```