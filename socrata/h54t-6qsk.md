# IDPH Home Health Agencies Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-home-health-agencies-directory-696d4) |
| Metadata | [Link](https://data.illinois.gov/api/views/h54t-6qsk) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/h54t-6qsk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/h54t-6qsk/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | h54t-6qsk |
| Name | IDPH Home Health Agencies Directory |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | home, health, agency |
| Created | 2012-01-30T19:50:45Z |
| Publication Date | 2017-01-06T18:13:53Z |

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | home_health_agency      | Home Health Agency      | text      | text        |
| No       |                | address                 | Address                 | text      | text        |
| Yes      | series tag     | city                    | City                    | text      | text        |
| Yes      | series tag     | zip                     | Zip                     | text      | number      |
| Yes      | series tag     | county                  | County                  | text      | text        |
| Yes      | series tag     | phone_                  | Phone #                 | phone     | phone       |
| Yes      | numeric metric | license_                | License #               | number    | number      |
| Yes      | series tag     | license_expiration_date | License Expiration Date | html      | html        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:h54t-6qsk d:2017-01-06T18:11:08.000Z t:zip=60193 t:license_expiration_date=10/31/17 t:phone_number="(630) 339-3688" t:county=Cook t:city=Schaumburg t:home_health_agency="1st Assist Home Healthcare, LLC" m:license_=1010496

series e:h54t-6qsk d:2017-01-06T18:11:08.000Z t:zip=60423 t:license_expiration_date=11/30/17 t:phone_number="(815) 464-9980" t:county=Will t:city=Frankfort t:home_health_agency="1st Choice Home Health Agency, Inc." m:license_=1011184

series e:h54t-6qsk d:2017-01-06T18:11:08.000Z t:zip=60564 t:license_expiration_date=06/30/17 t:phone_number="(855) 808-4442" t:county=Will t:city=Naperville t:home_health_agency="1st Choice Home Health Providers, LLC" m:license_=1011541
```

## Meta Commands

```ls
metric m:license_ p:integer l:"License #" t:dataTypeName=number

entity e:h54t-6qsk l:"IDPH Home Health Agencies Directory" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/h54t-6qsk

property e:h54t-6qsk t:meta.view v:id=h54t-6qsk v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Home Health Agencies Directory" v:attribution="Division of Health Care Facilities and Programs"

property e:h54t-6qsk t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:h54t-6qsk t:meta.view.tableauthor v:id=e75b-y6hv v:screenName=Jenny v:roleName=publisher v:displayName=Jenny
```

## Top Records

```ls
| :updated_at | home_health_agency                    | address                             | city              | zip   | county     | phone_                 | license_ | license_expiration_date | 
| =========== | ===================================== | =================================== | ================= | ===== | ========== | ====================== | ======== | ======================= | 
| 1483726268  | 1st Assist Home Healthcare, LLC       | 1019 W. Wise Rd., Ste. 200          | Schaumburg        | 60193 | Cook       | [(630) 339-3688, null] | 1010496  | 10/31/17                | 
| 1483726268  | 1st Choice Home Health Agency, Inc.   | 7260 W. Benton Drive                | Frankfort         | 60423 | Will       | [(815) 464-9980, null] | 1011184  | 11/30/17                | 
| 1483726268  | 1st Choice Home Health Providers, LLC | 2244 W 95th Street, Suite 219       | Naperville        | 60564 | Will       | [(855) 808-4442, null] | 1011541  | 06/30/17                | 
| 1483726268  | 1st Family Home Healthcare, Inc.      | 666 Russell Court, Ste 308          | Woodstock         | 60098 | Mc Henry   | [(815) 337-4240, null] | 1011088  | 06/30/17                | 
| 1483726268  | 1st Home Healthcare, Inc.             | 5875 N. Lincoln Ave., Ste 229       | Chicago           | 60659 | Cook       | [(773) 275-7935, null] | 1010441  | 06/30/17                | 
| 1483726268  | 2 Sisters Home Health Care Inc        | 6019 Fincham Drive, #9              | Rockford          | 61108 | Winnebago  | [(779) 537-3093, null] | 1011750  | 10/31/17                | 
| 1483726268  | 24/Seven Health Care Services, Inc.   | 5765 N Lincoln Ave. Suite 27        | Chicago           | 60659 | Cook       | [(773) 463-3755, null] | 1011165  | 08/31/17                | 
| 1483726268  | 24-Hour Care, LLC                     | 11420 Dander Dr. Suite 200          | Galena            | 61036 | Jo Daviess | [(815) 777-2424, null] | 1011511  | 08/31/17                | 
| 1483726268  | 3 Angels Home Health                  | 9933 Lawler Ave., Suite 355         | Skokie            | 60077 | Cook       | [(847) 581-1400, null] | 1011883  | 11/30/17                | 
| 1483726268  | 4Ever Care Home Health Services, Inc. | 2015 S. Arlington Hgts Rd., Ste 102 | Arlington Heights | 60005 | Cook       | [(847) 357-8008, null] | 1011868  | 03/31/17                | 
```