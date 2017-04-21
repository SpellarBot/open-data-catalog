# Zoning Reference Table

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/zoning-reference-table) |
| Metadata | [Link](https://data.lacity.org/api/views/ikdx-vgub) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/ikdx-vgub/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/ikdx-vgub/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | ikdx-vgub |
| Name | Zoning Reference Table |
| Attribution | City of Los Angeles Department of City Planning |
| Category | A Well Run City |
| Tags | zoning |
| Created | 2013-12-03T15:04:22Z |
| Publication Date | 2015-12-04T20:33:47Z |

## Description

Reference table to converting zoning nomenclature in ZONING (GIS Data) to zone.

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type | Render Type |
| ======== | ============== | ============ | ============ | ========= | =========== |
| No       | time           | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag     | zone_cmplt   | ZONE_CMPLT   | text      | text        |
| Yes      | series tag     | zone_class   | ZONE_CLASS   | text      | text        |
| Yes      | series tag     | zone_code    | ZONE_CODE    | text      | number      |
| Yes      | numeric metric | zc1          | ZC1          | number    | number      |
| Yes      | numeric metric | zc2          | ZC2          | number    | number      |
| Yes      | numeric metric | zc3          | ZC3          | number    | number      |
| Yes      | numeric metric | zc4          | ZC4          | number    | number      |
| Yes      | numeric metric | max_hgt_stry | MAX_HGT_STRY | number    | number      |
| Yes      | numeric metric | max_hgt_ft   | MAX_HGT_FT   | number    | number      |
| Yes      | numeric metric | hd1          | HD1          | number    | number      |
| Yes      | numeric metric | hd2          | HD2          | number    | number      |
| Yes      | numeric metric | hd3          | HD3          | number    | number      |
| Yes      | numeric metric | hd4          | HD4          | number    | number      |
| Yes      | numeric metric | sud1         | SUD1         | number    | number      |
| Yes      | numeric metric | sud2         | SUD2         | number    | number      |
| Yes      | numeric metric | sud3         | SUD3         | number    | number      |
| Yes      | numeric metric | sud4         | SUD4         | number    | number      |
| Yes      | numeric metric | sud5         | SUD5         | number    | number      |
| Yes      | numeric metric | sud6         | SUD6         | number    | number      |
| Yes      | numeric metric | sud7         | SUD7         | number    | number      |
| Yes      | numeric metric | sud8         | SUD8         | number    | number      |
| Yes      | numeric metric | sud9         | SUD9         | number    | number      |
| Yes      | numeric metric | sud10        | SUD10        | number    | number      |
| Yes      | numeric metric | sud11        | SUD11        | number    | number      |
| Yes      | numeric metric | hpoz         | HPOZ         | number    | number      |
| Yes      | numeric metric | fd2          | FD2          | number    | number      |
| Yes      | numeric metric | sud12        | SUD12        | number    | number      |
| Yes      | numeric metric | sud13        | SUD13        | number    | number      |
| Yes      | numeric metric | sud14        | SUD14        | number    | number      |
| Yes      | numeric metric | sud15        | SUD15        | number    | number      |
| Yes      | numeric metric | sud16        | SUD16        | number    | number      |
| Yes      | numeric metric | sud17        | SUD17        | number    | number      |
| Yes      | numeric metric | sud18        | SUD18        | number    | number      |
| Yes      | numeric metric | sud19        | SUD19        | number    | number      |
| Yes      | numeric metric | sud20        | SUD20        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ikdx-vgub d:2013-12-03T07:04:28.000Z t:zone_class=PF t:zone_cmplt=PF-O t:zone_code=801 m:max_hgt_ft=0 m:fd2=0 m:max_hgt_stry=0 m:sud1=1 m:sud6=0 m:sud7=0 m:sud8=0 m:sud9=0 m:sud2=0 m:sud3=0 m:sud4=0 m:sud5=0 m:hd2=0 m:hd3=0 m:hd1=0 m:sud19=0 m:sud17=0 m:sud18=0 m:sud15=0 m:sud16=0 m:sud13=0 m:sud14=0 m:sud11=0 m:sud12=0 m:hd4=0 m:sud10=0 m:hpoz=0 m:zc3=0 m:zc4=0 m:zc1=0 m:zc2=0 m:sud20=0

series e:ikdx-vgub d:2013-12-03T07:04:28.000Z t:zone_class=C2 t:zone_cmplt=[Q]C2-1VL-SN t:zone_code=606 m:max_hgt_ft=0 m:fd2=1 m:max_hgt_stry=0 m:sud1=0 m:sud6=0 m:sud7=0 m:sud8=0 m:sud9=0 m:sud2=0 m:sud3=0 m:sud4=0 m:sud5=0 m:hd2=2 m:hd3=0 m:hd1=1 m:sud19=0 m:sud17=0 m:sud18=0 m:sud15=0 m:sud16=0 m:sud13=0 m:sud14=0 m:sud11=1 m:sud12=0 m:hd4=0 m:sud10=0 m:hpoz=0 m:zc3=0 m:zc4=0 m:zc1=0 m:zc2=3 m:sud20=0

series e:ikdx-vgub d:2013-12-03T07:04:28.000Z t:zone_class=PF t:zone_cmplt=PF-1-O t:zone_code=801 m:max_hgt_ft=0 m:fd2=0 m:max_hgt_stry=0 m:sud1=1 m:sud6=0 m:sud7=0 m:sud8=0 m:sud9=0 m:sud2=0 m:sud3=0 m:sud4=0 m:sud5=0 m:hd2=0 m:hd3=0 m:hd1=1 m:sud19=0 m:sud17=0 m:sud18=0 m:sud15=0 m:sud16=0 m:sud13=0 m:sud14=0 m:sud11=0 m:sud12=0 m:hd4=0 m:sud10=0 m:hpoz=0 m:zc3=0 m:zc4=0 m:zc1=0 m:zc2=0 m:sud20=0
```

## Meta Commands

```ls
metric m:zc1 p:integer l:ZC1 t:dataTypeName=number

metric m:zc2 p:integer l:ZC2 t:dataTypeName=number

metric m:zc3 p:integer l:ZC3 t:dataTypeName=number

metric m:zc4 p:integer l:ZC4 t:dataTypeName=number

metric m:max_hgt_stry p:integer l:MAX_HGT_STRY t:dataTypeName=number

metric m:max_hgt_ft p:integer l:MAX_HGT_FT t:dataTypeName=number

metric m:hd1 p:integer l:HD1 t:dataTypeName=number

metric m:hd2 p:integer l:HD2 t:dataTypeName=number

metric m:hd3 p:integer l:HD3 t:dataTypeName=number

metric m:hd4 p:integer l:HD4 t:dataTypeName=number

metric m:sud1 p:integer l:SUD1 t:dataTypeName=number

metric m:sud2 p:integer l:SUD2 t:dataTypeName=number

metric m:sud3 p:integer l:SUD3 t:dataTypeName=number

metric m:sud4 p:integer l:SUD4 t:dataTypeName=number

metric m:sud5 p:integer l:SUD5 t:dataTypeName=number

metric m:sud6 p:integer l:SUD6 t:dataTypeName=number

metric m:sud7 p:integer l:SUD7 t:dataTypeName=number

metric m:sud8 p:integer l:SUD8 t:dataTypeName=number

metric m:sud9 p:integer l:SUD9 t:dataTypeName=number

metric m:sud10 p:integer l:SUD10 t:dataTypeName=number

metric m:sud11 p:integer l:SUD11 t:dataTypeName=number

metric m:hpoz p:integer l:HPOZ t:dataTypeName=number

metric m:fd2 p:integer l:FD2 t:dataTypeName=number

metric m:sud12 p:integer l:SUD12 t:dataTypeName=number

metric m:sud13 p:integer l:SUD13 t:dataTypeName=number

metric m:sud14 p:integer l:SUD14 t:dataTypeName=number

metric m:sud15 p:integer l:SUD15 t:dataTypeName=number

metric m:sud16 p:integer l:SUD16 t:dataTypeName=number

metric m:sud17 p:integer l:SUD17 t:dataTypeName=number

metric m:sud18 p:integer l:SUD18 t:dataTypeName=number

metric m:sud19 p:integer l:SUD19 t:dataTypeName=number

metric m:sud20 p:integer l:SUD20 t:dataTypeName=number

entity e:ikdx-vgub l:"Zoning Reference Table" t:attribution="City of Los Angeles Department of City Planning" t:url=https://data.lacity.org/api/views/ikdx-vgub

property e:ikdx-vgub t:meta.view v:id=ikdx-vgub v:category="A Well Run City" v:attributionLink=http://cityplanning.lacity.org v:averageRating=0 v:name="Zoning Reference Table" v:attribution="City of Los Angeles Department of City Planning"

property e:ikdx-vgub t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:ikdx-vgub t:meta.view.owner v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:displayName="Planning OpenData"

property e:ikdx-vgub t:meta.view.tableauthor v:id=9jxz-e3ru v:profileImageUrlMedium=/api/users/9jxz-e3ru/profile_images/THUMB v:profileImageUrlLarge=/api/users/9jxz-e3ru/profile_images/LARGE v:screenName="Planning OpenData" v:profileImageUrlSmall=/api/users/9jxz-e3ru/profile_images/TINY v:roleName=publisher v:displayName="Planning OpenData"
```

## Top Records

```ls
| :updated_at | zone_cmplt   | zone_class | zone_code | zc1 | zc2 | zc3 | zc4 | max_hgt_stry | max_hgt_ft | hd1 | hd2 | hd3 | hd4 | sud1 | sud2 | sud3 | sud4 | sud5 | sud6 | sud7 | sud8 | sud9 | sud10 | sud11 | hpoz | fd2 | sud12 | sud13 | sud14 | sud15 | sud16 | sud17 | sud18 | sud19 | sud20 | 
| =========== | ============ | ========== | ========= | === | === | === | === | ============ | ========== | === | === | === | === | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ===== | ===== | ==== | === | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | 
| 1386054268  | PF-O         | PF         | 801       | 0   | 0   | 0   | 0   | 0            | 0          | 0   | 0   | 0   | 0   | 1    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 0     | 0    | 0   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | [Q]C2-1VL-SN | C2         | 606       | 0   | 3   | 0   | 0   | 0            | 0          | 1   | 2   | 0   | 0   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 1     | 0    | 1   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | PF-1-O       | PF         | 801       | 0   | 0   | 0   | 0   | 0            | 0          | 1   | 0   | 0   | 0   | 1    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 0     | 0    | 0   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | (T)(Q)C4-2D  | C4         | 608       | 1   | 2   | 0   | 1   | 0            | 0          | 2   | 0   | 0   | 0   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 0     | 0    | 1   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | C4-1D        | C4         | 608       | 0   | 0   | 0   | 1   | 0            | 0          | 1   | 0   | 0   | 0   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 0     | 0    | 1   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | [Q]R2-1L-CDO | R2         | 401       | 0   | 3   | 0   | 0   | 0            | 0          | 1   | 1   | 0   | 0   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 1    | 0    | 0     | 0     | 0    | 0   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | A2-1-K       | A2         | 202       | 0   | 0   | 0   | 0   | 0            | 0          | 1   | 0   | 0   | 0   | 0    | 0    | 0    | 0    | 1    | 0    | 0    | 0    | 0    | 0     | 0     | 0    | 0   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | C4-1XL-SN    | C4         | 608       | 0   | 0   | 0   | 0   | 0            | 0          | 1   | 3   | 0   | 0   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 1     | 0    | 1   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | R2-1-HPOZ    | R2         | 401       | 0   | 0   | 0   | 0   | 0            | 0          | 1   | 0   | 0   | 0   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 0     | 1    | 0   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
| 1386054268  | QC1-2D       | C1         | 603       | 0   | 1   | 0   | 1   | 0            | 0          | 2   | 0   | 0   | 0   | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0    | 0     | 0     | 0    | 0   | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 0     | 
```