# IDPH Pregnancy Termination Center

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-pregnancy-termination-center-400dd) |
| Metadata | [Link](https://data.illinois.gov/api/views/2uck-mqsz) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/2uck-mqsz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/2uck-mqsz/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 2uck-mqsz |
| Name | IDPH Pregnancy Termination Center |
| Attribution | Division of Health Care Facilities and Programs |
| Category | Public Health |
| Tags | pregnancy, termination |
| Created | 2012-01-31T18:57:54Z |
| Publication Date | 2017-01-06T18:51:01Z |

## Description

Current as of January 2017

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type | Render Type |
| ======== | ============== | ============================ | ============================ | ========= | =========== |
| No       | time           | :updated_at                  | updated_at                   | meta_data | meta_data   |
| Yes      | series tag     | pregnancy_termination_center | Pregnancy Termination Center | text      | text        |
| No       |                | address                      | Address                      | text      | text        |
| Yes      | series tag     | city                         | City                         | text      | text        |
| Yes      | series tag     | county                       | County                       | text      | text        |
| Yes      | series tag     | zip                          | Zip                          | text      | number      |
| Yes      | series tag     | phone                        | Phone                        | phone     | phone       |
| Yes      | numeric metric | license_                     | License #                    | number    | number      |
| Yes      | series tag     | license_expiration_date      | License Expiration Date      | html      | html        |
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
series e:2uck-mqsz d:2017-01-06T18:50:11.000Z t:pregnancy_termination_center="Aanchor Health Center, Ltd." t:zip=60137 t:license_expiration_date=03/07/17 t:phone_number="(630) 495-4400" t:county="Du Page" t:city="Glen Ellyn" m:license_=7002447

series e:2uck-mqsz d:2017-01-06T18:50:11.000Z t:pregnancy_termination_center="Access Health Care Center, Ltd." t:zip=60016 t:license_expiration_date=05/06/17 t:phone_number="(847) 294-9614" t:county=Cook t:city="Des Plaines" m:license_=7003184

series e:2uck-mqsz d:2017-01-06T18:50:11.000Z t:pregnancy_termination_center="Access Health Center, Ltd." t:zip=60516 t:license_expiration_date=01/12/18 t:phone_number="(630) 964-0000" t:county="Du Page" t:city="Downers Grove" m:license_=7001613
```

## Meta Commands

```ls
metric m:license_ p:integer l:"License #" t:dataTypeName=number

entity e:2uck-mqsz l:"IDPH Pregnancy Termination Center" t:attribution="Division of Health Care Facilities and Programs" t:url=https://data.illinois.gov/api/views/2uck-mqsz

property e:2uck-mqsz t:meta.view v:id=2uck-mqsz v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/about/ohcr.htm v:averageRating=0 v:name="IDPH Pregnancy Termination Center" v:attribution="Division of Health Care Facilities and Programs"

property e:2uck-mqsz t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:2uck-mqsz t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| :updated_at | pregnancy_termination_center            | address                    | city          | county  | zip   | phone                  | license_ | license_expiration_date | 
| =========== | ======================================= | ========================== | ============= | ======= | ===== | ====================== | ======== | ======================= | 
| 1483728611  | Aanchor Health Center, Ltd.             | 1186 Roosevelt Road        | Glen Ellyn    | Du Page | 60137 | [(630) 495-4400, null] | 7002447  | 03/07/17                | 
| 1483728611  | Access Health Care Center, Ltd.         | 110 S. River Road, Suite 7 | Des Plaines   | Cook    | 60016 | [(847) 294-9614, null] | 7003184  | 05/06/17                | 
| 1483728611  | Access Health Center, Ltd.              | 1700 75th Street           | Downers Grove | Du Page | 60516 | [(630) 964-0000, null] | 7001613  | 01/12/18                | 
| 1483728611  | Michigan Avenue Center for Health, Ltd. | 2415 Michigan Ave          | Chicago       | Cook    | 60616 | [(312) 328-1200, null] | 7002777  | 07/18/17                | 
| 1483728611  | Whole Woman's Health of Peoria, LLC     | 7405 North University      | Peoria        | Peoria  | 61614 | [(309) 691-9073, null] | 7003195  | 06/03/17                | 
```