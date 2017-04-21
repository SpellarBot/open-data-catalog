# Parking Citations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/parking-citations) |
| Metadata | [Link](https://data.lacity.org/api/views/wjz9-h9np) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/wjz9-h9np/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/wjz9-h9np/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | wjz9-h9np |
| Name | Parking Citations |
| Category | A Well Run City |
| Created | 2016-07-20T21:05:56Z |
| Publication Date | 2016-12-19T21:41:33Z |

## Description

Parking citations with latitude / longitude (XY) in US Feet coordinates according to the NAD_1983_StatePlane_California_V_FIPS_0405_Feet projection.

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | ticket_number         | Ticket number         | text          | text          |
| Yes      | time           | issue_date            | Issue Date            | calendar_date | calendar_date |
| No       |                | issue_time            | Issue time            | number        | number        |
| Yes      | series tag     | meter_id              | Meter Id              | text          | text          |
| No       |                | marked_time           | Marked Time           | text          | text          |
| Yes      | series tag     | rp_state_plate        | RP State Plate        | text          | text          |
| No       |                | plate_expiry_date     | Plate Expiry Date     | text          | number        |
| Yes      | series tag     | vin                   | VIN                   | text          | text          |
| Yes      | series tag     | make                  | Make                  | text          | text          |
| Yes      | series tag     | body_style            | Body Style            | text          | text          |
| Yes      | series tag     | color                 | Color                 | text          | text          |
| Yes      | series tag     | location              | Location              | text          | text          |
| Yes      | series tag     | route                 | Route                 | text          | text          |
| Yes      | series tag     | agency                | Agency                | text          | number        |
| Yes      | series tag     | violation_code        | Violation code        | text          | text          |
| Yes      | series tag     | violation_description | Violation Description | text          | text          |
| Yes      | numeric metric | fine_amount           | Fine amount           | number        | number        |
| Yes      | numeric metric | latitude              | Latitude              | number        | number        |
| Yes      | numeric metric | longitude             | Longitude             | number        | number        |
```

## Time Field

```ls
Value = issue_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = issue_time,marked_time,plate_expiry_date
```

## Data Commands

```ls
series e:wjz9-h9np d:2015-12-30T00:00:00.000Z t:violation_code=80.56E4+ t:color=GN t:location="3069 SAN MARINO ST" t:route=00403 t:agency=54 t:body_style=PA t:violation_description="RED ZONE" t:rp_state_plate=CA t:make=OLDS t:ticket_number=4272349605 m:fine_amount=93 m:longitude=1842349.7 m:latitude=6471840.7

series e:wjz9-h9np d:2015-12-30T00:00:00.000Z t:violation_code=80.56E1 t:color=WT t:location="2936 8TH ST W" t:route=00403 t:agency=54 t:body_style=PA t:violation_description="WHITE ZONE" t:rp_state_plate=CA t:make=HOND t:ticket_number=4272349616 m:fine_amount=58 m:longitude=1843512 m:latitude=6473823.2

series e:wjz9-h9np d:2015-12-30T00:00:00.000Z t:violation_code=5204A- t:color=SL t:location="301 LAUREL AV N" t:route=00401 t:agency=54 t:body_style=PA t:violation_description="DISPLAY OF TABS" t:rp_state_plate=CA t:make=TOYT t:ticket_number=4272821512 m:fine_amount=25 m:longitude=1850273.2 m:latitude=6451207.5
```

## Meta Commands

```ls
metric m:fine_amount p:integer l:"Fine amount" t:dataTypeName=number

metric m:latitude p:double l:Latitude t:dataTypeName=number

metric m:longitude p:double l:Longitude t:dataTypeName=number

entity e:wjz9-h9np l:"Parking Citations" t:url=https://data.lacity.org/api/views/wjz9-h9np

property e:wjz9-h9np t:meta.view v:id=wjz9-h9np v:category="A Well Run City" v:averageRating=0 v:name="Parking Citations"

property e:wjz9-h9np t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:wjz9-h9np t:meta.view.owner v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:displayName=ChelseaU

property e:wjz9-h9np t:meta.view.tableauthor v:id=95pg-i79k v:profileImageUrlMedium=/api/users/95pg-i79k/profile_images/THUMB v:profileImageUrlLarge=/api/users/95pg-i79k/profile_images/LARGE v:screenName=ChelseaU v:profileImageUrlSmall=/api/users/95pg-i79k/profile_images/TINY v:roleName=administrator v:displayName=ChelseaU
```

## Top Records

```ls
| ticket_number | issue_date          | issue_time | meter_id | marked_time | rp_state_plate | plate_expiry_date | vin | make | body_style | color | location           | route | agency | violation_code | violation_description | fine_amount | latitude  | longitude | 
| ============= | =================== | ========== | ======== | =========== | ============== | ================= | === | ==== | ========== | ===== | ================== | ===== | ====== | ============== | ===================== | =========== | ========= | ========= | 
| 4272349605    | 2015-12-30T00:00:00 | 2201       |          |             | CA             | 201605            |     | OLDS | PA         | GN    | 3069 SAN MARINO ST | 00403 | 54     | 80.56E4+       | RED ZONE              | 93          | 6471840.7 | 1842349.7 | 
| 4272349616    | 2015-12-30T00:00:00 | 2205       |          |             | CA             | 201508            |     | HOND | PA         | WT    | 2936 8TH ST W      | 00403 | 54     | 80.56E1        | WHITE ZONE            | 58          | 6473823.2 | 1843512   | 
| 4272821512    | 2015-12-30T00:00:00 | 1725       |          |             | CA             | 10                |     | TOYT | PA         | SL    | 301 LAUREL AV N    | 00401 | 54     | 5204A-         | DISPLAY OF TABS       | 25          | 6451207.5 | 1850273.2 | 
| 4272821523    | 2015-12-30T00:00:00 | 1738       | WF74     |             | CA             | 2                 |     | RROV | PA         | BK    | 8321 3RD ST W      | 00401 | 54     | 88.13B+        | METER EXP.            | 63          | 6449387.2 | 1849063.5 | 
| 4272821534    | 2015-12-30T00:00:00 | 1807       | 13       |             | CA             | 1                 |     | FORD | PA         | GN    | 121 CROFT AVE      | 00401 | 54     | 80.58L         | PREFERENTIAL PARKING  | 68          | 6448347.2 | 1849662.2 | 
| 4272889353    | 2015-12-30T00:00:00 | 514        |          |             | CA             | 201605            |     | DODG | PA         | GY    | 4939 ECHO ST       | 00611 | 56     | 80.69BS        | NO PARK/STREET CLEAN  | 73          | 99999     | 99999     | 
| 4274301964    | 2016-01-04T00:00:00 | 1205       |          |             | TX             |                   |     | OTHR | TR         | WT    | 2650 12TH ST E     | 6T8   | 56     | 80.69B         | NO PARKING            | 73          | 6494776   | 1830622.8 | 
| 1112509506    | 2015-12-21T00:00:00 | 1255       |          |             | CA             |                   |     | CIMC | TL         | BL    | PENNINGTON/I ST    | 1A27  | 4      | 000            | 80691a                |             | 99999     | 99999     | 
| 1112509510    | 2015-12-21T00:00:00 | 1305       |          |             | CA             |                   |     | CIMC | TL         | BL    | PENNINGTON/I ST    | 1A27  | 4      | 000            | 80691a                |             | 99999     | 99999     | 
| 1112509926    | 2015-12-21T00:00:00 | 1340       |          |             | TN             |                   |     | HYTR | TL         | BK    | CANNERY ST/WAY ST  | L59   | 3      | 000            | 80691a                |             | 99999     | 99999     | 
```