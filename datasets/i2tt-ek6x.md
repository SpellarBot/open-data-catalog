# DBEDT Hawaii Utility Companies Rank Among The Top

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dbedt-hawaii-utility-companies-rank-among-the-top-9384e) |
| Metadata | [Link](https://data.hawaii.gov/api/views/i2tt-ek6x) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/i2tt-ek6x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/i2tt-ek6x/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | i2tt-ek6x |
| Name | DBEDT Hawaii Utility Companies Rank Among The Top |
| Attribution | Department of Economic Development and Tourism |
| Category | Economic Development |
| Tags | utility, energy, electric |
| Created | 2012-08-28T20:25:39Z |
| Publication Date | 2012-08-29T01:32:59Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                      | Name                                            | Data Type | Render Type |
| ======== | ============== | =============================================== | =============================================== | ========= | =========== |
| No       | time           | :updated_at                                     | updated_at                                      | meta_data | meta_data   |
| Yes      | series tag     | utility                                         | Utility                                         | text      | text        |
| Yes      | numeric metric | number_of_systems_installed_per_1_000_customers | Number of Systems Installed per 1,000 Customers | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i2tt-ek6x d:2012-08-28T13:25:40.000Z t:utility="1. Roseville Electric (CA)" m:number_of_systems_installed_per_1_000_customers=19.9

series e:i2tt-ek6x d:2012-08-28T13:25:40.000Z t:utility="2. Verendrye Electric Co-op (ND)" m:number_of_systems_installed_per_1_000_customers=18.8

series e:i2tt-ek6x d:2012-08-28T13:25:40.000Z t:utility="3. City of Palo Alto Utilities (CA)" m:number_of_systems_installed_per_1_000_customers=14.8
```

## Meta Commands

```ls
metric m:number_of_systems_installed_per_1_000_customers p:float l:"Number of Systems Installed per 1,000 Customers" t:dataTypeName=number

entity e:i2tt-ek6x l:"DBEDT Hawaii Utility Companies Rank Among The Top" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/i2tt-ek6x

property e:i2tt-ek6x t:meta.view v:id=i2tt-ek6x v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii Utility Companies Rank Among The Top" v:attribution="Department of Economic Development and Tourism"

property e:i2tt-ek6x t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:i2tt-ek6x t:meta.view.owner v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:i2tt-ek6x t:meta.view.tableauthor v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```

## Top Records

```ls
| :updated_at | utility                                       | number_of_systems_installed_per_1_000_customers | 
| =========== | ============================================= | =============================================== | 
| 1346160340  | 1. Roseville Electric (CA)                    | 19.9                                            | 
| 1346160340  | 2. Verendrye Electric Co-op (ND)              | 18.8                                            | 
| 1346160340  | 3. City of Palo Alto Utilities (CA)           | 14.8                                            | 
| 1346160340  | 4. Maui Electric Co. (HI)                     | 13.8                                            | 
| 1346160340  | 5. Sulphur Springs Valley Electric Co-op (AZ) | 11.9                                            | 
| 1346160340  | 6. Hawaiian Electric Co., Inc. (HI)           | 11.3                                            | 
| 1346160340  | 7. Hawaii Electric Light Co. (HI)             | 10.7                                            | 
| 1346160340  | 8. City of Banning (CA)                       | 9.1                                             | 
| 1346160340  | 9. Pacific Gas & Electric (CA)                | 9.0                                             | 
| 1346160340  | 10. San Diego Gas & Electric (CA)             | 8.6                                             | 
```