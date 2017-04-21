# Assessment Actions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/assessment-actions-c7e0c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4nft-bihw) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4nft-bihw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4nft-bihw/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4nft-bihw |
| Name | Assessment Actions |
| Attribution | New York City Tax Commission (TAXCOMM) |
| Category | City Government |
| Tags | reduction, action, assessment actions, tax commission, tax, finance, new york city tax commission (taxcomm) |
| Created | 2013-03-01T20:02:10Z |
| Publication Date | 2017-03-15T18:37:59Z |

## Description

Assessment Actions
Actions on Applications in 2016 Reducing Assessments or Reclassifying Property.  Listed here are Tax Commission actions during 2016 reducing assessments or reclassifying property.  KEY:  YR=Assessment year (15=2015/16; 16=2016/17); R=Reduction implemented by remission of taxes; B=Borough (1=Manhattan, 2=Bronx, 3=Brooklyn, 4=Queens, 5=Staten Island); TC=Tax Class or subclass. Classification claims.  Reductions are expressed in total actual assessed value.  For condominiums, actions shown are for representative lots only.

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | borough_code             | Borough Code             | text      | number      |
| Yes      | series tag     | block_number             | Block Number             | text      | number      |
| Yes      | series tag     | lot_number               | Lot Number               | text      | number      |
| Yes      | time           | tax_year                 | Tax Year                 | number    | number      |
| Yes      | series tag     | remission_code           | Remission Code           | text      | text        |
| Yes      | series tag     | owner_name               | Owner Name               | text      | text        |
| No       |                | property_address         | Property Address         | text      | text        |
| Yes      | numeric metric | granted_reduction_amount | Granted Reduction Amount | money     | money       |
| Yes      | series tag     | tax_class_code           | Tax Class Code           | text      | text        |
```

## Time Field

```ls
Value = tax_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = property_address
```

## Data Commands

```ls
series e:4nft-bihw d:2016-01-01T00:00:00.000Z t:lot_number=47 t:owner_name="77TH STREET RLTY ASOC" t:borough_code=1 t:block_number=1129 t:tax_class_code=2 t:remission_code=R m:granted_reduction_amount=295350

series e:4nft-bihw d:2016-01-01T00:00:00.000Z t:lot_number=50 t:owner_name="4077 OWNERS CORP" t:borough_code=1 t:block_number=1129 t:tax_class_code=2 t:remission_code=R m:granted_reduction_amount=1862500

series e:4nft-bihw d:2015-01-01T00:00:00.000Z t:lot_number=55 t:owner_name="PARK 44 CORP" t:borough_code=1 t:block_number=1129 t:tax_class_code=2 t:remission_code=R m:granted_reduction_amount=963800
```

## Meta Commands

```ls
metric m:granted_reduction_amount p:integer l:"Granted Reduction Amount" d:"Assessment reduction in dollars" t:dataTypeName=money

entity e:4nft-bihw l:"Assessment Actions" t:attribution="New York City Tax Commission (TAXCOMM)" t:url=https://data.cityofnewyork.us/api/views/4nft-bihw

property e:4nft-bihw t:meta.view v:id=4nft-bihw v:category="City Government" v:attributionLink=http://www.nyc.gov/html/taxcomm/html/reductions/reductions.shtml v:averageRating=0 v:name="Assessment Actions" v:attribution="New York City Tax Commission (TAXCOMM)"

property e:4nft-bihw t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4nft-bihw t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough_code | block_number | lot_number | tax_year | remission_code | owner_name            | property_address     | granted_reduction_amount | tax_class_code | 
| ============ | ============ | ========== | ======== | ============== | ===================== | ==================== | ======================== | ============== | 
| 1            | 1129         | 47         | 2016     | R              | 77TH STREET RLTY ASOC | 22 WEST 77 STREET    | 295350                   | 2              | 
| 1            | 1129         | 50         | 2016     | R              | 4077 OWNERS CORP      | 40 WEST 77 STREET    | 1862500                  | 2              | 
| 1            | 1129         | 55         | 2015     | R              | PARK 44 CORP          | 44 WEST 77 STREET    | 963800                   | 2              | 
| 1            | 1129         | 55         | 2016     | R              | PARK 44 CORP          | 44 WEST 77 STREET    | 396050                   | 2              | 
| 1            | 1129         | 1001       | 2016     | R              | THE RANA BUCKNER REVO | 53 WEST 76 STREET    | 9325                     | 4              | 
| 1            | 1138         | 34         | 2016     | R              | 148-154 COLUMBUS REAL | 154 COLUMBUS AVENUE  | 228700                   | 2              | 
| 1            | 1138         | 61         | 2016     | R              | 148 W. 67 LLC         | 153 AMSTERDAM AVENUE | 162120                   | 2              | 
| 1            | 1138         | 1001       | 2015     | R              | LINCOLN TRIANGLE COMM | 144 COLUMBUS AVENUE  | 376150                   | 4              | 
| 1            | 1138         | 1001       | 2016     | R              | LINCOLN TRIANGLE COMM | 144 COLUMBUS AVENUE  | 413650                   | 4              | 
| 1            | 1138         | 1002       | 2016     | R              | LINCOLN TRIANGLE COMM | 144 COLUMBUS AVENUE  | 987200                   | 4              | 
```