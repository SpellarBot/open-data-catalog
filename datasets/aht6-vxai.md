# Open Article 7 Petitions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-article-7-petitions-22ab9) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/aht6-vxai) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/aht6-vxai/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/aht6-vxai/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | aht6-vxai |
| Name | Open Article 7 Petitions |
| Attribution | New York City Tax Commission (TAXCOMM) |
| Category | City Government |
| Tags | new york city tax commission, taxcomm, open petition, article 7, finance |
| Created | 2013-03-01T19:48:20Z |
| Publication Date | 2017-03-03T00:22:07Z |

## Description

The information in the City's computer records with respect to open petitions challenging real property tax assessments pursuant to Article 7 of the Real Property Tax Law: contains the index number and year the petition was commenced, the name of the petitioner, the name of the attorney for the petitioner, and various note of issue codes.

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| Yes      | series tag  | borough_code                | Borough Code                | text      | number      |
| Yes      | series tag  | block_number                | Block Number                | text      | number      |
| Yes      | series tag  | lot_number                  | Lot Number                  | text      | number      |
| Yes      | series tag  | condominium_high_lot_number | Condominium High Lot Number | text      | number      |
| Yes      | time        | petition_year               | Petition Year               | number    | number      |
| Yes      | series tag  | petition_index_number       | Petition Index Number       | text      | number      |
| Yes      | series tag  | petitioner_name             | Petitioner Name             | text      | text        |
| Yes      | series tag  | attorney_identifier         | Attorney Identifier         | text      | number      |
| Yes      | series tag  | attorney_name               | Attorney Name               | text      | text        |
| Yes      | series tag  | notice_of_issuance_code     | Notice Of Issuance Code     | text      | number      |
```

## Time Field

```ls
Value = petition_year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:aht6-vxai l:"Open Article 7 Petitions" t:attribution="New York City Tax Commission (TAXCOMM)" t:url=https://data.cityofnewyork.us/api/views/aht6-vxai

property e:aht6-vxai t:meta.view v:id=aht6-vxai v:category="City Government" v:attributionLink=http://www.nyc.gov/html/taxcomm/html/petitions/petitions.shtml v:averageRating=0 v:name="Open Article 7 Petitions" v:attribution="New York City Tax Commission (TAXCOMM)"

property e:aht6-vxai t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:aht6-vxai t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| borough_code | block_number | lot_number | condominium_high_lot_number | petition_year | petition_index_number | petitioner_name           | attorney_identifier | attorney_name           | notice_of_issuance_code | 
| ============ | ============ | ========== | =========================== | ============= | ===================== | ========================= | =================== | ======================= | ======================= | 
| 1            | 2            | 2          | 0                           | 2013          | 259546                | 10 SSA LANDLORD, LLC      | 135                 | MARCUS & POLLACK LLP    | 0                       | 
| 1            | 2            | 2          | 0                           | 2014          | 252472                | 10 SSA LANDLORD, LLC      | 135                 | MARCUS & POLLACK LLP    | 0                       | 
| 1            | 2            | 2          | 0                           | 2015          | 260797                | 10 SSA LANDLORD, LLC      | 135                 | MARCUS & POLLACK LLP    | 0                       | 
| 1            | 4            | 1001       | 1052                        | 2016          | 254402                | ONE NY PLAZA CO. LLC      | 15                  | STROOCK STROOCK & LAVAN | 0                       | 
| 1            | 5            | 1001       | 0                           | 2007          | 260574                | MACK CALI 125 BROAD A L.L | 135                 | MARCUS & POLLACK LLP    | 510                     | 
| 1            | 5            | 1001       | 0                           | 2008          | 257427                | MACK CALI 125 BROAD A L.L | 135                 | MARCUS & POLLACK LLP    | 510                     | 
| 1            | 5            | 1001       | 0                           | 2009          | 259834                | MACK CALI 125 BROAD A L.L | 135                 | MARCUS & POLLACK LLP    | 510                     | 
| 1            | 5            | 1001       | 0                           | 2010          | 260218                | MACK CALI 125 BROAD A L.L | 135                 | MARCUS & POLLACK LLP    | 510                     | 
| 1            | 5            | 1001       | 0                           | 2011          | 261514                | MACK-CALI 125 BROAD A L.L | 135                 | MARCUS & POLLACK LLP    | 510                     | 
| 1            | 5            | 1001       | 0                           | 2012          | 259825                | MACK-CALI 125 BROAD A L.L | 135                 | MARCUS & POLLACK LLP    | 510                     | 
```