# County Agricultural Districts Profile

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-agricultural-districts-profile) |
| Metadata | [Link](https://data.ny.gov/api/views/9bc8-mx4a) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/9bc8-mx4a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/9bc8-mx4a/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 9bc8-mx4a |
| Name | County Agricultural Districts Profile |
| Attribution | New York State Department of Agriculture and Markets (DAM) |
| Category | Economic Development |
| Tags | agricultural districts, acres farmed, farmland |
| Created | 2014-12-10T18:00:56Z |
| Publication Date | 2016-02-05T15:43:25Z |

## Description

The Agricultural Districts Profile summary is a county listing that identifies the agricultural district number and names of towns within each district. Each district listing includes: creation date, anniversay date, total acres, farmed acres, cropped acres, acres owned, rented acres and number of farms.  This dataset will be updated in January of each year. The Agricultural District Profile Data Summary is  found at the following link:http://www.agriculture.ny.gov/AP/agservices/agdistricts.html. The Agricultural District Profile contains a listing of each county participating in the New York State Department of Agriculture and Markets (DAM) Agricultural District program. Agricultural districts have been created in 53 of New York?s 62 counties. Participation in the Agricultural District program is landowner initiated and represents a local mechanism for the protection and enhancement of farmlands as a viable segment of the local and state economies.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                                   | Data Type     | Render Type   |
| ======== | ============== | ============================ | ====================================== | ============= | ============= |
| Yes      | series tag     | county                       | County                                 | text          | text          |
| Yes      | series tag     | agricultural_district_number | Agricultural District Number           | text          | number        |
| Yes      | time           | creation_date                | Creation Date                          | calendar_date | calendar_date |
| No       |                | anniversary_date             | Anniversary Date                       | calendar_date | calendar_date |
| Yes      | series tag     | towns_affected               | Towns Affected                         | text          | text          |
| Yes      | numeric metric | total_acres                  | Total Acres in Agricultural Districts  | number        | number        |
| Yes      | numeric metric | farmed_acres                 | Farmed Acres in Agricultural Districts | number        | number        |
| Yes      | numeric metric | cropped_acres                | Cropped Acres                          | number        | number        |
| Yes      | numeric metric | acres_owned                  | Acres Owned                            | number        | number        |
| Yes      | numeric metric | acres_rented                 | Acres Rented                           | number        | number        |
| Yes      | numeric metric | number_of_farms              | Number of Farms                        | number        | number        |
```

## Time Field

```ls
Value = creation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = anniversary_date
```

## Data Commands

```ls
series e:9bc8-mx4a d:1974-07-29T00:00:00.000Z t:county=ALBANY t:towns_affected="BERNE, KNOX" t:agricultural_district_number=1 m:farmed_acres=27739 m:total_acres=27739 m:cropped_acres=6500 m:acres_rented=2417 m:acres_owned=25322 m:number_of_farms=70

series e:9bc8-mx4a d:1977-02-13T00:00:00.000Z t:county=ALBANY t:towns_affected="WESTERLO, RENSSELAERVILLE & BERNE" t:agricultural_district_number=2 m:farmed_acres=9858 m:total_acres=17719 m:cropped_acres=2153 m:acres_rented=2925 m:acres_owned=6933 m:number_of_farms=60

series e:9bc8-mx4a d:1977-02-22T00:00:00.000Z t:county=ALBANY t:towns_affected="GUILDERLAND, BETHLEHEM, NEW SCOTLAND, COEYMANS, COLONIE & CITY OF COHOES" t:agricultural_district_number=3 m:farmed_acres=24162 m:total_acres=26594 m:cropped_acres=6274 m:acres_rented=3679 m:acres_owned=21291 m:number_of_farms=131
```

## Meta Commands

```ls
metric m:total_acres p:float l:"Total Acres in Agricultural Districts" d:"Total acres in the agricultural districts only (does not include acreage that is not within an agricultural district). A blank means the data was not provided by the county." t:dataTypeName=number

metric m:farmed_acres p:float l:"Farmed Acres in Agricultural Districts" d:"Total acres farmed in agricultural districts. A blank means the data was not provided by the county." t:dataTypeName=number

metric m:cropped_acres p:float l:"Cropped Acres" d:"Total acres with crops planted in district. A blank means the data was not provided by the county." t:dataTypeName=number

metric m:acres_owned p:float l:"Acres Owned" d:"Total acres owned by a farmer. A blank means the data was not provided by the county." t:dataTypeName=number

metric m:acres_rented p:float l:"Acres Rented" d:"Total acres rented by a farmer. A blank means the data was not provided by the county." t:dataTypeName=number

metric m:number_of_farms p:float l:"Number of Farms" d:"Count of farms in district. A blank means the data was not provided by the county." t:dataTypeName=number

entity e:9bc8-mx4a l:"County Agricultural Districts Profile" t:attribution="New York State Department of Agriculture and Markets (DAM)" t:url=https://data.ny.gov/api/views/9bc8-mx4a

property e:9bc8-mx4a t:meta.view v:id=9bc8-mx4a v:category="Economic Development" v:attributionLink=http://www.agriculture.ny.gov/AP/agservices/agdistricts.html v:averageRating=0 v:name="County Agricultural Districts Profile" v:attribution="New York State Department of Agriculture and Markets (DAM)"

property e:9bc8-mx4a t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:9bc8-mx4a t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:9bc8-mx4a t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county   | agricultural_district_number | creation_date       | anniversary_date    | towns_affected                                                                                                                       | total_acres | farmed_acres | cropped_acres | acres_owned | acres_rented | number_of_farms | 
| ======== | ============================ | =================== | =================== | ==================================================================================================================================== | =========== | ============ | ============= | =========== | ============ | =============== | 
| ALBANY   | 1                            | 1974-07-29T00:00:00 | 2022-07-29T00:00:00 | BERNE, KNOX                                                                                                                          | 27739.00    | 27739.00     | 6500.00       | 25322.00    | 2417.00      | 70.00           | 
| ALBANY   | 2                            | 1977-02-13T00:00:00 | 2017-02-13T00:00:00 | WESTERLO, RENSSELAERVILLE & BERNE                                                                                                    | 17719.00    | 9858.00      | 2153.00       | 6933.00     | 2925.00      | 60.00           | 
| ALBANY   | 3                            | 1977-02-22T00:00:00 | 2019-02-22T00:00:00 | GUILDERLAND, BETHLEHEM, NEW SCOTLAND, COEYMANS, COLONIE & CITY OF COHOES                                                             | 26594.00    | 24162.00     | 6274.00       | 21291.00    | 3679.00      | 131.00          | 
| ALLEGANY | 1                            | 1976-04-05T00:00:00 | 2016-04-05T00:00:00 | ALLEN, BIRDSALL,CANEADEA, CENTERVILLE, GRANGER, HUME, NEW HUDSON, RUSHFORD & GROVE                                                   | 52712.00    | 36494.00     | 24438.00      | 31837.00    | 4657.00      | 100.00          | 
| ALLEGANY | 2                            | 1982-06-10T00:00:00 | 2022-06-10T00:00:00 | ALLEN, ALMOND, AMITY, ANDOVER, ANGELICA, BELFAST, BIRDSALL, CLARKSVILLE, CUBA, FRIENDSHIP, SCIO, WARD, WEST ALMOND, WELLSVILLE, WIRT | 32632.00    | 18646.00     | 15585.00      | 12345.00    | 6179.00      | 85.00           | 
| ALLEGANY | 3                            | 1979-10-07T00:00:00 | 2019-10-07T00:00:00 | ALMOND, BIRDSALL, BURNS, GROVE, VILLAGE OF CANASERAGA                                                                                | 15565.00    | 11137.00     | 8003.00       | 7963.00     | 3174.00      | 45.00           | 
| ALLEGANY | 4                            | 1977-08-07T00:00:00 | 2017-08-07T00:00:00 | ALFRED, ALMA, ANDOVER, BOLIVAR, GENESEE, INDEPENDENCE, WARD, WILLING                                                                 | 17995.00    | 12725.00     |               | 11152.00    | 1573.00      | 65.00           | 
| BROOME   | 3                            | 1975-12-10T00:00:00 | 2015-12-10T00:00:00 | SANFORD                                                                                                                              | 14537.00    | 9449.00      | 1342.00       | 8762.00     | 687.00       | 23.00           | 
| BROOME   | 4                            | 1976-06-24T00:00:00 | 2016-09-24T00:00:00 | BINGHAMTON, CHENANGO, COLESVILLE, CONKLIN, FENTON, KIRKWOOD, MAINE, UNION, SANFORD, WINDSOR                                          | 63997.00    | 41958.00     | 35664.00      | 27272.00    | 13856.00     | 168.00          | 
| BROOME   | 5                            | 1979-01-11T00:00:00 | 2019-01-11T00:00:00 | BARKER, CHENANGO, LISLE, MAINE, NANTICOKE, TRIANGLE                                                                                  | 71604.00    | 49316.00     | 22078.00      | 26526.00    | 7790.00      | 142.00          | 
```