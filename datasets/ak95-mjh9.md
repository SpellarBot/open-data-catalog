# Local Area Unemployment Statistics

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/ak95-mjh9/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/local-area-unemployment-statistics-3885c)
* [Metadata URL](https://data.wa.gov/api/views/ak95-mjh9)
* Id = ak95-mjh9
* Name = Local Area Unemployment Statistics
* Attribution = United States Department of Labor
* [Attribution Link](http://stats.bls.gov/lau/laucntycur14.txt)
* Category = Economics
* Tags = [unemployment]
* Created = 2014-02-06T04:36:01Z
* Publication Date = 2014-02-06T05:16:54Z
* Rows Updated = 2014-02-06T05:16:45Z

## Description

The Local Area Unemployment Statistics (LAUS) program produces monthly and annual employment, unemployment, and labor force data for Census regions and divisions, States, counties, metropolitan areas, and many cities, by place of residence.

## Columns

```ls
| Name                 | Field Name           | Data Type     | Render Type   | Schema Type    | Included | 
| ==================== | ==================== | ============= | ============= | ============== | ======== | 
| LAUS Area Code       | laus_area_code       | text          | text          | series tag     | Yes      | 
| State FIPS Code      | state_fips_code      | text          | number        | series tag     | Yes      | 
| County FIPS Code     | county_fips_code     | text          | number        | series tag     | Yes      | 
| Area Title           | area_title           | text          | text          | series tag     | Yes      | 
| County Name          | county_name          | text          | text          | series tag     | Yes      | 
| State                | state                | text          | text          | series tag     | Yes      | 
| Period               | period               | text          | text          | series tag     | Yes      | 
| Date                 | date                 | calendar_date | calendar_date | time           | Yes      | 
| Civilian Labor Force | civilian_labor_force | number        | number        | numeric metric | Yes      | 
| Employed Level       | employed_level       | number        | number        | numeric metric | Yes      | 
| Unemployed Level     | unemployed_level     | number        | number        | numeric metric | Yes      | 
| Unemployment Rate    | unemployment_rate    | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
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

metric m:unemployment_rate l:"Unemployment Rate" t:dataTypeName=number

entity e:ak95-mjh9 l:"Local Area Unemployment Statistics" t:attribution="United States Department of Labor" t:url=https://data.wa.gov/api/views/ak95-mjh9

property e:ak95-mjh9 t:meta.view d:2017-03-07T18:52:36.285Z v:id=ak95-mjh9 v:category=Economics v:attributionLink=http://stats.bls.gov/lau/laucntycur14.txt v:averageRating=60 v:name="Local Area Unemployment Statistics" v:attribution="United States Department of Labor"

property e:ak95-mjh9 t:meta.view.owner d:2017-03-07T18:52:36.285Z v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"

property e:ak95-mjh9 t:meta.view.tableauthor d:2017-03-07T18:52:36.285Z v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```