# TLC Luxury Limousine Bases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tlc-luxury-limousine-bases-45f9c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qahe-qhzp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qahe-qhzp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qahe-qhzp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qahe-qhzp |
| Name | TLC Luxury Limousine Bases |
| Attribution | Taxi and Limousine Commission (TLC) |
| Category | Transportation |
| Tags | spreadsheet of all tlc luxury limousine bases |
| Created | 2011-08-26T20:06:51Z |
| Publication Date | 2011-08-26T20:06:51Z |

## Description

Spreadsheet of all TLC luxury limousine bases

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type | Render Type |
| ======== | =========== | ============================ | ============================ | ========= | =========== |
| No       | time        | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag  | license_number               | License Number               | text      | text        |
| Yes      | series tag  | name_of_licensee             | Name of Licensee             | text      | text        |
| Yes      | series tag  | alternative_name_of_licensee | Alternative Name of Licensee | text      | text        |
| Yes      | series tag  | street_address               | Street_Address               | text      | text        |
| Yes      | series tag  | zip_code                     | Zip_Code                     | text      | number      |
| Yes      | series tag  | telephone                    | Telephone                    | text      | text        |
| Yes      | series tag  | license_type                 | License Type                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qahe-qhzp d:2011-08-26T13:06:52.000Z t:license_type="License Type" t:license_number="License Number" t:street_address=Street_Address t:name_of_licensee="Name of Licensee" t:telephone=Telephone t:alternative_name_of_licensee="Alternative Name of Licensee" m:row_number.qahe-qhzp=1

series e:qahe-qhzp d:2011-08-26T13:06:52.000Z t:license_type="TLC-licensed base (FHV, Commuter Van, or Para)" t:zip_code=11101 t:license_number=B00001 t:street_address="40-14 23 STREET" t:name_of_licensee="LONDON TOWNCARS INC" t:telephone=718-786-9700 m:row_number.qahe-qhzp=2

series e:qahe-qhzp d:2011-08-26T13:06:52.000Z t:license_type="TLC-licensed base (FHV, Commuter Van, or Para)" t:zip_code=10011 t:license_number=B00039 t:street_address="537 WEST   20 STREET" t:name_of_licensee="BERMUDA LIMOUSINE SERVICE INC." t:telephone=212-249-8400 m:row_number.qahe-qhzp=3
```

## Meta Commands

```ls
metric m:row_number.qahe-qhzp p:long l:"Row Number"

entity e:qahe-qhzp l:"TLC Luxury Limousine Bases" t:attribution="Taxi and Limousine Commission (TLC)" t:url=https://data.cityofnewyork.us/api/views/qahe-qhzp

property e:qahe-qhzp t:meta.view v:id=qahe-qhzp v:category=Transportation v:averageRating=0 v:name="TLC Luxury Limousine Bases" v:attribution="Taxi and Limousine Commission (TLC)"

property e:qahe-qhzp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qahe-qhzp t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | license_number | name_of_licensee               | alternative_name_of_licensee | street_address          | zip_code | telephone    | license_type                                   | 
| =========== | ============== | ============================== | ============================ | ======================= | ======== | ============ | ============================================== | 
| 1314364012  | License Number | Name of Licensee               | Alternative Name of Licensee | Street_Address          |          | Telephone    | License Type                                   | 
| 1314364012  | B00001         | LONDON TOWNCARS INC            |                              | 40-14 23 STREET         | 11101    | 718-786-9700 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314364012  | B00039         | BERMUDA LIMOUSINE SERVICE INC. |                              | 537 WEST 20 STREET      | 10011    | 212-249-8400 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314364012  | B00078         | R & R ROAD LIMO SVCE INC       |                              | 865 EAST 138 STREET     | 10454    | 718-585-8500 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314364012  | B00084         | AUTOMOTIVE SVC SYSTEM INC      |                              | 447 WEST 36 STREET      | 10018    | 212-966-6400 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314364012  | B00207         | E.R.A. LIMO SVC LTD.           |                              | 23-50 WATERS EDGE DRIVE | 11360    | 718-279-3723 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314364012  | B00208         | ERNEST SCHWARZ INC             |                              | 15 CHAIN LANE           | 11801    | 516-287-5550 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314364012  | B00227         | PARK WEST EXEC. SERVICES, INC. | TOWN CARS                    | 36-36 33 STREET 3RD FL  | 11106    | 212-727-7800 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314364012  | B00370         | DAV-EL SERVICES INC            |                              | 42-32 21 STREET         | 11101    | 718-729-2400 | TLC-licensed base (FHV, Commuter Van, or Para) | 
| 1314364012  | B00387         | FORTUNE LIMOUSINES INC         |                              | 25-15 23 STREET         | 11102    | 718-729-6800 | TLC-licensed base (FHV, Commuter Van, or Para) | 
```