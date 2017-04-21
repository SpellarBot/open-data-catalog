# Tax Increment Financing (TIF) Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/tax-increment-financing-tif-projects) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/mex4-ppfc) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/mex4-ppfc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/mex4-ppfc/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | mex4-ppfc |
| Name | Tax Increment Financing (TIF) Projects |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | tif |
| Created | 2015-02-11T01:08:49Z |
| Publication Date | 2015-03-06T16:35:17Z |

## Description

This dataset is a comprehensive list of every project in every TIF District that has received funding from the City of Chicago via the TIF program from the inception of TIF to current. Public Infrastructure projects are not included in this dataset. For more information on the Tax Increment Financing program, please see http://cityofchicago.org/tif.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| No       |                | id                  | ID                  | text          | text          |
| Yes      | series tag     | tif_district        | TIF DISTRICT        | text          | text          |
| Yes      | series tag     | project_name        | PROJECT NAME        | text          | text          |
| No       |                | address             | ADDRESS             | text          | text          |
| Yes      | series tag     | developer           | DEVELOPER           | text          | text          |
| Yes      | series tag     | project_id          | PROJECT ID          | text          | text          |
| Yes      | series tag     | project_description | PROJECT DESCRIPTION | html          | html          |
| Yes      | time           | cdc_date            | CDC DATE            | calendar_date | calendar_date |
| Yes      | numeric metric | approved_amount     | APPROVED AMOUNT     | money         | money         |
| Yes      | numeric metric | total_project_cost  | TOTAL PROJECT COST  | money         | money         |
| No       |                | x_coordinate        | X COORDINATE        | number        | number        |
| No       |                | y_coordinate        | Y COORDINATE        | number        | number        |
| No       |                | latitude            | LATITUDE            | number        | number        |
| No       |                | longitude           | LONGITUDE           | number        | number        |
```

## Time Field

```ls
Value = cdc_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,address,x_coordinate,y_coordinate,latitude,longitude
```

## Data Commands

```ls
series e:mex4-ppfc d:2009-09-09T00:00:00.000Z t:tif_district=67th/Cicero t:project_name="IGA - CPD - Park 0484 - Madigan Fields" t:developer="Chicago Park District" t:project_id=2126 t:project_description="Intergovernmental agreement between the City of Chicago and the Chicago Park District." m:approved_amount=2824023 m:total_project_cost=2824023

series e:mex4-ppfc d:2011-01-13T00:00:00.000Z t:tif_district=Lawrence/Kedzie t:project_name="IGA - CPD - Park 0042 - Kiwanis" t:developer="Chicago Park District" t:project_id=607 t:project_description="An intergovernmental agreement between the City of Chicago and the Chicago Park District" m:approved_amount=475000 m:total_project_cost=475000

series e:mex4-ppfc d:2011-07-06T00:00:00.000Z t:tif_district="53rd Street" t:project_name="IGA - CBE - Kenwood Academy - HS" t:developer="Chicago Board of Education" t:project_id=1145 t:project_description="An intergovernmental Aggreement between the City of Chicago and the Board of Education" m:approved_amount=60000 m:total_project_cost=94110
```

## Meta Commands

```ls
metric m:approved_amount p:integer l:"APPROVED AMOUNT" t:dataTypeName=money

metric m:total_project_cost p:integer l:"TOTAL PROJECT COST" t:dataTypeName=money

entity e:mex4-ppfc l:"Tax Increment Financing (TIF) Projects" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/mex4-ppfc

property e:mex4-ppfc t:meta.view v:id=mex4-ppfc v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Tax Increment Financing (TIF) Projects" v:attribution="City of Chicago"

