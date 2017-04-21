# Oahu TEFAP Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oahu-tefap-agencies-6fe92) |
| Metadata | [Link](https://data.hawaii.gov/api/views/e4jf-2nsz) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/e4jf-2nsz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/e4jf-2nsz/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | e4jf-2nsz |
| Name | Oahu TEFAP Agencies |
| Attribution | department of Labor and Industrial Relations |
| Category | Government-Wide Support |
| Tags | oahu tefap |
| Created | 2012-08-22T22:38:37Z |
| Publication Date | 2012-08-24T22:54:22Z |

## Description

Organizations participating in the USDA Emergency Food Assistance Program

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | agency_name | AGENCY NAME | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:e4jf-2nsz d:2012-08-22T16:49:51.000Z t:agency_name="STS. PETER AND PAUL CHURCH" m:row_number.e4jf-2nsz=1

series e:e4jf-2nsz d:2012-08-22T16:49:51.000Z t:agency_name="WINDWARD UNITED CHURCH OF CHRI" m:row_number.e4jf-2nsz=2

series e:e4jf-2nsz d:2012-08-22T16:49:51.000Z t:agency_name="ST. MARK LUTHERAN CHURCH" m:row_number.e4jf-2nsz=3
```

## Meta Commands

```ls
metric m:row_number.e4jf-2nsz p:long l:"Row Number"

entity e:e4jf-2nsz l:"Oahu TEFAP Agencies" t:attribution="department of Labor and Industrial Relations" t:url=https://data.hawaii.gov/api/views/e4jf-2nsz

property e:e4jf-2nsz t:meta.view v:id=e4jf-2nsz v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dlir v:averageRating=0 v:name="Oahu TEFAP Agencies" v:attribution="department of Labor and Industrial Relations"

property e:e4jf-2nsz t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:e4jf-2nsz t:meta.view.owner v:id=h984-m5gx v:screenName="En Young" v:displayName="En Young"

property e:e4jf-2nsz t:meta.view.tableauthor v:id=h984-m5gx v:screenName="En Young" v:displayName="En Young"
```

## Top Records

```ls
| :updated_at | agency_name                        | 
| =========== | ================================== | 
| 1345654191  | STS. PETER AND PAUL CHURCH         | 
| 1345654191  | WINDWARD UNITED CHURCH OF CHRI     | 
| 1345654191  | ST. MARK LUTHERAN CHURCH           | 
| 1345654191  | CENTRAL UNION CHURCH               | 
| 1345654191  | GREATER MOUNT ZION HOLINESS CHURCH | 
| 1345654191  | HCAP - CENTRAL                     | 
| 1345654191  | SALVATION ARMY - KANEOHE           | 
| 1345654191  | JOYFUL MINISTRIES                  | 
| 1345654191  | CITY OF REFUGE CHRISTIAN CHURCH    | 
| 1345654191  | HONOLULU FIL-AM SDA CHURCH         | 
```