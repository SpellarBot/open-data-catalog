# SENTINEL SITES WHM- 11-14-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sentinel-sites-whm-11-14-2014-6a1da) |
| Metadata | [Link](https://data.wa.gov/api/views/fri6-n6k5) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/fri6-n6k5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/fri6-n6k5/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | fri6-n6k5 |
| Name | SENTINEL SITES WHM- 11-14-2014 |
| Attribution | Washington Department of Ecology, Environmental Assessment Program |
| Category | Natural Resources & Environment |
| Tags | watershed health monitoring, sentinel |
| Created | 2014-11-14T18:19:02Z |
| Publication Date | 2014-11-14T18:22:55Z |

## Description

Watershed Health Monitoring samples sentinel sites on an annual basis to help with large-scale trend detection. They are located below landscapes where we expect few changes in land uses.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | site_id          | Site_ID          | text      | text        |
| Yes      | series tag     | site_description | Site_Description | text      | text        |
| Yes      | series tag     | str              | STR              | text      | text        |
| Yes      | numeric metric | active           | Active           | number    | number      |
| Yes      | series tag     | 8_digit_huc      | 8 Digit HUC      | text      | text        |
| Yes      | series tag     | wria             | WRIA             | text      | text        |
| Yes      | series tag     | ecoreg_l4        | ECOREG_L4        | text      | text        |
| Yes      | series tag     | ecoreg_l3        | ECOREG_L3        | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:fri6-n6k5 d:2014-01-01T00:00:00.000Z t:site_description="ASOTIN CREEK NORTH FORK" t:str="Snake River" t:8_digit_huc="17060103 - Lower Snake-Asotin" t:site_id=SEN06600-ASOT13 t:ecoreg_l4="10l - Lower Snake and Clearwater Canyons" t:ecoreg_l3="10 - Columbia Plateau" t:wria="35 - Middle Snake" m:active=1

series e:fri6-n6k5 d:2014-01-01T00:00:00.000Z t:site_description="CLE ELUM RIVER" t:str="Mid Columbia" t:8_digit_huc="17030001 - Upper Yakima" t:site_id=SEN06600-CLEE12 t:ecoreg_l4="77b - North Cascades Highland Forests" t:ecoreg_l3="77 - North Cascades" t:wria="39 - Upper Yakima" m:active=0

series e:fri6-n6k5 d:2014-01-01T00:00:00.000Z t:site_description="CUMMINGS CREEK" t:str="Snake River" t:8_digit_huc="17060107 - Lower Snake-Tucannon" t:site_id=SEN06600-CUMM10 t:ecoreg_l4="10f - Dissected Loess Uplands" t:ecoreg_l3="10 - Columbia Plateau" t:wria="35 - Middle Snake" m:active=1
```

## Meta Commands

```ls
metric m:active p:integer l:Active t:dataTypeName=number

entity e:fri6-n6k5 l:"SENTINEL SITES WHM- 11-14-2014" t:attribution="Washington Department of Ecology, Environmental Assessment Program" t:url=https://data.wa.gov/api/views/fri6-n6k5

property e:fri6-n6k5 t:meta.view v:id=fri6-n6k5 v:category="Natural Resources & Environment" v:attributionLink=http://tinyurl.com/WatershedHealth v:averageRating=0 v:name="SENTINEL SITES WHM- 11-14-2014" v:attribution="Washington Department of Ecology, Environmental Assessment Program"

property e:fri6-n6k5 t:meta.view.owner v:id=h9w5-qfr2 v:profileImageUrlMedium=/api/users/h9w5-qfr2/profile_images/THUMB v:profileImageUrlLarge=/api/users/h9w5-qfr2/profile_images/LARGE v:screenName=glenn.merritt@ecy.wa.gov v:profileImageUrlSmall=/api/users/h9w5-qfr2/profile_images/TINY v:displayName=glenn.merritt@ecy.wa.gov

property e:fri6-n6k5 t:meta.view.tableauthor v:id=h9w5-qfr2 v:profileImageUrlMedium=/api/users/h9w5-qfr2/profile_images/THUMB v:profileImageUrlLarge=/api/users/h9w5-qfr2/profile_images/LARGE v:screenName=glenn.merritt@ecy.wa.gov v:profileImageUrlSmall=/api/users/h9w5-qfr2/profile_images/TINY v:roleName=publisher v:displayName=glenn.merritt@ecy.wa.gov
```

## Top Records

```ls
| site_id         | site_description          | str                  | active | 8_digit_huc                     | wria                         | ecoreg_l4                                           | ecoreg_l3             | 
| =============== | ========================= | ==================== | ====== | =============================== | ============================ | =================================================== | ===================== | 
| SEN06600-ASOT13 | ASOTIN CREEK NORTH FORK   | Snake River          | 1      | 17060103 - Lower Snake-Asotin   | 35 - Middle Snake            | 10l - Lower Snake and Clearwater Canyons            | 10 - Columbia Plateau | 
| SEN06600-CLEE12 | CLE ELUM RIVER            | Mid Columbia         | 0      | 17030001 - Upper Yakima         | 39 - Upper Yakima            | 77b - North Cascades Highland Forests               | 77 - North Cascades   | 
| SEN06600-CUMM10 | CUMMINGS CREEK            | Snake River          | 1      | 17060107 - Lower Snake-Tucannon | 35 - Middle Snake            | 10f - Dissected Loess Uplands                       | 10 - Columbia Plateau | 
| SEN06600-DEAD19 | DEADMAN CREEK             | Northeast Washington | 1      | 17020002 - Kettle               | 60 - Kettle                  | 15x - Okanogan Highland Dry Forest                  | 15 - Northern Rockies | 
| SEN06600-ELLS01 | ELLSWORTH CREEK           | Washington Coastal   | 1      | 17100106 - Willapa Bay          | 24 - Willapa                 | 01b - Coastal Uplands                               | 01 - Coast Range      | 
| SEN06600-GRIF09 | GRIFFIN CREEK             | Puget Sound          | 1      | 17110010 - Snoqualmie           | 07 - Snohomish               | 02e - Eastern Puget Uplands                         | 02 - Puget Lowland    | 
| SEN06600-HAMM03 | HAMMA HAMMA RIVER         | Puget Sound          | 1      | 17110018 - Hood Canal           | 16 - Skokomish - Dosewallips | 01d - Volcanics                                     | 01 - Coast Range      | 
| SEN06600-LAUG07 | LAUGHINGWATER CREEK       | Lower Columbia       | 1      | 17080004 - Upper Cowlitz        | 26 - Cowlitz                 | 04b - Western Cascades Montane Highlands            | 04 - Cascades         | 
| SEN06600-LITT06 | LITTLE PEND OREILLE RIVER | Unlisted             | 1      | 17020003 - Colville             | 59 - Colville                | 15r - Okanogan-Colville Xeric Valleys and Foothills | 15 - Northern Rockies | 
| SEN06600-MARB21 | MARBLE CREEK              | Upper Columbia       | 1      | 17020011 - Wenatchee            | 45 - Wenatchee               | 77h - Chiwaukum Hills and Lowlands                  | 77 - North Cascades   | 
```