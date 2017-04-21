# Liquor Authority Quarterly List of Active Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/liquor-authority-quarterly-list-of-active-permits) |
| Metadata | [Link](https://data.ny.gov/api/views/mmmf-xgpx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mmmf-xgpx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mmmf-xgpx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mmmf-xgpx |
| Name | Liquor Authority Quarterly List of Active Permits |
| Attribution | New York State Liquor Authority |
| Category | Economic Development |
| Tags | permits, alcohol, liquor authority, abc |
| Created | 2013-07-12T14:54:50Z |
| Publication Date | 2017-04-19T22:03:27Z |

## Description

This dataset contains a list of all active permits issued by the State Liquor Authority.  Permits in this dataset are issued for 1-3 year terms.  This dataset does not include temporary or single event.

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                      | Data Type     | Render Type   |
| ======== | =========== | ======================================= | ========================================= | ============= | ============= |
| Yes      | series tag  | serial_number                           | Serial Number                             | text          | number        |
| Yes      | series tag  | agency_zone_office_name                 | Agency Zone Office Name                   | text          | text          |
| Yes      | series tag  | agency_zone_office_number               | Agency Zone Office Number                 | text          | number        |
| Yes      | series tag  | county_name                             | County Name                               | text          | text          |
| Yes      | series tag  | type_code                               | Type Code                                 | text          | text          |
| Yes      | series tag  | class_code                              | Class Code                                | text          | number        |
| Yes      | series tag  | permit_class_description                | Permit Class Description                  | text          | text          |
| Yes      | series tag  | premises_name                           | Premises Name                             | text          | text          |
| Yes      | series tag  | doing_business_as_dba                   | Doing Business As (DBA)                   | text          | text          |
| No       |             | actual_address_of_premises_address1     | Actual Address of Premises (Address1)     | text          | text          |
| No       |             | additional_address_information_address2 | Additional Address Information (Address2) | text          | text          |
| Yes      | series tag  | city                                    | City                                      | text          | text          |
| Yes      | series tag  | state                                   | State                                     | text          | text          |
| Yes      | series tag  | zip_code                                | Zip Code                                  | text          | text          |
| Yes      | series tag  | certificate_number                      | Certificate Number                        | text          | number        |
| No       |             | original_issue_date                     | Original Issue Date                       | calendar_date | calendar_date |
| No       |             | effective_date                          | Effective Date                            | calendar_date | calendar_date |
| Yes      | time        | expiration_date                         | Expiration Date                           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = actual_address_of_premises_address1,additional_address_information_address2,effective_date,original_issue_date
```

## Data Commands

```ls
series e:mmmf-xgpx d:2017-06-30T00:00:00.000Z t:premises_name="ALBANY BEVERAGE CORP" t:zip_code=12303 t:certificate_number=529721 t:state=NY t:agency_zone_office_number=2 t:class_code=601 t:permit_class_description="RETAIL BEER FUNCTION" t:county_name=ALBANY t:agency_zone_office_name=Albany t:serial_number=2001281 t:type_code=RB t:city=SCHENECTADY m:row_number.mmmf-xgpx=1

series e:mmmf-xgpx d:2017-06-30T00:00:00.000Z t:premises_name="MANHATTAN BEER DISTRIBUTORS LLC" t:zip_code=10455 t:certificate_number=529734 t:state=NY t:agency_zone_office_number=1 t:class_code=601 t:permit_class_description="RETAIL BEER FUNCTION" t:county_name=BRONX t:agency_zone_office_name="New York City" t:serial_number=1004256 t:type_code=RB t:city=BRONX m:row_number.mmmf-xgpx=2

series e:mmmf-xgpx d:2017-06-30T00:00:00.000Z t:premises_name="ROCCO J TESTANI INC" t:zip_code=13902 t:certificate_number=529728 t:state=NY t:agency_zone_office_number=2 t:class_code=601 t:permit_class_description="RETAIL BEER FUNCTION" t:county_name=BROOME t:agency_zone_office_name=Albany t:serial_number=2500645 t:type_code=RB t:city=BINGHAMTON m:row_number.mmmf-xgpx=3
```

## Meta Commands

```ls
metric m:row_number.mmmf-xgpx p:long l:"Row Number"

entity e:mmmf-xgpx l:"Liquor Authority Quarterly List of Active Permits" t:attribution="New York State Liquor Authority" t:url=https://data.ny.gov/api/views/mmmf-xgpx

property e:mmmf-xgpx t:meta.view v:id=mmmf-xgpx v:category="Economic Development" v:attributionLink=http://sla.ny.gov v:averageRating=0 v:name="Liquor Authority Quarterly List of Active Permits" v:attribution="New York State Liquor Authority"

property e:mmmf-xgpx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mmmf-xgpx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:mmmf-xgpx t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| serial_number | agency_zone_office_name | agency_zone_office_number | county_name | type_code | class_code | permit_class_description | premises_name                   | doing_business_as_dba | actual_address_of_premises_address1 | additional_address_information_address2 | city        | state | zip_code | certificate_number | original_issue_date | effective_date      | expiration_date     | 
| ============= | ======================= | ========================= | =========== | ========= | ========== | ======================== | =============================== | ===================== | =================================== | ======================================= | =========== | ===== | ======== | ================== | =================== | =================== | =================== | 
| 2001281       | Albany                  | 2                         | ALBANY      | RB        | 601        | RETAIL BEER FUNCTION     | ALBANY BEVERAGE CORP            |                       | 3899 CARMEN RD,T/O GUILDERLAND      |                                         | SCHENECTADY | NY    | 12303    | 529721             |                     | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 1004256       | New York City           | 1                         | BRONX       | RB        | 601        | RETAIL BEER FUNCTION     | MANHATTAN BEER DISTRIBUTORS LLC |                       | 955 E 149TH STREET                  |                                         | BRONX       | NY    | 10455    | 529734             |                     | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 2500645       | Albany                  | 2                         | BROOME      | RB        | 601        | RETAIL BEER FUNCTION     | ROCCO J TESTANI INC             |                       | 29 PHELPS ST                        | PORT DICKINSON                          | BINGHAMTON  | NY    | 13902    | 529728             |                     | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 2500649       | Albany                  | 2                         | BROOME      | RB        | 601        | RETAIL BEER FUNCTION     | FARGNOLI DISTRIBUTING INC       | SAM THE BEER MAN      | 1164 FRONT ST                       |                                         | BINGHAMTON  | NY    | 13905    | 529706             | 2015-04-10T00:00:00 | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 3001188       | Buffalo                 | 3                         | CHAUTAUQUA  | RB        | 601        | RETAIL BEER FUNCTION     | ARTHUR R GREN CO INC            |                       | 1886 MASON DR                       |                                         | JAMESTOWN   | NY    | 14701    | 529764             | 2003-05-19T00:00:00 | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 3001577       | Buffalo                 | 3                         | CHEMUNG     | RB        | 601        | RETAIL BEER FUNCTION     | JOHN G RYAN INC                 |                       | 14 KENT ROAD                        |                                         | PINE CITY   | NY    | 14871    | 529723             | 2014-05-22T00:00:00 | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 3001578       | Buffalo                 | 3                         | CHEMUNG     | RB        | 601        | RETAIL BEER FUNCTION     | SENECA BEVERAGE CORP            |                       | 2085 LAKE ROAD                      |                                         | ELMIRA      | NY    | 14903    | 529750             | 2010-09-14T00:00:00 | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 2004294       | Albany                  | 2                         | CLINTON     | RB        | 601        | RETAIL BEER FUNCTION     | PLATTSBURGH DISTRIBUTING CO INC |                       | 217 SHARRON AVENUE                  |                                         | PLATTSBURGH | NY    | 12901    | 529763             |                     | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 3005553       | Buffalo                 | 3                         | ERIE        | RB        | 601        | RETAIL BEER FUNCTION     | CONSUMERS BEVERAGES INC         |                       | 1244 FRENCH ROAD                    |                                         | DEPEW       | NY    | 14043    | 529777             | 2014-05-30T00:00:00 | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
| 3005554       | Buffalo                 | 3                         | ERIE        | RB        | 601        | RETAIL BEER FUNCTION     | CONSUMERS BEVERAGES INC         |                       | SOUTH 5755 MAELOU DRIVE             |                                         | HAMBURG     | NY    | 14075    | 529802             | 2003-06-24T00:00:00 | 2016-07-01T00:00:00 | 2017-06-30T00:00:00 | 
```