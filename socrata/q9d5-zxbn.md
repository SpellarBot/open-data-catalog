# Guides Currently Licensed in New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/guides-currently-licensed-in-new-york-state) |
| Metadata | [Link](https://data.ny.gov/api/views/q9d5-zxbn) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/q9d5-zxbn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/q9d5-zxbn/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | q9d5-zxbn |
| Name | Guides Currently Licensed in New York State |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | guides, outdoor recreation, licensed guides |
| Created | 2016-05-27T18:17:51Z |
| Publication Date | 2016-06-14T17:13:23Z |

## Description

List of all Guides currently licensed by the NY State Department of Environmental Conservation's (DEC) Division of Forest Protection (DFP).  While DFP issues the licenses, compliance is monitored by NYS Forest Rangers.

## Columns

```ls
| Included | Schema Type | Field Name         | Name                     | Data Type     | Render Type   |
| ======== | =========== | ================== | ======================== | ============= | ============= |
| Yes      | series tag  | last_name          | Last Name                | text          | text          |
| Yes      | series tag  | name               | First Name               | text          | text          |
| Yes      | series tag  | city               | City                     | text          | text          |
| Yes      | series tag  | state              | State                    | text          | text          |
| Yes      | series tag  | zip                | Zip                      | text          | text          |
| Yes      | time        | expiration_date    | Expiration Date          | calendar_date | calendar_date |
| Yes      | series tag  | county             | County                   | text          | text          |
| Yes      | series tag  | badge_number       | Badge Number             | text          | number        |
| Yes      | series tag  | activity_type_desc | Activity Type Desription | text          | text          |
| Yes      | series tag  | phone              | Phone                    | text          | text          |
| Yes      | series tag  | business_name      | Business Name            | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:q9d5-zxbn d:2017-12-10T00:00:00.000Z t:zip=J8B2M8 t:phone=514-589-2087 t:activity_type_desc="Tier I Rock" t:name=Bjarne t:badge_number=6874 t:state=QC t:last_name=Baek t:city="Sainte Adele" m:row_number.q9d5-zxbn=1

series e:q9d5-zxbn d:2017-12-10T00:00:00.000Z t:zip=J8B2M8 t:phone=514-589-2087 t:activity_type_desc=Camping t:name=Bjarne t:badge_number=6874 t:state=QC t:last_name=Baek t:city="Sainte Adele" m:row_number.q9d5-zxbn=2

series e:q9d5-zxbn d:2017-12-10T00:00:00.000Z t:zip=J8B2M8 t:phone=514-589-2087 t:activity_type_desc=Hiking t:name=Bjarne t:badge_number=6874 t:state=QC t:last_name=Baek t:city="Sainte Adele" m:row_number.q9d5-zxbn=3
```

## Meta Commands

```ls
metric m:row_number.q9d5-zxbn p:long l:"Row Number"

entity e:q9d5-zxbn l:"Guides Currently Licensed in New York State" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/q9d5-zxbn

property e:q9d5-zxbn t:meta.view v:id=q9d5-zxbn v:category=Recreation v:attributionLink=http://www.dec.ny.gov/permits/30969.html v:averageRating=0 v:name="Guides Currently Licensed in New York State" v:attribution="New York State Department of Environmental Conservation"

property e:q9d5-zxbn t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:q9d5-zxbn t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| last_name     | name          | city             | state | zip    | expiration_date     | county | badge_number | activity_type_desc | phone        | business_name | 
| ============= | ============= | ================ | ===== | ====== | =================== | ====== | ============ | ================== | ============ | ============= | 
| Baek          | Bjarne        | Sainte Adele     | QC    | J8B2M8 | 2017-12-10T00:00:00 |        | 6874         | Tier I Rock        | 514-589-2087 |               | 
| Baek          | Bjarne        | Sainte Adele     | QC    | J8B2M8 | 2017-12-10T00:00:00 |        | 6874         | Camping            | 514-589-2087 |               | 
| Baek          | Bjarne        | Sainte Adele     | QC    | J8B2M8 | 2017-12-10T00:00:00 |        | 6874         | Hiking             | 514-589-2087 |               | 
| Baek          | Bjarne        | Sainte Adele     | QC    | J8B2M8 | 2017-12-10T00:00:00 |        | 6874         | Tier I Ice         | 514-589-2087 |               | 
| Barmettler    | Luzia         | Longueuil        | QC    | J4J    | 2020-06-19T00:00:00 |        | 3524         | Hiking             | 450-448-5026 |               | 
| Beaudoin      | Jonathan D.   | Vaudreuil-Dorion | QC    | J7V1A6 | 2019-05-30T00:00:00 |        | 7411         | Hiking             | 450-424-3642 |               | 
| Beaudoin      | Jonathan D.   | Vaudreuil-Dorion | QC    | J7V1A6 | 2019-05-30T00:00:00 |        | 7411         | Camping            | 450-424-3642 |               | 
| Beaulieu      | Nadia         | Rosemere         | QC    | J7A3N8 | 2019-03-04T00:00:00 |        | 7102         | Camping            | 514-621-7506 |               | 
| Beaulieu      | Nadia         | Rosemere         | QC    | J7A3N8 | 2019-03-04T00:00:00 |        | 7102         | Hiking             | 514-621-7506 |               | 
| Beaulieu-Paul | Jean Francois | Montreal         | QC    | H2V2S7 | 2019-01-17T00:00:00 |        | 7107         | Camping            | 514-994-9440 |               | 
```