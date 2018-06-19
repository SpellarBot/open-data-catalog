# National Register of Historic Places

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/national-register-of-historic-places) |
| Metadata | [Link](https://data.ny.gov/api/views/iisn-hnyv) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/iisn-hnyv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/iisn-hnyv/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | iisn-hnyv |
| Name | National Register of Historic Places |
| Attribution | NYS State Historic Preservation Office |
| Category | Recreation |
| Tags | parks, recreation, historic, national register, historic preservation, nr, nrhp |
| Created | 2013-02-19T17:57:09Z |
| Publication Date | 2015-12-18T20:41:38Z |

## Description

The New York State Office of Parks, Recreation and Historic Preservation (OPRHP) oversees more than 214 state parks and historic sites, encompassing nearly 335,000 acres, that are visited by 60 million people annually. The New York State Historic Preservation Office maintains the list of New York State?s National Register of Historic Places. The National Register of Historic Places is the official list of the Nation's historic places worthy of preservation. Authorized by the National Historic Preservation Act of 1966 ( Federal Regulation 36 CFR 60 ) the National Park Service's National Register of Historic Places is part of a national program to coordinate and support public and private efforts to identify, evaluate, and protect America's historic and archeological resources. To be considered eligible, a building, district, structure or object must meet the National Register Criteria for Evaluation. This involves examining the property?s age, integrity, and significance. Please see metadata for additional information, including how to access the agency?s Cultural Resource Information System (CRIS) which provides access to the agency?s database of historic records associated with each project listing in this dataset.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                     | Data Type     | Render Type   |
| ======== | =========== | ====================== | ======================== | ============= | ============= |
| Yes      | series tag  | resource_name          | Resource Name            | text          | text          |
| Yes      | series tag  | county                 | County                   | text          | text          |
| Yes      | time        | national_register_date | National Register Date   | calendar_date | calendar_date |
| Yes      | series tag  | sphinx_number          | National Register Number | text          | text          |
| No       |             | x                      | Longitude                | number        | number        |
| No       |             | y                      | Latitude                 | number        | number        |
```

## Time Field

```ls
Value = national_register_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = x,y
```

## Data Commands

```ls
series e:iisn-hnyv d:1982-06-14T00:00:00.000Z t:sphinx_number=90NR01060 t:county=Ulster t:resource_name="Tuthilltown Gristmill" m:row_number.iisn-hnyv=1

series e:iisn-hnyv d:1978-12-19T00:00:00.000Z t:sphinx_number=90NR00947 t:county="New York" t:resource_name="Fort Tryon Park And The Cloisters" m:row_number.iisn-hnyv=2

series e:iisn-hnyv d:1979-01-25T00:00:00.000Z t:sphinx_number=90NR01949 t:county=Nassau t:resource_name="Planting Fields Arboretum" m:row_number.iisn-hnyv=3
```

## Meta Commands

```ls
metric m:row_number.iisn-hnyv p:long l:"Row Number"

entity e:iisn-hnyv l:"National Register of Historic Places" t:attribution="NYS State Historic Preservation Office" t:url=https://data.ny.gov/api/views/iisn-hnyv

property e:iisn-hnyv t:meta.view v:id=iisn-hnyv v:category=Recreation v:attributionLink=http://nysparks.com/shpo/ v:averageRating=0 v:name="National Register of Historic Places" v:attribution="NYS State Historic Preservation Office"

property e:iisn-hnyv t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:iisn-hnyv t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:iisn-hnyv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| resource_name                         | county       | national_register_date | sphinx_number | x               | y              | 
| ===================================== | ============ | ====================== | ============= | =============== | ============== | 
| Tuthilltown Gristmill                 | Ulster       | 1982-06-14T00:00:00    | 90NR01060     | -74.17890000000 | 41.68432715130 | 
| Fort Tryon Park And The Cloisters     | New York     | 1978-12-19T00:00:00    | 90NR00947     | -73.93210000000 | 40.86234813640 | 
| Planting Fields Arboretum             | Nassau       | 1979-01-25T00:00:00    | 90NR01949     | -73.55720000000 | 40.86191600630 | 
| Market Street Historic District       | St. Lawrence | 1979-11-16T00:00:00    | 90NR02575     | -74.98700000000 | 44.66966825770 | 
| Alcove Historic District              | Albany       | 1980-07-24T00:00:00    | 90NR02765     | -73.92600000000 | 42.46933537440 | 
| Boonville Historic District           | Oneida       | 1979-11-16T00:00:00    | 90NR02076     | -75.33780000000 | 43.48455292350 | 
| East Avenue Historic District         | Monroe       | 1979-04-17T00:00:00    | 90NR01468     | -77.58020000000 | 43.15139486890 | 
| Waterville Triangle Historic District | Oneida       | 1978-04-04T00:00:00    | 90NR02082     | -75.37830000000 | 42.93065483500 | 
| Albany Rural Cemetery                 | Albany       | 1979-10-25T00:00:00    | 90NR02835     | -73.73390000000 | 42.70786354830 | 
| Poughkeepsie Railroad Bridge          | Dutchess     | 1979-02-23T00:00:00    | 90NR00370     | -73.94080000000 | 41.71064989850 | 
```