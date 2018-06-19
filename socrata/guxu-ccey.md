# Registered Veterinarians for Fiscal 2017

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/registered-veterinarians-for-fiscal-2017) |
| Metadata | [Link](https://data.maryland.gov/api/views/guxu-ccey) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/guxu-ccey/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/guxu-ccey/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | guxu-ccey |
| Name | Registered Veterinarians for Fiscal 2017 |
| Attribution | MDA |
| Category | Agriculture |
| Tags | veterinarians |
| Created | 2016-07-27T16:22:48Z |
| Publication Date | 2016-07-27T19:43:47Z |

## Description

This data set lists the veterinarians that have renewed for Fiscal year 2017 (July 1, 2016 - June 30, 2017)

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | lic_no         | LIC_NO         | text          | number        |
| Yes      | time        | lic_date       | LIC_DATE       | calendar_date | calendar_date |
| Yes      | series tag  | fname          | FNAME          | text          | text          |
| No       |             | mi             | MI             | text          | text          |
| Yes      | series tag  | lname          | LNAME          | text          | text          |
| Yes      | series tag  | credentials    | CREDENTIALS    | text          | text          |
| Yes      | series tag  | name_ext       | NAME_EXT       | text          | text          |
| Yes      | series tag  | bus_phone      | BUS_PHONE      | text          | number        |
| Yes      | series tag  | bus_email      | BUS_EMAIL      | text          | text          |
| Yes      | series tag  | bus_fax        | BUS_FAX        | text          | number        |
| Yes      | series tag  | bus_county     | BUS_COUNTY     | text          | text          |
| No       |             | renew_year     | RENEW_YEAR     | number        | number        |
| Yes      | series tag  | specialty_name | SPECIALTY_NAME | text          | text          |
| Yes      | series tag  | accd           | ACCD           | text          | text          |
| Yes      | series tag  | discipline     | DISCIPLINE     | text          | text          |
```

## Time Field

```ls
Value = lic_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mi,renew_year
```

## Data Commands

```ls
series e:guxu-ccey d:1964-06-03T00:00:00.000Z t:accd=Y t:lname=GARDNER t:bus_phone=4108202058 t:bus_county=CL t:bus_fax=4108202291 t:credentials=DVM t:specialty_name="SMALL ANIMAL" t:lic_no=1173 t:bus_email=tuckanclinic@verizon.net t:fname=HILLIARD m:row_number.guxu-ccey=1

series e:guxu-ccey d:1966-11-01T00:00:00.000Z t:accd=Y t:lname=CORKRAN t:bus_phone=4107581535 t:bus_county=QA t:credentials=VMD t:specialty_name="EQUINE PRACTICE" t:lic_no=1310 t:bus_email=TSCORK@MYSHORELINK.COM t:fname=TERRY m:row_number.guxu-ccey=2

series e:guxu-ccey d:1977-06-29T00:00:00.000Z t:accd=Y t:lname=SENIOR t:bus_phone=4106426396 t:bus_county=CE t:credentials=VMD t:specialty_name="SMALL ANIMAL" t:lic_no=2011 t:bus_email=jsenior11@msn.com t:fname=JONATHAN m:row_number.guxu-ccey=3
```

## Meta Commands

```ls
metric m:row_number.guxu-ccey p:long l:"Row Number"

entity e:guxu-ccey l:"Registered Veterinarians for  Fiscal 2017" t:attribution=MDA t:url=https://data.maryland.gov/api/views/guxu-ccey

property e:guxu-ccey t:meta.view v:id=guxu-ccey v:category=Agriculture v:averageRating=0 v:name="Registered Veterinarians for  Fiscal 2017" v:attribution=MDA

property e:guxu-ccey t:meta.view.owner v:id=5i5x-vf5f v:screenName=teachoaa v:displayName=teachoaa

property e:guxu-ccey t:meta.view.tableauthor v:id=5i5x-vf5f v:screenName=teachoaa v:roleName=editor v:displayName=teachoaa
```

## Top Records

```ls
| lic_no | lic_date            | fname    | mi | lname      | credentials | name_ext | bus_phone  | bus_email                     | bus_fax    | bus_county | renew_year | specialty_name  | accd | discipline | 
| ====== | =================== | ======== | == | ========== | =========== | ======== | ========== | ============================= | ========== | ========== | ========== | =============== | ==== | ========== | 
| 1173   | 1964-06-03T00:00:00 | HILLIARD | E  | GARDNER    | DVM         |          | 4108202058 | tuckanclinic@verizon.net      | 4108202291 | CL         | 2017       | SMALL ANIMAL    | Y    |            | 
| 1310   | 1966-11-01T00:00:00 | TERRY    | R  | CORKRAN    | VMD         |          | 4107581535 | TSCORK@MYSHORELINK.COM        |            | QA         | 2017       | EQUINE PRACTICE | Y    |            | 
| 2011   | 1977-06-29T00:00:00 | JONATHAN | M  | SENIOR     | VMD         |          | 4106426396 | jsenior11@msn.com             |            | CE         | 2017       | SMALL ANIMAL    | Y    |            | 
| 2064   | 1978-06-28T00:00:00 | STEVEN   | H  | HARMAN     | DVM         |          | 3016892782 | JEANYVONNE@HOTMAIL.COM        | 3016890233 | AL         | 2017       | SMALL ANIMAL    | Y    |            | 
| 2160   | 1979-06-06T00:00:00 | ROGER    | L  | NICHOLS    | DVM         |          | 7032211880 | WILLOWLANDINGVETS@COMCAST.NET |            | XX         | 2017       | SMALL ANIMAL    | Y    |            | 
| 2181   | 1979-07-17T00:00:00 | LINDA    | R  | MILLER     | VMD         |          |            |                               |            |            | 2017       | EQUINE PRACTICE | Y    |            | 
| 2234   | 1980-06-03T00:00:00 | GRACE    | L  | CALABRESE  | DVM         |          | 4105576040 | gcala@erols.com               | 4105576040 | BC         | 2017       | SMALL ANIMAL    |      |            | 
| 2257   | 1980-06-03T00:00:00 | RICHARD  | J  | FORFA      | DVM         |          | 3016074025 |                               | 3016074027 | FR         | 2017       | EQUINE PRACTICE | Y    |            | 
| 2295   | 1980-06-03T00:00:00 | JAN      | L  | RUBENSTEIN | DVM         |          | 3015407770 |                               | 3015402841 | MG         | 2017       | SMALL ANIMAL    | Y    |            | 
| 2407   | 1981-06-30T00:00:00 | DALE     | L  | PACCAMONTI | DVM         |          | 2255789553 | PACC@LSU.EDU                  |            | XX         | 2017       | MIXED PRACTICE  | Y    |            | 
```