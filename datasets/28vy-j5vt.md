# Energy Efficiency Annual Energy Savings ( MWH)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-efficiency-annual-energy-savings-mwh) |
| Metadata | [Link](https://data.austintexas.gov/api/views/28vy-j5vt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/28vy-j5vt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/28vy-j5vt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 28vy-j5vt |
| Name | Energy Efficiency Annual Energy Savings ( MWH) |
| Category | Utility |
| Tags | energy efficiency, savings, energy, austin energy |
| Created | 2016-09-08T16:00:42Z |
| Publication Date | 2016-11-29T19:39:38Z |

## Description

Austin Energy provides rebates and low interest loans to customers  who make energy efficiency improvements. During fiscal year 2012, energy savings totaled nearly 106-million kilowatt hours. That's enough electricity to power nearly 9,400 residential homes in Austin.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name           | Data Type | Render Type |
| ======== | ============== | =========== | ============== | ========= | =========== |
| No       | time           | :updated_at | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | program     | Program Type   | text      | text        |
| Yes      | series tag     | type        | Customer Class | text      | text        |
| Yes      | numeric metric | 2007        | 2007           | number    | number      |
| Yes      | numeric metric | 2008        | 2008           | number    | number      |
| Yes      | numeric metric | 2009        | 2009           | number    | number      |
| Yes      | numeric metric | 2010        | 2010           | number    | number      |
| Yes      | numeric metric | 2011        | 2011           | number    | number      |
| Yes      | numeric metric | 2012        | 2012           | number    | number      |
| Yes      | numeric metric | 2013        | 2013           | number    | number      |
| Yes      | numeric metric | 2014        | 2014           | number    | number      |
| Yes      | numeric metric | 2015        | 2015           | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:28vy-j5vt d:2016-09-08T16:00:46.000Z t:program="EES/GB Commercial Projects" t:type=Commercial m:2008=0 m:2009=0 m:2007=0 m:2013=0 m:2014=4532.8197 m:2015=10253 m:2012=0 m:2011=0 m:2010=0

series e:28vy-j5vt d:2016-09-08T16:00:46.000Z t:program="GB- Multifamily Ratings" t:type=Commercial m:2008=0 m:2009=1812.473 m:2007=0 m:2013=3751 m:2014=4787.51438 m:2015=6134.73834 m:2012=1813.44135 m:2011=207.794 m:2010=640.502

series e:28vy-j5vt d:2016-09-08T16:00:46.000Z t:program="GB- Multifamily Energy Code" t:type=Commercial m:2008=4627.215 m:2009=2176.38 m:2007=5831.928 m:2013=12219 m:2014=10504.0742 m:2015=4684.14 m:2012=8019.50127 m:2011=2563.506 m:2010=281.196
```

## Meta Commands

```ls
metric m:2007 p:float l:2007 t:dataTypeName=number

metric m:2008 p:double l:2008 t:dataTypeName=number

metric m:2009 p:double l:2009 t:dataTypeName=number

metric m:2010 p:float l:2010 t:dataTypeName=number

metric m:2011 p:double l:2011 t:dataTypeName=number

metric m:2012 p:double l:2012 t:dataTypeName=number

metric m:2013 p:float l:2013 t:dataTypeName=number

metric m:2014 p:double l:2014 t:dataTypeName=number

metric m:2015 p:double l:2015 t:dataTypeName=number

entity e:28vy-j5vt l:"Energy Efficiency Annual Energy Savings ( MWH)" t:url=https://data.austintexas.gov/api/views/28vy-j5vt

property e:28vy-j5vt t:meta.view v:id=28vy-j5vt v:category=Utility v:averageRating=0 v:name="Energy Efficiency Annual Energy Savings ( MWH)"

property e:28vy-j5vt t:meta.view.license v:name="Public Domain"

property e:28vy-j5vt t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:28vy-j5vt t:meta.view.tableauthor v:id=3qbr-w2gj v:screenName="Elaine Lee" v:roleName=editor v:displayName="Elaine Lee"
```

## Top Records

```ls
| :updated_at | program                         | type                 | 2007       | 2008        | 2009     | 2010        | 2011       | 2012       | 2013        | 2014        | 2015       | 
| =========== | =============================== | ==================== | ========== | =========== | ======== | =========== | ========== | ========== | =========== | =========== | ========== | 
| 1473350446  | EES/GB Commercial Projects      | Commercial           | 0          | 0           | 0        | 0           | 0          | 0          | 0           | 4532.8197   | 10253      | 
| 1473350446  | GB- Multifamily Ratings         | Commercial           | 0          | 0           | 1812.473 | 640.502     | 207.794    | 1813.44135 | 3751        | 4787.51438  | 6134.73834 | 
| 1473350446  | GB- Multifamily Energy Code     | Commercial           | 5831.928   | 4627.215    | 2176.38  | 281.196     | 2563.506   | 8019.50127 | 12219       | 10504.0742  | 4684.14    | 
| 1473350446  | GB- Commercial Ratings          | Commercial           | 3716.324   | 13377.47277 | 11933.71 | 5298.8005   | 7503.482   | 1746.66265 | 10427.87974 | 7152.99395  | 6656.45232 | 
| 1473350446  | GB- Commercial Energy Code      | Commercial           | 8923.00927 | 14590.12312 | 9010.577 | 4137.904    | 8005.66296 | 5814.37465 | 8734.79199  | 15404.15214 | 31409.92   | 
| 1473350446  | DR- Power Partner               | Demand Response (DR) | 101.76     | 97.3532     | 76.8222  | 45.2466     | 14.8078    | 8.7318     | 51.2394     | 38.8747     | 2.5273     | 
| 1473350446  | DR- Cycle Saver                 | Demand Response (DR) | 13.62      | 7.422       | 10.092   | 12.054      | 5.682      | 3.522      | 9.246       | 14.772      | 3.99       | 
| 1473350446  | DR- Power Partner (Comm & Muni) | Demand Response (DR) | 1285.26    | 14.3748     | 8.3268   | 8.424       | 1.8036     | 3.1536     | 0.162       | 0           | 0          | 
| 1473350446  | DR- Load Coop                   | Demand Response (DR) | 128.939    | 19.2        | 56.81    | 5.333333333 | 0          | 0          | 133.4733408 | 0           | 0          | 
| 1473350446  | DR- Engineering Support & TES   | Demand Response (DR) | 0          | 0           | 0        | 0           | 0          | 0          | 0           | 0           | 1968.283   | 
```