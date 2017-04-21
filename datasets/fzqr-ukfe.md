# SSMMA TIF District

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ssmma-tif-district-b4f0f) |
| Metadata | [Link](https://data.illinois.gov/api/views/fzqr-ukfe) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fzqr-ukfe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fzqr-ukfe/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fzqr-ukfe |
| Name | SSMMA TIF District |
| Attribution | South Suburban Mayors and Managers Association |
| Category | Municipality |
| Tags | economic development, planning |
| Created | 2012-11-27T19:25:19Z |
| Publication Date | 2012-11-27T19:27:06Z |

## Description

This dataset contains a listing of all TIF Districts in the Chicago Southland region.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag     | agency      | AGENCY     | text      | number      |
| Yes      | series tag     | agency_des  | AGENCY_DES | text      | text        |
| Yes      | numeric metric | agencynum   | AGENCYNUM  | number    | number      |
| Yes      | numeric metric | first_tax   | First_Tax_ | number    | number      |
| Yes      | numeric metric | current_ye  | Current_Ye | money     | money       |
| Yes      | numeric metric | past_year   | Past_Year_ | money     | money       |
| Yes      | numeric metric | difference  | Difference | percent   | percent     |
| Yes      | series tag     | municipali  | Municipali | text      | text        |
| Yes      | series tag     | county      | County     | text      | text        |
| Yes      | series tag     | editor      | Editor     | text      | text        |
| Yes      | numeric metric | propreitar  | Propreitar | number    | number      |
| Yes      | series tag     | universal   | Universal_ | text      | text        |
| Yes      | numeric metric | shape_leng  | SHAPE_Leng | number    | number      |
| Yes      | numeric metric | shape_area  | SHAPE_Area | number    | number      |
| Yes      | series tag     | contact_na  | Contact_Na | text      | text        |
| Yes      | series tag     | website     | Website    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fzqr-ukfe d:2012-11-27T11:25:21.000Z t:agency_des="TIF CITY OF DES PLAINES - MANNHEIM/HIGGINS" t:website=http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf t:agency=6583 t:universal=2 t:objectid=2 m:shape_area=1073889.64856 m:agencynum=30290501 m:shape_leng=9740.75195915 m:propreitar=2

series e:fzqr-ukfe d:2012-11-27T11:25:21.000Z t:contact_na=Staff-(312)-744-4190 t:agency_des="TIF CITY OF CHICAGO - LAKE CALUMET" t:editor=MJR t:county=Cook t:website=http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Chicago-B.pdf t:agency=6594 t:universal=3 t:objectid=3 t:municipali=Chicago m:past_year=4213233.15 m:shape_area=343023361.77 m:current_ye=3512990.82 m:agencynum=30210562 m:shape_leng=235866.384139 m:first_tax=2001 m:propreitar=3

series e:fzqr-ukfe d:2012-11-27T11:25:21.000Z t:agency_des="TIF CITY OF CHICAGO - 95TH ST/STONY ISLAND" t:website=http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf t:agency=6646 t:universal=4 t:objectid=4 m:shape_area=4191633.30336 m:agencynum=30210520 m:shape_leng=16754.1533123 m:propreitar=4
```

## Meta Commands

```ls
metric m:agencynum p:integer l:AGENCYNUM t:dataTypeName=number

metric m:first_tax p:integer l:First_Tax_ t:dataTypeName=number

metric m:current_ye p:double l:Current_Ye t:dataTypeName=money

metric m:past_year p:double l:Past_Year_ t:dataTypeName=money

metric m:difference p:float l:Difference t:dataTypeName=percent

metric m:propreitar p:integer l:Propreitar t:dataTypeName=number

metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

metric m:shape_area p:double l:SHAPE_Area t:dataTypeName=number

entity e:fzqr-ukfe l:"SSMMA TIF District" t:attribution="South Suburban Mayors and Managers Association" t:url=https://data.illinois.gov/api/views/fzqr-ukfe

property e:fzqr-ukfe t:meta.view v:id=fzqr-ukfe v:category=Municipality v:attributionLink=http://www.ssmma.org v:averageRating=0 v:name="SSMMA TIF District" v:attribution="South Suburban Mayors and Managers Association"

property e:fzqr-ukfe t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:fzqr-ukfe t:meta.view.owner v:id=p88s-rkzf v:profileImageUrlMedium=/api/users/p88s-rkzf/profile_images/THUMB v:profileImageUrlLarge=/api/users/p88s-rkzf/profile_images/LARGE v:screenName=mrizzitiello v:profileImageUrlSmall=/api/users/p88s-rkzf/profile_images/TINY v:displayName=mrizzitiello

property e:fzqr-ukfe t:meta.view.tableauthor v:id=2fjt-8tt3 v:screenName=data.il.admin v:displayName=data.il.admin
```

## Top Records

```ls
| :updated_at | objectid | agency | agency_des                                 | agencynum | first_tax | current_ye | past_year  | difference | municipali | county | editor | propreitar | universal | shape_leng    | shape_area    | contact_na                        | website                                                                                        | 
| =========== | ======== | ====== | ========================================== | ========= | ========= | ========== | ========== | ========== | ========== | ====== | ====== | ========== | ========= | ============= | ============= | ================================= | ============================================================================================== | 
| 1354015521  | 2        | 6583   | TIF CITY OF DES PLAINES - MANNHEIM/HIGGINS | 30290501  |           |            |            |            |            |        |        | 2          | 2         | 9740.75195915 | 1073889.64856 |                                   | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
| 1354015521  | 3        | 6594   | TIF CITY OF CHICAGO - LAKE CALUMET         | 30210562  | 2001      | 3512990.82 | 4213233.15 |            | Chicago    | Cook   | MJR    | 3          | 3         | 235866.384139 | 343023361.77  | Staff-(312)-744-4190              | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Chicago-B.pdf  | 
| 1354015521  | 4        | 6646   | TIF CITY OF CHICAGO - 95TH ST/STONY ISLAND | 30210520  |           |            |            |            |            |        |        | 4          | 4         | 16754.1533123 | 4191633.30336 |                                   | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
| 1354015521  | 5        | 6676   | TIF CITY OF HARVEY - RPM BUSINESS PARK     | 30510503  | 2000      | 29496.93   | 29170.11   | 1.12       | Harvey     | Cook   | MJR    | 5          | 5         | 6018.56540908 | 1875691.80011 | Ms. LaTonya Rufus-(708)-210-5346  | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
| 1354015521  | 6        | 6677   | TIF VIL OF HOMEWOOD - 187TH ST/DIXIE HWY   | 60600502  | 2000      | 8793.93    | 108913.71  | -91.93     | Homewood   | Cook   | MJR    | 6          | 6         | 5059.09054184 | 323872.255058 | Ms. Paula Wallrich-(708)-206-3385 | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
| 1354015521  | 7        | 6683   | TIF CITY OF CHICAGO-JEFFERSON/ROOSEVELT    | 30210560  |           |            |            |            |            |        |        | 7          | 7         | 18405.6884352 | 6591814.08405 |                                   | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
| 1354015521  | 8        | 6696   | TIF CITY OF CHICAGO - SOUTH CHICAGO        | 30210596  |           |            |            |            |            |        |        | 8          | 8         | 40283.0197376 | 15381640.259  |                                   | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
| 1354015521  | 9        | 6697   | TIF VIL OF FRANKLIN PARK - O'HARE EAST     | 30450506  |           |            |            |            |            |        |        | 9          | 9         | 6859.03100645 | 1637721.6291  |                                   | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
| 1354015521  | 10       | 6699   | TIF CITY OF CHICAGO - MONTCLARE            | 30210571  |           |            |            |            |            |        |        | 10         | 10        | 3626.70487646 | 496755.353853 |                                   | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
| 1354015521  | 11       | 6709   | TIF CITY OF CHICAGO - CENTRAL WEST         | 30210534  |           |            |            |            |            |        |        | 11         | 11        | 45917.5301827 | 19692225.5672 |                                   | http://www.cookcountyclerk.com/tsd/DocumentLibrary/TIF%20Revenue%20Rpt%202010%20Suburban-C.pdf | 
```