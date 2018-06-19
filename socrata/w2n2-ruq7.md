# Certified Clean Marinas

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/certified-clean-marinas-2da43) |
| Metadata | [Link](https://data.oregon.gov/api/views/w2n2-ruq7) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/w2n2-ruq7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/w2n2-ruq7/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | w2n2-ruq7 |
| Name | Certified Clean Marinas |
| Attribution | Oregon State Marine Board |
| Category | Natural Resources |
| Tags | clean marinas, boating, clean boating, marinas, moorages, floating homes, marine board |
| Created | 2011-04-06T19:32:29Z |
| Publication Date | 2015-12-15T18:12:22Z |

## Description

The Oregon Clean Marina program is a voluntary program working to protect and improve local water quality by promoting the usage of environmentally sensitive practices at marinas. The program provides the opportunity for marinas, boatyards, yacht clubs, and floating home moorages to receive recognition for helping to establish and promote a cleaner marine environment for Oregon.

If a facility is in compliance with existing environmental regulations and uses a high percentage of the recommended best management practices, it can be designated as an Oregon Clean Marina. Such certified marinas are authorized to fly the Clean Marina flag and use the logo in their advertising. The flag and logo are signals to boaters that a marina cares about the cleanliness of Oregon waterways.

The program also provides information to marine facility managers on how to eliminate or reduce the input of polluting materials ? such as oil, paint, cleaning chemicals, sewage, fish waste, and trash ? into the environment.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | facility_name             | Facility Name             | text          | text          |
| Yes      | series tag     | view_marina_details_below | View Marina Details Below | photo         | photo         |
| Yes      | series tag     | phone                     | Phone                     | phone         | phone         |
| Yes      | series tag     | website                   | website                   | url           | url           |
| Yes      | series tag     | waterbody                 | Waterbody                 | text          | text          |
| Yes      | series tag     | region                    | Region                    | text          | text          |
| Yes      | series tag     | ownership                 | Ownership                 | text          | text          |
| Yes      | series tag     | facility_owner            | Facility Owner            | text          | text          |
| Yes      | series tag     | contact                   | Contact                   | text          | text          |
| No       |                | date_pledged              | Date Pledged              | calendar_date | calendar_date |
| Yes      | time           | date_certified            | Date Certified            | calendar_date | calendar_date |
| Yes      | series tag     | type                      | Type                      | text          | text          |
| Yes      | numeric metric | boat_slips                | Boat Slips                | number        | number        |
| Yes      | numeric metric | home_slips                | Home Slips                | number        | number        |
| Yes      | series tag     | boater_services           | Boater Services           | photo         | photo         |
```

## Time Field

```ls
Value = date_certified
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_pledged
```

## Data Commands

```ls
series e:w2n2-ruq7 d:2006-12-15T00:00:00.000Z t:region="Lower Columbia River" t:phone_number=503-543-3836 t:facility_name="McCuddy's Landing Marina" t:ownership=Private t:website=http://www.mccuddysmarina.com/marinas/landing.html t:waterbody="Multnomah Channel" t:facility_owner="McCuddy's Marina" t:view_marina_details_below=Xduq-rNf02Ft3qWEWUUmHeSF-KkhPRZN4mSIHP_2-FU t:type=Marina t:contact="Sharon McBride" t:boater_services=p9vfMqCtSWfqN4atGZ9aj-vlIUVIJ8yNntsyxUhrFkU m:home_slips=0 m:boat_slips=200

series e:w2n2-ruq7 d:2006-11-21T00:00:00.000Z t:region="Portland Area" t:phone_number=503-283-2444 t:facility_name="Tomahawk Bay Moorage" t:ownership=Private t:website=http://www.columbiacrossings.com/tomahawk.html t:waterbody="Columbia River" t:facility_owner="Columbia Crossings" t:view_marina_details_below=XX7Zzy5eJxLzxOOkhBw-LDkmVCadFmn-lG2QjgCq-Ec t:type=Marina t:contact="John Villanueva" t:boater_services=JSx8BwsFKe1geEa0S9Z4v5A7xTBcsjbKClNkvKgu5eU m:home_slips=0 m:boat_slips=770

series e:w2n2-ruq7 d:2008-08-19T00:00:00.000Z t:region="Upper Columbia River" t:phone_number=541-298-4148 t:facility_name="Port of The Dalles" t:ownership=Public/Private t:website=http://www.portofthedalles.com/m_info.cfm t:waterbody="Columbia River" t:facility_owner="Port of the Dalles" t:view_marina_details_below=_6ED1j9h97E5oGWWkk3iKd-0gOeqIn9q6Vx36MpqJi0 t:type=Marina t:contact="Kathleen Norton" t:boater_services=PL9wr5lA4Kfz9AdsRkMAwYzTJ1je1eNlIcYXmFDACY8 m:home_slips=62 m:boat_slips=25
```

## Meta Commands

```ls
metric m:boat_slips p:integer l:"Boat Slips" t:dataTypeName=number

metric m:home_slips p:integer l:"Home Slips" t:dataTypeName=number

entity e:w2n2-ruq7 l:"Certified Clean Marinas" t:attribution="Oregon State Marine Board" t:url=https://data.oregon.gov/api/views/w2n2-ruq7

property e:w2n2-ruq7 t:meta.view v:id=w2n2-ruq7 v:category="Natural Resources" v:attributionLink=http://www.boatoregon.com v:averageRating=0 v:name="Certified Clean Marinas" v:attribution="Oregon State Marine Board"

property e:w2n2-ruq7 t:meta.view.owner v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:displayName="Ashley Massey"

property e:w2n2-ruq7 t:meta.view.tableauthor v:id=a2bu-8256 v:profileImageUrlMedium=/api/users/a2bu-8256/profile_images/THUMB v:profileImageUrlLarge=/api/users/a2bu-8256/profile_images/LARGE v:screenName="Ashley Massey" v:profileImageUrlSmall=/api/users/a2bu-8256/profile_images/TINY v:roleName=editor v:displayName="Ashley Massey"
```

## Top Records

```ls
| facility_name            | view_marina_details_below                   | phone                | website                                                    | waterbody         | region               | ownership      | facility_owner     | contact            | date_pledged        | date_certified      | type                  | boat_slips | home_slips | boater_services                             | 
| ======================== | =========================================== | ==================== | ========================================================== | ================= | ==================== | ============== | ================== | ================== | =================== | =================== | ===================== | ========== | ========== | =========================================== | 
| McCuddy's Landing Marina | Xduq-rNf02Ft3qWEWUUmHeSF-KkhPRZN4mSIHP_2-FU | [503-543-3836, null] | [http://www.mccuddysmarina.com/marinas/landing.html, null] | Multnomah Channel | Lower Columbia River | Private        | McCuddy's Marina   | Sharon McBride     | 2005-11-30T00:00:00 | 2006-12-15T00:00:00 | Marina                | 200        | 0          | p9vfMqCtSWfqN4atGZ9aj-vlIUVIJ8yNntsyxUhrFkU | 
| Tomahawk Bay Moorage     | XX7Zzy5eJxLzxOOkhBw-LDkmVCadFmn-lG2QjgCq-Ec | [503-283-2444, null] | [http://www.columbiacrossings.com/tomahawk.html, null]     | Columbia River    | Portland Area        | Private        | Columbia Crossings | John Villanueva    | 2005-11-30T00:00:00 | 2006-11-21T00:00:00 | Marina                | 770        | 0          | JSx8BwsFKe1geEa0S9Z4v5A7xTBcsjbKClNkvKgu5eU | 
| Port of The Dalles       | _6ED1j9h97E5oGWWkk3iKd-0gOeqIn9q6Vx36MpqJi0 | [541-298-4148, null] | [http://www.portofthedalles.com/m_info.cfm, null]          | Columbia River    | Upper Columbia River | Public/Private | Port of the Dalles | Kathleen Norton    | 2007-07-25T00:00:00 | 2008-08-19T00:00:00 | Marina                | 25         | 62         | PL9wr5lA4Kfz9AdsRkMAwYzTJ1je1eNlIcYXmFDACY8 | 
| Rocky Pointe Marina      | 9cxwP4-OKQLds8af0MLiOq6Z6pie8YgrtueWb3AGGIA | [503-543-7003, null] | [http://rpmarina.com/marina_services.asp, null]            | Multnomah Channel | Lower Columbia River | Private        |                    | Stan Tonneson      | 2006-01-08T00:00:00 | 2006-04-26T00:00:00 | Marina with Boatyard  | 150        | 0          | 8k1TMZorpBVz8db_AO5K-oKsqe9jhm853N9KqFEf0KQ | 
| Columbia Ridge Marina    | 5RI9U3zdeV8trgJ1FmD5MXvkMOeoVwH7LqPcMK2iziI | [503-665-3705, null] | [http://www.columbiaridgemarina.com, null]                 | Columbia River    | Portland Area        | Private        |                    | Duane Dominguez    | 2006-03-23T00:00:00 | 2007-04-23T00:00:00 | Floating Home Moorage | 0          | 50         | rLf3JId0z4thvX871XZv3_i4kEMGFfg9XG29IsSFoUU | 
| Odell Lake Resort Marina | SLNSpkbiwDSFfNF6qN2Z6oz5k5vB4nu3f-kJ76ofHHs | [541-433-2540, null] | [http://www.odelllakeresort.com, null]                     | Odell Lake        | Southern Oregon      | Private        |                    | Jon & Tammy Ditgen | 2006-07-25T00:00:00 | 2007-07-30T00:00:00 | Marina                | 45         | 0          | u4usC6qY2IQM_dMQV5RPSxTWCPTQ38EcG7h0MeSWdvU | 
| Coos Bay Yacht Club      | LFdqF_apbPQEfZwW986BiA4MoSb-igEH9hSzP1Sf_zE | [, null]             | [http://coosbayyachtclub.org/, null]                       | Tenmile Lake      | South Central Coast  | Private        |                    | George Tinker      | 2007-08-02T00:00:00 | 2007-09-25T00:00:00 | Private Yacht Club    | 60         | 0          | FqVd6eTrve3xvOV_oGDpniGEpUypQKMP6IR6v2kj0iM | 
| Willamette Sailing Club  | uHdfj20or9YH3HX3w-KiUpV7ma-h3Uw_V2zEXg4ncyA | [503-246-5345, null] | [http://www.willamettesailingclub.com/, null]              | Willamette River  | Portland Area        | Private        |                    | Lauralee Symes     | 2007-12-09T00:00:00 | 2008-08-14T00:00:00 | Private Yacht Club    | 130        | 0          | FqVd6eTrve3xvOV_oGDpniGEpUypQKMP6IR6v2kj0iM | 
| Channel Island Marina    | Ekv2LJcNc5jnYXscVuKPmub4rJPhMSsPhxp0hQL7EgY | [, null]             | [null, null]                                               | Multnomah Channel | Lower Columbia River | Private        |                    | Skip Sticka        | 2007-05-23T00:00:00 | 2007-08-07T00:00:00 | Floating Home Moorage | 18         | 19         | FqVd6eTrve3xvOV_oGDpniGEpUypQKMP6IR6v2kj0iM | 
| Dikeside Moorage         | PmjeIFP-QlSsc7NuXTPrTQhjvhKZ2cZWtxzgIIGugv0 | [, null]             | [null, null]                                               | Multnomah Channel | Lower Columbia River | Private        |                    | Bill Shaw          | 2006-05-25T00:00:00 | 2006-11-15T00:00:00 | Floating Home Moorage | 0          | 32         | FqVd6eTrve3xvOV_oGDpniGEpUypQKMP6IR6v2kj0iM | 
```