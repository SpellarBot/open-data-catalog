# Category Page Box Content

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/category-page-box-content-76424) |
| Metadata | [Link](https://data.lacity.org/api/views/kxz5-hjdi) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/kxz5-hjdi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/kxz5-hjdi/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | kxz5-hjdi |
| Name | Category Page Box Content |
| Tags | socrata, homepage |
| Created | 2014-04-03T16:01:58Z |
| Publication Date | 2015-12-21T23:12:52Z |

## Description

This is one of several datasets used to customize the data.lacity homepage

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | category    | Category   | text      | text        |
| Yes      | numeric metric | sort        | Sort       | number    | number      |
| Yes      | series tag     | large_size  | Large size | checkbox  | checkbox    |
| Yes      | series tag     | image       | Image      | photo     | photo       |
| Yes      | series tag     | text        | Text       | html      | html        |
| Yes      | series tag     | link        | Link       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kxz5-hjdi d:2014-05-27T09:05:26.000Z t:text="<p><span>Solar Incentive Program</span></p>" t:category="A Livable and Sustainable City" t:link=https://data.lacity.org/A-Livable-and-Sustainable-City/LADWP-Solar-Incentive-Program/2yrw-q8tw t:image=tZ_7OKwN4J8SxpW_uJYPP7sOK41CSwx_7ENgZW73Kpo m:sort=3

series e:kxz5-hjdi d:2014-05-30T01:04:02.000Z t:text="<p>Port of LA Tsunami Evacuation Routes</p>" t:category="A Safe City" t:link=https://data.lacity.org/A-Safe-City/Port-of-Los-Angeles-Tsunami-Evacuation-Routes-Sign/xsnc-uga6 t:image=PQ_E1jHR6iSUAqheMYg3B-o2MdLMx98cBGrK42rGEa0 m:sort=2

series e:kxz5-hjdi d:2014-05-30T01:59:57.000Z t:text="<p>Library Usage</p>" t:category="A Well Run City" t:link=https://data.lacity.org/A-Well-Run-City/Library-Monthly-Stats/m4ev-cuzz t:image=RC1z-pQJXXbtYXAXJ9eAtYne_vR5nsWi76J52SKa8a0 m:sort=5
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

entity e:kxz5-hjdi l:"Category Page Box Content" t:url=https://data.lacity.org/api/views/kxz5-hjdi

property e:kxz5-hjdi t:meta.view v:id=kxz5-hjdi v:averageRating=0 v:name="Category Page Box Content"

property e:kxz5-hjdi t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:kxz5-hjdi t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:kxz5-hjdi t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| :updated_at | category                       | sort | large_size | image                                       | text                                                                                                                  | link                                                                                                 | 
| =========== | ============================== | ==== | ========== | =========================================== | ===================================================================================================================== | ==================================================================================================== | 
| 1401181526  | A Livable and Sustainable City | 3    |            | tZ_7OKwN4J8SxpW_uJYPP7sOK41CSwx_7ENgZW73Kpo | Solar Incentive Program                                                                                               | https://data.lacity.org/A-Livable-and-Sustainable-City/LADWP-Solar-Incentive-Program/2yrw-q8tw       | 
| 1401411842  | A Safe City                    | 2    |            | PQ_E1jHR6iSUAqheMYg3B-o2MdLMx98cBGrK42rGEa0 | Port of LA Tsunami Evacuation Routes                                                                                  | https://data.lacity.org/A-Safe-City/Port-of-Los-Angeles-Tsunami-Evacuation-Routes-Sign/xsnc-uga6     | 
| 1401415197  | A Well Run City                | 5    |            | RC1z-pQJXXbtYXAXJ9eAtYne_vR5nsWi76J52SKa8a0 | Library Usage                                                                                                         | https://data.lacity.org/A-Well-Run-City/Library-Monthly-Stats/m4ev-cuzz                              | 
| 1401462564  | A Livable and Sustainable City | 5    |            | 2Sre_cthotLAy2mvZ8JyFsQAnVKd0bfJizAN38znt7Q | Water Use by Zip Code                                                                                                 | https://data.lacity.org/A-Livable-and-Sustainable-City/Water-Use-Average-By-Zipcode/pzbs-vimf        | 
| 1450709776  | A Livable and Sustainable City | 1    | true       | PSq-PyoDebiDmwRD4Ri_v7_vpFLjf202ucqut_hdG4U | Greenhouse Gas Emissions                                                                                              | https://performance.lacity.org/en/stat/goals/yn4r-yz4i/jeid-b9sx/u8rc-u5tn                           | 
| 1450709825  | A Livable and Sustainable City | 2    |            | rInnkOTDzHne7t9TaRq0_xmB7FdyuAJ3x6Gbc355GH0 | Air Quality Measurements                                                                                              | https://performance.lacity.org/en/stat/goals/yn4r-yz4i/6bka-tmpz/cgy3-qtq2                           | 
| 1450710102  | A Well Run City                | 1    | true       | SXhnYQunvvtVcPlEWmU6ViX2K4Ui14q3yKthdf1kxBg | 311 App Adoption 
Increased use of the MyLA311 app allows for more efficient management and delivery of city services | https://data.lacity.org/dataset/ITA-Monthly-Downloads-My-LA-311-App/tsrc-szkh                        | 
| 1450710143  | A Well Run City                | 2    |            | plJwI2YonTIRHENdQMA6GTgmfcl8FQBvrjtlv55BPAo | LADWP Call Wait Time                                                                                                  | https://data.lacity.org/A-Well-Run-City/LADWP-Call-Wait-Times/2ep2-m9eh                              | 
| 1450710184  | A Well Run City                | 3    |            | u7W6BfB9V8BwdiqSFwCUd0h0i081AHAlGySNm8YexZ8 | Neighborhood Council Office Map                                                                                       | https://data.lacity.org/A-Well-Run-City/Neighborhood-Council-Office-Location-Map-with-Neig/4qre-xwjy | 
| 1450710338  | A Prosperous City              | 1    | true       | Vjk7vAld3V4cvKmTzBAXNtQq01kauhsJmianzUiPdtY | LA County Employment
  Overall employment is an important measure of our region's economic health.                    | https://data.lacity.org/A-Prosperous-City/CA-EDD-Employment-State-County-GOVSTAT/ecai-dcsz           | 
```