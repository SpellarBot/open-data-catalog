# Solid Waste Management Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solid-waste-management-facilities) |
| Metadata | [Link](https://data.ny.gov/api/views/2fni-raj8) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2fni-raj8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2fni-raj8/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2fni-raj8 |
| Name | Solid Waste Management Facilities |
| Attribution | Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | landfill, transfer station, municipal waste combustor, recycling, biosolids, processing, composting, household hazardous waste, land application, regulated medical waste, vehicle dismantler, waste... |
| Created | 2014-02-18T19:15:12Z |
| Publication Date | 2017-01-09T23:16:43Z |

## Description

Active Solid Waste Management Facilities

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | series tag     | facility_name            | Facility Name            | text          | text          |
| No       |                | location_address         | Location Address         | text          | text          |
| No       |                | location_address2        | Location Address2        | text          | text          |
| Yes      | series tag     | city                     | City                     | text          | text          |
| Yes      | series tag     | state                    | State                    | text          | text          |
| Yes      | series tag     | zip_code                 | Zip Code                 | text          | text          |
| Yes      | series tag     | county                   | County                   | text          | text          |
| Yes      | series tag     | region                   | Region                   | text          | number        |
| Yes      | series tag     | phone_number             | Phone Number             | text          | number        |
| Yes      | series tag     | owner_name               | Owner Name               | text          | text          |
| Yes      | series tag     | owner_type               | Owner Type               | text          | text          |
| Yes      | series tag     | activity_desc            | Activity Desc            | text          | text          |
| Yes      | series tag     | activity_number          | Activity Number          | text          | text          |
| Yes      | series tag     | active                   | Active                   | text          | text          |
| Yes      | numeric metric | east_coordinate          | East Coordinate          | number        | number        |
| Yes      | numeric metric | north_coordinate         | North Coordinate         | number        | number        |
| Yes      | series tag     | accuracy_code            | Accuracy Code            | text          | text          |
| Yes      | series tag     | waste_types              | Waste Types              | text          | text          |
| Yes      | series tag     | regulatory_status        | Regulatory Status        | text          | text          |
| Yes      | series tag     | authorization_number     | Authorization Number     | text          | text          |
| Yes      | time           | authorization_issue_date | Authorization Issue Date | calendar_date | calendar_date |
| No       |                | expiration_date          | Expiration Date          | calendar_date | calendar_date |
```

## Time Field

```ls
Value = authorization_issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = location_address,location_address2,expiration_date
```

## Data Commands

```ls
series e:2fni-raj8 d:2008-03-14T00:00:00.000Z t:region=1 t:owner_type=Private t:phone_number=6312347100 t:owner_name="Patricia DiMatteo" t:zip_code=?11749 t:regulatory_status=Permit t:state=NY t:city=Islandia t:facility_name="Jet Paper Stock Corp TS" t:county=Suffolk t:authorization_number=?1-4728-00720/00001 t:active=Yes t:activity_number=[52M07] t:activity_desc="C&D processing - permit" t:waste_types="Construction & Demolition Debris" m:north_coordinate=4518747 m:east_coordinate=653272

series e:2fni-raj8 d:2014-05-21T00:00:00.000Z t:region=2 t:owner_type=Private t:phone_number=7187392301 t:owner_name="Christopher Hein" t:zip_code=?11433 t:regulatory_status=Permit t:state=NY t:city=Jamaica t:facility_name="American Recycling Management LLC" t:county=Queens t:authorization_number=? t:accuracy_code="2.1 - NYSDEC 100 m grid collection" t:active=Yes t:activity_number=[41W06] t:activity_desc="C&D processing - permit" t:waste_types="Metal (Structural);Construction & Demolition Debris" m:north_coordinate=4506670 m:east_coordinate=602499

series e:2fni-raj8 d:2003-04-25T00:00:00.000Z t:region=2 t:owner_type=Private t:phone_number=7184467297 t:owner_name="Gerald Antonacci" t:zip_code=?11368 t:regulatory_status=Permit t:state=NY t:city=Flushing t:facility_name="Crown Container Transfer Station" t:county=Queens t:authorization_number=?2-6302-00006/00002 t:active=Yes t:activity_number=[41W50] t:activity_desc="C&D processing - permit" t:waste_types="Construction & Demolition Debris;Metals (Ferrous);Metals (Non-Ferrous)" m:north_coordinate=4512788 m:east_coordinate=597611
```

## Meta Commands

```ls
metric m:east_coordinate p:integer l:"East Coordinate" d:"NY Transverse Mercator system coordinate; NAD83 horizontal datum, Zone 18N." t:dataTypeName=number

metric m:north_coordinate p:integer l:"North Coordinate" d:"NY Transverse Mercator system coordinate; NAD83 horizontal datum, Zone 18N." t:dataTypeName=number

entity e:2fni-raj8 l:"Solid Waste Management Facilities" t:attribution="Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/2fni-raj8

property e:2fni-raj8 t:meta.view v:id=2fni-raj8 v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/8495.html v:averageRating=0 v:name="Solid Waste Management Facilities" v:attribution="Department of Environmental Conservation"

property e:2fni-raj8 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2fni-raj8 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:2fni-raj8 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| facility_name                                 | location_address           | location_address2 | city              | state | zip_code | county   | region | phone_number | owner_name                  | owner_type | activity_desc           | activity_number | active | east_coordinate | north_coordinate | accuracy_code                                      | waste_types                                                                                                                                                                                        | regulatory_status | authorization_number | authorization_issue_date | expiration_date     | 
| ============================================= | ========================== | ================= | ================= | ===== | ======== | ======== | ====== | ============ | =========================== | ========== | ======================= | =============== | ====== | =============== | ================ | ================================================== | ================================================================================================================================================================================================== | ================= | ==================== | ======================== | =================== | 
| Jet Paper Stock Corp TS                       | 228 Blydenburgh Road       |                   | Islandia          | NY    | ?11749   | Suffolk  | 1      | 6312347100   | Patricia DiMatteo           | Private    | C&D processing - permit | [52M07]         | Yes    | 653272          | 4518747          |                                                    | Construction & Demolition Debris                                                                                                                                                                   | Permit            | ?1-4728-00720/00001  | 2008-03-14T00:00:00      | 2013-03-13T00:00:00 | 
| American Recycling Management LLC             | 172-33 Douglas Avenue      |                   | Jamaica           | NY    | ?11433   | Queens   | 2      | 7187392301   | Christopher Hein            | Private    | C&D processing - permit | [41W06]         | Yes    | 602499          | 4506670          | 2.1 - NYSDEC 100 m grid collection                 | Metal (Structural);Construction & Demolition Debris                                                                                                                                                | Permit            | ?                    | 2014-05-21T00:00:00      | 2019-05-20T00:00:00 | 
| Crown Container Transfer Station              | 126-46 34 Avenue           |                   | Flushing          | NY    | ?11368   | Queens   | 2      | 7184467297   | Gerald Antonacci            | Private    | C&D processing - permit | [41W50]         | Yes    | 597611          | 4512788          |                                                    | Construction & Demolition Debris;Metals (Ferrous);Metals (Non-Ferrous)                                                                                                                             | Permit            | ?2-6302-00006/00002  | 2003-04-25T00:00:00      | 2008-04-25T00:00:00 | 
| New Style Recycling Corp                      | 49-10 Grand Avenue         |                   | Maspeth           | NY    | ?11378   | Queens   | 2      | 7183264175   | Antoinette Cristina         | Private    | C&D processing - permit | [41W53]         | Yes    | 591300          | 4507948          |                                                    | Construction & Demolition Debris;Soil (Clean);Wood (Clean);Concrete;Metals (Non-Ferrous);Metals (Ferrous);Wood (Unadulterated);Paper / Cardboard;Plastics;Waste Tires;Wood (Unadulterated Pallets) | Permit            | ?2-6304-00021/00001  | 2012-03-14T00:00:00      | 2017-03-14T00:00:00 | 
| Regal Recycling Inc                           | 172-06 Douglas Avenue      |                   | Jamaica           | NY    | ?11433   | Queens   | 2      | 7185239330   | Regal Recycling Company Inc | Private    | C&D processing - permit | [41T49]         | Yes    | 602523          | 4506701          | 2.1 - NYSDEC 100 m grid collection                 | Construction & Demolition Debris;Concrete;Soil (Clean);Wood (Clean);Metals (Ferrous);Metals (Non-Ferrous);Wood (Unadulterated)                                                                     | Permit            | ?2-6307-00008/00007  | 2013-06-18T00:00:00      | 2018-06-18T00:00:00 | 
| Thomas Novelli Contracting                    | 94-20 Merrick Blvd         |                   | Jamaica           | NY    | ?11433   | Queens   | 2      | 7185234439   | Enrico Novelli              | Private    | C&D processing - permit | [41W57]         | Yes    | 602041          | 4506545          | 4.3 - Utilization of Digital Orthophoto Quads      | Soil (Clean)                                                                                                                                                                                       | Permit            | ?2-6307-00128/00001  | 2010-11-19T00:00:00      | 2015-11-19T00:00:00 | 
| Watch Hill Holding Corp/Royal Carting Service | 409 Rt. 82; PO Box 1209    |                   | Hopewell Junction | NY    | ?12533   | Dutchess | 3      | 8458966000   | Emil Panichi                |            | C&D processing - permit | [14T03]         | Yes    | 596306          | 4602468          |                                                    | Wood (Brush/ Branches/ Trees/ Stumps);Metals (Ferrous);Metals (Non-Ferrous);Concrete;Construction & Demolition Debris;Commingled Paper;Waste Tires;Electronics                                     | Permit            | ?3-1328-00129/00002  | 2013-03-26T00:00:00      | 2018-03-26T00:00:00 | 
| Middletown Carting LLC (Auto Wreckers)        | 83-85 Industrial Place Ext |                   | Middletown        | NY    | ?10940   | Orange   | 3      | 8453438011   | John Carbone                | Private    | C&D processing - permit | [36W17]         | Yes    | 549654          | 4590600          |                                                    |                                                                                                                                                                                                    | Permit            | ?3-3309-00131/00001  | 2013-02-21T00:00:00      | 2018-02-20T00:00:00 | 
| Taylor Biomass Gasification Facility          | 350 Nelleytown Road        |                   | Montgomery        | NY    | ?12549   | Orange   | 3      | 8454574021   | James W. Taylor             | Private    | C&D processing - permit | [36W02]         | Yes    | 564419          | 4593596          |                                                    | Asphalt;Metals (Ferrous);Metals (Non-Ferrous);Construction & Demolition Debris;Paper / Cardboard;Wood (Unadulterated);Brick;Soil (Clean)                                                           | Permit            | ?3-3342-00105/00009  | 2010-12-03T00:00:00      | 2020-12-02T00:00:00 | 
| Greece (T) Transfer Station                   | 635 Flynn Road             |                   | Rochester         | NY    | ?14612   | Monroe   | 8      | 5857232376   | Town of Greece              | Municipal  | C&D processing - permit | [28R04]         | Yes    | 279577          | 4795981          | 4.2 - Utilization of GIS and existing spatial data | Concrete;Wood (Brush/ Branches/ Trees/ Stumps);Asphalt;Wood (Chips)                                                                                                                                | Permit            | ?                    |                          |                     | 
```