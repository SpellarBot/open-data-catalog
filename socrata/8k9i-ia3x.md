# Water Exemptions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/water-exemptions-e5594) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/8k9i-ia3x) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/8k9i-ia3x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/8k9i-ia3x/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 8k9i-ia3x |
| Name | Water Exemptions |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | water |
| Created | 2012-06-01T19:59:45Z |
| Publication Date | 2012-06-05T15:42:53Z |

## Description

List of organizations currently receiving reduced water rates by premise. Data Owner: Water Management. Time Period: Data current as of May 2012. Update Frequency: Data is updated as needed.

## Columns

```ls
| Included | Schema Type | Field Name             | Name          | Data Type | Render Type |
| ======== | =========== | ====================== | ============= | ========= | =========== |
| No       | time        | :updated_at            | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | customer_last_name     | Customer      | text      | text        |
| Yes      | series tag  | premises_street_number | Street Number | text      | text        |
| Yes      | series tag  | pdir_pre               | Street Prefix | text      | text        |
| Yes      | series tag  | premise_street_name    | Street Name   | text      | text        |
| Yes      | series tag  | ssfx                   | Street Suffix | text      | text        |
| Yes      | series tag  | city                   | City          | text      | text        |
| No       |             | st                     | ST            | text      | text        |
| Yes      | series tag  | zip                    | Zip           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = st
```

## Data Commands

```ls
series e:8k9i-ia3x d:2012-06-01T12:59:47.000Z t:zip=60606-1705 t:customer_last_name="BRIDGE HOUSE E END" t:ssfx=ST t:premises_street_number=348 t:pdir_pre=W t:city=CHICAGO t:premise_street_name=RANDOLPH m:row_number.8k9i-ia3x=1

series e:8k9i-ia3x d:2012-06-01T12:59:47.000Z t:zip=60632-1808 t:customer_last_name="DEPT OF GENERAL SERVICES" t:ssfx=AVE t:premises_street_number="3900 02" t:pdir_pre=S t:city=CHICAGO t:premise_street_name=CALIFORNIA m:row_number.8k9i-ia3x=2

series e:8k9i-ia3x d:2012-06-01T12:59:47.000Z t:zip=60629-3633 t:customer_last_name="CHICAGO FIRE DEPT" t:ssfx=ST t:premises_street_number=3500 t:pdir_pre=W t:city=CHICAGO t:premise_street_name=60TH m:row_number.8k9i-ia3x=3
```

## Meta Commands

```ls
metric m:row_number.8k9i-ia3x p:long l:"Row Number"

entity e:8k9i-ia3x l:"Water Exemptions" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/8k9i-ia3x

property e:8k9i-ia3x t:meta.view v:id=8k9i-ia3x v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="Water Exemptions" v:attribution="City of Chicago"

property e:8k9i-ia3x t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:8k9i-ia3x t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| :updated_at | customer_last_name                     | premises_street_number | pdir_pre | premise_street_name | ssfx | city    | st | zip        | 
| =========== | ====================================== | ====================== | ======== | =================== | ==== | ======= | == | ========== | 
| 1338555587  | BRIDGE HOUSE E END                     | 348                    | W        | RANDOLPH            | ST   | CHICAGO | IL | 60606-1705 | 
| 1338555587  | DEPT OF GENERAL SERVICES               | 3900 02                | S        | CALIFORNIA          | AVE  | CHICAGO | IL | 60632-1808 | 
| 1338555587  | CHICAGO FIRE DEPT                      | 3500                   | W        | 60TH                | ST   | CHICAGO | IL | 60629-3633 | 
| 1338555587  | MARQUETTE POLICE ST                    | 1940 56                | W        | 23RD                | ST   | CHICAGO | IL | 60608-4208 | 
| 1338555587  | CITY OF CHGO BRIDGE                    | 847                    | N        | HALSTED             | ST   | CHICAGO | IL | 60642-     | 
| 1338555587  | CITY OF CHICAGO                        | 250                    | N        | WABASH              | AVE  | CHICAGO | IL | 60601      | 
| 1338555587  | CITY OF CHICAGO                        | 3600 02                | N        | HALSTED             | ST   | CHICAGO | IL | 60613-4316 | 
| 1338555587  | FIRE STATION                           | 1721 23                | W        | GREENLEAF           | AVE  | CHICAGO | IL | 60626-2411 | 
| 1338555587  | CITY COLLEGES OF CHICAGO-DALEY COLLEGE | 4173                   | W        | 76TH                | ST   | CHICAGO | IL | 60652-1201 | 
| 1338555587  | COOK COUNTY                            | 12901                  | S        | HALSTED             |      | CHICAGO | IL | 60628      | 
```