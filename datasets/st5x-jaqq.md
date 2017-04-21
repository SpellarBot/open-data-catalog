# Hudson River Park Flora - Plantings: Beginning 1997

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hudson-river-park-flora-plantings-beginning-1997) |
| Metadata | [Link](https://data.ny.gov/api/views/st5x-jaqq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/st5x-jaqq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/st5x-jaqq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | st5x-jaqq |
| Name | Hudson River Park Flora - Plantings: Beginning 1997 |
| Attribution | Hudson River Park Trust (HRPT) |
| Category | Energy & Environment |
| Tags | hrpt, flora, horticulture |
| Created | 2014-11-04T17:49:57Z |
| Publication Date | 2014-12-31T16:10:59Z |

## Description

A list of plants installed (planted) in Hudson River Park, along with the date and location of the installation.  This is part of the ongoing efforts of  the Hudson River Park Trust?s (HRPT) Horticulture staff to care for the thousands of plants throughout the five-mile park area.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | flora_description | Flora Description | text          | text          |
| Yes      | series tag  | flora_type        | Flora Type        | text          | text          |
| Yes      | time        | installation_date | Installation Date | calendar_date | calendar_date |
| Yes      | series tag  | location          | Location          | text          | text          |
```

## Time Field

```ls
Value = installation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:st5x-jaqq d:2012-10-12T00:00:00.000Z t:location="Meatpacking District" t:flora_type=PERENNIAL t:flora_description="Echinacea ;Tiki Torch;  75ct" m:row_number.st5x-jaqq=1

series e:st5x-jaqq d:2012-10-12T00:00:00.000Z t:location="Meatpacking District" t:flora_type=PERENNIAL t:flora_description="Hemerocallis ;Spellbinder;  30ct" m:row_number.st5x-jaqq=2

series e:st5x-jaqq d:2012-10-12T00:00:00.000Z t:location="Meatpacking District" t:flora_type=PERENNIAL t:flora_description="Origanum ;Kent Beauty;   50ct" m:row_number.st5x-jaqq=3
```

## Meta Commands

```ls
metric m:row_number.st5x-jaqq p:long l:"Row Number"

entity e:st5x-jaqq l:"Hudson River Park Flora - Plantings:  Beginning 1997" t:attribution="Hudson River Park Trust (HRPT)" t:url=https://data.ny.gov/api/views/st5x-jaqq

property e:st5x-jaqq t:meta.view v:id=st5x-jaqq v:category="Energy & Environment" v:attributionLink=http://www.hudsonriverpark.org/vision-and-progress/operations-highlights v:averageRating=0 v:name="Hudson River Park Flora - Plantings:  Beginning 1997" v:attribution="Hudson River Park Trust (HRPT)"

property e:st5x-jaqq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:st5x-jaqq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:st5x-jaqq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| flora_description                      | flora_type | installation_date   | location             | 
| ====================================== | ========== | =================== | ==================== | 
| Echinacea ;Tiki Torch; 75ct            | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Hemerocallis ;Spellbinder; 30ct        | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Origanum ;Kent Beauty; 50ct            | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Geranium biokora 80ct                  | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Heuchera ;Christa; 70ct                | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Aster novae-angliae ;Purple Dome; 35ct | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Imperata koenigii ;Red Baron; 380ct    | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Gaillardia ;Oranges and Lemons; 60ct   | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Hosta ;Sum & Substance; 6ct            | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
| Hemerocallis ;Ruffled Apricot; 60ct    | PERENNIAL  | 2012-10-12T00:00:00 | Meatpacking District | 
```