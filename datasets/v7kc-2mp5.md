# Business Service Representatives

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/business-service-representatives) |
| Metadata | [Link](https://data.ny.gov/api/views/v7kc-2mp5) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/v7kc-2mp5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/v7kc-2mp5/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | v7kc-2mp5 |
| Name | Business Service Representatives |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | business service representatives, business, post jobs |
| Created | 2014-04-21T20:39:45Z |
| Publication Date | 2016-09-14T22:00:36Z |

## Description

The Business Service Representatives data set houses information about business service representatives across the state. These representatives are able to help businesses with their workforce needs.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | field_office    | Field Office    | text      | text        |
| Yes      | series tag  | counties_served | Counties Served | text      | text        |
| Yes      | series tag  | name            | Name            | text      | text        |
| Yes      | series tag  | street_address  | Street Address  | text      | text        |
| Yes      | series tag  | city            | City            | text      | text        |
| Yes      | series tag  | state           | State           | text      | text        |
| Yes      | series tag  | zip             | ZIP             | text      | number      |
| Yes      | series tag  | phone           | Phone           | text      | text        |
| Yes      | series tag  | email           | Email           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:v7kc-2mp5 d:2016-09-14T22:00:34.000Z t:zip=11801 t:phone="(516) 934-8521" t:email=Pamela.Bedford@labor.ny.gov t:field_office="Long Island" t:name="Pamela Bedford" t:state=NY t:counties_served="Nassau, Suffolk" t:street_address="303 Old Country Rd" t:city=Hicksville m:row_number.v7kc-2mp5=1

series e:v7kc-2mp5 d:2016-09-14T22:00:34.000Z t:zip=13760 t:phone="(607) 741-4518" t:email=David.Croston@labor.ny.gov t:field_office="Southern Tier" t:name="David Croston" t:state=NY t:counties_served="Broome, Tioga, Otsego, Delaware, Chenango, Chemung, Schuyler, Steuben, Tompkins" t:street_address="2001 E. Perimeter Rd. E" t:city=Endicott m:row_number.v7kc-2mp5=2

series e:v7kc-2mp5 d:2016-09-14T22:00:34.000Z t:zip=12903 t:phone="(518) 561-8308" t:email=Melissa.Johnson@labor.ny.gov t:field_office="North Country" t:name="Melissa Johnston" t:state=NY t:counties_served="Clinton, Essex, Franklin, Hamilton, Jefferson, Lewis, St. Lawrence" t:street_address="194 US Oval" t:city=Plattsburgh m:row_number.v7kc-2mp5=3
```

## Meta Commands

```ls
metric m:row_number.v7kc-2mp5 p:long l:"Row Number"

entity e:v7kc-2mp5 l:"Business Service Representatives" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/v7kc-2mp5

property e:v7kc-2mp5 t:meta.view v:id=v7kc-2mp5 v:category="Economic Development" v:attributionLink=https://labor.ny.gov/businessservices/localcontacts/localcontactsindex.shtm v:averageRating=0 v:name="Business Service Representatives" v:attribution="New York State Department of Labor"

property e:v7kc-2mp5 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:v7kc-2mp5 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:v7kc-2mp5 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | field_office   | counties_served                                                                 | name             | street_address                 | city        | state | zip   | phone          | email                         | 
| =========== | ============== | =============================================================================== | ================ | ============================== | =========== | ===== | ===== | ============== | ============================= | 
| 1473890434  | Long Island    | Nassau, Suffolk                                                                 | Pamela Bedford   | 303 Old Country Rd             | Hicksville  | NY    | 11801 | (516) 934-8521 | Pamela.Bedford@labor.ny.gov   | 
| 1473890434  | Southern Tier  | Broome, Tioga, Otsego, Delaware, Chenango, Chemung, Schuyler, Steuben, Tompkins | David Croston    | 2001 E. Perimeter Rd. E        | Endicott    | NY    | 13760 | (607) 741-4518 | David.Croston@labor.ny.gov    | 
| 1473890434  | North Country  | Clinton, Essex, Franklin, Hamilton, Jefferson, Lewis, St. Lawrence              | Melissa Johnston | 194 US Oval                    | Plattsburgh | NY    | 12903 | (518) 561-8308 | Melissa.Johnson@labor.ny.gov  | 
| 1473890434  | Hudson Valley  | Dutchess, Putnam, Westchester, Rockland, Sullivan, Orange, Ulster               | Sherry Young     | 3 Washington Center            | Newburg     | NY    | 12550 | (845) 568-5371 | Sherry.Young@labor.ny.gov     | 
| 1473890434  | New York City  | Bronx, Kings, New York, Queens, Richmond                                        | Jennifer Oh      | 9 Bond Street                  | Brooklyn    | NY    | 11201 | (718) 613-3413 | Jennifer.Oh@labor.ny.gov      | 
| 1473890434  | Capital Region | Albany, Rensselaer, Schenectady, Saratoga, Warren, Washington, Columbia, Greene | Brian Suedkamp   | 1220 Washington Ave. Room 169  | Albany      | NY    | 12240 | (518) 457-1504 | Brian.Suedkamp@labor.ny.gov   | 
| 1473890434  | Mohawk Valley  | Herkimer, Schoharie, Montgomery, Fulton, Madison, Oneida                        | Maria Abraham    | 207 Genesee Street             | Utica       | NY    | 13501 | (315) 793-2271 | Maria.Abraham@labor.ny.gov    | 
| 1473890434  | Central NY     | Cortland, Cayuga, Onondaga, Oswego                                              | Roy Jewell       | 450 South Salina St, Suite 302 | Syracuse    | NY    | 13202 | (315) 479-3362 | Roy.Jewell@labor.ny.gov       | 
| 1473890434  | Finger Lakes   | Monroe, Orleans, Genesee, Wyoming, Livingston, Ontario, Yates, Seneca, Wayne    | Brendalyn Bynoe  | 276 Waring Road                | Rochester   | NY    | 14609 | (585) 258-8875 | Brendalyn.Bynoe@labor.ny.gov  | 
| 1473890434  | Western NY     | Erie, Niagara, Allegany, Cattaraugus, Chautauqua                                | Deborah Arbutina | 290 Main St.                   | Buffalo     | NY    | 14202 | (716) 851-2673 | Deborah.Arbutina@labor.ny.gov | 
```