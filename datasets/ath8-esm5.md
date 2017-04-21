# Smoke Free Housing in King County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/smoke-free-housing-in-king-county) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/ath8-esm5) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/ath8-esm5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/ath8-esm5/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | ath8-esm5 |
| Name | Smoke Free Housing in King County |
| Attribution | Seattle-King County Public Health |
| Category | Health |
| Tags | asthma, smoke-free, tobacco-free, housing |
| Created | 2017-01-24T18:15:57Z |
| Publication Date | 2017-02-23T00:16:22Z |

## Description

Locations and contact information for smoke-free housing in King County

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | building_name  | Building Name  | text      | text        |
| Yes      | series tag  | description    | Description    | text      | text        |
| Yes      | series tag  | street_address | Street Address | text      | text        |
| Yes      | series tag  | city           | City           | text      | text        |
| Yes      | series tag  | zip_code       | Zip code       | text      | text        |
| Yes      | series tag  | url            | URL            | url       | url         |
| Yes      | series tag  | phone          | Phone          | phone     | phone       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ath8-esm5 d:2017-02-23T00:09:04.000Z t:building_name="Glennwood Townhomes" t:phone_number=425-226-1853 t:zip_code=98058 t:description="Affordable Housing" t:street_address="1141 & 1147 Glenwood Avenue NE" t:url=http://www.rentonhousing.org/subsidized-housing.html t:city=Renton m:row_number.ath8-esm5=1

series e:ath8-esm5 d:2017-02-23T00:09:04.000Z t:building_name="Plaza Roberto Maestas" t:zip_code=98104 t:description="Affordable Housing" t:street_address="1670 South Roberto Maestas Festival St" t:url=http://plazarobertomaestas.org/ t:city=Seattle m:row_number.ath8-esm5=2

series e:ath8-esm5 d:2017-02-23T00:09:04.000Z t:building_name="Vantage Point" t:phone_number=206-315-4379 t:zip_code=98055 t:description="Subsidized Housing" t:street_address="17901 105th Pl SE" t:url="https://www.kcha.org/housing/property.aspx?PropertyID=146" t:city=Renton m:row_number.ath8-esm5=3
```

## Meta Commands

```ls
metric m:row_number.ath8-esm5 p:long l:"Row Number"

entity e:ath8-esm5 l:"Smoke Free Housing in King County" t:attribution="Seattle-King County Public Health" t:url=https://data.kingcounty.gov/api/views/ath8-esm5

property e:ath8-esm5 t:meta.view v:id=ath8-esm5 v:category=Health v:attributionLink=http://kingcounty.gov/depts/health v:averageRating=0 v:name="Smoke Free Housing in King County" v:attribution="Seattle-King County Public Health"

property e:ath8-esm5 t:meta.view.license v:name="Public Domain"

property e:ath8-esm5 t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:ath8-esm5 t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| :updated_at | building_name         | description             | street_address                         | city             | zip_code | url                                                                            | phone                  | 
| =========== | ===================== | ======================= | ====================================== | ================ | ======== | ============================================================================== | ====================== | 
| 1487808544  | Glennwood Townhomes   | Affordable Housing      | 1141 & 1147 Glenwood Avenue NE         | Renton           | 98058    | [http://www.rentonhousing.org/subsidized-housing.html, null]                   | [425-226-1853, null]   | 
| 1487808544  | Plaza Roberto Maestas | Affordable Housing      | 1670 South Roberto Maestas Festival St | Seattle          | 98104    | [http://plazarobertomaestas.org/, null]                                        | [null, null]           | 
| 1487808544  | Vantage Point         | Subsidized Housing      | 17901 105th Pl SE                      | Renton           | 98055    | [https://www.kcha.org/housing/property.aspx?PropertyID=146, null]              | [206-315-4379, null]   | 
| 1487808558  | Shelcor               | Subsidized Housing      | 503 Fourth Ave. S.                     | Kent             | 98030    | [https://www.kcha.org/housing/property.aspx?PropertyID=90, null]               | [(253) 437-2440, null] | 
| 1487808558  | Stewart Manor         | Affordable Housing      | 6339 34th Ave SW                       | Seattle          | 98126    | [https://www.seattlehousing.org/housing/public/locations/stewart-manor/, null] | [206-932-8107, null]   | 
| 1487808558  | Harbor Steps          |                         | 1221 First Avenue                      | Seattle          | 98101    | [http://www.harborsteps.com/main.htm, null]                                    | [206-866-0497, null]   | 
| 1487808558  | Cedar River Terrace   | Senior Housing          | 51 Burnett Ave S                       | Renton           | 98057    | [http://www.rentonhousing.org/senior-housing.html, null]                       | [425-226-1854, null]   | 
| 1487808558  | Center West           | Affordable Housing      | 533 3rd Ave W                          | Seattle          | 98119    | [https://www.seattlehousing.org/housing/public/locations/center-west/, null]   | [206-281-9195, null]   | 
| 1487808558  | Woodland North        | Moderate-Income Housing | 3611 N.E. 155th St.                    | Lake Forest Park | 98155    | [https://www.kcha.org/housing/property.aspx?PropertyID=117, null]              | [(206) 367-6537, null] | 
| 1487808558  | Meadows on Lea Hill   | Other Rental Housing    | 12505 S.E. 312th St.                   | Auburn           | 98092    | [https://www.kcha.org/housing/property.aspx?PropertyID=63, null]               | [(253) 833-5300, null] | 
```