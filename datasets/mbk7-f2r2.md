# DART (Department Application Review and Tracking) on the Web: Beginning 1988

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dart-department-application-review-and-tracking-on-the-web-beginning-1988) |
| Metadata | [Link](https://data.ny.gov/api/views/mbk7-f2r2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mbk7-f2r2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mbk7-f2r2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mbk7-f2r2 |
| Name | DART (Department Application Review and Tracking) on the Web: Beginning 1988 |
| Attribution | Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | permit application tracking system, dart, web interface application, permits |
| Created | 2015-01-08T21:55:20Z |
| Publication Date | 2017-04-17T22:46:24Z |

## Description

Tabular Data for Permits administered by the Agency in which the general public can use a web interface to look up specific facilities and applications.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                   | Data Type     | Render Type   |
| ======== | =========== | ===================== | ====================== | ============= | ============= |
| Yes      | series tag  | application_id        | Application ID         | text          | number        |
| Yes      | series tag  | facility              | Facility               | text          | text          |
| Yes      | series tag  | location              | Location               | text          | text          |
| Yes      | series tag  | town_or_city          | Town or City           | text          | text          |
| Yes      | series tag  | applicant             | Applicant              | text          | text          |
| Yes      | series tag  | permit_type           | Permit Type            | text          | text          |
| Yes      | series tag  | application_type      | Application Type       | text          | text          |
| Yes      | time        | date_received         | Date Received          | calendar_date | calendar_date |
| Yes      | series tag  | status                | Status                 | text          | text          |
| Yes      | series tag  | complete_status       | Complete Status        | text          | text          |
| Yes      | series tag  | upa_class             | UPA Class              | text          | text          |
| Yes      | series tag  | short_description     | Short Description      | text          | text          |
| No       |             | enb_publication_date  | ENB Publication Date   | calendar_date | calendar_date |
| No       |             | written_comments_due  | Written Comments Due   | calendar_date | calendar_date |
| Yes      | series tag  | seqr_class            | SEQR Class             | text          | text          |
| Yes      | series tag  | seqr_determination    | SEQR Determination     | text          | text          |
| Yes      | series tag  | lead_agency           | Lead Agency            | text          | text          |
| Yes      | series tag  | enivronmental_justice | Enivronmental Justice  | text          | text          |
| Yes      | series tag  | shpa_status           | SHPA Status            | text          | text          |
| Yes      | series tag  | coastal_zone_status   | Coastal Zone Status    | text          | text          |
| Yes      | series tag  | final_disposition     | Final Disposition      | text          | text          |
| No       |             | permit_effective_date | Permit Effective Date  | calendar_date | calendar_date |
| No       |             | permit_expration_date | Permit Expiration Date | calendar_date | calendar_date |
| Yes      | series tag  | stimulus_project      | Stimulus Project       | text          | text          |
| Yes      | series tag  | other_known_ids       | Other Known IDs        | text          | text          |
| Yes      | series tag  | dec_contact           | DEC Contact            | text          | text          |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = enb_publication_date,written_comments_due,permit_effective_date,permit_expration_date
```

## Data Commands

```ls
series e:mbk7-f2r2 d:1993-05-26T00:00:00.000Z t:seqr_determination="Not Applicable" t:coastal_zone_status="This project is not located in a Coastal Management area." t:application_type=New t:permit_type="Solid Waste Transporter" t:status=Expired t:location="222 OLD MILITARY RD LAKE PLACID 12946" t:lead_agency="None Designated" t:seqr_class="Type II Action" t:final_disposition=Issued t:upa_class=MINOR t:facility="LAKE PLACID DISPOSAL SERVICE" t:short_description="WASTE HAULER PERMIT TO HAUL SLUDGE/LANDFL DISPSL" t:stimulus_project=N t:dec_contact="CLIFFORD C WRAY  JR" t:applicant="LAKE PLACID DISPOSAL SERVICE INC" t:complete_status=Complete t:application_id=515400014400001 t:town_or_city="NORTH ELBA" t:other_known_ids="NYR00D598 - State Pollutant Discharge Elimination System ID (NYSDEC)" m:row_number.mbk7-f2r2=1

series e:mbk7-f2r2 d:1993-05-26T00:00:00.000Z t:seqr_determination="Negative Declaration" t:coastal_zone_status="This project is not located in a Coastal Management area." t:application_type=New t:permit_type="Freshwater Wetlands" t:status=Expired t:location="E SHORE DR VALATIE 12184" t:lead_agency=DEC t:seqr_class="Unlisted Action" t:final_disposition=Issued t:upa_class=MINOR t:facility="MUELLER PROPERTY" t:short_description="FWW K-109,KINDERHOOK LAKE,REPAIR RAILROAD TIE WALL" t:shpa_status="The proposed activity is not subject to review in accordance with SHPA. The permit type is exempt or the activity is being reviewed in accordance with federal historic preservation regulations." t:stimulus_project=N t:dec_contact="MICHAEL T HIGGINS" t:applicant="BETTY MUELLER" t:complete_status=Complete t:application_id=410260004700001 t:town_or_city=CHATHAM t:other_known_ids="K-109 - Freshwater Wetland ID (NYSDEC)" m:row_number.mbk7-f2r2=2

series e:mbk7-f2r2 d:1995-01-12T00:00:00.000Z t:seqr_determination="Not Applicable" t:coastal_zone_status="This project is not located in a Coastal Management area." t:application_type=Renewal t:permit_type="Freshwater Wetlands" t:location="E SHORE DR VALATIE 12184" t:lead_agency="None Designated" t:status=Expired t:seqr_class="Type II Action" t:final_disposition=Issued t:upa_class=MINOR t:facility="MUELLER PROPERTY" t:short_description="FWW K-109,RENEWAL OF PERMIT TO COMPLETE WORK" t:stimulus_project=N t:dec_contact="MICHAEL T HIGGINS" t:applicant="BETTY MUELLER" t:application_id=410260004700001 t:town_or_city=CHATHAM t:other_known_ids="K-109 - Freshwater Wetland ID (NYSDEC)" m:row_number.mbk7-f2r2=3
```

## Meta Commands

```ls
metric m:row_number.mbk7-f2r2 p:long l:"Row Number"

entity e:mbk7-f2r2 l:"DART (Department Application Review and Tracking) on the Web: Beginning 1988" t:attribution="Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/mbk7-f2r2

property e:mbk7-f2r2 t:meta.view v:id=mbk7-f2r2 v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/cfmx/extapps/envapps/index.cfm v:averageRating=0 v:name="DART (Department Application Review and Tracking) on the Web: Beginning 1988" v:attribution="Department of Environmental Conservation"

property e:mbk7-f2r2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mbk7-f2r2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| application_id  | facility                     | location                                    | town_or_city  | applicant                            | permit_type                             | application_type | date_received       | status  | complete_status | upa_class | short_description                                  | enb_publication_date | written_comments_due | seqr_class      | seqr_determination   | lead_agency     | enivronmental_justice | shpa_status                                                                                                                                                                                                                            | coastal_zone_status                                                                                                             | final_disposition | permit_effective_date | permit_expration_date | stimulus_project | other_known_ids                                                                              | dec_contact        | 
| =============== | ============================ | =========================================== | ============= | ==================================== | ======================================= | ================ | =================== | ======= | =============== | ========= | ================================================== | ==================== | ==================== | =============== | ==================== | =============== | ===================== | ====================================================================================================================================================================================================================================== | =============================================================================================================================== | ================= | ===================== | ===================== | ================ | ============================================================================================ | ================== | 
| 515400014400001 | LAKE PLACID DISPOSAL SERVICE | 222 OLD MILITARY RD LAKE PLACID 12946       | NORTH ELBA    | LAKE PLACID DISPOSAL SERVICE INC     | Solid Waste Transporter                 | New              | 1993-05-26T00:00:00 | Expired | Complete        | MINOR     | WASTE HAULER PERMIT TO HAUL SLUDGE/LANDFL DISPSL   |                      |                      | Type II Action  | Not Applicable       | None Designated |                       |                                                                                                                                                                                                                                        | This project is not located in a Coastal Management area.                                                                       | Issued            | 1993-06-09T00:00:00   | 1993-10-31T00:00:00   | N                | NYR00D598 - State Pollutant Discharge Elimination System ID (NYSDEC)                         | CLIFFORD C WRAY JR | 
| 410260004700001 | MUELLER PROPERTY             | E SHORE DR VALATIE 12184                    | CHATHAM       | BETTY MUELLER                        | Freshwater Wetlands                     | New              | 1993-05-26T00:00:00 | Expired | Complete        | MINOR     | FWW K-109,KINDERHOOK LAKE,REPAIR RAILROAD TIE WALL |                      |                      | Unlisted Action | Negative Declaration | DEC             |                       | The proposed activity is not subject to review in accordance with SHPA. The permit type is exempt or the activity is being reviewed in accordance with federal historic preservation regulations.                                      | This project is not located in a Coastal Management area.                                                                       | Issued            | 1993-06-29T00:00:00   | 1993-12-31T00:00:00   | N                | K-109 - Freshwater Wetland ID (NYSDEC)                                                       | MICHAEL T HIGGINS  | 
| 410260004700001 | MUELLER PROPERTY             | E SHORE DR VALATIE 12184                    | CHATHAM       | BETTY MUELLER                        | Freshwater Wetlands                     | Renewal          | 1995-01-12T00:00:00 | Expired |                 | MINOR     | FWW K-109,RENEWAL OF PERMIT TO COMPLETE WORK       |                      |                      | Type II Action  | Not Applicable       | None Designated |                       |                                                                                                                                                                                                                                        | This project is not located in a Coastal Management area.                                                                       | Issued            | 1995-01-13T00:00:00   | 1995-12-31T00:00:00   | N                | K-109 - Freshwater Wetland ID (NYSDEC)                                                       | MICHAEL T HIGGINS  | 
| 640120007400001 | NICE-N-EASY GROCERY          | STATE STREET OGDENSBURG 13669               | OGDENSBURG    | PARISH ENERGY FUELS INC              | Process, Exhaust, Ventilation (Operate) | New              | 1993-05-27T00:00:00 | Expired | Complete        | MINOR     | PERMIT TO OPERATE FOR 5 YEARS                      |                      |                      | Type II Action  | Not Applicable       | None Designated |                       |                                                                                                                                                                                                                                        | This project is not located in a Coastal Management area.                                                                       | Issued            | 1993-05-27T00:00:00   | 1998-06-01T00:00:00   | N                | 4012000389 - Division of Air Resources ID (NYSDEC)                                           | C RANDY VAAS       | 
| 622340004600001 | CHATTERTON TOPSOIL PIT       | DAVIS HILL ROAD ELLISBURG 13636             | ELLISBURG     | TUG HILL CONSTRUCTION INC            | Mined Land Reclamation                  | New              | 1993-05-27T00:00:00 | Expired | Complete        | MAJOR     | NYS MINE FILE 6023-44-0847                         | 1993-06-16T00:00:00  | 1993-07-01T00:00:00  | Unlisted Action | Negative Declaration | DEC             |                       | The proposed activity is not subject to review in accordance with SHPA. The permit type is exempt or the activity is being reviewed in accordance with federal historic preservation regulations.                                      | This project is not located in a Coastal Management area.                                                                       | Issued            | 1993-10-06T00:00:00   | 1996-10-01T00:00:00   | N                | 60847 - Mined Land ID (NYSDEC)                                                               | C RANDY VAAS       | 
| 436320003900001 | PHILLIPS LUMBER CO           | POPLAR AVE HARTWICK                         | HARTWICK      | PHILLIPS LUMBER CO INC               | Freshwater Wetlands                     | New              | 1993-05-27T00:00:00 | Issued  | Complete        | MINOR     | STORE LUMBER IN ADJACENT AREA OF FWW HW-9          |                      |                      | Unlisted Action | Negative Declaration | DEC             |                       | The proposed activity is not subject to review in accordance with SHPA. The permit type is exempt or the activity is being reviewed in accordance with federal historic preservation regulations.                                      | This project is not located in a Coastal Management area.                                                                       | Issued            | 1993-06-29T00:00:00   |                       | N                | NYR00B449 - State Pollutant Discharge Elimination System ID (NYSDEC)                         | ROBERT G SNYDER    | 
| 262060005700001 | TRI LON COLOR LITOGRAPHERS   | 54 WEST 21ST ST NEW YORK 10010              | MANHATTAN     | TRI LON COLOR LITHOGRAPHERS INC      | Process, Exhaust, Ventilation (Operate) | New              | 1993-05-26T00:00:00 | Expired | Complete        | MINOR     | 54 W 21ST ST (EP - 1)                              |                      |                      | Unlisted Action | Negative Declaration | None Designated |                       |                                                                                                                                                                                                                                        | This project is not located in a Coastal Management area.                                                                       | Issued            | 1994-02-25T00:00:00   | 1999-02-25T00:00:00   | N                | 620000K455 - Division of Air Resources ID (NYSDEC);PA0JD - Compliance Data System ID (USEPA) | HAROLD J DICKEY    | 
| 262060005700003 | TRI LON COLOR LITOGRAPHERS   | 54 WEST 21ST ST NEW YORK 10010              | MANHATTAN     | TRI LON COLOR LITHOGRAPHERS INC      | Process, Exhaust, Ventilation (Operate) | New              | 1991-01-30T00:00:00 | Denied  | Complete        | MINOR     | 54 W 21ST ST (EP - 1)                              |                      |                      | Unlisted Action | Negative Declaration | None Designated |                       |                                                                                                                                                                                                                                        | This project is not located in a Coastal Management area.                                                                       | Denied            |                       |                       | N                | 620000K455 - Division of Air Resources ID (NYSDEC);PA0JD - Compliance Data System ID (USEPA) | HAROLD J DICKEY    | 
| 264040034900001 | NYC DEP-FILBERT AVENUE       | HYLAN BLVD & FILBER AVE STATEN ISLAND 10305 | STATEN ISLAND | NYC DEPT OF ENVIRONMENTAL PROTECTION | Freshwater Wetlands                     | New              | 1993-05-25T00:00:00 | Issued  | Complete        | MAJOR     | MAINTENANCE OF WATERCOURSE                         | 1994-06-03T00:00:00  | 1994-06-18T00:00:00  | Unlisted Action | Negative Declaration | DEC             |                       | Cultural resource lists and map have been checked. No registered, eligible, or inventoried archaeological sites or historic structures were identified at the project location. No further review in accordance with SHPA is required. | This project is located in a Coastal Management area and is subject to the Waterfront Revitalization and Coastal Resources Act. | Issued            | 1994-07-05T00:00:00   |                       | N                | NA 9 - Freshwater Wetland ID (NYSDEC)                                                        | JEFFREY S RABKIN   | 
| 750340003700001 | MAZOUREK PIT                 | ROUTE 13 NEWFIELD                           | NEWFIELD      | JENNEY EXCAVATING                    | Mined Land Reclamation                  | New              | 1993-05-27T00:00:00 | Expired | Complete        | MINOR     | MAZOUREK SAND AND GRAVEL PIT                       |                      |                      | Unlisted Action | Negative Declaration | None Designated |                       |                                                                                                                                                                                                                                        | This project is not located in a Coastal Management area.                                                                       | Issued            | 1993-07-08T00:00:00   | 1996-07-08T00:00:00   | N                | 70677 - Mined Land ID (NYSDEC)                                                               | RAYMOND J NOLAN    | 
```