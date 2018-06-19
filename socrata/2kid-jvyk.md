# NYS Liquor Authority New Applications Received

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nys-liquor-authority-new-applications-received) |
| Metadata | [Link](https://data.ny.gov/api/views/2kid-jvyk) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/2kid-jvyk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/2kid-jvyk/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 2kid-jvyk |
| Name | NYS Liquor Authority New Applications Received |
| Attribution | NYS Liquor Authority Licensing Bureau / NYSITS |
| Category | Economic Development |
| Tags | restaurant, bar, package store, alcohol, liquor license, manufacturing, wine, beer, liquor, spirits, grocery store, drug store, wholesale, retail |
| Created | 2014-05-14T16:19:53Z |
| Publication Date | 2017-04-19T22:00:41Z |

## Description

Liquor License applications received

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                      | Data Type     | Render Type   |
| ======== | =========== | ======================================= | ========================================= | ============= | ============= |
| Yes      | series tag  | license_serial_number                   | License Serial Number                     | text          | number        |
| Yes      | series tag  | license_type_name                       | License Type Name                         | text          | text          |
| Yes      | series tag  | license_class_code                      | License Class Code                        | text          | number        |
| Yes      | series tag  | license_type_code                       | License Type Code                         | text          | text          |
| Yes      | series tag  | agency_zone_office_number               | Agency Zone Office Number                 | text          | number        |
| Yes      | series tag  | agency_zone_office_name                 | Agency Zone Office Name                   | text          | text          |
| Yes      | series tag  | county_name_licensee                    | County Name (Licensee)                    | text          | text          |
| Yes      | series tag  | premises_name                           | Premises Name                             | text          | text          |
| Yes      | series tag  | doing_business_as_dba                   | Doing Business As (DBA)                   | text          | text          |
| No       |             | actual_address_of_premises_address1     | Actual Address of Premises (Address1)     | text          | text          |
| No       |             | additional_address_information_address2 | Additional Address Information (Address2) | text          | text          |
| Yes      | series tag  | city                                    | City                                      | text          | text          |
| Yes      | series tag  | state                                   | State                                     | text          | text          |
| Yes      | series tag  | zip                                     | ZIP                                       | text          | number        |
| Yes      | series tag  | license_certificate_number              | License Certificate Number                | text          | number        |
| Yes      | time        | license_received_date                   | License Received Date                     | calendar_date | calendar_date |
```

## Time Field

```ls
Value = license_received_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = actual_address_of_premises_address1,additional_address_information_address2
```

## Data Commands

```ls
series e:2kid-jvyk d:2017-02-23T00:00:00.000Z t:premises_name="JEROME DELI PLAZA CORP" t:zip=11207 t:license_type_name="GROCERY BEER, WINE PROD" t:state=NY t:license_class_code=122 t:license_type_code=AX t:agency_zone_office_number=1 t:license_serial_number=1292739 t:county_name_licensee=KINGS t:agency_zone_office_name="New York City" t:city=BROOKLYN m:row_number.2kid-jvyk=1

series e:2kid-jvyk d:2017-01-23T00:00:00.000Z t:premises_name="FLUSHING BUFFET INC" t:zip=11354 t:license_type_name="RESTAURANT WINE" t:doing_business_as_dba="RED TOP MOUNTAIN RESTAURANT" t:license_certificate_number=823751 t:state=NY t:license_class_code=341 t:license_type_code=RW t:agency_zone_office_number=1 t:license_serial_number=1293143 t:county_name_licensee=QUEENS t:agency_zone_office_name="New York City" t:city=FLUSHING m:row_number.2kid-jvyk=2

series e:2kid-jvyk d:2017-03-02T00:00:00.000Z t:premises_name="CABREJA DELI GROCERY CORP" t:zip=11212 t:license_type_name="GROCERY BEER, WINE PROD" t:license_certificate_number=865218 t:state=NY t:license_class_code=122 t:license_type_code=AX t:agency_zone_office_number=1 t:license_serial_number=1293958 t:county_name_licensee=KINGS t:agency_zone_office_name="New York City" t:city=BROOKLYN m:row_number.2kid-jvyk=3
```

## Meta Commands

```ls
metric m:row_number.2kid-jvyk p:long l:"Row Number"

entity e:2kid-jvyk l:"NYS Liquor Authority New Applications Received" t:attribution="NYS Liquor Authority Licensing Bureau / NYSITS" t:url=https://data.ny.gov/api/views/2kid-jvyk

property e:2kid-jvyk t:meta.view v:id=2kid-jvyk v:category="Economic Development" v:attributionLink=http://www.sla.ny.gov v:averageRating=0 v:name="NYS Liquor Authority New Applications Received" v:attribution="NYS Liquor Authority Licensing Bureau / NYSITS"

property e:2kid-jvyk t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:2kid-jvyk t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| license_serial_number | license_type_name       | license_class_code | license_type_code | agency_zone_office_number | agency_zone_office_name | county_name_licensee | premises_name                     | doing_business_as_dba        | actual_address_of_premises_address1 | additional_address_information_address2 | city          | state | zip   | license_certificate_number | license_received_date | 
| ===================== | ======================= | ================== | ================= | ========================= | ======================= | ==================== | ================================= | ============================ | =================================== | ======================================= | ============= | ===== | ===== | ========================== | ===================== | 
| 1292739               | GROCERY BEER, WINE PROD | 122                | AX                | 1                         | New York City           | KINGS                | JEROME DELI PLAZA CORP            |                              | 621 JEROME ST                       |                                         | BROOKLYN      | NY    | 11207 |                            | 2017-02-23T00:00:00   | 
| 1293143               | RESTAURANT WINE         | 341                | RW                | 1                         | New York City           | QUEENS               | FLUSHING BUFFET INC               | RED TOP MOUNTAIN RESTAURANT  | 37-02 MAIN ST                       | 2ND FL                                  | FLUSHING      | NY    | 11354 | 823751                     | 2017-01-23T00:00:00   | 
| 1293958               | GROCERY BEER, WINE PROD | 122                | AX                | 1                         | New York City           | KINGS                | CABREJA DELI GROCERY CORP         |                              | 430 MOTHER GASTON BLVD              |                                         | BROOKLYN      | NY    | 11212 | 865218                     | 2017-03-02T00:00:00   | 
| 1295166               | RESTAURANT WINE         | 341                | RW                | 1                         | New York City           | QUEENS               | EL RINCON PERUANO RESTAURANT CORP | EL RINCON PERUANO RESTAURANT | 64-06 ROOSEVELT AVE                 |                                         | WOODSIDE      | NY    | 11377 |                            | 2017-03-02T00:00:00   | 
| 3157839               | ON-PREMISES LIQUOR      | 252                | OP                | 3                         | Buffalo                 | ERIE                 | B P GLOBAL FUNDS INC              | LEGACY LOUNGE                | 1261 FILLMORE AVE                   |                                         | BUFFALO       | NY    | 14211 |                            | 2017-03-30T00:00:00   | 
| 1296327               | LIQUOR STORE            | 222                | L                 | 1                         | New York City           | KINGS                | NEW YORK DISCOUNT LIQUOR INC      |                              | 596 598 NEW YORK AVE                |                                         | BROOKLYN      | NY    | 11225 | 865114                     | 2017-02-01T00:00:00   | 
| 1296359               | ON-PREMISES LIQUOR      | 252                | OP                | 1                         | New York City           | NEW YORK             | FAT PIG INC                       |                              | 120 DYCKMAN ST                      |                                         | NEW YORK      | NY    | 10040 | 861675                     | 2017-03-02T00:00:00   | 
| 3158095               | ON-PREMISES LIQUOR      | 252                | OP                | 3                         | Buffalo                 | ERIE                 | EUROPEAN EATS INC                 | ZOE RESTAURANT               | 5701 TRANSIT RD                     |                                         | EAST AMHERST  | NY    | 14051 | 825753                     | 2017-03-03T00:00:00   | 
| 2205303               | GROCERY BEER, WINE PROD | 122                | AX                | 2                         | Albany                  | ORANGE               | E Z R DELI AND CONVENIENCE INC    |                              | 194 RTE 209                         | UNIT #2 T/O DEER PARK                   | PORT JERVIS   | NY    | 12771 | 889122                     | 2017-02-16T00:00:00   | 
| 1297457               | ON-PREMISES LIQUOR      | 252                | OP                | 1                         | New York City           | NASSAU               | MSGIOS PIZZA CORP                 | GIOVANNI'S PIZZA RESTAURANT  | 47 FRANKLIN AVE                     |                                         | VALLEY STREAM | NY    | 11580 |                            | 2017-02-15T00:00:00   | 
```