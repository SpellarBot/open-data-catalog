# Housing and Urban Development (HUD) Grants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/housing-and-urban-development-hud-grants) |
| Metadata | [Link](https://data.nola.gov/api/views/rtej-a36y) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/rtej-a36y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/rtej-a36y/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | rtej-a36y |
| Name | Housing and Urban Development (HUD) Grants |
| Attribution | The Office of Community Development |
| Category | Housing, Land Use, and Blight |
| Tags | housing, development, community |
| Created | 2017-01-10T22:30:53Z |
| Publication Date | 2017-01-10T22:33:21Z |

## Description

The Office of Community Development manages federal grant money given to New Orleans by taking, selecting, and distributing funds to local service providers. Data below represents funding from the following HUD grants: HOME Investment Partnership Program (HOME) - Owner-occupied Rehabilitation Program, Rental Rehabilitation Program and the CDBG Disaster Recovery Grant - Homebuyer Soft Second Mortgage Program.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | ocd_program | OCD Program | text      | text        |
| Yes      | series tag  | partnership | Partnership | text      | text        |
| Yes      | series tag  | status      | Status      | text      | text        |
| No       |             | address     | Address     | text      | text        |
| No       |             | latitude    | Latitude    | number    | number      |
| No       |             | longitude   | Longitude   | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:rtej-a36y d:2017-01-10T22:35:44.000Z t:ocd_program="Owner Occupied Rental" t:status=Complete t:partnership="PRC Rebuilding Together Award" m:row_number.rtej-a36y=1

series e:rtej-a36y d:2017-01-10T22:35:44.000Z t:ocd_program=Rental t:status=Complete t:partnership="Gert Town Ent Econ Redev" m:row_number.rtej-a36y=2

series e:rtej-a36y d:2017-01-10T22:35:44.000Z t:ocd_program=Homebuyer t:status=Active t:partnership="Hoffman Triangle" m:row_number.rtej-a36y=3
```

## Meta Commands

```ls
metric m:row_number.rtej-a36y p:long l:"Row Number"

entity e:rtej-a36y l:"Housing and Urban Development (HUD) Grants" t:attribution="The Office of Community Development" t:url=https://data.nola.gov/api/views/rtej-a36y

property e:rtej-a36y t:meta.view v:id=rtej-a36y v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="Housing and Urban Development (HUD) Grants" v:attribution="The Office of Community Development"

property e:rtej-a36y t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rtej-a36y t:meta.view.owner v:id=ubux-5uyn v:profileImageUrlMedium=/api/users/ubux-5uyn/profile_images/THUMB v:profileImageUrlLarge=/api/users/ubux-5uyn/profile_images/LARGE v:screenName=Cameron v:profileImageUrlSmall=/api/users/ubux-5uyn/profile_images/TINY v:lastNotificationSeenAt=1492115091 v:displayName=Cameron

property e:rtej-a36y t:meta.view.tableauthor v:id=ubux-5uyn v:profileImageUrlMedium=/api/users/ubux-5uyn/profile_images/THUMB v:profileImageUrlLarge=/api/users/ubux-5uyn/profile_images/LARGE v:screenName=Cameron v:profileImageUrlSmall=/api/users/ubux-5uyn/profile_images/TINY v:roleName=publisher v:lastNotificationSeenAt=1492115091 v:displayName=Cameron

property e:rtej-a36y t:meta.view.metadata.custom_fields.common_core v:Contact_Email=camacphee@nola.gov
```

## Top Records

```ls
| :updated_at | ocd_program           | partnership                   | status   | address             | latitude         | longitude         | 
| =========== | ===================== | ============================= | ======== | =================== | ================ | ================= | 
| 1484087744  | Owner Occupied Rental | PRC Rebuilding Together Award | Complete | 3915 Marais St      | 29.9667825472747 | -90.035696659621  | 
| 1484087744  | Rental                | Gert Town Ent Econ Redev      | Complete | 3235 Fern St        | 29.9608062260907 | -90.1120890003018 | 
| 1484087744  | Homebuyer             | Hoffman Triangle              | Active   | 3229 Washington Ave | 29.9448305615665 | -90.0961419026806 | 
| 1484087744  | Rental                | GNORAC 1st Emanuel Homes      | Active   | 2851 Baronne St     | 29.9321219844333 | -90.088403511812  | 
| 1484087744  | Owner Occupied Rental | St Bernard Project            | Active   | 4424 D'hemecourt St | 29.9728456874423 | -90.1085636468018 | 
| 1484087744  | Owner Occupied Rental | St Bernard Project            | Complete | 4805 Stemway Dr     | 30.0183024962974 | -90.0184465910922 | 
| 1484087744  | Owner Occupied Rental | St Bernard Project            | Active   | 8 Shepard Ct        | 29.9354935328895 | -90.0338034331903 | 
| 1484087744  | Owner Occupied Rental | St Bernard Project            | Complete | 2308 Touro St       | 29.9808336860037 | -90.060540785791  | 
| 1484087744  | Homebuyer             | Jericho Rd Homebuyer          | Active   | 2037 Seventh St     | 29.9337407310658 | -90.090984965888  | 
| 1484087744  | Owner Occupied Rental | St Bernard Project            | Active   | 1525 St Roch Ave    | 29.9735213996134 | -90.0521090061885 | 
```