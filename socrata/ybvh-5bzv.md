# Cook County Municipalities with City Hall Addresses and URLs

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cook-county-municipalities-with-city-hall-addresses-and-urls-cde94) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/ybvh-5bzv) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ybvh-5bzv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/ybvh-5bzv/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | ybvh-5bzv |
| Name | Cook County Municipalities with City Hall Addresses and URLs |
| Category | Economic Development |
| Tags | municipalities |
| Created | 2013-06-11T15:06:22Z |
| Publication Date | 2014-11-06T20:15:23Z |

## Description

Cook County is home to over 130 municipalities. Our list gives each one along with the City Hall Address and URL.

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| No       | time        | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag  | municipality   | Municipality   | text      | text        |
| Yes      | series tag  | street_address | Street Address | text      | text        |
| Yes      | series tag  | zip_code       | Zip Code       | text      | text        |
| Yes      | series tag  | url            | URL            | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ybvh-5bzv d:2014-11-06T12:13:34.000Z t:zip_code=60426 t:municipality=Harvey t:street_address="15320 Broadway Avenue" t:url=http://www.cityofharvey.org/site2/ m:row_number.ybvh-5bzv=1

series e:ybvh-5bzv d:2014-11-06T12:13:34.000Z t:zip_code=60546 t:municipality="North Riverside" t:street_address="2401 S. Des Plaines Avenue" t:url=http://www.northriverside-il.org m:row_number.ybvh-5bzv=2

series e:ybvh-5bzv d:2014-11-06T12:13:34.000Z t:zip_code=60527 t:municipality="Burr Ridge" t:street_address="7660 County Line Road" t:url=http://www.burr-ridge.gov/ m:row_number.ybvh-5bzv=3
```

## Meta Commands

```ls
metric m:row_number.ybvh-5bzv p:long l:"Row Number"

entity e:ybvh-5bzv l:"Cook County Municipalities with City Hall Addresses and URLs" t:url=https://datacatalog.cookcountyil.gov/api/views/ybvh-5bzv

property e:ybvh-5bzv t:meta.view v:id=ybvh-5bzv v:category="Economic Development" v:averageRating=0 v:name="Cook County Municipalities with City Hall Addresses and URLs"

property e:ybvh-5bzv t:meta.view.owner v:id=64st-bp2a v:screenName="Economic Development" v:displayName="Economic Development"

property e:ybvh-5bzv t:meta.view.tableauthor v:id=64st-bp2a v:screenName="Economic Development" v:roleName=editor v:displayName="Economic Development"
```

## Top Records

```ls
| :updated_at | municipality      | street_address             | zip_code | url                                        | 
| =========== | ================= | ========================== | ======== | ========================================== | 
| 1415276014  | Harvey            | 15320 Broadway Avenue      | 60426    | [http://www.cityofharvey.org/site2/, null] | 
| 1415276014  | North Riverside   | 2401 S. Des Plaines Avenue | 60546    | [http://www.northriverside-il.org, null]   | 
| 1415276014  | Burr Ridge        | 7660 County Line Road      | 60527    | [http://www.burr-ridge.gov/, null]         | 
| 1415276014  | Morton Grove      | 6101 Capulina Avenue       | 60053    | [http://www.mortongroveil.org, null]       | 
| 1415276014  | Barrington        | 200 S. Hough Street        | 60010    | [http://www.barrington-il.gov/, null]      | 
| 1415276014  | Arlington Heights | 33 S. Arlington Heights Rd | 60005    | [http://www.vah.com, null]                 | 
| 1415276014  | Hometown          | 4331 Southwest Hwy.        | 60456    | [http://www.cityofhometown.com, null]      | 
| 1415276014  | Wheeling          | 2 Community Boulevard      | 60090    | [http://www.wheelingil.gov, null]          | 
| 1415276014  | Streamwood        | 301 E. Irving Park Road    | 60107    | [http://www.streamwood.org, null]          | 
| 1415276014  | Palos Heights     | 7607 W. College Drive      | 60463    | [http://www.palosheights.org, null]        | 
```