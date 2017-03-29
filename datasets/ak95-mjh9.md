# Local Area Unemployment Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/local-area-unemployment-statistics-3885c) |
| Metadata | [Link](https://data.wa.gov/api/views/ak95-mjh9) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ak95-mjh9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ak95-mjh9/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ak95-mjh9 |
| Name | Local Area Unemployment Statistics |
| Attribution | United States Department of Labor |
| Category | Economics |
| Tags | unemployment |
| Created | 2014-02-06T04:36:01Z |
| Publication Date | 2014-02-06T05:16:54Z |

## Description

The Local Area Unemployment Statistics (LAUS) program produces monthly and annual employment, unemployment, and labor force data for Census regions and divisions, States, counties, metropolitan areas, and many cities, by place of residence.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag     | laus_area_code       | LAUS Area Code       | text          | text          |
| Yes      | series tag     | state_fips_code      | State FIPS Code      | text          | number        |
| Yes      | series tag     | county_fips_code     | County FIPS Code     | text          | number        |
| Yes      | series tag     | area_title           | Area Title           | text          | text          |
| Yes      | series tag     | county_name          | County Name          | text          | text          |
| Yes      | series tag     | state                | State                | text          | text          |
| Yes      | series tag     | period               | Period               | text          | text          |
| Yes      | time           | date                 | Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | civilian_labor_force | Civilian Labor Force | number        | number        |
| Yes      | numeric metric | employed_level       | Employed Level       | number        | number        |
| Yes      | numeric metric | unemployed_level     | Unemployed Level     | number        | number        |
| Yes      | numeric metric | unemployment_rate    | Unemployment Rate    | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ak95-mjh9 d:2012-11-01T00:00:00.000Z t:laus_area_code=CN5300100000000 t:area_title="Adams County, WA" t:state_fips_code=53 t:state=WA t:county_fips_code=1 t:period=12-Nov t:county_name="Adams County" m:employed_level=7389 m:unemployment_rate=8.6 m:civilian_labor_force=8082 m:unemployed_level=693

series e:ak95-mjh9 d:2012-12-01T00:00:00.000Z t:laus_area_code=CN5300100000000 t:area_title="Adams County, WA" t:state_fips_code=53 t:state=WA t:county_fips_code=1 t:period=12-Dec t:county_name="Adams County" m:employed_level=7061 m:unemployment_rate=10.9 m:civilian_labor_force=7922 m:unemployed_level=861

series e:ak95-mjh9 d:2013-01-01T00:00:00.000Z t:laus_area_code=CN5300100000000 t:area_title="Adams County, WA" t:state_fips_code=53 t:state=WA t:county_fips_code=1 t:period=13-Jan t:county_name="Adams County" m:employed_level=6915 m:unemployment_rate=12.5 m:civilian_labor_force=7907 m:unemployed_level=992
```

## Meta Commands

```ls
metric m:civilian_labor_force p:integer l:"Civilian Labor Force" t:dataTypeName=number

metric m:employed_level p:integer l:"Employed Level" t:dataTypeName=number

metric m:unemployed_level p:integer l:"Unemployed Level" t:dataTypeName=number

metric m:unemployment_rate p:float l:"Unemployment Rate" t:dataTypeName=number

entity e:ak95-mjh9 l:"Local Area Unemployment Statistics" t:attribution="United States Department of Labor" t:url=https://data.wa.gov/api/views/ak95-mjh9

property e:ak95-mjh9 t:meta.view v:id=ak95-mjh9 v:category=Economics v:attributionLink=http://stats.bls.gov/lau/laucntycur14.txt v:averageRating=60 v:name="Local Area Unemployment Statistics" v:attribution="United States Department of Labor"

property e:ak95-mjh9 t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:ak95-mjh9 t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| laus_area_code  | state_fips_code | county_fips_code | area_title       | county_name  | state | period | date                | civilian_labor_force | employed_level | unemployed_level | unemployment_rate | 
| =============== | =============== | ================ | ================ | ============ | ===== | ====== | =================== | ==================== | ============== | ================ | ================= | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 12-Nov | 2012-11-01T00:00:00 | 8082                 | 7389           | 693              | 8.6               | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 12-Dec | 2012-12-01T00:00:00 | 7922                 | 7061           | 861              | 10.9              | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 13-Jan | 2013-01-01T00:00:00 | 7907                 | 6915           | 992              | 12.5              | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 13-Feb | 2013-02-01T00:00:00 | 7917                 | 6919           | 998              | 12.6              | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 13-Mar | 2013-03-01T00:00:00 | 8105                 | 7291           | 814              | 10                | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 13-Apr | 2013-04-01T00:00:00 | 8526                 | 7844           | 682              | 8                 | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 13-May | 2013-05-01T00:00:00 | 8211                 | 7555           | 656              | 8                 | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 13-Jun | 2013-06-01T00:00:00 | 8812                 | 8135           | 677              | 7.7               | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 13-Jul | 2013-07-01T00:00:00 | 8913                 | 8236           | 677              | 7.6               | 
| CN5300100000000 | 53              | 1                | Adams County, WA | Adams County | WA    | 13-Aug | 2013-08-01T00:00:00 | 9078                 | 8451           | 627              | 6.9               | 
```