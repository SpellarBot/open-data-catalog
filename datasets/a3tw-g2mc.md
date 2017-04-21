# IDHS Active Cases By CCR& R And SITE FY 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-active-cases-by-ccr-r-and-site-fy-2011-602d5) |
| Metadata | [Link](https://data.illinois.gov/api/views/a3tw-g2mc) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/a3tw-g2mc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/a3tw-g2mc/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | a3tw-g2mc |
| Name | IDHS Active Cases By CCR& R And SITE FY 2011 |
| Category | Social/Healthcare |
| Created | 2011-11-02T16:06:01Z |
| Publication Date | 2011-11-02T16:07:55Z |

## Description

Number of cases approved for child care for the service month.

## Columns

```ls
| Included | Schema Type    | Field Name | Name   | Data Type | Render Type |
| ======== | ============== | ========== | ====== | ========= | =========== |
| Yes      | series tag     | region     | REGION | text      | text        |
| Yes      | numeric metric | jul        | JUL    | number    | number      |
| Yes      | numeric metric | aug        | AUG    | number    | number      |
| Yes      | numeric metric | sep        | SEP    | number    | number      |
| Yes      | numeric metric | oct        | OCT    | number    | number      |
| Yes      | numeric metric | nov        | NOV    | number    | number      |
| Yes      | numeric metric | dec        | DEC    | number    | number      |
| Yes      | numeric metric | jan        | JAN    | number    | number      |
| Yes      | numeric metric | feb        | FEB    | number    | number      |
| Yes      | numeric metric | mar        | MAR    | number    | number      |
| Yes      | numeric metric | apr        | APR    | number    | number      |
| Yes      | numeric metric | may        | MAY    | number    | number      |
| Yes      | numeric metric | jun        | JUN    | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:a3tw-g2mc d:2011-01-01T00:00:00.000Z t:region=Rockford m:may=3333 m:apr=3565 m:dec=3455 m:oct=3676 m:feb=3495 m:nov=3577 m:jul=3273 m:sep=3297 m:jun=3187 m:mar=3467 m:jan=3492 m:aug=3229

series e:a3tw-g2mc d:2011-01-01T00:00:00.000Z t:region="De Kalb" m:may=1683 m:apr=1654 m:dec=1625 m:oct=1652 m:feb=1593 m:nov=1662 m:jul=1433 m:sep=1550 m:jun=1495 m:mar=1632 m:jan=1431 m:aug=1480

series e:a3tw-g2mc d:2011-01-01T00:00:00.000Z t:region=Waukegan m:may=3500 m:apr=3635 m:dec=3520 m:oct=3713 m:feb=3327 m:nov=3714 m:jul=3421 m:sep=3525 m:jun=3255 m:mar=3469 m:jan=3329 m:aug=3422
```

## Meta Commands

```ls
metric m:jul p:integer l:JUL t:dataTypeName=number

metric m:aug p:integer l:AUG t:dataTypeName=number

metric m:sep p:integer l:SEP t:dataTypeName=number

metric m:oct p:integer l:OCT t:dataTypeName=number

metric m:nov p:integer l:NOV t:dataTypeName=number

metric m:dec p:integer l:DEC t:dataTypeName=number

metric m:jan p:integer l:JAN t:dataTypeName=number

metric m:feb p:integer l:FEB t:dataTypeName=number

metric m:mar p:integer l:MAR t:dataTypeName=number

metric m:apr p:integer l:APR t:dataTypeName=number

metric m:may p:integer l:MAY t:dataTypeName=number

metric m:jun p:integer l:JUN t:dataTypeName=number

entity e:a3tw-g2mc l:"IDHS Active Cases By CCR& R And SITE FY 2011" t:url=https://data.illinois.gov/api/views/a3tw-g2mc

property e:a3tw-g2mc t:meta.view v:id=a3tw-g2mc v:category=Social/Healthcare v:averageRating=0 v:name="IDHS Active Cases By CCR& R And SITE FY 2011"

property e:a3tw-g2mc t:meta.view.owner v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"

property e:a3tw-g2mc t:meta.view.tableauthor v:id=e9y5-49nr v:screenName="Carl Awe" v:displayName="Carl Awe"
```

## Top Records

```ls
| region       | jul   | aug   | sep   | oct   | nov   | dec   | jan   | feb   | mar   | apr   | may   | jun   | 
| ============ | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | ===== | 
| Rockford     | 3273  | 3229  | 3297  | 3676  | 3577  | 3455  | 3492  | 3495  | 3467  | 3565  | 3333  | 3187  | 
| De Kalb      | 1433  | 1480  | 1550  | 1652  | 1662  | 1625  | 1431  | 1593  | 1632  | 1654  | 1683  | 1495  | 
| Waukegan     | 3421  | 3422  | 3525  | 3713  | 3714  | 3520  | 3329  | 3327  | 3469  | 3635  | 3500  | 3255  | 
| Crystal Lake | 872   | 875   | 894   | 989   | 965   | 962   | 881   | 958   | 952   | 983   | 979   | 944   | 
| Glen Ellyn   | 3529  | 3291  | 3046  | 2981  | 2739  | 3162  | 3183  | 3168  | 3864  | 4613  | 4539  | 4358  | 
| Joliet       | 3573  | 3589  | 3531  | 4211  | 4128  | 3967  | 3768  | 3932  | 4042  | 4112  | 3718  | 3590  | 
| AFC(Chicago) | 46037 | 44612 | 43735 | 48110 | 47979 | 46244 | 45284 | 45199 | 45950 | 48242 | 44331 | 42759 | 
| Davenport    | 1514  | 1546  | 1602  | 1705  | 1728  | 1440  | 1528  | 1602  | 1723  | 1745  | 1493  | 1477  | 
| Peoria       | 3012  | 2997  | 3188  | 3395  | 3285  | 2975  | 3008  | 3125  | 3248  | 3353  | 2920  | 2943  | 
| Bloomington  | 1249  | 1296  | 1356  | 1375  | 1372  | 1221  | 1290  | 1304  | 1300  | 1321  | 1176  | 1151  | 
```