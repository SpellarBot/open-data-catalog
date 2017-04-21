# Liquor Authority Quarterly List of Active Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/liquor-authority-quarterly-list-of-active-licenses) |
| Metadata | [Link](https://data.ny.gov/api/views/hrvs-fxs2) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/hrvs-fxs2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/hrvs-fxs2/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | hrvs-fxs2 |
| Name | Liquor Authority Quarterly List of Active Licenses |
| Attribution | New York State Liquor Authority |
| Category | Economic Development |
| Tags | licenses, farm, wholesale, mapping, brewer, cidery, distiller, beer, wine, liquor, restaurant, bar, club, grocery, drug store |
| Created | 2013-05-10T20:22:45Z |
| Publication Date | 2017-04-19T22:28:04Z |

## Description

Liquor Authority quarterly list of all active licensees in NYS.

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                      | Data Type     | Render Type   |
| ======== | =========== | ======================================= | ========================================= | ============= | ============= |
| Yes      | series tag  | license_serial_number                   | License Serial Number                     | text          | number        |
| Yes      | series tag  | license_type_name                       | License Type Name                         | text          | text          |
| Yes      | series tag  | license_class_code                      | License Class Code                        | text          | number        |
| Yes      | series tag  | license_type_code                       | License Type Code                         | text          | text          |
| Yes      | series tag  | agency_zone_office_name                 | Agency Zone Office Name                   | text          | text          |
| Yes      | series tag  | agency_zone_office_number               | Agency Zone Office Number                 | text          | number        |
| Yes      | series tag  | county_name_licensee                    | County Name (Licensee)                    | text          | text          |
| Yes      | series tag  | premises_name                           | Premises Name                             | text          | text          |
| Yes      | series tag  | doing_business_as_dba                   | Doing Business As (DBA)                   | text          | text          |
| No       |             | actual_address_of_premises_address1     | Actual Address of Premises (Address1)     | text          | text          |
| No       |             | additional_address_information_address2 | Additional Address Information (Address2) | text          | text          |
| Yes      | series tag  | city                                    | City                                      | text          | text          |
| Yes      | series tag  | state                                   | State                                     | text          | text          |
| Yes      | series tag  | zip                                     | Zip                                       | text          | text          |
| Yes      | series tag  | license_certificate_number              | License Certificate Number                | text          | number        |
| No       |             | license_original_issue_date             | License Original Issue Date               | calendar_date | calendar_date |
| No       |             | license_effective_date                  | License Effective Date                    | calendar_date | calendar_date |
| Yes      | time        | license_expiration_date                 | License Expiration Date                   | calendar_date | calendar_date |
| No       |             | latitude                                | Latitude                                  | number        | number        |
| No       |             | longitude                               | Longitude                                 | number        | number        |
```

## Time Field

```ls
Value = license_expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = actual_address_of_premises_address1,additional_address_information_address2,license_original_issue_date,license_effective_date,latitude,longitude
```

## Data Commands

```ls
series e:hrvs-fxs2 d:2019-02-28T00:00:00.000Z t:premises_name="ERIDANIA CORP" t:zip=10452 t:license_type_name="GROCERY STORE BEER" t:doing_business_as_dba="1888 WALTON GROCERY" t:license_certificate_number=876158 t:state=NY t:license_class_code=122 t:license_type_code=A t:agency_zone_office_number=1 t:license_serial_number=1000080 t:county_name_licensee=BRONX t:agency_zone_office_name="New York" t:city=BRONX m:row_number.hrvs-fxs2=1

series e:hrvs-fxs2 d:2020-02-29T00:00:00.000Z t:premises_name="1098 MINI MARKET INC" t:zip=10452 t:license_type_name="GROCERY STORE BEER" t:doing_business_as_dba="JACOBO GROCERY & DELI" t:license_certificate_number=888708 t:state=NY t:license_class_code=122 t:license_type_code=A t:agency_zone_office_number=1 t:license_serial_number=1000090 t:county_name_licensee=BRONX t:agency_zone_office_name="New York" t:city=BRONX m:row_number.hrvs-fxs2=2

series e:hrvs-fxs2 d:2017-10-31T00:00:00.000Z t:premises_name="J & A FRUIT & GROCERY CORP" t:zip=10452 t:license_type_name="GROCERY STORE BEER" t:doing_business_as_dba="J & A FRUIT & GROCERY CTR" t:license_certificate_number=861876 t:state=NY t:license_class_code=122 t:license_type_code=A t:agency_zone_office_number=1 t:license_serial_number=1000099 t:county_name_licensee=BRONX t:agency_zone_office_name="New York" t:city=BRONX m:row_number.hrvs-fxs2=3
```

## Meta Commands

```ls
metric m:row_number.hrvs-fxs2 p:long l:"Row Number"

entity e:hrvs-fxs2 l:"Liquor Authority Quarterly List of Active Licenses" t:attribution="New York State Liquor Authority" t:url=https://data.ny.gov/api/views/hrvs-fxs2

property e:hrvs-fxs2 t:meta.view v:id=hrvs-fxs2 v:category="Economic Development" v:attributionLink=http://www.sla.ny.gov/licensing-information-0 v:averageRating=0 v:name="Liquor Authority Quarterly List of Active Licenses" v:attribution="New York State Liquor Authority"

property e:hrvs-fxs2 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:hrvs-fxs2 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| license_serial_number | license_type_name       | license_class_code | license_type_code | agency_zone_office_name | agency_zone_office_number | county_name_licensee | premises_name              | doing_business_as_dba     | actual_address_of_premises_address1 | additional_address_information_address2 | city  | state | zip   | license_certificate_number | license_original_issue_date | license_effective_date | license_expiration_date | latitude       | longitude       | 
| ===================== | ======================= | ================== | ================= | ======================= | ========================= | ==================== | ========================== | ========================= | =================================== | ======================================= | ===== | ===== | ===== | ========================== | =========================== | ====================== | ======================= | ============== | =============== | 
| 1000080               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | ERIDANIA CORP              | 1888 WALTON GROCERY       | 1888 WALTON AVE                     |                                         | BRONX | NY    | 10452 | 876158                     |                             | 2016-03-01T00:00:00    | 2019-02-28T00:00:00     | 40.84942969500 | -73.90926082760 | 
| 1000090               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | 1098 MINI MARKET INC       | JACOBO GROCERY & DELI     | 1098 ANDERSON AVENUE                |                                         | BRONX | NY    | 10452 | 888708                     | 2004-08-31T00:00:00         | 2017-03-01T00:00:00    | 2020-02-29T00:00:00     | 40.83471022020 | -73.92523844010 | 
| 1000099               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | J & A FRUIT & GROCERY CORP | J & A FRUIT & GROCERY CTR | 11 17 E 171ST STREET                |                                         | BRONX | NY    | 10452 | 861876                     | 2007-09-20T00:00:00         | 2014-11-01T00:00:00    | 2017-10-31T00:00:00     | 40.84127748180 | -73.91658233050 | 
| 1000167               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | ALTAGRACIA GROCERY CORP    |                           | 10 12 E 176TH STREET                |                                         | BRONX | NY    | 10453 | 860177                     |                             | 2014-07-01T00:00:00    | 2017-06-30T00:00:00     |                |                 | 
| 1000207               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | 48 BURNSIDE FOOD CORP      | FOOD DYNASTY              | 40 48 WEST BURNSIDE AVE             |                                         | BRONX | NY    | 10453 | 872236                     | 1997-10-15T00:00:00         | 2015-10-01T00:00:00    | 2018-09-30T00:00:00     | 40.85390041090 | -73.90943979810 | 
| 1000218               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | CRISMELI DELI GROCERY INC  | CRISMELI DELI GROCERY     | 297 BROOK AVE                       | DELI & GROCERY                          | BRONX | NY    | 10454 | 860600                     | 2008-12-09T00:00:00         | 2014-08-01T00:00:00    | 2017-07-31T00:00:00     | 40.80896069870 | -73.91847507760 | 
| 1000305               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | RAMON A RODRIGUEZ          | RODRIGUEZ GROCERY         | 753 FOX STREET                      |                                         | BRONX | NY    | 10455 | 879792                     | 1995-08-10T00:00:00         | 2016-08-01T00:00:00    | 2019-07-31T00:00:00     | 40.81555152060 | -73.89842355070 | 
| 1000351               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | JOSE A DUME                | FOREST DELI GROCERY       | 751 FOREST AVENUE                   |                                         | BRONX | NY    | 10456 | 890290                     |                             | 2017-05-01T00:00:00    | 2020-04-30T00:00:00     | 40.81826236460 | -73.90626702450 | 
| 1000407               | GROCERY STORE BEER      | 122                | A                 | New York                | 1                         | BRONX                | ANGELO RUIZ                | ANGELOS GROCERY STORE     | 279 E 173RD STREET                  |                                         | BRONX | NY    | 10457 | 828489                     |                             | 2014-07-01T00:00:00    | 2017-06-30T00:00:00     | 40.84372021590 | -73.90713683780 | 
| 1000471               | GROCERY BEER, WINE PROD | 122                | AX                | New York                | 1                         | BRONX                | WILLIS DELI INC            |                           | 538 E 178TH STREET                  |                                         | BRONX | NY    | 10457 | 828490                     | 2003-07-08T00:00:00         | 2014-07-01T00:00:00    | 2017-06-30T00:00:00     | 40.84767453650 | -73.89523622600 | 
```