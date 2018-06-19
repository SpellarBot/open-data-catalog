# Enforcement Cases

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/enforcement-cases-since-2015-01-01) |
| Metadata | [Link](https://data.srcity.org/api/views/vvka-2nem) |
| Data: JSON | [100 Rows](https://data.srcity.org/api/views/vvka-2nem/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.srcity.org/api/views/vvka-2nem/rows.csv?max_rows=100) |
| Host | data.srcity.org |
| Id | vvka-2nem |
| Name | Enforcement Cases |
| Category | Housing |
| Created | 2016-02-11T05:30:48Z |
| Publication Date | 2016-02-11T17:37:51Z |

## Description

Accela Automation Enforcement Cases Since 1998

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | permitnum        | PermitNum        | text          | text          |
| Yes      | series tag  | description      | Project          | text          | text          |
| No       |             | applieddate      | AppliedDate      | text          | text          |
| No       |             | originaladdress1 | OriginalAddress1 | text          | text          |
| Yes      | series tag  | originalcity     | OriginalCity     | text          | text          |
| Yes      | series tag  | originalstate    | OriginalState    | text          | text          |
| Yes      | series tag  | originalzip      | OriginalZip      | text          | text          |
| Yes      | series tag  | permitclass      | PermitClass      | text          | text          |
| Yes      | series tag  | statuscurrent    | StatusCurrent    | text          | text          |
| Yes      | series tag  | permittype       | PermitType       | text          | text          |
| No       |             | statusdate       | StatusDate       | text          | text          |
| Yes      | time        | lastupdated      | LastUpdated      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = lastupdated
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = applieddate,originaladdress1,statusdate
```

## Data Commands

```ls
series e:vvka-2nem d:2017-04-21T00:50:03.000Z t:originalcity="SANTA ROSA" t:permitclass=Case t:originalstate=CA t:statuscurrent=Closed t:permittype="Enforcement Case" t:permitnum=CE14-0660 m:row_number.vvka-2nem=1

series e:vvka-2nem d:2017-04-21T00:50:03.000Z t:originalcity="SANTA ROSA" t:permitclass=Case t:originalstate=CA t:statuscurrent=Closed t:permittype="Enforcement Case" t:permitnum=CE14-0870 m:row_number.vvka-2nem=2

series e:vvka-2nem d:2017-04-21T00:50:03.000Z t:originalcity="SANTA ROSA" t:permitclass=Case t:originalstate=CA t:statuscurrent=Closed t:permittype="Enforcement Case" t:permitnum=CE08-0652 m:row_number.vvka-2nem=3
```

## Meta Commands

```ls
metric m:row_number.vvka-2nem p:long l:"Row Number"

entity e:vvka-2nem l:"Enforcement Cases" t:url=https://data.srcity.org/api/views/vvka-2nem

property e:vvka-2nem t:meta.view v:id=vvka-2nem v:category=Housing v:averageRating=0 v:name="Enforcement Cases"

property e:vvka-2nem t:meta.view.owner v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:displayName=Webmaster

property e:vvka-2nem t:meta.view.tableauthor v:id=s466-99pv v:profileImageUrlMedium=/api/users/s466-99pv/profile_images/THUMB v:profileImageUrlLarge=/api/users/s466-99pv/profile_images/LARGE v:screenName=Webmaster v:profileImageUrlSmall=/api/users/s466-99pv/profile_images/TINY v:roleName=administrator v:displayName=Webmaster
```

## Top Records

```ls
| permitnum | description                     | applieddate | originaladdress1   | originalcity | originalstate | originalzip | permitclass | statuscurrent | permittype       | statusdate | lastupdated         | 
| ========= | =============================== | =========== | ================== | ============ | ============= | =========== | =========== | ============= | ================ | ========== | =================== | 
| CE14-0660 |                                 | 2014-09-30  | 1407 HENDLEY ST J  | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2014-11-07 | 2017-04-21T00:50:03 | 
| CE14-0870 |                                 | 2014-12-05  | 757 ROCKWELL PL    | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2015-01-12 | 2017-04-21T00:50:03 | 
| CE08-0652 |                                 | 2008-08-01  | 110 7TH ST W       | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2008-09-15 | 2017-04-21T00:50:03 | 
| CE05-0327 |                                 | 2005-05-05  | 696 POWDERHORN AVE | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2005-05-13 | 2017-04-21T00:50:03 | 
| CE00-0504 |                                 | 2000-04-24  | 2700 YULUPA AVE    | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2000-05-30 | 2017-04-21T00:50:03 | 
| CE07-0484 |                                 | 2007-06-04  | 1625 WOODHUE AVE   | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2015-01-06 | 2017-04-21T00:50:03 | 
| CE07-0738 |                                 | 2007-08-16  | 1564 CAVENDISH AVE | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2007-08-30 | 2017-04-21T00:50:03 | 
| CE17-0045 | HRIL - Illegal Residential Unit | 2017-01-23  | 3785 CLEVELAND AVE | SANTA ROSA   | CA            | 95403       | Case        | Closed        | Enforcement Case | 2017-02-20 | 2017-04-21T00:50:03 | 
| CE02-0972 |                                 | 2002-10-18  | 3973 FINLEY AVE    | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2009-02-23 | 2017-04-21T00:50:03 | 
| CE01-0529 |                                 | 2001-04-20  | 983 A ST S         | SANTA ROSA   | CA            |             | Case        | Closed        | Enforcement Case | 2001-11-07 | 2017-04-21T00:50:03 | 
```