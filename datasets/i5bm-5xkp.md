# IDHS Office Locator

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idhs-office-locator-0b8ef) |
| Metadata | [Link](https://data.illinois.gov/api/views/i5bm-5xkp) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/i5bm-5xkp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/i5bm-5xkp/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | i5bm-5xkp |
| Name | IDHS Office Locator |
| Attribution | Department of Human Services |
| Category | Social/Healthcare |
| Tags | office locations |
| Created | 2011-08-24T23:08:50Z |
| Publication Date | 2012-01-26T15:29:22Z |

## Description

Listing of Department of Human Services and Service Provider Office Locations

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| No       | time           | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag     | resource               | Resource               | text      | text        |
| Yes      | series tag     | office_type            | Office Type            | text      | text        |
| Yes      | series tag     | street_address         | Street Address         | text      | text        |
| No       |                | supplemental_address   | Supplemental Address   | text      | text        |
| Yes      | series tag     | zip_code               | Zip Code               | text      | text        |
| Yes      | numeric metric | phone                  | Phone                  | number    | text        |
| Yes      | numeric metric | tty                    | TTY                    | number    | text        |
| Yes      | numeric metric | fax                    | Fax                    | number    | text        |
| Yes      | numeric metric | toll_free_phone        | Toll Free Phone        | number    | text        |
| Yes      | series tag     | website                | Website                | url       | url         |
| Yes      | series tag     | additional_information | Additional information | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = supplemental_address
```

## Data Commands

```ls
series e:i5bm-5xkp d:2011-08-24T16:08:53.000Z t:zip_code=62353-1561 t:office_type="Mental Health" t:resource="Brown County Mental Health Center" t:street_address="700 Se Cross St" t:additional_information="Afterhour Crisis Number: (217) 773-2011" m:phone=2177733325 m:fax=2177732425

series e:i5bm-5xkp d:2011-08-24T16:08:53.000Z t:zip_code=62205-2146 t:office_type="Mental Health" t:resource="Comprehensive Mental Health Center" t:street_address="3911 State St" m:phone=6184827330

series e:i5bm-5xkp d:2011-08-24T16:08:53.000Z t:zip_code=60056 t:office_type="Women, Infants and Children (WIC)" t:resource="Community and Economic Development Association of Cook County" t:street_address="1300 W Northwest Hwy" m:phone=8473920325 m:fax=8473922427
```

## Meta Commands

```ls
metric m:phone p:long l:Phone t:dataTypeName=number

metric m:tty p:long l:TTY t:dataTypeName=number

metric m:fax p:long l:Fax t:dataTypeName=number

metric m:toll_free_phone p:long l:"Toll Free Phone" t:dataTypeName=number

entity e:i5bm-5xkp l:"IDHS Office Locator" t:attribution="Department of Human Services" t:url=https://data.illinois.gov/api/views/i5bm-5xkp

property e:i5bm-5xkp t:meta.view v:id=i5bm-5xkp v:category=Social/Healthcare v:attributionLink="http://www.dhs.state.il.us/page.aspx?module=12" v:averageRating=0 v:name="IDHS Office Locator" v:attribution="Department of Human Services"

property e:i5bm-5xkp t:meta.view.owner v:id=ktsu-w554 v:screenName=Jeremy v:displayName=Jeremy

property e:i5bm-5xkp t:meta.view.tableauthor v:id=ktsu-w554 v:screenName=Jeremy v:displayName=Jeremy
```

## Top Records

```ls
| :updated_at | resource                                                      | office_type                       | street_address       | supplemental_address | zip_code   | phone      | tty | fax        | toll_free_phone | website                          | additional_information                  | 
| =========== | ============================================================= | ================================= | ==================== | ==================== | ========== | ========== | === | ========== | =============== | ================================ | ======================================= | 
| 1314202133  | Brown County Mental Health Center                             | Mental Health                     | 700 Se Cross St      | PO Box 254           | 62353-1561 | 2177733325 |     | 2177732425 |                 | [null, null]                     | Afterhour Crisis Number: (217) 773-2011 | 
| 1314202133  | Comprehensive Mental Health Center                            | Mental Health                     | 3911 State St        |                      | 62205-2146 | 6184827330 |     |            |                 | [null, null]                     |                                         | 
| 1314202133  | Community and Economic Development Association of Cook County | Women, Infants and Children (WIC) | 1300 W Northwest Hwy |                      | 60056      | 8473920325 |     | 8473922427 |                 | [null, null]                     |                                         | 
| 1314202133  | East Side Health District                                     | Women, Infants and Children (WIC) | 638 N 20th St        |                      | 62205-1812 | 6188744713 |     | 6188744737 |                 | [null, null]                     |                                         | 
| 1314202133  | Kankakee County Health Department                             | Women, Infants and Children (WIC) | 3400 S Main St       |                      | 60964-5098 | 8159446415 |     |            |                 | [null, null]                     | Pembroke Medical Center                 | 
| 1314202133  | Well Child Center, Inc.                                       | Women, Infants and Children (WIC) | 1710 S 7th Ave       |                      | 60174-4380 | 8477417370 |     | 8477412413 |                 | [null, null]                     |                                         | 
| 1314202135  | Cass County                                                   | Family Planning                   | 331 S Main St        |                      | 62691      | 2174523057 |     | 2174527245 |                 | [null, null]                     | 3rd Wednesday of Month 8:30-4:30        | 
| 1314202133  | Community Service Options                                     | Developmental Disabilities        | 6845 S Western Ave   |                      | 60636      | 8882764467 |     | 7738389362 |                 | [http://www.cso1.org, null]      |                                         | 
| 1314202133  | PACT, Inc                                                     | Developmental Disabilities        | 555 E Butterfield Rd |                      | 60148-5680 | 6309609700 |     |            |                 | [null, null]                     |                                         | 
| 1314202133  | Access Services of Northern Illinois                          | Developmental Disabilities        | 7399 Forest Hills Rd |                      | 61111      | 8152828824 |     |            |                 | [http://www.accessni.com/, null] |                                         | 
```