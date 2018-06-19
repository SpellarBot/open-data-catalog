# Department of Motor Vehicle (DMV) Office Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-motor-vehicle-dmv-office-locations) |
| Metadata | [Link](https://data.ny.gov/api/views/9upz-c7xg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9upz-c7xg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9upz-c7xg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9upz-c7xg |
| Name | Department of Motor Vehicle (DMV) Office Locations |
| Attribution | NYS Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv, offices, tvb, tickets, vehicle safety |
| Created | 2013-02-28T22:34:09Z |
| Publication Date | 2016-02-10T23:03:37Z |

## Description

This dataset contains the list of all Department of Motor Vehicle, (DMV), offices in NYS, with addresses, office hours, latitude and longitude coordinates, and phone numbers.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| No       | time        | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | series tag  | office_name               | Office Name               | text      | text        |
| Yes      | series tag  | office_type               | Office Type               | text      | text        |
| Yes      | series tag  | public_phone_number       | Public Phone Number       | text      | number      |
| Yes      | series tag  | public_phone_extension    | Public Phone Extension    | text      | text        |
| Yes      | series tag  | street_address_line_1     | Street Address Line 1     | text      | text        |
| Yes      | series tag  | street_address_line_2     | Street Address Line 2     | text      | text        |
| Yes      | series tag  | city                      | City                      | text      | text        |
| Yes      | series tag  | state                     | State                     | text      | text        |
| Yes      | series tag  | zip_code                  | Zip Code                  | text      | text        |
| Yes      | series tag  | monday_beginning_hours    | Monday Beginning Hours    | text      | text        |
| Yes      | series tag  | monday_ending_hours       | Monday Ending Hours       | text      | text        |
| Yes      | series tag  | tuesday_beginning_hours   | Tuesday Beginning Hours   | text      | text        |
| Yes      | series tag  | tuesday_ending_hours      | Tuesday Ending Hours      | text      | text        |
| Yes      | series tag  | wednesday_beginning_hours | Wednesday Beginning Hours | text      | text        |
| Yes      | series tag  | wednesday_ending_hours    | Wednesday Ending Hours    | text      | text        |
| Yes      | series tag  | thursday_beginning_hours  | Thursday Beginning Hours  | text      | text        |
| Yes      | series tag  | thursday_ending_hours     | Thursday Ending Hours     | text      | text        |
| Yes      | series tag  | friday_beginning_hours    | Friday Beginning Hours    | text      | text        |
| Yes      | series tag  | friday_ending_hours       | Friday Ending Hours       | text      | text        |
| Yes      | series tag  | saturday_beginning_hours  | Saturday Beginning Hours  | text      | text        |
| Yes      | series tag  | saturday_ending_hours     | Saturday Ending Hours     | text      | text        |
| Yes      | series tag  | has_kiosk                 | Has Kiosk?                | text      | text        |
| No       |             | latitude                  | Latitude                  | number    | number      |
| No       |             | longitude                 | Longitude                 | number    | number      |
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
series e:9upz-c7xg d:2016-02-10T15:02:36.000Z t:office_name=ALBION t:monday_ending_hours="4:30 PM" t:friday_ending_hours="4:30 PM" t:monday_beginning_hours="9:00 AM" t:zip_code=14411 t:office_type=CO t:state=NY t:wednesday_beginning_hours="9:00 AM" t:friday_beginning_hours="9:00 AM" t:city=Albion t:thursday_ending_hours="4:30 PM" t:wednesday_ending_hours="4:30 PM" t:public_phone_number=5855893214 t:street_address_line_1="14016 Route 31W" t:tuesday_ending_hours="4:30 PM" t:thursday_beginning_hours="9:00 AM" t:has_kiosk=N t:tuesday_beginning_hours="9:00 AM" m:row_number.9upz-c7xg=1

series e:9upz-c7xg d:2016-02-10T15:02:36.000Z t:office_name=ALBANY t:monday_ending_hours="4:00 PM" t:friday_ending_hours="4:00 PM" t:monday_beginning_hours="8:30 AM" t:zip_code=12202 t:office_type=DO t:state=NY t:wednesday_beginning_hours="8:30 AM" t:friday_beginning_hours="8:30 AM" t:city=Albany t:thursday_ending_hours="6:00 PM" t:wednesday_ending_hours="4:00 PM" t:public_phone_number=5184869786 t:street_address_line_1="224-260 S. Pearl Street" t:tuesday_ending_hours="4:00 PM" t:thursday_beginning_hours="10:00 AM" t:has_kiosk=N t:tuesday_beginning_hours="8:30 AM" m:row_number.9upz-c7xg=2

series e:9upz-c7xg d:2016-02-10T15:02:36.000Z t:office_name="AMHERST - NORTHTOWN PLAZA" t:monday_ending_hours="4:45 PM" t:friday_ending_hours="4:45 PM" t:monday_beginning_hours="9:00 AM" t:zip_code=14226 t:office_type=CO t:state=NY t:wednesday_beginning_hours="9:00 AM" t:friday_beginning_hours="9:00 AM" t:city=Amherst t:thursday_ending_hours="4:45 PM" t:wednesday_ending_hours="4:45 PM" t:public_phone_number=7168587450 t:street_address_line_1="3095-A Sheridan Drive" t:tuesday_ending_hours="4:45 PM" t:thursday_beginning_hours="9:00 AM" t:has_kiosk=N t:tuesday_beginning_hours="9:00 AM" m:row_number.9upz-c7xg=3
```

## Meta Commands

```ls
metric m:row_number.9upz-c7xg p:long l:"Row Number"

entity e:9upz-c7xg l:"Department of Motor Vehicle (DMV) Office Locations" t:attribution="NYS Department of Motor Vehicles" t:url=https://data.ny.gov/api/views/9upz-c7xg

property e:9upz-c7xg t:meta.view v:id=9upz-c7xg v:category=Transportation v:averageRating=0 v:name="Department of Motor Vehicle (DMV) Office Locations" v:attribution="NYS Department of Motor Vehicles"

property e:9upz-c7xg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9upz-c7xg t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:9upz-c7xg t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | office_name               | office_type | public_phone_number | public_phone_extension | street_address_line_1   | street_address_line_2    | city         | state | zip_code | monday_beginning_hours | monday_ending_hours | tuesday_beginning_hours | tuesday_ending_hours | wednesday_beginning_hours | wednesday_ending_hours | thursday_beginning_hours | thursday_ending_hours | friday_beginning_hours | friday_ending_hours | saturday_beginning_hours | saturday_ending_hours | has_kiosk | latitude  | longitude  | 
| =========== | ========================= | =========== | =================== | ====================== | ======================= | ======================== | ============ | ===== | ======== | ====================== | =================== | ======================= | ==================== | ========================= | ====================== | ======================== | ===================== | ====================== | =================== | ======================== | ===================== | ========= | ========= | ========== | 
| 1455116556  | ALBION                    | CO          | 5855893214          |                        | 14016 Route 31W         |                          | Albion       | NY    | 14411    | 9:00 AM                | 4:30 PM             | 9:00 AM                 | 4:30 PM              | 9:00 AM                   | 4:30 PM                | 9:00 AM                  | 4:30 PM               | 9:00 AM                | 4:30 PM             |                          |                       | N         | 43.238145 | -78.214506 | 
| 1455116556  | ALBANY                    | DO          | 5184869786          |                        | 224-260 S. Pearl Street |                          | Albany       | NY    | 12202    | 8:30 AM                | 4:00 PM             | 8:30 AM                 | 4:00 PM              | 8:30 AM                   | 4:00 PM                | 10:00 AM                 | 6:00 PM               | 8:30 AM                | 4:00 PM             |                          |                       | N         | 42.642577 | -73.756299 | 
| 1455116556  | AMHERST - NORTHTOWN PLAZA | CO          | 7168587450          |                        | 3095-A Sheridan Drive   |                          | Amherst      | NY    | 14226    | 9:00 AM                | 4:45 PM             | 9:00 AM                 | 4:45 PM              | 9:00 AM                   | 4:45 PM                | 9:00 AM                  | 4:45 PM               | 9:00 AM                | 4:45 PM             |                          |                       | N         | 42.980445 | -78.819265 | 
| 1455116556  | AUBURN                    | CO          | 3152531241          |                        | 160 Genesee Street      |                          | Auburn       | NY    | 13021    | 9:00 AM                | 4:30 PM             | 9:00 AM                 | 4:30 PM              | 9:00 AM                   | 4:30 PM                | 9:00 AM                  | 6:00 PM               | 9:00 AM                | 4:30 PM             |                          |                       | N         | 42.929729 | -76.569901 | 
| 1455116556  | BRONX T V B               | TV          | 7184885710          |                        | 696 East Fordham Road   |                          | Bronx        | NY    | 10458    | 8:30 AM                | 4:00 PM             | 8:30 AM                 | 4:00 PM              | 8:30 AM                   | 4:00 PM                | 8:30 AM                  | 6:00 PM               | 8:30 AM                | 4:00 PM             |                          |                       | N         |           |            | 
| 1455116556  | BEACON                    | CO          | 8458384891          |                        | 223 Main Street         |                          | Beacon       | NY    | 12508    | 9:00 AM                | 4:45 PM             | 9:00 AM                 | 4:45 PM              | 9:00 AM                   | 4:45 PM                | 9:00 AM                  | 4:45 PM               | 9:00 AM                | 4:45 PM             |                          |                       | N         | 41.506693 | -73.973895 | 
| 1455116556  | BELMONT                   | CO          | 5852689267          |                        | 7 Court Street          | Court House              | Belmont      | NY    | 14813    | 9:00 AM                | 5:00 PM             | 9:00 AM                 | 5:00 PM              | 9:00 AM                   | 5:00 PM                | 9:00 AM                  | 5:00 PM               | 9:00 AM                | 5:00 PM             |                          |                       | N         | 42.224775 | -78.033519 | 
| 1455116556  | BALLSTON SPA              | CO          | 5188852227          |                        | 40 McMaster Street      |                          | Ballston Spa | NY    | 12020    | 8:00 AM                | 4:45 PM             | 8:00 AM                 | 4:45 PM              | 8:00 AM                   | 6:00 PM                | 8:00 AM                  | 4:45 PM               | 8:00 AM                | 4:45 PM             |                          |                       | N         | 42.998908 | -73.850503 | 
| 1455116556  | BROOME COUNTY MOBILE      | MO          | 6077782337          |                        | Headquartered at        | 181 Clinton St           | Binghamton   | NY    | 13905    | 10:00 AM               | 3:00 PM             | 10:00 AM                | 3:00 PM              | 10:00 AM                  | 3:00 PM                | 10:00 AM                 | 3:00 PM               | 10:00 AM               | 3:00 PM             |                          |                       | N         |           |            | 
| 1455116556  | BROOKLYN NORTH T V B      | TV          | 7184885710          |                        | Atlantic Center Mall    | 625 Atlantic Ave, 2nd Fl | Brooklyn     | NY    | 11217    | 8:30 AM                | 4:00 PM             | 8:30 AM                 | 4:00 PM              | 8:30 AM                   | 4:00 PM                | 8:30 AM                  | 6:00 PM               | 8:30 AM                | 4:00 PM             |                          |                       | N         |           |            | 
```