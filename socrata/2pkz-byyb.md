# Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part B

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/demographic-projection-report-enrollment-projections-new-york-city-public-schools-prepared-11a12) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2pkz-byyb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2pkz-byyb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2pkz-byyb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2pkz-byyb |
| Name | Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part B |
| Attribution | School Construction Authority (SCA) |
| Category | Housing & Development |
| Tags | school, construction, authority, sca, demographic projection, part b, lifelong learning |
| Created | 2013-03-06T15:18:55Z |
| Publication Date | 2013-06-21T20:48:51Z |

## Description

The SCA?s comprehensive capital planning process includes developing and analyzing quality data, creating and updating the Department of Education?s Five-Year Capital Plans, and monitoring projects through completion. The SCA prioritizes capital projects to best meet the capacity and building improvements needs throughout the City.  Additionally, the SCA assures that the Capital Plan aligns with New York State and City Department of Education mandates, academic initiatives, and budgetary resources.  This is one of the most current published reports.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | district    | District   | text      | text        |
| Yes      | series tag     | grade       | Grade      | text      | text        |
| Yes      | numeric metric | 2008        | 2008       | number    | text        |
| Yes      | numeric metric | 2009        | 2009       | number    | text        |
| Yes      | numeric metric | 2010        | 2010       | number    | text        |
| Yes      | numeric metric | 2011        | 2011       | number    | text        |
| Yes      | numeric metric | 2012        | 2012       | number    | text        |
| Yes      | numeric metric | 2013        | 2013       | number    | text        |
| Yes      | numeric metric | 2014        | 2014       | number    | text        |
| Yes      | numeric metric | 2015        | 2015       | number    | text        |
| Yes      | numeric metric | 2016        | 2016       | number    | text        |
| Yes      | numeric metric | 2017        | 2017       | number    | text        |
| Yes      | numeric metric | 2018        | 2018       | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:2pkz-byyb d:2013-03-06T07:19:29.000Z t:grade=PRE-K t:district=1 m:2008=1163 m:2017=1332 m:2009=1085 m:2018=1349 m:2013=1239 m:2014=1261 m:2015=1283 m:2016=1305 m:2012=1217 m:2011=1195 m:2010=1136

series e:2pkz-byyb d:2013-03-06T07:19:29.000Z t:grade=K t:district=1 m:2008=856 m:2017=991 m:2009=837 m:2018=1015 m:2013=915 m:2014=933 m:2015=953 m:2016=973 m:2012=895 m:2011=867 m:2010=816

series e:2pkz-byyb d:2013-03-06T07:19:29.000Z t:grade=1 t:district=1 m:2008=870 m:2017=1006 m:2009=883 m:2018=1025 m:2013=926 m:2014=946 m:2015=965 m:2016=986 m:2012=896 m:2011=843 m:2010=866
```

## Meta Commands

```ls
metric m:2008 p:integer l:2008 t:dataTypeName=number

metric m:2009 p:integer l:2009 t:dataTypeName=number

metric m:2010 p:integer l:2010 t:dataTypeName=number

metric m:2011 p:integer l:2011 t:dataTypeName=number

metric m:2012 p:integer l:2012 t:dataTypeName=number

metric m:2013 p:integer l:2013 t:dataTypeName=number

metric m:2014 p:integer l:2014 t:dataTypeName=number

metric m:2015 p:integer l:2015 t:dataTypeName=number

metric m:2016 p:integer l:2016 t:dataTypeName=number

metric m:2017 p:integer l:2017 t:dataTypeName=number

metric m:2018 p:integer l:2018 t:dataTypeName=number

entity e:2pkz-byyb l:"Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part B" t:attribution="School Construction Authority (SCA)" t:url=https://data.cityofnewyork.us/api/views/2pkz-byyb

property e:2pkz-byyb t:meta.view v:id=2pkz-byyb v:category="Housing & Development" v:averageRating=0 v:name="Demographic Projection Report - Enrollment Projections - New York City Public Schools prepared by the Grier Partnership Part B" v:attribution="School Construction Authority (SCA)"

property e:2pkz-byyb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2pkz-byyb t:meta.view.tableauthor v:id=ci6y-i73t v:screenName="Harish Pathria" v:displayName="Harish Pathria"
```

## Top Records

```ls
| :updated_at | district | grade | 2008 | 2009 | 2010 | 2011 | 2012 | 2013 | 2014 | 2015 | 2016 | 2017 | 2018 | 
| =========== | ======== | ===== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | ==== | 
| 1362554369  | 1        | PRE-K | 1163 | 1085 | 1136 | 1195 | 1217 | 1239 | 1261 | 1283 | 1305 | 1332 | 1349 | 
| 1362554369  | 1        | K     | 856  | 837  | 816  | 867  | 895  | 915  | 933  | 953  | 973  | 991  | 1015 | 
| 1362554369  | 1        | 1     | 870  | 883  | 866  | 843  | 896  | 926  | 946  | 965  | 986  | 1006 | 1025 | 
| 1362554369  | 1        | 2     | 879  | 834  | 846  | 831  | 809  | 859  | 889  | 908  | 927  | 947  | 966  | 
| 1362554369  | 1        | 3     | 829  | 855  | 813  | 825  | 812  | 789  | 837  | 869  | 889  | 907  | 927  | 
| 1362554369  | 1        | 4     | 793  | 812  | 839  | 797  | 808  | 794  | 773  | 820  | 849  | 868  | 886  | 
| 1362554369  | 1        | 5     | 736  | 753  | 773  | 802  | 760  | 771  | 756  | 736  | 782  | 808  | 826  | 
| 1362554369  | 1        | 6     | 807  | 753  | 773  | 804  | 841  | 798  | 811  | 791  | 774  | 820  | 851  | 
| 1362554369  | 1        | 7     | 743  | 812  | 757  | 776  | 808  | 844  | 802  | 816  | 796  | 778  | 825  | 
| 1362554369  | 1        | 8     | 781  | 748  | 816  | 762  | 780  | 811  | 848  | 804  | 818  | 798  | 780  | 
```