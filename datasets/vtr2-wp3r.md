# Seattle Major Crimes Last 48 Hours

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-major-crimes-last-48-hours) |
| Metadata | [Link](https://data.seattle.gov/api/views/vtr2-wp3r) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vtr2-wp3r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vtr2-wp3r/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vtr2-wp3r |
| Name | Seattle Major Crimes Last 48 Hours |
| Category | Public Safety |
| Created | 2015-03-09T15:02:23Z |
| Publication Date | 2016-06-17T20:56:25Z |

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                              | Data Type | Render Type |
| ======== | ============== | ================================= | ================================= | ========= | =========== |
| Yes      | numeric metric | cosid                             | cosid                             | number    | number      |
| Yes      | series tag     | rms_cdw_id                        | rms_cdw_id                        | text      | text        |
| Yes      | series tag     | general_offense_number            | general_offense_number            | text      | text        |
| Yes      | series tag     | offense_code                      | offense_code                      | text      | text        |
| Yes      | numeric metric | offense_code_extension            | offense_code_extension            | number    | text        |
| Yes      | series tag     | offense_type                      | offense_type                      | text      | text        |
| Yes      | series tag     | summary_offense_code              | summary_offense_code              | text      | text        |
| Yes      | series tag     | summarized_offense_description    | summarized_offense_description    | text      | text        |
| Yes      | time           | date_reported                     | date_reported                     | date      | date        |
| No       |                | occurred_date_or_date_range_start | occurred_date_or_date_range_start | date      | date        |
| No       |                | occurred_date_range_end           | occurred_date_range_end           | date      | date        |
| Yes      | series tag     | hundred_block_location            | hundred_block_location            | text      | text        |
| Yes      | series tag     | district_sector                   | district_sector                   | text      | text        |
| Yes      | series tag     | zone_beat                         | zone_beat                         | text      | text        |
| Yes      | numeric metric | census_tract_2000                 | census_tract_2000                 | number    | text        |
| No       |                | longitude                         | longitude                         | number    | number      |
| No       |                | latitude                          | latitude                          | number    | number      |
| No       |                | relative_date                     | Relative_Date                     | date      | date        |
```

## Time Field

```ls
Value = date_reported
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = occurred_date_or_date_range_start,occurred_date_range_end,longitude,latitude,relative_date
```

## Data Commands

```ls
series e:vtr2-wp3r d:2016-03-28T21:03:00.000Z t:offense_code=1305 t:offense_type=ASSLT-AGG-WEAPON t:hundred_block_location="1 AV / YESLER WY" t:summarized_offense_description=ASSAULT t:zone_beat=K1 t:general_offense_number=2016107414 t:summary_offense_code=1300 t:district_sector=K t:rms_cdw_id=771393 m:census_tract_2000=9200.2007 m:cosid=95018 m:offense_code_extension=0

series e:vtr2-wp3r d:2016-03-28T17:04:00.000Z t:offense_code=2606 t:offense_type=FRAUD-CHECK t:hundred_block_location="102XX BLOCK OF LAKE CITY WY NE" t:summarized_offense_description=FRAUD t:zone_beat=L2 t:general_offense_number=2016107189 t:summary_offense_code=2600 t:district_sector=L t:rms_cdw_id=771299 m:census_tract_2000=1100.2015 m:cosid=94928 m:offense_code_extension=1

series e:vtr2-wp3r d:2016-03-28T09:42:00.000Z t:offense_code=1316 t:offense_type=THREATS-OTHER t:hundred_block_location="3XX BLOCK OF PONTIUS AV N" t:summarized_offense_description=THREATS t:zone_beat=D3 t:general_offense_number=2016106667 t:summary_offense_code=1300 t:district_sector=D t:rms_cdw_id=771394 m:census_tract_2000=7300.1027 m:cosid=95019 m:offense_code_extension=4
```

## Meta Commands

```ls
metric m:cosid p:integer l:cosid t:dataTypeName=number

metric m:offense_code_extension p:integer l:offense_code_extension t:dataTypeName=number

metric m:census_tract_2000 p:double l:census_tract_2000 t:dataTypeName=number

entity e:vtr2-wp3r l:"Seattle Major Crimes Last 48 Hours" t:url=https://data.seattle.gov/api/views/vtr2-wp3r

property e:vtr2-wp3r t:meta.view v:id=vtr2-wp3r v:category="Public Safety" v:averageRating=0 v:name="Seattle Major Crimes Last 48 Hours"

property e:vtr2-wp3r t:meta.view.license v:name="Public Domain"

property e:vtr2-wp3r t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:vtr2-wp3r t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| cosid | rms_cdw_id | general_offense_number | offense_code | offense_code_extension | offense_type             | summary_offense_code | summarized_offense_description | date_reported | occurred_date_or_date_range_start | occurred_date_range_end | hundred_block_location         | district_sector | zone_beat | census_tract_2000 | longitude      | latitude     | relative_date | 
| ===== | ========== | ====================== | ============ | ====================== | ======================== | ==================== | ============================== | ============= | ================================= | ======================= | ============================== | =============== | ========= | ================= | ============== | ============ | ============= | 
| 95018 | 771393     | 2016107414             | 1305         | 0                      | ASSLT-AGG-WEAPON         | 1300                 | ASSAULT                        | 1459198980    | 1459198980                        |                         | 1 AV / YESLER WY               | K               | K1        | 9200.2007         | -122.334182739 | 47.601722717 | 1459141254    | 
| 94928 | 771299     | 2016107189             | 2606         | 1                      | FRAUD-CHECK              | 2600                 | FRAUD                          | 1459184640    | 1456790400                        | 1459166400              | 102XX BLOCK OF LAKE CITY WY NE | L               | L2        | 1100.2015         | -122.301612854 | 47.703125    | 1459141254    | 
| 95019 | 771394     | 2016106667             | 1316         | 4                      | THREATS-OTHER            | 1300                 | THREATS                        | 1459158120    | 1459158120                        |                         | 3XX BLOCK OF PONTIUS AV N      | D               | D3        | 7300.1027         | -122.331710815 | 47.621391296 | 1459141254    | 
| 93836 | 770202     | 2016107313             | 2404         | 1                      | VEH-THEFT-AUTO           | 2400                 | VEHICLE THEFT                  | 1459191540    | 1459080000                        | 1459188000              | 8XX BLOCK OF N 36 ST           | B               | B2        | 4900.2017         | -122.348930359 | 47.651199341 | 1459141254    | 
| 94826 | 771195     | 2016107662             | 1316         | 5                      | THREATS-WEAPON           | 1300                 | THREATS                        | 1459220820    | 1459220820                        |                         | 14XX BLOCK OF NW MARKET ST     | B               | B1        | 4700.3021         | -122.374900818 | 47.66866684  | 1459141254    | 
| 94517 | 770884     | 2016106901             | 2589         | 1                      | FORGERY-OTH              | 2500                 | FORGERY                        | 1459171740    | 1451405700                        | 1458831600              | 90XX BLOCK OF SEWARD PARK AV S | S               | S3        | 11800.6018        | -122.26449585  | 47.522407532 | 1459141254    | 
| 95015 | 771390     | 2016107121             | 2605         | 0                      | FRAUD-CREDIT CARD        | 2600                 | FRAUD                          | 1459185540    | 1458900000                        | 1459116000              | 26XX BLOCK OF NE 65 ST         | U               | U3        | 4301.2002         | -122.298995972 | 47.675777435 | 1459141254    | 
| 94927 | 771298     | 2016107235             | 1204         | 0                      | ROBBERY-STREET-GUN       | 1200                 | ROBBERY                        | 1459191240    | 1458909900                        |                         | 4 AV S / S WASHINGTON ST       | K               | K3        | 9200.1004         | -122.328964233 | 47.60087204  | 1459141254    | 
| 94819 | 771188     | 2016106993             | 2303         | 0                      | THEFT-SHOPLIFT           | 2300                 | SHOPLIFTING                    | 1459176000    | 1459175100                        |                         | 6XX BLOCK OF PINE ST           | M               | M2        | 8200.1002         | -122.334815979 | 47.612369537 | 1459141254    | 
| 95306 | 771795     | 2016107664             | 1206         | 0                      | ROBBERY-STREET-BODYFORCE | 1200                 | ROBBERY                        | 1459232520    | 1459221720                        |                         | E PIKE ST / BOYLSTON AV        | E               | E2        | 8400.1005         | -122.323402405 | 47.614067078 | 1459141254    | 
```