# Accredited Veterinarians updated 11/07/2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/accredited-veterinarians-refreshable-file-11-07-2016) |
| Metadata | [Link](https://data.maryland.gov/api/views/4zej-knfm) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/4zej-knfm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/4zej-knfm/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 4zej-knfm |
| Name | Accredited Veterinarians updated 11/07/2016 |
| Attribution | Maryland Department of Agriculture |
| Category | Agriculture |
| Tags | maryland department of agriculture, mda, veterinarians, animal, pet |
| Created | 2016-11-07T19:38:23Z |
| Publication Date | 2016-11-07T20:58:02Z |

## Description

Registered Veterinarians for FY 2017 (July 1, 2016 to June 30, 2017) - updated 11/07/2016

## Columns

```ls
| Included | Schema Type | Field Name     | Name            | Data Type     | Render Type   |
| ======== | =========== | ============== | =============== | ============= | ============= |
| Yes      | series tag  | lic_no         | LICENSE NUMBER  | text          | number        |
| Yes      | time        | lic_date       | LICENSE DATE    | calendar_date | calendar_date |
| Yes      | series tag  | fname          | FIRST NAME      | text          | text          |
| No       |             | mi             | MIDDLE INITIAL  | text          | text          |
| Yes      | series tag  | lname          | LAST NAME       | text          | text          |
| Yes      | series tag  | name_ext       | SUFFIX          | text          | text          |
| Yes      | series tag  | bus_name       | BUSINESS NAME   | text          | text          |
| Yes      | series tag  | phone          | PHONE           | text          | number        |
| Yes      | series tag  | bus_email      | BUSINESS EMAIL  | text          | text          |
| Yes      | series tag  | fax            | FAX             | text          | number        |
| Yes      | series tag  | bus_county     | BUSINESS COUNTY | text          | text          |
| No       |             | renew_year     | RENEW_YEAR      | number        | number        |
| Yes      | series tag  | credentials    | CREDENTIALS     | text          | text          |
| Yes      | series tag  | specialty_name | SPECIALTY       | text          | text          |
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
series e:4zej-knfm d:1980-06-03T00:00:00.000Z t:lname=RUBENSTEIN t:phone=3015407770 t:fax=3015402841 t:bus_county=MG t:bus_name="A CAT CLINIC" t:credentials=DVM t:specialty_name="SMALL ANIMAL" t:lic_no=2295 t:fname=JAN m:row_number.4zej-knfm=1

series e:4zej-knfm d:2001-03-23T00:00:00.000Z t:lname=HAUGHTON t:phone=8592573548 t:bus_county=XX t:bus_name="UK Division of Laboratory Animal Resources" t:credentials=DVM t:specialty_name="SMALL ANIMAL" t:lic_no=5258 t:bus_email=cheryl.haughton@uky.edu t:fname=CHERYL m:row_number.4zej-knfm=2

series e:4zej-knfm d:1995-05-22T00:00:00.000Z t:lname=SEIBEL t:phone=3016398766 t:fax=4106356930 t:bus_county=CR t:bus_name="SEIBEL VETERINARY SERVICES, LLC" t:credentials=DVM t:specialty_name="SMALL ANIMAL" t:lic_no=4463 t:bus_email=SEIBELVET@GMAIL.COM t:fname=SHERYL m:row_number.4zej-knfm=3
```

## Meta Commands

```ls
metric m:row_number.4zej-knfm p:long l:"Row Number"

entity e:4zej-knfm l:"Accredited Veterinarians updated 11/07/2016" t:attribution="Maryland Department of Agriculture" t:url=https://data.maryland.gov/api/views/4zej-knfm

property e:4zej-knfm t:meta.view v:id=4zej-knfm v:category=Agriculture v:attributionLink=http://mda.maryland.gov/Pages/default.aspx v:averageRating=0 v:name="Accredited Veterinarians updated 11/07/2016" v:attribution="Maryland Department of Agriculture"

property e:4zej-knfm t:meta.view.owner v:id=5i5x-vf5f v:screenName=teachoaa v:displayName=teachoaa

property e:4zej-knfm t:meta.view.tableauthor v:id=5i5x-vf5f v:screenName=teachoaa v:roleName=editor v:displayName=teachoaa
```

## Top Records

```ls
| lic_no | lic_date            | fname     | mi | lname           | name_ext | bus_name                                   | phone      | bus_email                            | fax        | bus_county | renew_year | credentials | specialty_name  | 
| ====== | =================== | ========= | == | =============== | ======== | ========================================== | ========== | ==================================== | ========== | ========== | ========== | =========== | =============== | 
| 2295   | 1980-06-03T00:00:00 | JAN       | L  | RUBENSTEIN      |          | A CAT CLINIC                               | 3015407770 |                                      | 3015402841 | MG         | 2017       | DVM         | SMALL ANIMAL    | 
| 5258   | 2001-03-23T00:00:00 | CHERYL    | L  | HAUGHTON        |          | UK Division of Laboratory Animal Resources | 8592573548 | cheryl.haughton@uky.edu              |            | XX         | 2017       | DVM         | SMALL ANIMAL    | 
| 4463   | 1995-05-22T00:00:00 | SHERYL    | R  | SEIBEL          |          | SEIBEL VETERINARY SERVICES, LLC            | 3016398766 | SEIBELVET@GMAIL.COM                  | 4106356930 | CR         | 2017       | DVM         | SMALL ANIMAL    | 
| 3078   | 1986-06-27T00:00:00 | DONNA     | P  | MOORE           |          | CONCORDIA VETERINARY CARE                  | 6106562860 |                                      |            | XX         | 2017       | DVM         | EQUINE PRACTICE | 
| 4205   | 1993-06-04T00:00:00 | KARA      |    | CHAPLIN SCHOEPP |          | VCA PEACHTREE ANIMAL HOSPITAL              | 3017622070 | KARA.CHAPLINSCHOEPP@VCAHOSPITALS.COM | 3013492181 | MG         | 2017       | DVM         | SMALL ANIMAL    | 
| 6712   | 2011-01-24T00:00:00 | MOIRA     | N  | MYERS           |          | PENMAR EQUINE                              | 3016395563 | penmarequine@gmail.com               |            | FR         | 2017       | DVM         | EQUINE PRACTICE | 
| 6106   | 2007-03-22T00:00:00 | KERRY     | M  | MURPHY          |          | Clover Veterinary Services                 | 4435365319 | clovervetservices@gmail.com          | 0          | CR         | 2017       | DVM         | MIXED PRACTICE  | 
| 5399   | 2002-02-15T00:00:00 | THERESA   |    | KOTHSTEIN       |          | FOUR PAWS ANIMAL HOSPITAL                  | 3028413081 | reynardfarm@gmail.com                | 3026297008 | XX         | 2017       | DVM         | SMALL ANIMAL    | 
| 4840   | 1997-12-10T00:00:00 | FREDERICK | R  | ADAMS           |          |                                            |            |                                      |            |            | 2017       | DVM         | LARGE ANIMAL    | 
| 3312   | 1987-06-29T00:00:00 | CAROL     | D  | SWANDBY         |          | Carol Swandby                              | 3018020747 | cdswandby@earthlink.net              |            | FR         | 2017       | VMD         | EQUINE PRACTICE | 
```