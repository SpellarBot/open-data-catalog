# Wireless Service Facility Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/wireless-service-facility-permits) |
| Metadata | [Link](https://data.sfgov.org/api/views/xtj2-daw9) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/xtj2-daw9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/xtj2-daw9/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | xtj2-daw9 |
| Name | Wireless Service Facility Permits |
| Category | City Infrastructure |
| Tags | wireless, permits, mobile, antenna, cell, phone, telecommunication, service, facility |
| Created | 2015-09-24T21:43:41Z |
| Publication Date | 2016-09-20T22:48:56Z |

## Description

All active and closed wireless service facility permits issued by Public Works.  These permits are issued to commercial mobile service company who will use the permit to install antennas that transmit cell phone services to cell phones.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | permit_number        | Permit_Number        | text          | text          |
| No       |             | permit_address       | Permit_Address       | text          | text          |
| Yes      | series tag  | street_name          | Street_Name          | text          | text          |
| Yes      | series tag  | cross_street_1       | Cross_Street_1       | text          | text          |
| Yes      | series tag  | cross_street_2       | Cross_Street_2       | text          | text          |
| Yes      | series tag  | permit_zipcode       | Permit_ZipCode       | text          | number        |
| Yes      | series tag  | applicant            | Applicant            | text          | text          |
| Yes      | series tag  | permit_purpose       | Permit_Purpose       | text          | text          |
| Yes      | time        | permit_approval_date | Permit_Approval_Date | calendar_date | calendar_date |
| Yes      | series tag  | permit_status        | Permit_Status        | text          | text          |
| Yes      | series tag  | permit_files_url     | Permit_Files_URL     | url           | url           |
| No       |             | x                    | X                    | number        | number        |
| No       |             | y                    | Y                    | number        | number        |
| No       |             | latitude             | Latitude             | number        | number        |
| No       |             | longitude            | Longitude            | number        | number        |
```

## Time Field

```ls
Value = permit_approval_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = permit_address,x,y,latitude,longitude
```

## Data Commands

```ls
series e:xtj2-daw9 d:2015-12-24T16:52:01.000Z t:permit_number=15WR-0140 t:permit_files_url="http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=15WR-0140" t:permit_status=APPROVED t:street_name="PACIFIC AVE" t:applicant="ExteNet Systems, Inc." t:permit_purpose="Wireless Box" t:cross_street_2="LARKIN ST" t:cross_street_1="LARKIN ST" m:row_number.xtj2-daw9=1

series e:xtj2-daw9 d:2009-07-14T15:48:16.000Z t:permit_number=09WR-0076 t:permit_zipcode=94116 t:permit_files_url="http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=09WR-0076" t:permit_status=APPROVED t:street_name="46TH AVE" t:applicant="Omnipoint Communications, Inc. (T-Mobile)" t:permit_purpose="Wireless Box" t:cross_street_2="VICENTE ST" t:cross_street_1="VICENTE ST" m:row_number.xtj2-daw9=2

series e:xtj2-daw9 d:2010-10-01T09:04:23.000Z t:permit_number=10WR-0033 t:permit_zipcode=94122 t:permit_files_url="http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=10WR-0033" t:permit_status=APPROVED t:street_name="34TH AVE" t:applicant="NextG Network, Inc" t:permit_purpose="Wireless Box" t:cross_street_2="LAWTON ST" t:cross_street_1="LAWTON ST" m:row_number.xtj2-daw9=3
```

## Meta Commands

```ls
metric m:row_number.xtj2-daw9 p:long l:"Row Number"

entity e:xtj2-daw9 l:"Wireless Service Facility Permits" t:url=https://data.sfgov.org/api/views/xtj2-daw9

property e:xtj2-daw9 t:meta.view v:id=xtj2-daw9 v:category="City Infrastructure" v:averageRating=0 v:name="Wireless Service Facility Permits"

property e:xtj2-daw9 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:xtj2-daw9 t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:xtj2-daw9 t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| permit_number | permit_address    | street_name | cross_street_1      | cross_street_2      | permit_zipcode | applicant                                 | permit_purpose | permit_approval_date | permit_status | permit_files_url                                                               | x             | y             | latitude         | longitude         | 
| ============= | ================= | =========== | =================== | =================== | ============== | ========================================= | ============== | ==================== | ============= | ============================================================================== | ============= | ============= | ================ | ================= | 
| 15WR-0140     | 1580 PACIFIC AVE  | PACIFIC AVE | LARKIN ST           | LARKIN ST           |                | ExteNet Systems, Inc.                     | Wireless Box   | 2015-12-24T16:52:01  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=15WR-0140, null] | 6006565.068   | 2117760.90226 | 37.7953384954351 | -122.421285391606 | 
| 09WR-0076     | 2601 46TH AVE     | 46TH AVE    | VICENTE ST          | VICENTE ST          | 94116          | Omnipoint Communications, Inc. (T-Mobile) | Wireless Box   | 2009-07-14T15:48:16  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=09WR-0076, null] | 5982081.86894 | 2097356.33677 | 37.7379027034157 | -122.50448739419  | 
| 10WR-0033     | 1663 34TH AVE     | 34TH AVE    | LAWTON ST           | LAWTON ST           | 94122          | NextG Network, Inc                        | Wireless Box   | 2010-10-01T09:04:23  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=10WR-0033, null] | 5985583.62867 | 2103904.84992 | 37.7560884941929 | -122.492862477039 | 
| 11WR-0063     |                   | BALBOA ST   | 17TH AVE            | 17TH AVE            |                | NextG Networks of California, Inc         | Wireless Box   | 2012-08-30T18:27:32  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=11WR-0063, null] | 5990492.34706 | 2111296.00457 | 37.7766684388394 | -122.476426560453 | 
| 15WR-0461     | 150 JACKSON ST    | JACKSON ST  | DAVIS CT \ DAVIS ST | DAVIS CT \ DAVIS ST | 94111          | ExteNet Systems, Inc.                     | Wireless Box   | 2016-01-08T09:07:36  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=15WR-0461, null] | 6013015.1988  | 2118400.09226 | 37.7974550906144 | -122.399011623379 | 
| 09WR-0127     | 1691 29TH AVE     | 29TH AVE    | LAWTON ST           | LAWTON ST           |                | Omnipoint Communications, Inc. (T-Mobile) | Wireless Box   | 2010-07-15T13:53:44  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=09WR-0127, null] | 5987140.56092 | 2103782.9394  | 37.7558446845623 | -122.487469198059 | 
| 09WR-0060     | 897 CAROLINA ST   | 22ND ST     | WISCONSIN ST        | WISCONSIN ST        | 94107          | Omnipoint Communications, Inc. (T-Mobile) | Wireless Box   | 2009-10-22T10:44:52  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=09WR-0060, null] | 6012507.3304  | 2103818.72444 | 37.757389684011  | -122.399744618899 | 
| 09WR-0044     | 885 UNIVERSITY ST | MANSELL ST  | UNIVERSITY ST       | UNIVERSITY ST       | 94134          | Newpath Networks, LLC.                    | Wireless Box   | 2009-07-21T10:16:24  | ACTIVE        | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=09WR-0044, null] | 6008993.5205  | 2090007.06997 | 37.7192693761375 | -122.41092133337  | 
| 09WR-0089     | 2896 22ND ST      | 22ND ST     | HARRISON ST         | HARRISON ST         | 94110          | Omnipoint Communications, Inc. (T-Mobile) | Wireless Box   | 2009-07-30T10:04:28  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=09WR-0089, null] | 6008947.5803  | 2103364.78801 | 37.7559441923378 | -122.412023612553 | 
| 15WR-0224     | 660 03RD ST       | 03RD ST     | BRANNAN ST          | BRANNAN ST          | 94107          | Verizon Wireless                          | Wireless Box   | 2016-02-11T16:12:08  | APPROVED      | [http://bsm.sfdpw.org/permitsTracker/reviewpermit.aspx?permit=15WR-0224, null] | 6014476.58335 | 2111735.33853 | 37.7792365408232 | -122.393488138455 | 
```