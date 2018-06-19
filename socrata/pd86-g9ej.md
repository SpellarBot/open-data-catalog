# Home Page - Featured Datasets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/home-page-featured-datasets-aeead) |
| Metadata | [Link](https://data.lacity.org/api/views/pd86-g9ej) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/pd86-g9ej/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/pd86-g9ej/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | pd86-g9ej |
| Name | Home Page - Featured Datasets |
| Tags | socrata, homepage |
| Created | 2014-04-01T23:47:36Z |
| Publication Date | 2014-05-31T14:51:19Z |

## Description

This is one of several datasets used to customize the data.lacity homepage

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | sort        | Sort       | number    | number      |
| Yes      | series tag     | title       | Title      | text      | text        |
| Yes      | series tag     | body        | Body       | text      | text        |
| Yes      | series tag     | link        | Link       | url       | url         |
| Yes      | series tag     | image       | Image      | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:pd86-g9ej d:2014-05-28T18:43:23.000Z t:body="The home of the U.S. Government?s open data Here you will find data, tools, and resources to conduct research, develop web and mobile applications, design data visualizations, and more." t:title="US Open Data (data.gov)" t:link=http://www.data.gov t:image=ZXIABkmyXkWfOhzR9QmEU3tjCuYNq9u1qSdHEdevRwY m:sort=1

series e:pd86-g9ej d:2014-05-28T18:43:31.000Z t:body="The State of California was one of the first states to launch an open data repository. Data.CA.gov was designed to provide a single source of raw data in the state. By posting state government data in raw, machine-readable formats, it can be reformatted and reused in different ways, allowing the public greater access to build custom applications in order to analyze and display the information. Data.CA.gov provides information and raw data on the economy, public health, transportation, environment, and more on this single website." t:title="California Open Data (data.CA.gov)" t:link=http://data.ca.gov t:image=eiB9A_DQv83d51yoNQgBPrVi21lamBvdwoLVSSjTUeQ m:sort=2

series e:pd86-g9ej d:2014-05-28T18:43:45.000Z t:body="The LA County GIS Data Portal is a rapidly growing resource where you can download shapefiles and get information about the County?s data holdings." t:title="LA County Open Data" t:link=http://egis3.lacounty.gov/dataportal/ t:image=Hpp-hPbqvHMuYvVJm8OPQf5LeNHfHULvh_eVCvqf5d0 m:sort=3
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

entity e:pd86-g9ej l:"Home Page - Featured Datasets" t:url=https://data.lacity.org/api/views/pd86-g9ej

property e:pd86-g9ej t:meta.view v:id=pd86-g9ej v:averageRating=0 v:name="Home Page - Featured Datasets"

property e:pd86-g9ej t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:pd86-g9ej t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:pd86-g9ej t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | sort | title                              | body                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | link                                                            | image                                       | 
| =========== | ==== | ================================== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | =============================================================== | =========================================== | 
| 1401302603  | 1    | US Open Data (data.gov)            | The home of the U.S. Government?s open data Here you will find data, tools, and resources to conduct research, develop web and mobile applications, design data visualizations, and more.                                                                                                                                                                                                                                                                                                                                                               | [http://www.data.gov, US Data]                                  | ZXIABkmyXkWfOhzR9QmEU3tjCuYNq9u1qSdHEdevRwY | 
| 1401302611  | 2    | California Open Data (data.CA.gov) | The State of California was one of the first states to launch an open data repository. Data.CA.gov was designed to provide a single source of raw data in the state. By posting state government data in raw, machine-readable formats, it can be reformatted and reused in different ways, allowing the public greater access to build custom applications in order to analyze and display the information. Data.CA.gov provides information and raw data on the economy, public health, transportation, environment, and more on this single website. | [http://data.ca.gov, California Data]                           | eiB9A_DQv83d51yoNQgBPrVi21lamBvdwoLVSSjTUeQ | 
| 1401302625  | 3    | LA County Open Data                | The LA County GIS Data Portal is a rapidly growing resource where you can download shapefiles and get information about the County?s data holdings.                                                                                                                                                                                                                                                                                                                                                                                                     | [http://egis3.lacounty.gov/dataportal/, LA County Data]         | Hpp-hPbqvHMuYvVJm8OPQf5LeNHfHULvh_eVCvqf5d0 | 
| 1401522670  | 4    | ControlPanel.LA                    | Financial Data for the City of LA including salaries and expenditures from the Office of the Controller                                                                                                                                                                                                                                                                                                                                                                                                                                                 | [https://controllerdata.lacity.org/, City of LA Financial Data] | fFzBDnOXagqCWwB0eQ2R2Ir3yy1NpaobWz4MfuYWKbw | 
```