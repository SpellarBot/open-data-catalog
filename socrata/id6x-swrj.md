# Case-Specific Beneficial Use Determinations: Beginning 1988

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/case-specific-beneficial-use-determinations-beginning-1988) |
| Metadata | [Link](https://data.ny.gov/api/views/id6x-swrj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/id6x-swrj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/id6x-swrj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | id6x-swrj |
| Name | Case-Specific Beneficial Use Determinations: Beginning 1988 |
| Attribution | Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | solid waste, beneficial use, recycling, energy recovery |
| Created | 2015-04-20T19:48:53Z |
| Publication Date | 2016-03-04T17:32:31Z |

## Description

All case-specific beneficial use determinations (BUDs) granted by DEC?s Division of Materials Management since 1988.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | bud_number     | BUD Number     | text          | text          |
| Yes      | series tag  | bud_grantee    | BUD Grantee    | text          | text          |
| Yes      | series tag  | city           | City           | text          | text          |
| Yes      | series tag  | state          | State          | text          | text          |
| Yes      | series tag  | solid_waste    | Solid Waste    | text          | text          |
| Yes      | series tag  | beneficial_use | Beneficial Use | text          | text          |
| Yes      | series tag  | status         | Status         | text          | text          |
| Yes      | time        | effective_date | Effective Date | calendar_date | calendar_date |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:id6x-swrj d:1990-05-15T00:00:00.000Z t:bud_number=079-0-00 t:bud_grantee="AWT Capital" t:status=Inactive t:state=NY t:solid_waste=Plastic t:beneficial_use="Manufactured products" t:city=Unknown m:row_number.id6x-swrj=1

series e:id6x-swrj d:1994-04-11T00:00:00.000Z t:bud_number=227-0-00 t:bud_grantee="Generic BUD - Glass as Fill" t:status=Inactive t:state=NY t:solid_waste=Glass t:beneficial_use=Fill t:city=Unknown m:row_number.id6x-swrj=2

series e:id6x-swrj d:1991-11-29T00:00:00.000Z t:bud_number=159-0-00 t:bud_grantee="Generic BUD-RUMAC-Glassphalt" t:status="Generic Nature" t:state=NY t:solid_waste=Glass t:beneficial_use="Aggregate (Asphalt)" t:city=Statewide m:row_number.id6x-swrj=3
```

## Meta Commands

```ls
metric m:row_number.id6x-swrj p:long l:"Row Number"

entity e:id6x-swrj l:"Case-Specific Beneficial Use Determinations: Beginning 1988" t:attribution="Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/id6x-swrj

property e:id6x-swrj t:meta.view v:id=id6x-swrj v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/8821.html v:averageRating=0 v:name="Case-Specific Beneficial Use Determinations: Beginning 1988" v:attribution="Department of Environmental Conservation"

property e:id6x-swrj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:id6x-swrj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:id6x-swrj t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bud_number | bud_grantee                          | city      | state | solid_waste                 | beneficial_use               | status         | effective_date      | 
| ========== | ==================================== | ========= | ===== | =========================== | ============================ | ============== | =================== | 
| 079-0-00   | AWT Capital                          | Unknown   | NY    | Plastic                     | Manufactured products        | Inactive       | 1990-05-15T00:00:00 | 
| 227-0-00   | Generic BUD - Glass as Fill          | Unknown   | NY    | Glass                       | Fill                         | Inactive       | 1994-04-11T00:00:00 | 
| 159-0-00   | Generic BUD-RUMAC-Glassphalt         | Statewide | NY    | Glass                       | Aggregate (Asphalt)          | Generic Nature | 1991-11-29T00:00:00 | 
| 159-0-00   | Generic BUD-RUMAC-Glassphalt         | Statewide | NY    | Tire (Shreds)               | Aggregate (Asphalt)          | Generic Nature | 1991-11-29T00:00:00 | 
| 198-0-00   | Generic BUD - Wood Ash               | Statewide | NY    | Ash (Wood)                  | Fertilizer                   | Generic Nature | 1992-06-23T00:00:00 | 
| 203-0-00   | Generic BUD - PCS - Cold-mix asphalt | Unknown   | NY    | Petroleum Contaminated Soil | Aggregate (Asphalt-Cold Mix) | Generic Nature | 1992-06-09T00:00:00 | 
| 227-0-00   | Generic BUD - Glass as Fill          | Unknown   | NY    | Glass                       | Base (sub)                   | Inactive       | 1994-04-11T00:00:00 | 
| 254-0-00   | Generic BUD - Recycled Concrete      | Statewide | NY    | C&D (Concrete/Masonry)      | Aggregate                    | Generic Nature | 1992-10-28T00:00:00 | 
| 259-0-00   | Generic BUD - Roofing Gravel         | Statewide | NY    | C&D (Roofing Gravel)        | Fill                         | Generic Nature | 1992-11-24T00:00:00 | 
| 259-0-00   | Generic BUD - Roofing Gravel         | Statewide | NY    | C&D (Roofing Gravel)        | Surfacing (Road, Driveway)   | Generic Nature | 1992-11-24T00:00:00 | 
```