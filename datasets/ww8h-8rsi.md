# Maui County TEFAP Agencies

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maui-county-tefap-agencies-49a99) |
| Metadata | [Link](https://data.hawaii.gov/api/views/ww8h-8rsi) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/ww8h-8rsi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/ww8h-8rsi/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | ww8h-8rsi |
| Name | Maui County TEFAP Agencies |
| Attribution | department of Labor and Industrial Relations |
| Category | Government-Wide Support |
| Tags | maui county agencies |
| Created | 2012-08-22T23:58:11Z |
| Publication Date | 2012-08-24T22:54:00Z |

## Description

Organizations in Maui County participating in the USDA

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | agency      | Agency     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ww8h-8rsi d:2012-08-22T16:58:51.000Z t:agency="Lanai - Sacred Heart Church" m:row_number.ww8h-8rsi=1

series e:ww8h-8rsi d:2012-08-22T16:58:51.000Z t:agency="Family Life Center" m:row_number.ww8h-8rsi=2

series e:ww8h-8rsi d:2012-08-22T16:58:51.000Z t:agency="Maui Family Support Services" m:row_number.ww8h-8rsi=3
```

## Meta Commands

```ls
metric m:row_number.ww8h-8rsi p:long l:"Row Number"

entity e:ww8h-8rsi l:"Maui County TEFAP Agencies" t:attribution="department of Labor and Industrial Relations" t:url=https://data.hawaii.gov/api/views/ww8h-8rsi

property e:ww8h-8rsi t:meta.view v:id=ww8h-8rsi v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dlir v:averageRating=0 v:name="Maui County TEFAP Agencies" v:attribution="department of Labor and Industrial Relations"

property e:ww8h-8rsi t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:ww8h-8rsi t:meta.view.owner v:id=h984-m5gx v:screenName="En Young" v:displayName="En Young"

property e:ww8h-8rsi t:meta.view.tableauthor v:id=h984-m5gx v:screenName="En Young" v:displayName="En Young"
```

## Top Records

```ls
| :updated_at | agency                                                                                         | 
| =========== | ============================================================================================== | 
| 1345654731  | Lanai - Sacred Heart Church                                                                    | 
| 1345654731  | Family Life Center                                                                             | 
| 1345654731  | Maui Family Support Services                                                                   | 
| 1345654731  | Lahaina Baptist                                                                                | 
| 1345654731  | Salvation Army Hale Palekana Kevin Nagasaki Lahaina HI 96761-0456661-3717 (kev.)281383661-8088 | 
| 1345654731  | Malama Family Support                                                                          | 
| 1345654731  | Grace Church                                                                                   | 
| 1345654731  | Child & Family Service                                                                         | 
| 1345654731  | Faith Family Fellowship                                                                        | 
| 1345654731  | St. Joseph Church                                                                              | 
```