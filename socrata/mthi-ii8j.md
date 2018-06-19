# WDFW Item Statistics By Month

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/test-melody) |
| Metadata | [Link](https://data.wa.gov/api/views/mthi-ii8j) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mthi-ii8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mthi-ii8j/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mthi-ii8j |
| Name | WDFW Item Statistics By Month |
| Category | Natural Resources & Environment |
| Tags | wdfw, net revenue, licensing |
| Created | 2015-02-17T22:49:35Z |
| Publication Date | 2015-05-14T22:16:31Z |

## Description

Data provided here is used by WDFW?s partners, government entities, schools, private businesses, and the general public. WDFW actively promotes inter-agency data exchange and resource sharing. Every effort is made to provide accurate, complete, and timely information on this site. However, some content may be incomplete or out of date. The content on this site is subject to change without notice. The Washington Department of Fish and Wildlife (WDFW) shall not be liable for any activity involving this data with regard to lost profits or savings or any other consequential damages; or the fitness for use of the data for a particular purpose; or the installation of the data, its use, or the results obtained.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name             | Data Type | Render Type |
| ======== | ============== | ============= | ================ | ========= | =========== |
| Yes      | series tag     | ic_rcn        | Item Number      | text      | text        |
| Yes      | series tag     | it_descr      | Item Description | text      | text        |
| Yes      | series tag     | discount_type | Discount Type    | text      | text        |
| Yes      | series tag     | weapon_type   | Weapon Type      | text      | text        |
| Yes      | time           | ls_year       | License Year     | number    | text        |
| Yes      | numeric metric | cy_month      | Calendar Month   | number    | number      |
| No       |                | cy_year       | Calendar Year    | number    | number      |
| Yes      | series tag     | zip_code      | Zip Code         | text      | text        |
| Yes      | series tag     | county        | County           | text      | text        |
| Yes      | numeric metric | net_sales     | Net Sales        | number    | number      |
| Yes      | numeric metric | net_revenue   | Net Revenue      | money     | money       |
```

## Time Field

```ls
Value = ls_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = cy_year
```

## Data Commands

```ls
series e:mthi-ii8j d:2014-01-01T00:00:00.000Z t:zip_code=98264 t:it_descr="DEER LICENSE" t:discount_type=RESIDENT t:ic_rcn=1 m:cy_month=10 m:net_revenue=4633.2 m:net_sales=108

series e:mthi-ii8j d:2014-01-01T00:00:00.000Z t:zip_code=98266 t:it_descr="DEER LICENSE" t:discount_type=RESIDENT t:ic_rcn=1 m:cy_month=10 m:net_revenue=986.7 m:net_sales=23

series e:mthi-ii8j d:2014-01-01T00:00:00.000Z t:zip_code=98272 t:it_descr="DEER LICENSE" t:discount_type=RESIDENT t:ic_rcn=1 m:cy_month=10 m:net_revenue=5276.7 m:net_sales=123
```

## Meta Commands

```ls
metric m:cy_month p:integer l:"Calendar Month" d:"The calendar month in which this item was purchased." t:dataTypeName=number

metric m:net_sales p:integer l:"Net Sales" d:"The net number of items sold." t:dataTypeName=number

metric m:net_revenue p:double l:"Net Revenue" d:"The sum of the transaction fee and state fee for items sold." t:dataTypeName=money

entity e:mthi-ii8j l:"WDFW Item Statistics By Month" t:url=https://data.wa.gov/api/views/mthi-ii8j

property e:mthi-ii8j t:meta.view v:id=mthi-ii8j v:category="Natural Resources & Environment" v:averageRating=0 v:name="WDFW Item Statistics By Month"

property e:mthi-ii8j t:meta.view.owner v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:displayName="WDFW Data"

property e:mthi-ii8j t:meta.view.tableauthor v:id=h2p6-jrpv v:profileImageUrlMedium=/api/users/h2p6-jrpv/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2p6-jrpv/profile_images/LARGE v:screenName="WDFW Data" v:profileImageUrlSmall=/api/users/h2p6-jrpv/profile_images/TINY v:roleName=publisher v:displayName="WDFW Data"
```

## Top Records

```ls
| ic_rcn | it_descr     | discount_type | weapon_type | ls_year | cy_month | cy_year | zip_code | county | net_sales | net_revenue | 
| ====== | ============ | ============= | =========== | ======= | ======== | ======= | ======== | ====== | ========= | =========== | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98264    |        | 108       | 4633.2      | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98266    |        | 23        | 986.7       | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98272    |        | 123       | 5276.7      | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98275    |        | 18        | 772.2       | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98277    |        | 110       | 4719        | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98284    |        | 245       | 10510.5     | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98286    |        | 4         | 171.6       | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98287    |        | 1         | 42.9        | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98294    |        | 42        | 1801.8      | 
| 1      | DEER LICENSE | RESIDENT      |             | 2014    | 10       | 2014    | 98296    |        | 56        | 2402.4      | 
```