# County Seats

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-seats) |
| Metadata | [Link](https://data.ny.gov/api/views/4xc7-bukh) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4xc7-bukh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4xc7-bukh/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4xc7-bukh |
| Name | County Seats |
| Attribution | Office of Information Technology Services |
| Category | Government & Finance |
| Tags | county, office, seat, gis |
| Created | 2013-03-01T18:19:02Z |
| Publication Date | 2014-01-16T17:47:47Z |

## Description

Listing of the official county seat for each county in New York. The locations are the street address of the primary county office building.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | county         | County         | text      | text        |
| Yes      | series tag  | county_seat    | County Seat    | text      | text        |
| No       |             | address        | Address        | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | zip5           | Zip5           | text      | number      |
| Yes      | series tag  | contact_type   | Contact Type   | text      | text        |
| Yes      | series tag  | phone          | Phone          | text      | text        |
| No       |             | longitude      | Longitude      | number    | number      |
| No       |             | latitude       | Latitude       | number    | number      |
| Yes      | series tag  | county_website | County Website | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,longitude,latitude
```

## Data Commands

```ls
series e:4xc7-bukh d:2014-01-16T09:47:15.000Z t:zip5=12207 t:phone=(518)447-7040 t:county=Albany t:county_website=http://www.albanycounty.com/ t:contact_type="County Executive's Office" t:county_seat="City of Albany" t:city=Albany m:row_number.4xc7-bukh=1

series e:4xc7-bukh d:2014-01-16T09:47:15.000Z t:zip5=14813 t:phone=(585)268-9217 t:county=Allegany t:county_website=http://www.alleganyco.com/ t:contact_type="County Administrator's Office" t:county_seat="Village of Belmont" t:city=Belmont m:row_number.4xc7-bukh=2

series e:4xc7-bukh d:2014-01-16T09:47:15.000Z t:zip5=10451 t:phone=(718)590-3500 t:county=Bronx t:county_website=http://bronxboropres.nyc.gov/ t:contact_type="Borough President's Office" t:county_seat="Borough of the Bronx" t:city="New York" m:row_number.4xc7-bukh=3
```

## Meta Commands

```ls
metric m:row_number.4xc7-bukh p:long l:"Row Number"

entity e:4xc7-bukh l:"County Seats" t:attribution="Office of Information Technology Services" t:url=https://data.ny.gov/api/views/4xc7-bukh

property e:4xc7-bukh t:meta.view v:id=4xc7-bukh v:category="Government & Finance" v:averageRating=0 v:name="County Seats" v:attribution="Office of Information Technology Services"

property e:4xc7-bukh t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4xc7-bukh t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4xc7-bukh t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | county      | county_seat              | address             | city          | zip5  | contact_type                  | phone         | longitude         | latitude         | county_website                                            | 
| =========== | =========== | ======================== | =================== | ============= | ===== | ============================= | ============= | ================= | ================ | ========================================================= | 
| 1389865635  | Albany      | City of Albany           | 112 State Street    | Albany        | 12207 | County Executive's Office     | (518)447-7040 | -73.7539594378    | 42.6501637986    | [http://www.albanycounty.com/, null]                      | 
| 1389865635  | Allegany    | Village of Belmont       | 7 Court St.         | Belmont       | 14813 | County Administrator's Office | (585)268-9217 | -78.0332072212    | 42.2248679417    | [http://www.alleganyco.com/, null]                        | 
| 1389865635  | Bronx       | Borough of the Bronx     | 851 Grand Concourse | New York      | 10451 | Borough President's Office    | (718)590-3500 | -73.9237616166996 | 40.8262886480416 | [http://bronxboropres.nyc.gov/, null]                     | 
| 1389865635  | Broome      | City of Binghamton       | 60 Hawley Street    | Binghamton    | 13902 | County Executive's Office     | (607)778-2109 | -75.9107060717799 | 42.0966824827941 | [http://www.gobroomecounty.com/, null]                    | 
| 1389865635  | Cattaraugus | Village of Little Valley | 303 Court St.       | Little Valley | 14755 | County Administrator's Office | (716)938-2577 | -78.8005248568    | 42.2521093584    | [http://www.cattco.org/, null]                            | 
| 1389865635  | Cayuga      | City of Auburn           | 160 Genesee St.     | Auburn        | 13021 | County Administrator's Office | (315)253-1525 | -76.5695460095    | 42.9297172717    | [http://www.co.cayuga.ny.us/, null]                       | 
| 1389865635  | Chautauqua  | Village of Mayville      | 3 North Erie Street | Mayville      | 14757 | County Executive's Office     | (716)753-7111 | -79.5049079999    | 42.2546709999    | [http://www.co.chautauqua.ny.us/pages/default.aspx, null] | 
| 1389865635  | Chemung     | City of Elmira           | 203 Lake St.        | Elmira        | 14902 | County Executive's Office     | (607)737-2912 | -76.8020805169769 | 42.0899894611913 | [http://www.chemungcounty.com/, null]                     | 
| 1389865635  | Chenango    | City of Norwich          | 5 Court St.         | Norwich       | 13815 | County Clerk's Office         | (607)337-1450 | -75.526183406     | 42.5319299709    | [http://www.co.chenango.ny.us/, null]                     | 
| 1389865635  | Clinton     | City of Plattsburgh      | 137 Margaret St.    | Plattsburgh   | 12901 | County Administrator's Office | (518)565-4600 | -73.4539736654    | 44.6992641965    | [http://www.clintoncountygov.com/, null]                  | 
```