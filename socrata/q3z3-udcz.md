# Green Roofs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/green-roofs-d4907) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/q3z3-udcz) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/q3z3-udcz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/q3z3-udcz/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | q3z3-udcz |
| Name | Green Roofs |
| Attribution | City of Chicago |
| Category | Environment & Sustainable Development |
| Tags | sustainability |
| Created | 2012-10-03T17:53:20Z |
| Publication Date | 2012-10-16T18:08:57Z |

## Description

This dataset and corresponding map provide the location, satellite images and square footage of existing green roofs within the City of Chicago. This information is derived from an analysis of high-spatial resolution (50cm), pan-sharpened, ortho-rectified, 8-band multi-spectral satellite images collected by Digital Globe?s Worldview-2 satellite. The City supplied the consultant with a 2009 City boundary shapefile to determine the required extent of the imagery. Acquisition of three different strips of imagery corresponding to the satellite?s paths was required. These strips of imagery spanned three consecutive months and were collected in August 2010 (90% coverage), September 2010 (5% coverage) and October 2010 (5% coverage). The results of the analysis include overall count of vegetated roofs, their total square footage, and the ratio of required to elective vegetated roofs. A total of 359 vegetated roofs were identified within the City of Chicago. The total square footage of these vegetated roofs was calculated to be approximately 5,469,463 square feet. The ratio of required vegetated roofs to elective vegetative roofs was 297:62 (~5:1). The median size of the vegetated roofs was calculated to be 5,234 square feet.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name               | Data Type | Render Type |
| ======== | ============== | =============== | ================== | ========= | =========== |
| No       | time           | :updated_at     | updated_at         | meta_data | meta_data   |
| No       |                | id              | ID                 | text      | text        |
| Yes      | series tag     | house_number    | HOUSE_NUMBER       | text      | number      |
| Yes      | series tag     | pre_dir         | PRE_DIR            | text      | text        |
| Yes      | series tag     | street_name     | STREET_NAME        | text      | text        |
| Yes      | series tag     | street_type     | STREET_TYPE        | text      | text        |
| No       |                | full_address    | FULL_ADDRESS_RANGE | text      | text        |
| Yes      | series tag     | building_name1  | BUILDING_NAME1     | text      | text        |
| Yes      | series tag     | building_name2  | BUILDING_NAME2     | text      | text        |
| Yes      | series tag     | month_view      | MONTH_VIEW         | text      | text        |
| Yes      | numeric metric | total_roof_sqft | TOTAL_ROOF_SQFT    | number    | number      |
| Yes      | numeric metric | vegetated_sqft  | VEGETATED_SQFT     | number    | number      |
| Yes      | series tag     | fact_sheet      | FACT_SHEET         | url       | url         |
| No       |                | latitude        | LATITUDE           | number    | number      |
| No       |                | longitude       | LONGITUDE          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,full_address,latitude,longitude
```

## Data Commands

```ls
series e:q3z3-udcz d:2012-10-16T11:08:11.000Z t:month_view="August 2010" t:house_number=330 t:street_name=GREEN t:pre_dir=N t:fact_sheet=https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_000.pdf t:street_type=ST m:total_roof_sqft=48806 m:vegetated_sqft=13582

series e:q3z3-udcz d:2012-10-16T11:08:11.000Z t:month_view="August 2010" t:house_number=217 t:street_name="VAN BUREN" t:pre_dir=W t:fact_sheet=https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_001.pdf t:street_type=ST m:total_roof_sqft=23946 m:vegetated_sqft=7055

series e:q3z3-udcz d:2012-10-16T11:08:11.000Z t:month_view="August 2010" t:house_number=1746 t:street_name=SPAULDING t:pre_dir=N t:fact_sheet=https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_002.pdf t:street_type=AVE m:total_roof_sqft=11696 m:vegetated_sqft=3139
```

## Meta Commands

```ls
metric m:total_roof_sqft p:integer l:TOTAL_ROOF_SQFT t:dataTypeName=number

metric m:vegetated_sqft p:integer l:VEGETATED_SQFT t:dataTypeName=number

entity e:q3z3-udcz l:"Green Roofs" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/q3z3-udcz

property e:q3z3-udcz t:meta.view v:id=q3z3-udcz v:category="Environment & Sustainable Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Green Roofs" v:attribution="City of Chicago"

property e:q3z3-udcz t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:q3z3-udcz t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| :updated_at | id  | house_number | pre_dir | street_name         | street_type | full_address               | building_name1 | building_name2 | month_view  | total_roof_sqft | vegetated_sqft | fact_sheet                                                                | latitude    | longitude    | 
| =========== | === | ============ | ======= | =================== | =========== | ========================== | ============== | ============== | =========== | =============== | ============== | ========================================================================= | =========== | ============ | 
| 1350385691  | 000 | 330          | N       | GREEN               | ST          | 330-330 N GREEN ST         |                |                | August 2010 | 48806           | 13582          | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_000.pdf, null] | 41.88781649 | -87.64912988 | 
| 1350385691  | 001 | 217          | W       | VAN BUREN           | ST          | 217-241 W VAN BUREN ST     |                |                | August 2010 | 23946           | 7055           | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_001.pdf, null] | 41.87661344 | -87.63462733 | 
| 1350385691  | 002 | 1746         | N       | SPAULDING           | AVE         | 1746-1752 N SPAULDING AVE  |                |                | August 2010 | 11696           | 3139           | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_002.pdf, null] | 41.91343961 | -87.71039583 | 
| 1350385691  | 003 | 2000         | N       | CALIFORNIA          | AVE         | 2000-2000 N CALIFORNIA AVE |                |                | August 2010 | 5393            | 3910           | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_003.pdf, null] | 41.91773177 | -87.69741338 | 
| 1350385691  | 004 | 445          | N       | SACRAMENTO          | BLVD        | 445-445 N SACRAMENTO BLVD  |                |                | August 2010 | 14733           | 2962           | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_004.pdf, null] | 41.88949181 | -87.70106869 | 
| 1350385691  | 005 | 232          | E       | SUPERIOR            | ST          | 232-254 E SUPERIOR ST      |                |                | August 2010 | 58431           | 11235          | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_005.pdf, null] | 41.89641295 | -87.62094686 | 
| 1350385691  | 006 | 677          | N       | MICHIGAN            | AVE         | 677-679 N MICHIGAN AVE     |                |                | August 2010 | 7733            | 2684           | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_006.pdf, null] | 41.89481420 | -87.62378911 | 
| 1350385691  | 007 | 0            |         | LINCOLN PARK ZOO #2 |             | 0-0 LINCOLN PARK ZOO #2    |                |                | August 2010 | 1693            | 1453           | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_007.pdf, null] | 41.92098553 | -87.63536765 | 
| 1350385691  | 008 | 1466         | N       | HALSTED             | ST          | 1466-1466 N HALSTED ST     | R.E.I. Store   |                | August 2010 | 64084           | 13647          | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_008.pdf, null] | 41.90808464 | -87.64853878 | 
| 1350385691  | 009 | 6000         | N       | CICERO              | AVE         | 6000-6020 N CICERO AVE     |                |                | August 2010 | 48931           | 20924          | [https://gisapps.cityofchicago.org/gisimages/Greenroofs/VR_009.pdf, null] | 41.99048371 | -87.74907432 | 
```