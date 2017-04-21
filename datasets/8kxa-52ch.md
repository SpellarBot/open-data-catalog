# Bridges To Health Service Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bridges-to-health-service-agencies) |
| Metadata | [Link](https://data.ny.gov/api/views/8kxa-52ch) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/8kxa-52ch/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/8kxa-52ch/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 8kxa-52ch |
| Name | Bridges To Health Service Agencies |
| Attribution | New York State Office of Children and Family Services |
| Category | Human Services |
| Tags | bridges to health (b2h), mental health, developmental disabilities |
| Created | 2013-10-09T13:11:40Z |
| Publication Date | 2016-02-19T15:19:41Z |

## Description

Included in this data set are all the Health Care Integration Agencies (HCIA) authorized to provide Bridges to Health (B2H) services in New York State. These community based services are available to children with significant mental health care needs, developmental disabilities or medical fragility who would otherwise require an institutional level of care.

## Columns

```ls
| Included | Schema Type | Field Name      | Name                                     | Data Type | Render Type |
| ======== | =========== | =============== | ======================================== | ========= | =========== |
| No       | time        | :updated_at     | updated_at                               | meta_data | meta_data   |
| Yes      | series tag  | agency_name     | Agency Name                              | text      | text        |
| Yes      | series tag  | street          | Street Address                           | text      | text        |
| Yes      | series tag  | city            | City                                     | text      | text        |
| Yes      | series tag  | state           | State                                    | text      | text        |
| Yes      | series tag  | zip             | Zip                                      | text      | text        |
| Yes      | series tag  | business_phone  | Business Phone                           | text      | text        |
| Yes      | series tag  | county          | Agency County                            | text      | text        |
| Yes      | series tag  | counties_served | Served Waiver Service Providers Counties | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8kxa-52ch d:2016-02-19T07:18:56.000Z t:zip=13502 t:business_phone=315-235-7701 t:county=Oneida t:street="1550 Champlin Ave." t:state=NY t:counties_served="Broome, Cayuga, Chenango, Cortland, Herkimer, Jefferson, Lewis, Madison, Oneida, Onondaga, Oswego, St. Lawrence, Tiago, Tompkins." t:agency_name="House of the Good Shepherd" t:city=Utica m:row_number.8kxa-52ch=1

series e:8kxa-52ch d:2016-02-19T07:18:56.000Z t:zip=10455 t:business_phone="347- 293-4160" t:county="New York" t:street="384 East 149th St., 5th Floor" t:state=NY t:counties_served="Bronx, Brooklyn, Manhattan, Queens, Staten Island" t:agency_name="Jewish Child Care Association of New York" t:city=Bronx m:row_number.8kxa-52ch=2

series e:8kxa-52ch d:2016-02-19T07:18:56.000Z t:zip=10010 t:business_phone=212-994-7912 t:county="New York" t:street="15 West 26th St., 6th Floor" t:state=NY t:counties_served="Bronx, Brooklyn, Manhattan, Queens, Staten Island" t:agency_name="New Alternatives for Children" t:city="New York" m:row_number.8kxa-52ch=3
```

## Meta Commands

```ls
metric m:row_number.8kxa-52ch p:long l:"Row Number"

entity e:8kxa-52ch l:"Bridges To Health Service Agencies" t:attribution="New York State Office of Children and Family Services" t:url=https://data.ny.gov/api/views/8kxa-52ch

property e:8kxa-52ch t:meta.view v:id=8kxa-52ch v:category="Human Services" v:attributionLink=http://ocfs.ny.gov/main/b2h/ v:averageRating=0 v:name="Bridges To Health Service Agencies" v:attribution="New York State Office of Children and Family Services"

property e:8kxa-52ch t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:8kxa-52ch t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:8kxa-52ch t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | agency_name                               | street                          | city      | state | zip   | business_phone         | county      | counties_served                                                                                                                   | 
| =========== | ========================================= | =============================== | ========= | ===== | ===== | ====================== | =========== | ================================================================================================================================= | 
| 1455866336  | House of the Good Shepherd                | 1550 Champlin Ave.              | Utica     | NY    | 13502 | 315-235-7701           | Oneida      | Broome, Cayuga, Chenango, Cortland, Herkimer, Jefferson, Lewis, Madison, Oneida, Onondaga, Oswego, St. Lawrence, Tiago, Tompkins. | 
| 1455866336  | Jewish Child Care Association of New York | 384 East 149th St., 5th Floor   | Bronx     | NY    | 10455 | 347- 293-4160          | New York    | Bronx, Brooklyn, Manhattan, Queens, Staten Island                                                                                 | 
| 1455866336  | New Alternatives for Children             | 15 West 26th St., 6th Floor     | New York  | NY    | 10010 | 212-994-7912           | New York    | Bronx, Brooklyn, Manhattan, Queens, Staten Island                                                                                 | 
| 1455866336  | Hillside 2 Children's Center              | 1183 Monroe Ave.                | Rochester | NY    | 14620 | 585-350-2513           | Monroe      | Chemung, Livingston, Monroe, Ontario, Schuyler, Seneca, Steuben, Wayne, Yates.                                                    | 
| 1455866336  | SCO Long Island - SCO Family of Services  | 1 Alexander Place               | Glen Cove | NY    | 11542 | 631-253-3504           | Suffolk     | Nassau, Suffolk                                                                                                                   | 
| 1455866336  | Abbott House Lower Hudson Valley          | 100 North Broadway              | Irvington | NY    | 10533 | 914-591-7300 ext. 3205 | Westchester | Dutchess, Orange, Putnam, Rockland, Sullivan, Ulster, Westchester.                                                                | 
| 1455866336  | Elmcrest Children's Center, Inc.          | 960 Salt Spring Road            | Syracuse  | NY    | 13224 | 315-463-9415 ext. 48   | Onandaga    | Broome, Cayuga, Chenango, Cortland, Herkimer, Jefferson, Lewis, Madison, Oneida, Onondaga, Oswego, St. Lawrence, Tiago, Tompkins. | 
| 1455866336  | Cardinal McCloskey Services               | 529 Courtlandt Ave., 4th Floor  | Bronx     | NY    | 10451 | 718-402-2150 ext. 737  | New York    | Bronx, Brooklyn, Manhattan, Queens, Staten Island                                                                                 | 
| 1455866336  | Catholic Guardian Society                 | 1780 Grand Concourse, 2nd floor | Bronx     | NY    | 10453 | 718-228-1515           | New York    | Bronx, Brooklyn, Manhattan, Queens, Staten Island                                                                                 | 
| 1455866336  | SCO Family of Services                    | 1958 Fulton St., 3rd Floor      | Brooklyn  | NY    | 11233 | 718-363-7490 ext.309   | New York    | Bronx, Brooklyn, Manhattan, Queens, Staten Island                                                                                 | 
```