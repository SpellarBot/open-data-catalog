# Currently Registered Pesticide Businesses and Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/currently-registered-pesticide-businesses-and-agencies) |
| Metadata | [Link](https://data.ny.gov/api/views/h8u2-6ejg) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/h8u2-6ejg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/h8u2-6ejg/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | h8u2-6ejg |
| Name | Currently Registered Pesticide Businesses and Agencies |
| Attribution | New York State Department of Environmental Conservation (DEC) |
| Category | Energy & Environment |
| Tags | pesticides, dec, environmental conservation |
| Created | 2016-06-06T12:29:37Z |
| Publication Date | 2017-04-20T10:12:18Z |

## Description

This file contains information on Pesticide Businesses and Agencies currently registered by New York State Department of Environmental Conservation (DEC) in the various categories of operation (6NYCRR Part 325).

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                           | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================== | ============= | ============= |
| Yes      | series tag     | business_agency_name         | Business/Agency Name           | text          | text          |
| Yes      | series tag     | registration_number          | Registration Number            | text          | number        |
| Yes      | series tag     | city                         | City                           | text          | text          |
| Yes      | series tag     | state                        | State                          | text          | text          |
| Yes      | series tag     | zip_code                     | Zip Code                       | text          | text          |
| Yes      | numeric metric | dec_region                   | DEC Region                     | number        | number        |
| Yes      | time           | registration_effective_date  | Registration Effective Date    | calendar_date | calendar_date |
| No       |                | registration_expiration_date | Registration Expiration Date   | calendar_date | calendar_date |
| Yes      | series tag     | pesticide_category_code      | Pesticide Category Code        | text          | text          |
| Yes      | series tag     | pesticide_category_desc      | Pesticide Category Description | text          | text          |
```

## Time Field

```ls
Value = registration_effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = registration_expiration_date
```

## Data Commands

```ls
series e:h8u2-6ejg d:2013-07-08T00:00:00.000Z t:zip_code=11790 t:business_agency_name="BEACH PEST CONTROL SERVICE INC" t:state=NY t:pesticide_category_code=7c t:pesticide_category_desc="Termite Control" t:registration_number=15900 t:city="STONY BROOK" m:dec_region=1

series e:h8u2-6ejg d:2015-05-01T00:00:00.000Z t:zip_code=12567 t:business_agency_name="BAYLAND INC" t:state=NY t:pesticide_category_code=3a t:pesticide_category_desc="Ornamental and Turf" t:registration_number=10471 t:city="PINE PLAINS" m:dec_region=3

series e:h8u2-6ejg d:2015-03-01T00:00:00.000Z t:zip_code=10465 t:business_agency_name="BAYSIDE MARINA AT LOCUST POINT INC" t:state=NY t:pesticide_category_code=5d t:pesticide_category_desc="Aquatic Anti-Fouling Paints" t:registration_number=13276 t:city=BRONX m:dec_region=2
```

## Meta Commands

```ls
metric m:dec_region p:long l:"DEC Region" d:"NYS DEC Region where the business or agency is located; Region 0 indicates an out-of-state business or agency." t:dataTypeName=number

entity e:h8u2-6ejg l:"Currently Registered Pesticide Businesses and Agencies" t:attribution="New York State Department of Environmental Conservation (DEC)" t:url=https://data.ny.gov/api/views/h8u2-6ejg

property e:h8u2-6ejg t:meta.view v:id=h8u2-6ejg v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/nyspad/ v:averageRating=0 v:name="Currently Registered Pesticide Businesses and Agencies" v:attribution="New York State Department of Environmental Conservation (DEC)"

property e:h8u2-6ejg t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:h8u2-6ejg t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| business_agency_name               | registration_number | city              | state | zip_code | dec_region | registration_effective_date | registration_expiration_date | pesticide_category_code | pesticide_category_desc     | 
| ================================== | =================== | ================= | ===== | ======== | ========== | =========================== | ============================ | ======================= | =========================== | 
| BEACH PEST CONTROL SERVICE INC     | 15900               | STONY BROOK       | NY    | 11790    | 1          | 2013-07-08T00:00:00         | 2019-12-31T00:00:00          | 7c                      | Termite Control             | 
| BAYLAND INC                        | 10471               | PINE PLAINS       | NY    | 12567    | 3          | 2015-05-01T00:00:00         | 2018-04-30T00:00:00          | 3a                      | Ornamental and Turf         | 
| BAYSIDE MARINA AT LOCUST POINT INC | 13276               | BRONX             | NY    | 10465    | 2          | 2015-03-01T00:00:00         | 2018-02-28T00:00:00          | 5d                      | Aquatic Anti-Fouling Paints | 
| BEAUTIFUL LAWNS LLC                | 11995               | CLIFTON PARK      | NY    | 12065    | 4          | 2015-07-01T00:00:00         | 2018-06-30T00:00:00          | 3a                      | Ornamental and Turf         | 
| BAYFIELD LANDSCAPING INC           | 15623               | WESTHAMPTON BEACH | NY    | 11978    | 1          | 2015-05-08T00:00:00         | 2017-12-31T00:00:00          | 3a                      | Ornamental and Turf         | 
| BAYPORT MARINE COMPANY INC         | 7886                | BAYPORT           | NY    | 11705    | 1          | 2015-01-01T00:00:00         | 2017-12-31T00:00:00          | 5d                      | Aquatic Anti-Fouling Paints | 
| BEACH PEST CONTROL SERVICE INC     | 15900               | STONY BROOK       | NY    | 11790    | 1          | 2013-07-08T00:00:00         | 2019-12-31T00:00:00          | 7f                      | Food Processing             | 
| BAY POINT MARINA LP                | 14335               | BLUE POINT        | NY    | 11715    | 1          | 2013-01-01T00:00:00         | 2018-12-31T00:00:00          | 13                      | Anti-Fouling Paint          | 
| BEAU ENTERPRISES INC               | 12232               | RANSOMVILLE       | NY    | 14131    | 9          | 2014-10-01T00:00:00         | 2017-09-30T00:00:00          | 3a                      | Ornamental and Turf         | 
| BEAU ENTERPRISES INC               | 12232               | RANSOMVILLE       | NY    | 14131    | 9          | 2014-10-01T00:00:00         | 2017-09-30T00:00:00          | 6a                      | Rights-of Way Vegetation    | 
```