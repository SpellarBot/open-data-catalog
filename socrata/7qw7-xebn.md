# Workers' Compensation Board Hearing Site Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/workers-compensation-board-hearing-site-locations) |
| Metadata | [Link](https://data.ny.gov/api/views/7qw7-xebn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7qw7-xebn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7qw7-xebn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7qw7-xebn |
| Name | Workers' Compensation Board Hearing Site Locations |
| Attribution | New York State Workers? Compensation Board |
| Category | Government & Finance |
| Tags | wcb, hearing locations, workers' comp |
| Created | 2014-08-25T15:11:51Z |
| Publication Date | 2014-09-22T14:48:54Z |

## Description

The New York State Workers? Compensation Board (WCB) has locations for hearings throughout the state.  This data set provides the address for those hearing sites, as well as the contact phone number and district website, where available.   This data set is a current list and is only updated as needed.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | district                | District                | text      | text        |
| Yes      | series tag  | hearing_point_name      | Hearing Point Name      | text      | text        |
| Yes      | series tag  | street_address          | Street Address          | text      | text        |
| No       |             | address_2               | Address 2               | text      | text        |
| Yes      | series tag  | city                    | City                    | text      | text        |
| Yes      | series tag  | state                   | State                   | text      | text        |
| Yes      | series tag  | zip_code                | Zip Code                | text      | number      |
| Yes      | series tag  | phone_number            | Phone Number            | text      | text        |
| Yes      | series tag  | district_office_website | District Office Website | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_2
```

## Data Commands

```ls
series e:7qw7-xebn d:2014-08-25T08:30:40.000Z t:hearing_point_name=Queens t:phone_number="(800) 877-1373" t:zip_code=11432 t:state=NY t:district_office_website=http://www.wcb.ny.gov/content/main/DistrictOffices/Queens.jsp t:street_address="168-46 91st Avenue" t:district=Queens t:city=Jamaica m:row_number.7qw7-xebn=1

series e:7qw7-xebn d:2014-08-25T08:30:40.000Z t:hearing_point_name=Manhattan t:phone_number="(800) 877-1373" t:zip_code=10027 t:state=NY t:district_office_website=http://www.wcb.ny.gov/content/main/DistrictOffices/Manhattan.jsp t:street_address="215 W. 125th Street" t:district=Manhattan t:city="New York" m:row_number.7qw7-xebn=2

series e:7qw7-xebn d:2014-08-25T08:30:40.000Z t:hearing_point_name="New city" t:phone_number=None t:zip_code=10956 t:state=NY t:district_office_website=http://www.wcb.ny.gov/content/main/DistrictOffices/Peeks.jsp t:street_address="20 Maple Avenue" t:district=Peekskill t:city="New City" m:row_number.7qw7-xebn=3
```

## Meta Commands

```ls
metric m:row_number.7qw7-xebn p:long l:"Row Number"

entity e:7qw7-xebn l:"Workers' Compensation Board Hearing Site Locations" t:attribution="New York State Workers? Compensation Board" t:url=https://data.ny.gov/api/views/7qw7-xebn

property e:7qw7-xebn t:meta.view v:id=7qw7-xebn v:category="Government & Finance" v:attributionLink=http://www.wcb.ny.gov v:averageRating=0 v:name="Workers' Compensation Board Hearing Site Locations" v:attribution="New York State Workers? Compensation Board"

property e:7qw7-xebn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7qw7-xebn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7qw7-xebn t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | district   | hearing_point_name | street_address        | address_2     | city        | state | zip_code | phone_number   | district_office_website                                                  | 
| =========== | ========== | ================== | ===================== | ============= | =========== | ===== | ======== | ============== | ======================================================================== | 
| 1408955440  | Queens     | Queens             | 168-46 91st Avenue    | 3rd Floor     | Jamaica     | NY    | 11432    | (800) 877-1373 | [http://www.wcb.ny.gov/content/main/DistrictOffices/Queens.jsp, null]    | 
| 1408955440  | Manhattan  | Manhattan          | 215 W. 125th Street   | 4th Floor     | New York    | NY    | 10027    | (800) 877-1373 | [http://www.wcb.ny.gov/content/main/DistrictOffices/Manhattan.jsp, null] | 
| 1408955440  | Peekskill  | New city           | 20 Maple Avenue       |               | New City    | NY    | 10956    | None           | [http://www.wcb.ny.gov/content/main/DistrictOffices/Peeks.jsp, null]     | 
| 1408955440  | Albany     | Plattsburgh        | 23 Elm Street         | Suite 500     | Plattsburgh | NY    | 12901    | (866) 750-5157 | [http://www.wcb.ny.gov/content/main/DistrictOffices/Albany.jsp, null]    | 
| 1408955440  | Rochester  | Batavia            | 83 Main Street        | Rear Entrance | Batavia     | NY    | 14020    | (866) 211-0644 | [http://www.wcb.ny.gov/content/main/DistrictOffices/Roch.jsp, null]      | 
| 1408955440  | Peekskill  | Peekskill          | 41 N. Division Street |               | Peekskill   | NY    | 10566    | (866) 746-0552 | [http://www.wcb.ny.gov/content/main/DistrictOffices/Peeks.jsp, null]     | 
| 1408955440  | Syracuse   | Watertown          | 317 Washington Street | 4th Floor     | Watertown   | NY    | 13601    | (866) 802-3730 | [http://www.wcb.ny.gov/content/main/DistrictOffices/Syra.jsp, null]      | 
| 1408955440  | Binghamton | Elmira             | 167 Lake Street       |               | Elmira      | NY    | 14901    | (866) 802-3604 | [http://www.wcb.ny.gov/content/main/DistrictOffices/Bing.jsp, null]      | 
| 1408955440  | Buffalo    | Allegany           | 106 East Main Street  |               | Allegany    | NY    | 14706    | None           | [http://www.wcb.ny.gov/content/main/DistrictOffices/Buffalo.jsp, null]   | 
| 1408955440  | Albany     | Hudson             | 309 Power Avenue      |               | Hudson      | NY    | 12534    | (866) 750-5157 | [http://www.wcb.ny.gov/content/main/DistrictOffices/Albany.jsp, null]    | 
```