# City of Colfax: Vendor Log February 16th, 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-colfax-vendor-log-february-16th-2016) |
| Metadata | [Link](https://data.wa.gov/api/views/5duh-m3h5) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/5duh-m3h5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/5duh-m3h5/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 5duh-m3h5 |
| Name | City of Colfax: Vendor Log February 16th, 2016 |
| Attribution | City of Colfax, Washington |
| Category | Economics |
| Tags | colfax, finance, accounts payable, vendor |
| Created | 2016-03-15T17:42:26Z |
| Publication Date | 2016-03-15T17:44:34Z |

## Description

This dataset entails Accounts Payable activity between February 2nd and 16th.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | reference  | Reference | text      | text        |
| Yes      | numeric metric | amount     | Amount    | money     | money       |
| Yes      | series tag     | notes      | Notes     | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5duh-m3h5 d:2016-01-01T00:00:00.000Z t:reference="Reference Number: 1267" m:amount=340.36

series e:5duh-m3h5 d:2016-01-01T00:00:00.000Z t:reference="2/2/2016 Utility Postage" m:amount=340.36

series e:5duh-m3h5 d:2016-01-01T00:00:00.000Z t:reference="Reference Number: 1268" m:amount=241.59
```

## Meta Commands

```ls
metric m:amount p:double l:Amount t:dataTypeName=money

entity e:5duh-m3h5 l:"City of Colfax: Vendor Log February 16th, 2016" t:attribution="City of Colfax, Washington" t:url=https://data.wa.gov/api/views/5duh-m3h5

property e:5duh-m3h5 t:meta.view v:id=5duh-m3h5 v:category=Economics v:attributionLink=http://www.colfaxwa.org v:averageRating=0 v:name="City of Colfax: Vendor Log February 16th, 2016" v:attribution="City of Colfax, Washington"

property e:5duh-m3h5 t:meta.view.license v:name="Public Domain"

property e:5duh-m3h5 t:meta.view.owner v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:displayName="Mike Rizzitiello"

property e:5duh-m3h5 t:meta.view.tableauthor v:id=bn5q-s6v7 v:screenName="Mike Rizzitiello" v:roleName=editor v:displayName="Mike Rizzitiello"
```

## Top Records

```ls
| reference                | amount   | notes | 
| ======================== | ======== | ===== | 
| Reference Number: 1267   | 340.36   |       | 
| 2/2/2016 Utility Postage | 340.36   |       | 
| Reference Number: 1268   | 241.59   |       | 
| 1/25/2016 Statement      | 241.59   |       | 
| Reference Number: 1269   | 485.00   |       | 
| 16853                    | 485.00   |       | 
| Reference Number: 1270   | 80.00    |       | 
| 25990                    | 80.00    |       | 
| Reference Number: 1271   | 15114.16 |       | 
| February 2016 Statement  | 15114.16 |       | 
```