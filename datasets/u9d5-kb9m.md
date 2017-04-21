# Annual 2015 Water Quality Index Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/annual-2015-water-quality-index-data) |
| Metadata | [Link](https://data.wa.gov/api/views/u9d5-kb9m) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/u9d5-kb9m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/u9d5-kb9m/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | u9d5-kb9m |
| Name | Annual 2015 Water Quality Index Data |
| Attribution | WA Department of Ecology River and Stream Monitoring Program |
| Category | Natural Resources & Environment |
| Tags | wa ecology river and stream monitoring/wqi |
| Created | 2016-10-20T19:09:01Z |
| Publication Date | 2016-10-20T19:12:57Z |

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       |                | id              | ID              | text      | number      |
| Yes      | series tag     | station         | STATION         | text      | text        |
| Yes      | series tag     | station_name    | STATION NAME    | text      | text        |
| Yes      | numeric metric | overallwqi_2015 | OVERALLWQI 2015 | number    | number      |
| Yes      | numeric metric | wqifc           | WQIFC           | number    | number      |
| Yes      | numeric metric | wqioxy          | WQIOXY          | number    | number      |
| Yes      | numeric metric | wqiph           | WQIPH           | number    | number      |
| Yes      | numeric metric | wqitss          | WQITSS          | number    | number      |
| Yes      | numeric metric | wqitemp         | WQITEMP         | number    | number      |
| Yes      | numeric metric | wqitpn          | WQITPN          | number    | number      |
| Yes      | numeric metric | wqitp           | WQITP           | number    | number      |
| Yes      | numeric metric | wqiturb         | WQITURB         | number    | number      |
| Yes      | series tag     | core            | CORE            | text      | text        |
| Yes      | numeric metric | cat             | CAT             | number    | number      |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:u9d5-kb9m d:2015-01-01T00:00:00.000Z t:station_name="Nooksack R @ Brennan" t:station=01A050 t:core=C m:cat=3 m:wqitss=39.67 m:wqitemp=44.77 m:wqiturb=33.94 m:wqitp=32.85 m:overallwqi_2015=44.67 m:wqitpn=72.93 m:wqiph=90.29 m:wqioxy=60.01 m:wqifc=79.46

series e:u9d5-kb9m d:2015-01-01T00:00:00.000Z t:station_name="Nooksack R @ No Cedarville" t:station=01A120 t:core=C m:cat=3 m:wqitss=28.79 m:wqitemp=68.3 m:wqiturb=20.53 m:wqitp=1.51 m:overallwqi_2015=59.64 m:wqitpn=88.71 m:wqiph=93.88 m:wqioxy=84.06 m:wqifc=91.92

series e:u9d5-kb9m d:2015-01-01T00:00:00.000Z t:station_name="Skagit R nr Mount Vernon" t:station=03A060 t:core=C m:cat=2 m:wqitss=42.09 m:wqitemp=78.26 m:wqiturb=54.74 m:wqitp=45.44 m:overallwqi_2015=68.13 m:wqitpn=97.59 m:wqiph=94.86 m:wqioxy=83.09 m:wqifc=91.93
```

## Meta Commands

```ls
metric m:overallwqi_2015 p:float l:"OVERALLWQI 2015" t:dataTypeName=number

metric m:wqifc p:double l:WQIFC t:dataTypeName=number

metric m:wqioxy p:float l:WQIOXY t:dataTypeName=number

metric m:wqiph p:float l:WQIPH t:dataTypeName=number

metric m:wqitss p:double l:WQITSS t:dataTypeName=number

metric m:wqitemp p:double l:WQITEMP t:dataTypeName=number

metric m:wqitpn p:double l:WQITPN t:dataTypeName=number

metric m:wqitp p:double l:WQITP t:dataTypeName=number

metric m:wqiturb p:double l:WQITURB t:dataTypeName=number

metric m:cat p:integer l:CAT t:dataTypeName=number

entity e:u9d5-kb9m l:"Annual 2015 Water Quality Index Data" t:attribution="WA Department of Ecology River and Stream Monitoring Program" t:url=https://data.wa.gov/api/views/u9d5-kb9m

property e:u9d5-kb9m t:meta.view v:id=u9d5-kb9m v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov/programs/eap/fw_riv/index.html v:averageRating=0 v:name="Annual 2015 Water Quality Index Data" v:attribution="WA Department of Ecology River and Stream Monitoring Program"

property e:u9d5-kb9m t:meta.view.owner v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:u9d5-kb9m t:meta.view.tableauthor v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```

## Top Records

```ls
| id | station | station_name                        | overallwqi_2015 | wqifc | wqioxy | wqiph | wqitss | wqitemp | wqitpn | wqitp | wqiturb | core | cat | 
| == | ======= | =================================== | =============== | ===== | ====== | ===== | ====== | ======= | ====== | ===== | ======= | ==== | === | 
| 1  | 01A050  | Nooksack R @ Brennan                | 44.67           | 79.46 | 60.01  | 90.29 | 39.67  | 44.77   | 72.93  | 32.85 | 33.94   | C    | 3   | 
| 2  | 01A120  | Nooksack R @ No Cedarville          | 59.64           | 91.92 | 84.06  | 93.88 | 28.79  | 68.3    | 88.71  | 1.51  | 20.53   | C    | 3   | 
| 3  | 03A060  | Skagit R nr Mount Vernon            | 68.13           | 91.93 | 83.09  | 94.86 | 42.09  | 78.26   | 97.59  | 45.44 | 54.74   | C    | 2   | 
| 4  | 03B050  | Samish R nr Burlington              | 67.66           | 80.12 | 77.87  | 93.81 | 77.97  | 80.34   | 19.79  | 71.07 | 75.36   | C    | 3   | 
| 5  | 04A100  | Skagit R @ Marblemount              | 70.12           | 97.62 | 87.69  | 94.86 | 45.64  | 84.71   | 83.75  | 70.48 | 47.07   | C    | 2   | 
| 7  | 05A070  | Stillaguamish R nr Silvana          | 63.02           | 86.53 | 85.85  | 95.68 | 46.63  | 64.01   | 81.39  | 43.59 | 41.14   | C    | 3   | 
| 8  | 05A090  | SF Stillaguamish R @ Arlington      | 65.86           | 87.17 | 68.25  | 95.03 | 68.64  | 47.53   | 84.41  | 70.03 | 59.91   | C    | 3   | 
| 9  | 05A110  | SF Stillaguamish R nr Granite Falls | 66.95           | 84.65 | 72.04  | 92.68 | 56.4   | 67.26   | 96.85  | 74.5  | 40.28   | C    | 3   | 
| 10 | 05B070  | NF Stillaguamish R @ Cicero         | 29.03           | 85.91 | 82.09  | 91.18 | 17.55  | 60.62   | 27.96  | 36.2  | 15.38   | C    | 4   | 
| 11 | 05B110  | NF Stillaguamish R nr Darrington    | 43.01           | 91.7  | 83.09  | 89.13 | 33.53  | 68.62   | 41.98  | 50.83 | 34.28   | C    | 3   | 
```