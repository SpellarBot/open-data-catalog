# Buyout agreements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/buyout-agreements) |
| Metadata | [Link](https://data.sfgov.org/api/views/wmam-7g8d) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wmam-7g8d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wmam-7g8d/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wmam-7g8d |
| Name | Buyout agreements |
| Category | Housing and Buildings |
| Tags | buyouts, rent control |
| Created | 2015-12-28T23:17:30Z |
| Publication Date | 2016-05-03T18:50:33Z |

## Description

Contains buyout declarations and buyout agreements filed at the Rent Board. Rent Ordinance Section 37.9E, effective March 7, 2015, is a new provision that regulates "buyout agreements" between landlords and tenants under which landlords pay tenants money or other consideration to vacate their rent-controlled rental units. For more information, please see: http://sfrb.org/new-ordinance-amendment-regulating-buyout-agreements

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type     | Render Type   |
| ======== | ============== | ================================= | =================================== | ============= | ============= |
| Yes      | series tag     | case_number                       | Case Number                         | text          | text          |
| Yes      | time           | pre_buyout_disclosure_date        | Pre Buyout Disclosure Date          | calendar_date | calendar_date |
| No       |                | date_buyout_filed                 | Date Buyout Filed                   | calendar_date | calendar_date |
| Yes      | numeric metric | buyout_amount                     | Buyout Amount                       | money         | money         |
| Yes      | numeric metric | number_of_tenants                 | Number of Tenants                   | number        | number        |
| No       |                | address                           | Address                             | text          | text          |
| Yes      | series tag     | buyout_agreement_source_zipcode   | Buyout Agreement Source Zipcode     | text          | text          |
| Yes      | series tag     | supervisor_district               | Supervisor District                 | text          | text          |
| Yes      | series tag     | neighborhoods_analysis_boundaries | Neighborhoods - Analysis Boundaries | text          | text          |
```

## Time Field

```ls
Value = pre_buyout_disclosure_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_buyout_filed,address
```

## Data Commands

```ls
series e:wmam-7g8d d:2015-03-12T00:00:00.000Z t:case_number=B150588 t:neighborhoods_analysis_boundaries="Bernal Heights" t:buyout_agreement_source_zipcode=94110 t:supervisor_district=9 m:buyout_amount=32000 m:number_of_tenants=4

series e:wmam-7g8d d:2015-03-16T00:00:00.000Z t:case_number=B150590 t:neighborhoods_analysis_boundaries="Hayes Valley" t:buyout_agreement_source_zipcode=94117 t:supervisor_district=5 m:buyout_amount=6000 m:number_of_tenants=2

series e:wmam-7g8d d:2015-03-17T00:00:00.000Z t:case_number=B150597 t:neighborhoods_analysis_boundaries="Noe Valley" t:buyout_agreement_source_zipcode=94131 t:supervisor_district=8 m:buyout_amount=54000 m:number_of_tenants=2
```

## Meta Commands

```ls
metric m:buyout_amount p:double l:"Buyout Amount" d:"Amount of buyout." t:dataTypeName=money

metric m:number_of_tenants p:integer l:"Number of Tenants" d:"Number of tenants in buyout agreement." t:dataTypeName=number

entity e:wmam-7g8d l:"Buyout agreements" t:url=https://data.sfgov.org/api/views/wmam-7g8d

property e:wmam-7g8d t:meta.view v:id=wmam-7g8d v:category="Housing and Buildings" v:averageRating=0 v:name="Buyout agreements"

property e:wmam-7g8d t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wmam-7g8d t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:wmam-7g8d t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| case_number | pre_buyout_disclosure_date | date_buyout_filed   | buyout_amount | number_of_tenants | address                       | buyout_agreement_source_zipcode | supervisor_district | neighborhoods_analysis_boundaries | 
| =========== | ========================== | =================== | ============= | ================= | ============================= | =============================== | =================== | ================================= | 
| B150587     | 2015-03-09T00:00:00        |                     |               |                   | 1200 Block Of 48th Avenue     | 94122                           | 4                   | Sunset/Parkside                   | 
| B150588     | 2015-03-12T00:00:00        | 2015-05-08T00:00:00 | 32000         | 4                 | 1300 Block Of Shotwell Street | 94110                           | 9                   | Bernal Heights                    | 
| B150590     | 2015-03-16T00:00:00        | 2015-03-18T00:00:00 | 6000          | 2                 | 600 Block Of Broderick Street | 94117                           | 5                   | Hayes Valley                      | 
| B150597     | 2015-03-17T00:00:00        | 2015-12-11T00:00:00 | 54000         | 2                 | 100 Block Of Valley Street    | 94131                           | 8                   | Noe Valley                        | 
| B150598     | 2015-03-18T00:00:00        |                     |               |                   | 3900 Block Of Cabrillo Street | 94121                           | 1                   | Outer Richmond                    | 
| B150599     | 2015-03-18T00:00:00        |                     |               |                   | 3900 Block Of Cabrillo Street | 94121                           | 1                   | Outer Richmond                    | 
| B150600     | 2015-03-18T00:00:00        |                     |               |                   | 3900 Block Of Cabrillo Street | 94121                           | 1                   | Outer Richmond                    | 
| B150601     | 2015-03-18T00:00:00        | 2015-07-07T00:00:00 | 30000         | 1                 | 3900 Block Of Cabrillo Street | 94121                           | 1                   | Outer Richmond                    | 
| B150602     | 2015-03-18T00:00:00        | 2015-07-10T00:00:00 | 26300         | 4                 | 1700 Block Of Haight Street   | 94117                           | 5                   | Haight Ashbury                    | 
| B150605     | 2015-03-23T00:00:00        |                     |               |                   | 3200 Block Of Folsom Street   | 94110                           | 9                   | Bernal Heights                    | 
```