property e:mex4-ppfc t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:mex4-ppfc t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| id   | tif_district                  | project_name                                     | address              | developer                                                            | project_id | project_description                                                                                                                                                                                                                                                          | cdc_date            | approved_amount | total_project_cost | x_coordinate      | y_coordinate      | latitude     | longitude     | 
| ==== | ============================= | ================================================ | ==================== | ==================================================================== | ========== | ============================================================================================================================================================================================================================================================================ | =================== | =============== | ================== | ================= | ================= | ============ | ============= | 
| 1772 | 67th/Cicero                   | IGA - CPD - Park 0484 - Madigan Fields           | 4701 W 67th St       | Chicago Park District                                                | 2126       | Intergovernmental agreement between the City of Chicago and the Chicago Park District.                                                                                                                                                                                       | 2009-09-09T00:00:00 | 2824023         | 2824023            | 1146192.523820768 | 1859722.22921691  | 41.771055325 | -87.739670696 | 
| 1492 | Lawrence/Kedzie               | IGA - CPD - Park 0042 - Kiwanis                  | 3315 W Carmen Av     | Chicago Park District                                                | 607        | An intergovernmental agreement between the City of Chicago and the Chicago Park District                                                                                                                                                                                     | 2011-01-13T00:00:00 | 475000          | 475000             | 1153208.34312301  | 1933650.397940519 | 41.973786461 | -87.711991277 | 
| 1712 | 53rd Street                   | IGA - CBE - Kenwood Academy - HS                 | 5015 S Blackstone Av | Chicago Board of Education                                           | 1145       | An intergovernmental Aggreement between the City of Chicago and the Board of Education                                                                                                                                                                                       | 2011-07-06T00:00:00 | 60000           | 94110              | 1186813.04651228  | 1871954.152407077 | 41.803754791 | -87.590383945 | 
| 1756 | Western/Ogden                 | IGA - CPD - Park 0206 - Altgeld                  | 515 S Washtenaw Av   | Chicago Park District                                                | 2109       | An intergovernmental agreement between the City of Chicago and the Chicago Park District                                                                                                                                                                                     | 2012-03-31T00:00:00 | 750000          | 1762548            | 1158488.481450452 | 1897480.510131188 | 41.874426916 | -87.69356713  | 
| 1606 | Englewood Neighborhood        | IGA - CBE - Holmes - ES                          | 955 W Garfield Bv    | Chicago Board of Education                                           | 909        | INTERGOVERNMENTAL AGREEMENT BETWEEN THE CITY OF CHICAGO, BY AND THROUGH ITS DEPARTMENT OF HOUSING AND ECONOMIC DEVELOPMENT, AND THE BOARD OF EDUCATION OF THE CrTY OF CHICAGO REGARDING OLIVER WENDELL HOLMES ELEMENTARY                                                     | 2012-02-07T00:00:00 | 3270000         | 3427074.38         | 1170648.336088636 | 1868177.890625542 | 41.793760444 | -87.649777851 | 
| 1788 | Near North                    | IGA - CPD - Park ____ - W Chicago Ave Fieldhouse | 410 W Chicago Av     | Chicago Park District                                                | 2156       | WEST CHICAGO AVENUE FIELDHOUSE                                                                                                                                                                                                                                               | 2010-11-17T00:00:00 | 5000000         | 15000000           | 1173239.770529503 | 1905688.253490657 | 41.896634984 | -87.639163487 | 
| 1280 | Canal/Congress                | Quaker Oats                                      | 555 W Monroe St      | Monroe Clinton LLC                                                   | 70         | The project consists of construction of a 17-story, 450,000 square foot office building for use as Quaker Oats' headquarters including 15,000 square feet of retail space.                                                                                                   | 2000-03-14T00:00:00 | 11000000        | 88381685           | 1172558.891231282 | 1899783.806522353 | 41.880447909 | -87.641838975 | 
| 1527 | Central Loop                  | Lytton Bldg - Chicago Info Tech Exchange         | 14 E Jackson Bv      | State CITE, L.L.C.                                                   | 671        | Located in the Loop, the project consists of rehabilitation of a building for use by information technology companies. The project renovated 121,000 square feet of office space, 25,000 square feet of retail space, exterior facades, and installation of IT improvements. | 1999-02-09T00:00:00 | 8000000         | 36521000           | 1176557.491878281 | 1899045.614676228 | 41.878332921 | -87.627178969 | 
| 1336 | Northwest Industrial Corridor | Merlin Coke                                      | 1401 N Cicero Av     | MLRP-Merlin, LLC, with limited joinder by Coca-Cola Enterprises Inc. | 159        | Located in the Austin community, the project includes the complete rehabilitation of 209,000 square feet space as a distribution and office facility for Coca-Cola.                                                                                                          | 2006-02-14T00:00:00 | 3225000         | 7045345            | 1144159.234990476 | 1908913.155480153 | 41.90608046  | -87.745890879 | 
| 1651 | Bronzeville                   | IGA - CPD - Park 0267 - Dunbar                   | 300 E 31st St        | Chicago Park District                                                | 1036       | An intergovernmental agreement between the City of Chicago and the Chicago Park District                                                                                                                                                                                     | 2010-02-05T00:00:00 | 1000000         | 2000000            | 1178590.273244363 | 1884545.28966343  | 41.838496977 | -87.620157381 | 
```