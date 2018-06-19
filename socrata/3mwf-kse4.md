# Consumer Confidence Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/consumer-confidence-report-09246) |
| Metadata | [Link](https://data.mo.gov/api/views/3mwf-kse4) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/3mwf-kse4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/3mwf-kse4/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 3mwf-kse4 |
| Name | Consumer Confidence Report |
| Category | Natural Resources |
| Created | 2014-11-10T21:03:30Z |
| Publication Date | 2017-04-17T16:33:35Z |

## Description

Public Drinking Water Branch Consumer Confidence Reports

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | pwsid       | PWSID      | text      | text        |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | county      | County     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3mwf-kse4 d:2014-11-10T13:03:33.000Z t:pwsid=MO1010001 t:county=BATES t:name=ADRIAN m:row_number.3mwf-kse4=1

series e:3mwf-kse4 d:2014-11-10T13:03:33.000Z t:pwsid=MO1010006 t:county=GENTRY t:name=ALBANY m:row_number.3mwf-kse4=2

series e:3mwf-kse4 d:2014-11-10T13:03:33.000Z t:pwsid=MO1010009 t:county=LAFAYETTE t:name=ALMA m:row_number.3mwf-kse4=3
```

## Meta Commands

```ls
metric m:row_number.3mwf-kse4 p:long l:"Row Number"

entity e:3mwf-kse4 l:"Consumer Confidence Report" t:url=https://data.mo.gov/api/views/3mwf-kse4

property e:3mwf-kse4 t:meta.view v:id=3mwf-kse4 v:category="Natural Resources" v:averageRating=0 v:name="Consumer Confidence Report"

property e:3mwf-kse4 t:meta.view.owner v:id=6kse-a3fw v:screenName="Paul Schelich" v:displayName="Paul Schelich"

property e:3mwf-kse4 t:meta.view.tableauthor v:id=6kse-a3fw v:screenName="Paul Schelich" v:roleName=publisher v:displayName="Paul Schelich"
```

## Top Records

```ls
| :updated_at | pwsid     | name       | county    | 
| =========== | ========= | ========== | ========= | 
| 1415624613  | MO1010001 | ADRIAN     | BATES     | 
| 1415624613  | MO1010006 | ALBANY     | GENTRY    | 
| 1415624613  | MO1010009 | ALMA       | LAFAYETTE | 
| 1415624613  | MO1010010 | ALTAMONT   | DAVIESS   | 
| 1415624613  | MO1010013 | AMAZONIA   | ANDREW    | 
| 1415624613  | MO1010014 | AMORET     | BATES     | 
| 1415624613  | MO1010024 | ARCHIE     | CASS      | 
| 1415624613  | MO1010046 | BARNARD    | NODAWAY   | 
| 1415624613  | MO1010049 | BATES CITY | LAFAYETTE | 
| 1415624613  | MO1010061 | BELTON     | CASS      | 
```