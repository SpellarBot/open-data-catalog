# Legally Operating Businesses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/legally-operating-businesses-93b76) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/w7w3-xahh) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/w7w3-xahh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/w7w3-xahh/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | w7w3-xahh |
| Name | Legally Operating Businesses |
| Attribution | Department of Consumer Affairs (DCA) |
| Category | Business |
| Tags | city government, business, dca, department of consumer affairs, license |
| Created | 2015-03-06T21:01:28Z |
| Publication Date | 2016-10-17T21:06:38Z |

## Description

This data set features businesses/individuals holding a DCA license so that they may legally operate in New York City. Note: Sightseeing guides and temporary street fair vendors are not included in this data set.

## Columns

```ls
| Included | Schema Type | Field Name            | Name                          | Data Type     | Render Type   |
| ======== | =========== | ===================== | ============================= | ============= | ============= |
| Yes      | series tag  | license_nbr           | DCA License Number            | text          | text          |
| Yes      | series tag  | license_type          | License Type                  | text          | text          |
| Yes      | time        | lic_expir_dd          | License Expiration Date       | calendar_date | calendar_date |
| Yes      | series tag  | license_category      | License Category              | text          | text          |
| Yes      | series tag  | business_name         | Business Name                 | text          | text          |
| Yes      | series tag  | business_name_2       | Business Name 2               | text          | text          |
| No       |             | address_building      | Address Building              | text          | text          |
| Yes      | series tag  | address_street_name   | Address Street Name           | text          | text          |
| Yes      | series tag  | address_street_name_2 | Secondary Address Street Name | text          | text          |
| No       |             | address_city          | Address City                  | text          | text          |
| No       |             | address_state         | Address State                 | text          | text          |
| No       |             | address_zip           | Address ZIP                   | text          | text          |
| Yes      | series tag  | contact_phone         | Contact Phone Number          | text          | text          |
| No       |             | address_borough       | Address Borough               | text          | text          |
| Yes      | series tag  | detail                | Detail                        | text          | text          |
| No       |             | longitude             | Longitude                     | number        | text          |
| No       |             | latitude              | Latitude                      | number        | text          |
```

## Time Field

```ls
Value = lic_expir_dd
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_building,address_city,address_state,address_zip,address_borough,longitude,latitude
```

## Data Commands

```ls
series e:w7w3-xahh d:2017-07-31T00:00:00.000Z t:business_name="GOLD CITY OF 181, INC." t:license_nbr=1383112-DCA t:license_type=Business t:address_street_name="FLATBUSH AVE" t:contact_phone=718-825-5296 t:license_category="Secondhand Dealer - General" m:row_number.w7w3-xahh=1

series e:w7w3-xahh d:2017-12-31T00:00:00.000Z t:business_name="J & H FRENCH CLEANERS INC." t:license_nbr=2036980-DCA t:license_type=Business t:address_street_name="CHURCH AVE" t:contact_phone=7182874040 t:license_category="Laundry Jobber" m:row_number.w7w3-xahh=2

series e:w7w3-xahh d:2017-09-30T00:00:00.000Z t:business_name="HOWARD, HENRY E." t:license_nbr=1298647-DCA t:license_type=Individual t:address_street_name="REMINGTON PL" t:contact_phone=9144970435 t:license_category="General Vendor" m:row_number.w7w3-xahh=3
```

## Meta Commands

```ls
metric m:row_number.w7w3-xahh p:long l:"Row Number"

entity e:w7w3-xahh l:"Legally Operating Businesses" t:attribution="Department of Consumer Affairs (DCA)" t:url=https://data.cityofnewyork.us/api/views/w7w3-xahh

property e:w7w3-xahh t:meta.view v:id=w7w3-xahh v:category=Business v:averageRating=0 v:name="Legally Operating Businesses" v:attribution="Department of Consumer Affairs (DCA)"

property e:w7w3-xahh t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:w7w3-xahh t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| license_nbr | license_type | lic_expir_dd        | license_category             | business_name                 | business_name_2    | address_building | address_street_name | address_street_name_2 | address_city  | address_state | address_zip | contact_phone | address_borough | detail | longitude          | latitude          | 
| =========== | ============ | =================== | ============================ | ============================= | ================== | ================ | =================== | ===================== | ============= | ============= | =========== | ============= | =============== | ====== | ================== | ================= | 
| 1383112-DCA | Business     | 2017-07-31T00:00:00 | Secondhand Dealer - General  | GOLD CITY OF 181, INC.        |                    | 859              | FLATBUSH AVE        |                       | BROOKLYN      | NY            | 11226       | 718-825-5296  | Brooklyn        |        | -73.95895964189803 | 40.65139829818225 | 
| 2036980-DCA | Business     | 2017-12-31T00:00:00 | Laundry Jobber               | J & H FRENCH CLEANERS INC.    |                    | 3011             | CHURCH AVE          |                       | BROOKLYN      | NY            | 11226       | 7182874040    | Brooklyn        |        | -73.94935588173706 | 40.65082630019566 | 
| 1298647-DCA | Individual   | 2017-09-30T00:00:00 | General Vendor               | HOWARD, HENRY E.              |                    | 140              | REMINGTON PL        |                       | NEW ROCHELLE  | NY            | 10801       | 9144970435    |                 |        |                    |                   | 
| 2044869-DCA | Individual   | 2019-02-28T00:00:00 | Home Improvement Salesperson | li, kun                       |                    | 6357             | DOUGLASTON PKWY     |                       | LITTLE NECK   | NY            | 11362       | 4152154872    |                 |        |                    |                   | 
| 0953009-DCA | Individual   | 2018-02-28T00:00:00 | Process Server Individual    | EDGE, JAMES T                 |                    | 10               | PARSONS DR          |                       | DIX HILLS     | NY            | 11746       | 5162203161    |                 |        |                    |                   | 
| 1457600-DCA | Individual   | 2019-02-28T00:00:00 | Home Improvement Salesperson | TANZI, PATRICK                |                    | 229              | ARLENE ST           |                       | STATEN ISLAND | NY            | 10314       | 7326624017    |                 |        |                    |                   | 
| 2047173-DCA | Business     | 2017-07-31T00:00:00 | Secondhand Dealer - General  | ELITE BULLION CORP            |                    | 41               | W 47TH ST           |                       | NEW YORK      | NY            | 10036       | 6466101834    | Manhattan       |        | -73.97996698547324 | 40.75725846263866 | 
| 1095462-DCA | Business     | 2019-02-28T00:00:00 | Home Improvement Contractor  | SUPER EAGLE CONTRACTING, INC. |                    | 3132             | 86TH ST             |                       | EAST ELMHURST | NY            | 11369       | 7183924050    | Queens          |        | -73.88222074444559 | 40.75903623056475 | 
| 2005211-DCA | Business     | 2017-02-28T00:00:00 | Home Improvement Contractor  | BEES HIVE ENTERPRISE INC.     |                    | 42               | STEPHENS CT         |                       | BROOKLYN      | NY            | 11226       | 3472994831    | Brooklyn        |        | -73.95475526302867 | 40.63887501302433 | 
| 1166574-DCA | Business     | 2017-12-31T00:00:00 | Laundry                      | ROMA LAUNDRY, INC.            | ROMA LAUNDRY, INC. | 2020             | FRANCIS LEWIS BLVD  |                       | WHITESTONE    | NY            | 11357       | 7187469721    | Queens          |        | -73.80232060342692 | 40.77986101735039 | 
```