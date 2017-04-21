# SPDES Multi-Sector General Permit (MSGP) Permitted Facilities: Beginning 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spdes-multi-sector-general-permit-msgp-permitted-facilities-beginning-2012) |
| Metadata | [Link](https://data.ny.gov/api/views/7hs3-2njf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7hs3-2njf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7hs3-2njf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7hs3-2njf |
| Name | SPDES Multi-Sector General Permit (MSGP) Permitted Facilities: Beginning 2012 |
| Attribution | New York State Department of Environmental Conservation |
| Category | Energy & Environment |
| Tags | msgp, permitted facilities, spdes |
| Created | 2014-11-04T17:15:54Z |
| Publication Date | 2016-03-29T17:31:14Z |

## Description

The SPDES Multi-Sector General Permit (MSGP), which is administered by the Department of Environmental Conservation (the Department), regulates stormwater discharges associated with industrial activity from a point source.  The MSGP covers thirty one different industrial sectors which include activities such as mining, land transportation, and scrap recycling.  The dataset displays information on facilities that have active MSGP coverage in New York State.   Information included in the data set include the facility?s name, address, contact information, industrial sector(s), discharging waterbody, and location of the facility?s Stormwater Pollution Prevention Plan.  For more information, please go to http://www.dec.ny.gov/chemical/62803.html.

## Columns

```ls
| Included | Schema Type | Field Name    | Name                        | Data Type     | Render Type   |
| ======== | =========== | ============= | =========================== | ============= | ============= |
| Yes      | series tag  | npdes_id      | NPDES ID                    | text          | text          |
| Yes      | series tag  | facility      | Facility                    | text          | text          |
| Yes      | series tag  | location      | Location                    | text          | text          |
| Yes      | series tag  | city          | City                        | text          | text          |
| Yes      | series tag  | state         | State                       | text          | text          |
| Yes      | series tag  | zip           | Zip                         | text          | text          |
| Yes      | series tag  | first_name    | Facility Contact First Name | text          | text          |
| Yes      | series tag  | last_name     | Facility Contact Last Name  | text          | text          |
| Yes      | series tag  | waterbody     | Waterbody                   | text          | text          |
| Yes      | series tag  | sector        | Sector                      | text          | text          |
| No       |             | swppp_address | SWPPP Address               | text          | text          |
| Yes      | series tag  | waivers       | Waivers                     | text          | text          |
| No       |             | latitude      | Latitude                    | number        | number        |
| No       |             | longitude     | Longitude                   | number        | number        |
| Yes      | time        | update        | Update                      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = update
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = swppp_address,latitude,longitude
```

## Data Commands

```ls
series e:7hs3-2njf d:2016-03-03T00:00:00.000Z t:sector=M t:first_name=FRANK t:zip=11558 t:npdes_id=NYR00F668 t:facility="LIBERTY METAL RECYCLING LLC" t:location="4276 INDUSTRIAL PL" t:waterbody="BARNUM CREEK" t:last_name=AGNELLO t:waivers="None Claimed" t:state=NY t:city="ISLAND PARK" m:row_number.7hs3-2njf=1

series e:7hs3-2njf d:2016-03-03T00:00:00.000Z t:sector=M t:first_name=MICHAEL t:zip=11757 t:npdes_id=NYR00F658 t:facility="INTERNATIONAL TRANSPORTATION & EQUIPMENT" t:location="1A BAHAMA ST" t:waterbody="GREAT SOUTH BAY" t:last_name=BOLZOMI t:waivers="None Claimed" t:state=NY t:city=LINDENHURST m:row_number.7hs3-2njf=2

series e:7hs3-2njf d:2016-03-03T00:00:00.000Z t:sector=M t:first_name=NATAN t:zip=11729 t:npdes_id=NYR00F657 t:facility="DPA AUTO PARTS" t:location="999 LONG ISLAND AVE" t:waterbody="GREAT SOUTH BAY WEST" t:last_name=SERI t:waivers="None Claimed" t:state=NY t:city="DEER PARK" m:row_number.7hs3-2njf=3
```

## Meta Commands

```ls
metric m:row_number.7hs3-2njf p:long l:"Row Number"

entity e:7hs3-2njf l:"SPDES Multi-Sector General Permit (MSGP) Permitted Facilities: Beginning 2012" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/7hs3-2njf

property e:7hs3-2njf t:meta.view v:id=7hs3-2njf v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/chemical/9009.html v:averageRating=0 v:name="SPDES Multi-Sector General Permit (MSGP) Permitted Facilities: Beginning 2012" v:attribution="New York State Department of Environmental Conservation"

property e:7hs3-2njf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7hs3-2njf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7hs3-2njf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| npdes_id  | facility                                 | location             | city                        | state | zip        | first_name | last_name | waterbody                                 | sector | swppp_address                                              | waivers      | latitude | longitude | update              | 
| ========= | ======================================== | ==================== | =========================== | ===== | ========== | ========== | ========= | ========================================= | ====== | ========================================================== | ============ | ======== | ========= | =================== | 
| NYR00F668 | LIBERTY METAL RECYCLING LLC              | 4276 INDUSTRIAL PL   | ISLAND PARK                 | NY    | 11558      | FRANK      | AGNELLO   | BARNUM CREEK                              | M      | 4276 INDUSTRIAL PL ISLAND PARK, NY 11558                   | None Claimed | 40.362   | -73.39    | 2016-03-03T00:00:00 | 
| NYR00F658 | INTERNATIONAL TRANSPORTATION & EQUIPMENT | 1A BAHAMA ST         | LINDENHURST                 | NY    | 11757      | MICHAEL    | BOLZOMI   | GREAT SOUTH BAY                           | M      | 1A BAHAMA ST LINDENHURST, NY 11757                         | None Claimed | 40.415   | -73.201   | 2016-03-03T00:00:00 | 
| NYR00F657 | DPA AUTO PARTS                           | 999 LONG ISLAND AVE  | DEER PARK                   | NY    | 11729      | NATAN      | SERI      | GREAT SOUTH BAY WEST                      | M      | 999 LONG ISLAND AVE DEER PARK, NY 11729                    | None Claimed | 40.46    | -73.185   | 2016-03-03T00:00:00 | 
| NYR00F709 | PRINCESS BAY BOATMEN'S ASSOCIATION       | 175 JOHNSTON TERRACE | STATEN ISLAND (SUBDIVISION) | NY    | 10308      | ED         | HUMPHRIES | LEMON CREEK                               | Q      | 175 JOHNSTON TERRACE STATEN ISLAND (SUBDIVISION), NY 10308 | None Claimed | 40.514   | -74.199   | 2016-03-03T00:00:00 | 
| NYR00A509 | TOTTENVILLE MARINA                       | 201 ELLIS ST         | STATEN ISLAND               | NY    | 10307-1128 | JOHN       | GARNER    | ARTHUR KILL                               | Q      | 201 ELLIS ST STATEN ISLAND, NY 10307-1128                  | None Claimed | 40.515   | -74.247   | 2016-03-03T00:00:00 | 
| NYR00F414 | ATLANTIC MARINA LLC                      | 225 ELLIS ST         | STATEN ISLAND               | NY    | 10307-1127 | GREGORY    | FRESCA    | ARTHUR KILL                               | Q      | 225 ELLIS ST STATEN ISLAND, NY 10307-1127                  | None Claimed | 40.515   | -74.248   | 2016-03-03T00:00:00 | 
| NYR00E644 | GARPO MARINE SERVICES INC                | 113-135 ELLIS ST     | STATEN ISLAND               | NY    | 10307      | ELEANOR    | ROMA      | ARTHUR KILL                               | R      | 113-135 ELLIS ST STATEN ISLAND, NY 10307                   | None Claimed | 40.517   | -74.246   | 2016-03-03T00:00:00 | 
| NYR00F259 | HENRY'S SERVICE CENTER                   | 4414 ARTHUR KILL RD  | STATEN ISLAND               | NY    | 10309      | ENRICO     | ARENA     | ARTHUR KILL                               | M      | 4414 ARTHUR KILL RD STATEN ISLAND, NY 10309                | None Claimed | 40.534   | -74.235   | 2016-03-03T00:00:00 | 
| NYR00E301 | NICHOLS GREAT KILLS PARK MARINA          | 3270 HYLAN BLVD      | STATEN ISLAND               | NY    | 10306      | EDWARD     | TOMANEK   | GREAT KILLS HARBOR                        | Q      | 3270 HYLAN BLVD STATEN ISLAND, NY 10306                    | None Claimed | 40.537   | -74.131   | 2016-03-03T00:00:00 | 
| NYR00F252 | EASTERN CONCRETE MATERIALS SHARROTTS RD  | 709 SHARROTTS RD     | STATEN ISLAND               | NY    | 10309      | DREW       | HOPE      | WETLANDS UNNAMED TRIBUTARY TO ARTHUR KILL | E      | 709 SHARROTTS RD STATEN ISLAND, NY 10309                   | None Claimed | 40.539   | -74.241   | 2016-03-03T00:00:00 | 
```