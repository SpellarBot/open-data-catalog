# Registered Business Locations - San Francisco

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-business-locations-san-francisco-0fdcb) |
| Metadata | [Link](https://data.sfgov.org/api/views/g8m3-pdis) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/g8m3-pdis/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/g8m3-pdis/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | g8m3-pdis |
| Name | Registered Business Locations - San Francisco |
| Attribution | City and County of San Francisco |
| Category | Economy and Community |
| Tags | business |
| Created | 2014-01-16T18:47:47Z |
| Publication Date | 2016-09-14T17:06:05Z |

## Description

This dataset includes the locations of businesses that pay taxes to the City and County of San Francisco. Each registered business may have multiple locations and each location is a single row. The Treasurer & Tax Collector?s Office collects this data through business registration applications, account update/closure forms, and taxpayer filings. The data is collected to help enforce the Business and Tax Regulations Code including, but not limited to: Article 6, Article 12, Article 12-A, and Article 12-A-1. http://sftreasurer.org/registration

## Columns

```ls
| Included | Schema Type | Field Name                        | Name                                | Data Type     | Render Type   |
| ======== | =========== | ================================= | =================================== | ============= | ============= |
| Yes      | series tag  | ttxid                             | Location Id                         | text          | text          |
| Yes      | series tag  | certificate_number                | Business Account Number             | text          | text          |
| Yes      | series tag  | ownership_name                    | Ownership Name                      | text          | text          |
| Yes      | series tag  | dba_name                          | DBA Name                            | text          | text          |
| No       |             | full_business_address             | Street Address                      | text          | text          |
| Yes      | series tag  | city                              | City                                | text          | text          |
| Yes      | series tag  | state                             | State                               | text          | text          |
| Yes      | series tag  | business_zip                      | Source Zipcode                      | text          | text          |
| Yes      | time        | dba_start_date                    | Business Start Date                 | calendar_date | calendar_date |
| No       |             | dba_end_date                      | Business End Date                   | calendar_date | calendar_date |
| No       |             | location_start_date               | Location Start Date                 | calendar_date | calendar_date |
| No       |             | location_end_date                 | Location End Date                   | calendar_date | calendar_date |
| No       |             | mailing_address_1                 | Mail Address                        | text          | text          |
| Yes      | series tag  | mail_city                         | Mail City                           | text          | text          |
| Yes      | series tag  | mail_zipcode                      | Mail Zipcode                        | text          | text          |
| Yes      | series tag  | mail_state                        | Mail State                          | text          | text          |
| Yes      | series tag  | naic_code                         | NAICS Code                          | text          | text          |
| Yes      | series tag  | naic_code_description             | NAICS Code Description              | text          | text          |
| Yes      | series tag  | parking_tax                       | Parking Tax                         | checkbox      | checkbox      |
| Yes      | series tag  | transient_occupancy_tax           | Transient Occupancy Tax             | checkbox      | checkbox      |
| Yes      | series tag  | lic                               | LIC Code                            | text          | text          |
| Yes      | series tag  | lic_code_description              | LIC Code Description                | text          | text          |
| Yes      | series tag  | supervisor_district               | Supervisor District                 | text          | text          |
| Yes      | series tag  | neighborhoods_analysis_boundaries | Neighborhoods - Analysis Boundaries | text          | text          |
| Yes      | series tag  | business_corridor                 | Business Corridor                   | text          | text          |
```

## Time Field

```ls
Value = dba_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = full_business_address,dba_end_date,location_start_date,location_end_date,mailing_address_1
```

## Data Commands

```ls
series e:g8m3-pdis d:1968-10-01T00:00:00.000Z t:neighborhoods_analysis_boundaries="Nob Hill" t:transient_occupancy_tax=false t:certificate_number=0003856 t:state=CA t:dba_name="1365-1373 California Pats" t:supervisor_district=3 t:city="San Francisco" t:mail_state=CA t:parking_tax=false t:mail_zipcode=94109 t:ttxid=0003856-06-001 t:mail_city="San Francisco" t:business_zip=94109 t:ownership_name="Lew Willie L & Po S" m:row_number.g8m3-pdis=1

series e:g8m3-pdis d:2003-01-01T00:00:00.000Z t:mail_state=NY t:parking_tax=false t:transient_occupancy_tax=false t:ttxid=0000024-02-999 t:mail_zipcode=14650 t:business_zip=14650 t:mail_city=Rochester t:certificate_number=0000024 t:state=NY t:dba_name="Eastman Kodak Co" t:naic_code=3100-3399 t:ownership_name="Eastman Kodak Co" t:naic_code_description=Manufacturing t:city=Rochester m:row_number.g8m3-pdis=2

series e:g8m3-pdis d:1968-10-01T00:00:00.000Z t:neighborhoods_analysis_boundaries="North Beach" t:transient_occupancy_tax=false t:certificate_number=0007457 t:state=CA t:dba_name="Cafe Delucchi" t:supervisor_district=3 t:city="San Francisco" t:mail_state=CA t:parking_tax=false t:mail_zipcode=94133 t:ttxid=0007457-02-001 t:mail_city="San Francisco" t:business_zip=94133 t:ownership_name="Delucchi Mechanical Inc" m:row_number.g8m3-pdis=3
```

## Meta Commands

```ls
metric m:row_number.g8m3-pdis p:long l:"Row Number"

entity e:g8m3-pdis l:"Registered Business Locations - San Francisco" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/g8m3-pdis

property e:g8m3-pdis t:meta.view v:id=g8m3-pdis v:category="Economy and Community" v:attributionLink=http://www.sfgov.org v:averageRating=0 v:name="Registered Business Locations - San Francisco" v:attribution="City and County of San Francisco"

property e:g8m3-pdis t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:g8m3-pdis t:meta.view.owner v:id=zhvw-4ft9 v:screenName=TTX-DataSF v:displayName=TTX-DataSF

property e:g8m3-pdis t:meta.view.tableauthor v:id=zhvw-4ft9 v:screenName=TTX-DataSF v:roleName=editor v:displayName=TTX-DataSF
```

## Top Records

```ls
| ttxid          | certificate_number | ownership_name               | dba_name                       | full_business_address | city          | state | business_zip | dba_start_date      | dba_end_date        | location_start_date | location_end_date   | mailing_address_1   | mail_city     | mail_zipcode | mail_state | naic_code | naic_code_description | parking_tax | transient_occupancy_tax | lic         | lic_code_description | supervisor_district | neighborhoods_analysis_boundaries | business_corridor | 
| ============== | ================== | ============================ | ============================== | ===================== | ============= | ===== | ============ | =================== | =================== | =================== | =================== | =================== | ============= | ============ | ========== | ========= | ===================== | =========== | ======================= | =========== | ==================== | =================== | ================================= | ================= | 
| 0003856-06-001 | 0003856            | Lew Willie L & Po S          | 1365-1373 California Pats      | 1365 California St    | San Francisco | CA    | 94109        | 1968-10-01T00:00:00 |                     | 1972-07-01T00:00:00 |                     | 1361 California St  | San Francisco | 94109        | CA         |           |                       | false       | false                   |             |                      | 3                   | Nob Hill                          |                   | 
| 0000024-02-999 | 0000024            | Eastman Kodak Co             | Eastman Kodak Co               | 343 State St          | Rochester     | NY    | 14650        | 2003-01-01T00:00:00 |                     | 2003-01-01T00:00:00 |                     | 343 State Street    | Rochester     | 14650        | NY         | 3100-3399 | Manufacturing         | false       | false                   |             |                      |                     |                                   |                   | 
| 0007457-02-001 | 0007457            | Delucchi Mechanical Inc      | Cafe Delucchi                  | 500 Columbus Ave      | San Francisco | CA    | 94133        | 1968-10-01T00:00:00 | 2013-10-01T00:00:00 | 1968-10-01T00:00:00 | 2013-10-01T00:00:00 | 1526 Powell St      | San Francisco | 94133        | CA         |           |                       | false       | false                   |             |                      | 3                   | North Beach                       |                   | 
| 0008972-03-003 | 0008972            | Euromotors Inc               | Mercedes Benz Of San Francisco | 1480 Folsom St.       | San Francisco | CA    | 94103        | 2007-12-31T00:00:00 |                     | 2007-12-31T00:00:00 |                     | 500 8th St          | San Francisco | 94103        | CA         | 4400-4599 | Retail Trade          | false       | false                   | D03 D19 D23 | Multiple             | 6                   | South of Market                   |                   | 
| 0010032-03-001 | 0010032            | Frank Roy M                  | 32 Lundys Apts                 | 32 Lundys Ln          | San Francisco | CA    | 94110        | 1968-10-01T00:00:00 | 2013-12-31T00:00:00 | 1970-01-01T00:00:00 | 2013-12-31T00:00:00 | 311 S Ellsworth Ave | San Mateo     | 94401        | CA         |           |                       | false       | false                   |             |                      | 9                   | Bernal Heights                    |                   | 
| 0011673-01-001 | 0011673            | Stauffacher Jack W           | Greenwood Press                | 300 Broadway St 300   | San+francisco | CA    | 94133        | 1968-10-01T00:00:00 |                     | 1968-10-01T00:00:00 |                     | 1945 Broadway #305  | San Francisco | 94109        | CA         |           |                       | false       | false                   |             |                      |                     |                                   |                   | 
| 0013445-05-001 | 0013445            | Kennedy Dorothy              | 5174 3rd St Apartments         | 5174 3rd St           | San Francisco | CA    | 94124        | 1968-10-01T00:00:00 |                     | 1971-01-01T00:00:00 |                     | 2413 Whitetail Dr   | Antioch       | 94531        | CA         |           |                       | false       | false                   |             |                      | 10                  | Bayview Hunters Point             |                   | 
| 0019790-23-001 | 0019790            | Oreilly Auto Enterprises Llc | Oreilly Auto Parts #3139       | 2500 San Bruno Ave    | San Francisco | CA    | 94134        | 1968-10-01T00:00:00 |                     | 2010-02-25T00:00:00 |                     | Po Box 1156         | Springfield   | 65801        | MO         | 4400-4599 | Retail Trade          | false       | false                   |             |                      | 9                   | Portola                           |                   | 
| 0020309-14-001 | 0020309            | Varni Tony                   | Anthony Varni Gen Contractor   | 217 Balboa St         | San Francisco | CA    | 94118        | 1968-10-01T00:00:00 |                     | 2013-10-11T00:00:00 |                     | 217 Balboa St       | San Francisco | 94118        | CA         |           |                       | false       | false                   |             |                      |                     |                                   |                   | 
| 0020716-01-999 | 0020716            | Nishimoto Trading Co Ltd     | Nishimoto Trading Co Ltd       | 340 Valley Dr         | Brisbane      | CA    | 94005        | 1968-10-01T00:00:00 |                     | 1968-10-01T00:00:00 |                     | 13409 Orden Dr      | Santa         | SPRIN        | FE         | 4200-4299 | Wholesale Trade       | false       | false                   |             |                      |                     |                                   |                   | 
```