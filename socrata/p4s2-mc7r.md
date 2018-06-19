# Maryland Total Acres For Residential Development: 2006-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-total-acres-for-residential-development-2006-2010-a0976) |
| Metadata | [Link](https://data.maryland.gov/api/views/p4s2-mc7r) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/p4s2-mc7r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/p4s2-mc7r/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | p4s2-mc7r |
| Name | Maryland Total Acres For Residential Development: 2006-2015 |
| Attribution | Maryland Department of Planning |
| Category | Housing |
| Tags | total, acres, residential, development, planning, mdp |
| Created | 2012-12-21T17:40:29Z |
| Publication Date | 2017-05-25T14:43:10Z |

## Description

Total Acres used for Residential Development in Maryland and its jurisdictions from 2006 through and including 2015 based on MdProperty View Edition year data referenced below. 
 
2006-2012 Data Sources:
-MdProperty View 2012 Edition for all jurisdictions except Allegany and Garrett counties, which are based on MdProperty View 2011 Edition updated with August 2014 parcel data from the State Department of Assessments and Taxation. 

2013-2015 Data Sources:
-MdProperty View 2013/14 Edition parcel data for all jurisdictions in Maryland except the following: Baltimore, Caroline, Cecil, Dorchester, Harford, Kent, Queen Anne’s, Talbot, and Wicomico counties and Baltimore City, 2013/2014 Edition data updated with June 2016 parcel data from Assessments, and Anne Arundel and Carroll Counties, 2012 Edition data updated with June 2016 parcel data from Assessments. For new parcels included in the June 2016 update, parcel point placement was done via geocoding and not via placement by deed and/or plat.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | time           | date_created           | Date created           | text      | text        |
| No       |                | year                   | Year                   | number    | text        |
| Yes      | numeric metric | maryland               | MARYLAND               | number    | text        |
| Yes      | numeric metric | allegany_county        | Allegany County        | number    | text        |
| Yes      | numeric metric | anne_arundel_county    | Anne Arundel County    | number    | text        |
| Yes      | numeric metric | baltimore_city         | Baltimore City         | number    | text        |
| Yes      | numeric metric | baltimore_county       | Baltimore County       | number    | text        |
| Yes      | numeric metric | calvert_county         | Calvert County         | number    | text        |
| Yes      | numeric metric | caroline_county        | Caroline County        | number    | text        |
| Yes      | numeric metric | carroll_county         | Carroll County         | number    | text        |
| Yes      | numeric metric | cecil_county           | Cecil County           | number    | text        |
| Yes      | numeric metric | charles_county         | Charles County         | number    | text        |
| Yes      | numeric metric | dorchester_county      | Dorchester County      | number    | text        |
| Yes      | numeric metric | frederick_county       | Frederick County       | number    | text        |
| Yes      | numeric metric | garrett_county         | Garrett County         | number    | text        |
| Yes      | numeric metric | harford_county         | Harford County         | number    | text        |
| Yes      | numeric metric | howard_county          | Howard County          | number    | text        |
| Yes      | numeric metric | kent_county            | Kent County            | number    | text        |
| Yes      | numeric metric | montgomery_county      | Montgomery County      | number    | text        |
| Yes      | numeric metric | prince_george_s_county | Prince George's County | number    | text        |
| Yes      | numeric metric | queen_anne_s_county    | Queen Anne's County    | number    | text        |
| Yes      | numeric metric | somerset_county        | Somerset County        | number    | text        |
| Yes      | numeric metric | st_mary_s_county       | St. Mary's County      | number    | text        |
| Yes      | numeric metric | talbot_county          | Talbot County          | number    | text        |
| Yes      | numeric metric | washington_county      | Washington County      | number    | text        |
| Yes      | numeric metric | wicomico_county        | Wicomico County        | number    | text        |
| Yes      | numeric metric | worcester_county       | Worcester County       | number    | text        |
```

## Time Field

```ls
Value = date_created
Format & Zone = MM/dd/yyyy
```

## Series Fields

```ls
Excluded Fields = year
```

## Data Commands

```ls
series e:p4s2-mc7r d:2017-05-15T00:00:00.000Z m:howard_county=522.06 m:maryland=14362.14 m:frederick_county=908.61 m:talbot_county=316.67 m:cecil_county=403.18 m:montgomery_county=651.93 m:wicomico_county=510.55 m:charles_county=1059.03 m:baltimore_city=19.07 m:harford_county=1097.07 m:dorchester_county=287.62 m:worcester_county=487.65 m:anne_arundel_county=736.82 m:somerset_county=334.12 m:baltimore_county=1033.65 m:allegany_county=275.27 m:caroline_county=264.3 m:garrett_county=618.74 m:prince_george_s_county=1422.29 m:kent_county=124.26 m:st_mary_s_county=1049.88 m:queen_anne_s_county=277.23 m:washington_county=858.65 m:calvert_county=407.78 m:carroll_county=695.71

series e:p4s2-mc7r d:2017-05-15T00:00:00.000Z m:howard_county=355.05 m:maryland=10556.72 m:frederick_county=611.59 m:talbot_county=216.65 m:cecil_county=316.56 m:montgomery_county=529.09 m:wicomico_county=305.29 m:charles_county=553.22 m:baltimore_city=16.56 m:harford_county=710.05 m:dorchester_county=291.76 m:worcester_county=329.21 m:anne_arundel_county=620.17 m:somerset_county=250.66 m:baltimore_county=835.65 m:allegany_county=335.66 m:caroline_county=226.71 m:garrett_county=449.41 m:prince_george_s_county=1181.67 m:kent_county=147.8 m:st_mary_s_county=774.6 m:queen_anne_s_county=265.43 m:washington_county=414.39 m:calvert_county=349.13 m:carroll_county=470.43

series e:p4s2-mc7r d:2017-05-15T00:00:00.000Z m:howard_county=387.42 m:maryland=7595.09 m:frederick_county=421.74 m:talbot_county=186.63 m:cecil_county=217.91 m:montgomery_county=430.26 m:wicomico_county=225.63 m:charles_county=453.76 m:baltimore_city=16.5 m:harford_county=424.21 m:dorchester_county=190.65 m:worcester_county=183.46 m:anne_arundel_county=637 m:somerset_county=186.24 m:baltimore_county=501.17 m:allegany_county=198.19 m:caroline_county=147.43 m:garrett_county=392.55 m:prince_george_s_county=655.07 m:kent_county=64.8 m:st_mary_s_county=679.62 m:queen_anne_s_county=206.53 m:washington_county=312.62 m:calvert_county=211.4 m:carroll_county=264.32
```

## Meta Commands

```ls
metric m:maryland p:float l:MARYLAND t:dataTypeName=number

metric m:allegany_county p:float l:"Allegany County" t:dataTypeName=number

metric m:anne_arundel_county p:float l:"Anne Arundel County" t:dataTypeName=number

metric m:baltimore_city p:float l:"Baltimore City" t:dataTypeName=number

metric m:baltimore_county p:float l:"Baltimore County" t:dataTypeName=number

metric m:calvert_county p:float l:"Calvert County" t:dataTypeName=number

metric m:caroline_county p:float l:"Caroline County" t:dataTypeName=number

metric m:carroll_county p:float l:"Carroll County" t:dataTypeName=number

metric m:cecil_county p:float l:"Cecil County" t:dataTypeName=number

metric m:charles_county p:float l:"Charles County" t:dataTypeName=number

metric m:dorchester_county p:float l:"Dorchester County" t:dataTypeName=number

metric m:frederick_county p:float l:"Frederick County" t:dataTypeName=number

metric m:garrett_county p:float l:"Garrett County" t:dataTypeName=number

metric m:harford_county p:float l:"Harford County" t:dataTypeName=number

metric m:howard_county p:float l:"Howard County" t:dataTypeName=number

metric m:kent_county p:float l:"Kent County" t:dataTypeName=number

metric m:montgomery_county p:float l:"Montgomery County" t:dataTypeName=number

metric m:prince_george_s_county p:float l:"Prince George's County" t:dataTypeName=number

metric m:queen_anne_s_county p:float l:"Queen Anne's County" t:dataTypeName=number

metric m:somerset_county p:float l:"Somerset County" t:dataTypeName=number

metric m:st_mary_s_county p:float l:"St. Mary's County" t:dataTypeName=number

metric m:talbot_county p:float l:"Talbot County" t:dataTypeName=number

metric m:washington_county p:float l:"Washington County" t:dataTypeName=number

metric m:wicomico_county p:float l:"Wicomico County" t:dataTypeName=number

metric m:worcester_county p:float l:"Worcester County" t:dataTypeName=number

entity e:p4s2-mc7r l:"Maryland Total Acres For Residential Development: 2006-2015" t:attribution="Maryland Department of Planning" t:url=https://data.maryland.gov/api/views/p4s2-mc7r

property e:p4s2-mc7r t:meta.view d:2017-09-25T07:27:21.991Z v:averageRating=0 v:name="Maryland Total Acres For Residential Development: 2006-2015" v:attribution="Maryland Department of Planning" v:id=p4s2-mc7r v:category=Housing

property e:p4s2-mc7r t:meta.view.license d:2017-09-25T07:27:21.991Z v:name="Public Domain"

property e:p4s2-mc7r t:meta.view.owner d:2017-09-25T07:27:21.991Z v:displayName=MDP v:lastNotificationSeenAt=1495028713 v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:id=85mq-rt9c v:screenName=MDP v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB

property e:p4s2-mc7r t:meta.view.tableauthor d:2017-09-25T07:27:21.991Z v:displayName=MDP v:lastNotificationSeenAt=1495028713 v:profileImageUrlLarge=/api/users/85mq-rt9c/profile_images/LARGE v:roleName=editor v:profileImageUrlSmall=/api/users/85mq-rt9c/profile_images/TINY v:id=85mq-rt9c v:screenName=MDP v:profileImageUrlMedium=/api/users/85mq-rt9c/profile_images/THUMB
```

## Top Records

```ls
| date_created | year | maryland | allegany_county | anne_arundel_county | baltimore_city | baltimore_county | calvert_county | caroline_county | carroll_county | cecil_county | charles_county | dorchester_county | frederick_county | garrett_county | harford_county | howard_county | kent_county | montgomery_county | prince_george_s_county | queen_anne_s_county | somerset_county | st_mary_s_county | talbot_county | washington_county | wicomico_county | worcester_county | 
| ============ | ==== | ======== | =============== | =================== | ============== | ================ | ============== | =============== | ============== | ============ | ============== | ================= | ================ | ============== | ============== | ============= | =========== | ================= | ====================== | =================== | =============== | ================ | ============= | ================= | =============== | ================ | 
| 5/15/2017    | 2006 | 14362.14 | 275.27          | 736.82              | 19.07          | 1033.65          | 407.78         | 264.30          | 695.71         | 403.18       | 1059.03        | 287.62            | 908.61           | 618.74         | 1097.07        | 522.06        | 124.26      | 651.93            | 1422.29                | 277.23              | 334.12          | 1049.88          | 316.67        | 858.65            | 510.55          | 487.65           | 
| 5/15/2017    | 2007 | 10556.72 | 335.66          | 620.17              | 16.56          | 835.65           | 349.13         | 226.71          | 470.43         | 316.56       | 553.22         | 291.76            | 611.59           | 449.41         | 710.05         | 355.05        | 147.80      | 529.09            | 1181.67                | 265.43              | 250.66          | 774.60           | 216.65        | 414.39            | 305.29          | 329.21           | 
| 5/15/2017    | 2008 | 7595.09  | 198.19          | 637.00              | 16.50          | 501.17           | 211.40         | 147.43          | 264.32         | 217.91       | 453.76         | 190.65            | 421.74           | 392.55         | 424.21         | 387.42        | 64.80       | 430.26            | 655.07                 | 206.53              | 186.24          | 679.62           | 186.63        | 312.62            | 225.63          | 183.46           | 
| 5/15/2017    | 2009 | 5715.81  | 151.12          | 398.01              | 18.27          | 293.93           | 234.04         | 96.09           | 186.92         | 201.73       | 335.18         | 95.72             | 278.20           | 368.85         | 291.78         | 341.96        | 118.35      | 341.86            | 521.37                 | 137.74              | 100.60          | 634.55           | 115.61        | 178.69            | 157.72          | 117.52           | 
| 5/15/2017    | 2010 | 5067.32  | 119.58          | 333.24              | 9.36           | 301.86           | 223.27         | 120.02          | 179.07         | 159.28       | 359.68         | 114.44            | 273.36           | 230.14         | 379.43         | 357.85        | 45.09       | 272.91            | 380.56                 | 126.48              | 36.56           | 515.71           | 86.66         | 175.34            | 153.47          | 113.97           | 
| 5/15/2017    | 2011 | 4632.17  | 115.24          | 351.66              | 11.55          | 340.28           | 269.60         | 50.11           | 128.73         | 231.01       | 290.02         | 71.47             | 166.45           | 176.96         | 336.38         | 389.14        | 62.41       | 239.20            | 513.26                 | 94.47               | 37.97           | 334.52           | 122.46        | 110.86            | 101.08          | 87.32            | 
| 5/15/2017    | 2012 | 4544.51  | 93.28           | 377.45              | 3.99           | 292.21           | 253.82         | 39.81           | 303.46         | 157.72       | 297.85         | 57.51             | 255.43           | 251.01         | 303.67         | 376.21        | 32.23       | 210.81            | 389.66                 | 118.33              | 36.87           | 389.09           | 38.18         | 81.64             | 93.29           | 90.98            | 
| 5/15/2017    | 2013 | 5309.11  | 96.64           | 465.71              | 10.41          | 329.53           | 284.51         | 35.16           | 346.08         | 138.60       | 339.46         | 53.51             | 295.62           | 144.16         | 424.20         | 290.74        | 51.09       | 372.23            | 559.07                 | 130.81              | 33.01           | 431.16           | 66.51         | 207.08            | 106.49          | 97.34            | 
| 5/15/2017    | 2014 | 4862.29  | 32.56           | 530.66              | 8.72           | 369.48           | 237.09         | 57.22           | 251.04         | 134.85       | 428.94         | 24.98             | 285.24           | 95.72          | 242.56         | 440.91        | 41.28       | 259.48            | 459.57                 | 131.00              | 53.05           | 436.20           | 61.20         | 134.70            | 61.75           | 84.11            | 
| 5/15/2017    | 2015 | 4446.61  | 62.28           | 380.96              | 11.91          | 415.05           | 134.92         | 29.65           | 445.43         | 97.17        | 371.14         | 39.78             | 194.56           | 115.46         | 276.78         | 281.02        | 42.06       | 284.63            | 545.80                 | 107.46              | 51.03           | 193.60           | 52.16         | 126.88            | 152.63          | 34.27            | 
```