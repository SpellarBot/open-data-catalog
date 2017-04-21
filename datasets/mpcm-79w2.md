# 2011 Housing Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2011-housing-inventory) |
| Metadata | [Link](https://data.sfgov.org/api/views/mpcm-79w2) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/mpcm-79w2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/mpcm-79w2/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | mpcm-79w2 |
| Name | 2011 Housing Inventory |
| Category | Housing and Buildings |
| Tags | housing |
| Created | 2015-06-19T19:26:17Z |
| Publication Date | 2015-09-23T21:54:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name        | Data Type     | Render Type   |
| ======== | ============== | ================ | =========== | ============= | ============= |
| Yes      | series tag     | appl_no          | APPL_NO     | text          | number        |
| Yes      | numeric metric | form             | FORM        | number        | number        |
| No       |                | standardad       | STRDADDRESS | text          | text          |
| Yes      | series tag     | block            | BLOCK       | text          | text          |
| Yes      | series tag     | lot              | LOT         | text          | text          |
| Yes      | numeric metric | units            | UNITS       | number        | number        |
| Yes      | numeric metric | netunits         | NETUNITS    | number        | number        |
| Yes      | series tag     | affordable       | AFF_HSG     | text          | text          |
| Yes      | series tag     | aff_target       | AFF_TARGET  | text          | text          |
| Yes      | series tag     | type             | CNG_TYPE    | text          | text          |
| Yes      | series tag     | existuse         | EXISTUSE    | text          | text          |
| Yes      | series tag     | propuse          | PROPUSE     | text          | text          |
| Yes      | time           | actdate          | ACTDATE     | calendar_date | calendar_date |
| Yes      | series tag     | zoning           | ZONING      | text          | text          |
| Yes      | series tag     | planningdistrict | PD_NO       | text          | number        |
| Yes      | series tag     | supedist         | SD_NO       | text          | number        |
```

## Time Field

```ls
Value = actdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = standardad
```

## Data Commands

```ls
series e:mpcm-79w2 d:2015-06-19T12:26:26.000Z t:planningdistrict=5 t:appl_no=200807116520 t:lot=028 t:block=0792 t:supedist=6 t:propuse=APARTMENTS t:type=N t:affordable=120 t:zoning=NCT-3 m:form=2 m:netunits=120 m:units=120

series e:mpcm-79w2 d:2015-06-19T12:26:26.000Z t:planningdistrict=10 t:appl_no=201009201195 t:lot=277 t:block=4991 t:supedist=11 t:type=N t:zoning=RH-2 m:form=1 m:netunits=36 m:units=36

series e:mpcm-79w2 d:2015-06-19T12:26:26.000Z t:planningdistrict=5 t:appl_no=200710306825 t:lot=022 t:block=1101 t:supedist=5 t:propuse=APARTMENTS t:type=N t:affordable=21 t:zoning=RM-3 m:form=2 m:netunits=21 m:units=21
```

## Meta Commands

```ls
metric m:form p:integer l:FORM t:dataTypeName=number

metric m:units p:integer l:UNITS t:dataTypeName=number

metric m:netunits p:integer l:NETUNITS t:dataTypeName=number

entity e:mpcm-79w2 l:"2011 Housing Inventory" t:url=https://data.sfgov.org/api/views/mpcm-79w2

property e:mpcm-79w2 t:meta.view v:id=mpcm-79w2 v:category="Housing and Buildings" v:averageRating=0 v:name="2011 Housing Inventory"

property e:mpcm-79w2 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:mpcm-79w2 t:meta.view.owner v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:displayName="Information & Analysis Group (IAG) - SFPlanning"

property e:mpcm-79w2 t:meta.view.tableauthor v:id=hwt3-twww v:screenName="Information & Analysis Group (IAG) - SFPlanning" v:roleName=editor v:displayName="Information & Analysis Group (IAG) - SFPlanning"
```

## Top Records

```ls
| appl_no      | form | standardad            | block | lot | units | netunits | affordable | aff_target | type | existuse | propuse    | actdate             | zoning | planningdistrict | supedist | 
| ============ | ==== | ===================== | ===== | === | ===== | ======== | ========== | ========== | ==== | ======== | ========== | =================== | ====== | ================ | ======== | 
| 200807116520 | 2    | 365 FULTON ST         | 0792  | 028 | 120   | 120      | 120        |            | N    |          | APARTMENTS |                     | NCT-3  | 5                | 6        | 
| 201009201195 | 1    | 855 JAMESTOWN AV      | 4991  | 277 | 36    | 36       |            |            | N    |          |            |                     | RH-2   | 10               | 11       | 
| 200710306825 | 2    | 2139 OFARRELL ST      | 1101  | 022 | 21    | 21       | 21         |            | N    |          | APARTMENTS |                     | RM-3   | 5                | 5        | 
| 200809192140 | 2    | 420 29TH AV           | 1460  | 015 | 20    | 20       | 20         |            | N    |          | APARTMENTS |                     | RH-2   | 1                | 1        | 
| 200505182747 | 2    | 121 09TH ST           | 3728  | 069 | 20    | 20       | 2          |            | N    |          | APARTMENTS |                     | SLR    | 4                | 6        | 
| 200612139733 | 2    | 55 TRUMBULL ST        | 5868  | 006 | 18    | 18       | 2          |            | N    |          | APARTMENTS |                     | NC-2   | 12               | 11       | 
| 201103282964 | 1    | 867 JAMESTOWN AV      | 4991  | 277 | 18    | 18       |            |            | N    |          | APARTMENTS |                     | RH-2   | 10               | 11       | 
| 201009201205 | 1    | 857 JAMESTOWN AV      | 4991  | 277 | 12    | 12       |            |            | N    |          | APARTMENTS | 2011-06-29T00:00:00 | RH-2   | 10               | 11       | 
| 200512281131 | 2    | 101 EXECUTIVE PARK BL | 4991  | 279 | 7     | 7        |            |            | N    |          | APARTMENTS | 2011-02-09T00:00:00 | C-2    | 10               | 11       | 
| 200512281126 | 2    | 101 EXECUTIVE PARK BL | 4991  | 279 | 6     | 6        |            |            | N    |          |            |                     | C-2    | 10               | 11       | 
```