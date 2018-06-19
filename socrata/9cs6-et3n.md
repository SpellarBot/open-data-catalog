# Hawaii State Ethics Commission's Public Disclosures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-state-ethics-commissions-public-disclosures) |
| Metadata | [Link](https://data.hawaii.gov/api/views/9cs6-et3n) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/9cs6-et3n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/9cs6-et3n/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 9cs6-et3n |
| Name | Hawaii State Ethics Commission's Public Disclosures |
| Created | 2013-10-29T23:44:30Z |
| Publication Date | 2017-04-18T01:54:32Z |

## Columns

```ls
| Included | Schema Type | Field Name           | Name       | Data Type     | Render Type   |
| ======== | =========== | ==================== | ========== | ============= | ============= |
| Yes      | series tag  | filer                | Filer      | text          | text          |
| Yes      | series tag  | financial_disclosure | View       | url           | url           |
| Yes      | series tag  | title                | Title      | text          | text          |
| Yes      | series tag  | dept_board           | Dept/Board | text          | text          |
| Yes      | series tag  | file_type            | File Type  | text          | text          |
| No       |             | file_year            | File Year  | number        | text          |
| Yes      | time        | date_filed           | Date Filed | calendar_date | calendar_date |
| Yes      | series tag  | original             | Original   | checkbox      | checkbox      |
| Yes      | series tag  | amended              | Amended    | checkbox      | checkbox      |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = file_year
```

## Data Commands

```ls
series e:9cs6-et3n d:2012-06-22T00:00:00.000Z t:filer="Yamane, Ryan Ichiro" t:amended=false t:title="Legislator, District 37" t:original=true t:dept_board="House of Representatives" t:financial_disclosure=http://files.hawaii.gov/ethics/disc/2012/KfxDis-3334.pdf t:file_type=Gift m:row_number.9cs6-et3n=1

series e:9cs6-et3n d:2012-06-22T00:00:00.000Z t:filer="Heim, Darolyn Lendio" t:amended=false t:title="Vice President, Legal Affairs and University General Counsel" t:original=true t:dept_board="University of Hawaii-System" t:financial_disclosure=http://files.hawaii.gov/ethics/disc/2012/KfxDis-3335.pdf t:file_type=Gift m:row_number.9cs6-et3n=2

series e:9cs6-et3n d:2012-06-29T00:00:00.000Z t:filer="Saiki, Scott K." t:amended=false t:title="Legislator, District 26" t:original=false t:dept_board="House of Representatives" t:financial_disclosure=http://files.hawaii.gov/ethics/disc/2012/KfxDis-3544.pdf t:file_type=Gift m:row_number.9cs6-et3n=3
```

## Meta Commands

```ls
metric m:row_number.9cs6-et3n p:long l:"Row Number"

entity e:9cs6-et3n l:"Hawaii State Ethics Commission's Public Disclosures" t:url=https://data.hawaii.gov/api/views/9cs6-et3n

property e:9cs6-et3n t:meta.view v:id=9cs6-et3n v:averageRating=0 v:name="Hawaii State Ethics Commission's Public Disclosures"

property e:9cs6-et3n t:meta.view.owner v:id=ikz2-vjne v:screenName=PatrickLui v:displayName=PatrickLui

property e:9cs6-et3n t:meta.view.tableauthor v:id=ikz2-vjne v:screenName=PatrickLui v:roleName=editor v:displayName=PatrickLui
```

## Top Records

```ls
| filer                | financial_disclosure                                             | title                                                        | dept_board                  | file_type | file_year | date_filed          | original | amended | 
| ==================== | ================================================================ | ============================================================ | =========================== | ========= | ========= | =================== | ======== | ======= | 
| Yamane, Ryan Ichiro  | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3334.pdf, Form] | Legislator, District 37                                      | House of Representatives    | Gift      | 2012      | 2012-06-22T00:00:00 | true     | false   | 
| Heim, Darolyn Lendio | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3335.pdf, Form] | Vice President, Legal Affairs and University General Counsel | University of Hawaii-System | Gift      | 2012      | 2012-06-22T00:00:00 | true     | false   | 
| Saiki, Scott K.      | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3544.pdf, Form] | Legislator, District 26                                      | House of Representatives    | Gift      | 2012      | 2012-06-29T00:00:00 | false    | false   | 
| Har, Sharon E.       | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3545.pdf, Form] | Legislator, District 42                                      | House of Representatives    | Gift      | 2012      | 2012-06-29T00:00:00 | true     | false   | 
| Rhoads, Karl A.      | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3546.pdf, Form] | Legislator, District 29                                      | House of Representatives    | Gift      | 2012      | 2012-06-29T00:00:00 | true     | false   | 
| Tsutsui, Shan S.     | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3547.pdf, Form] | Legislator, District 4                                       | Senate                      | Gift      | 2012      | 2012-06-29T00:00:00 | true     | false   | 
| Belatti, Della Au    | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3548.pdf, Form] | Legislator, District 24                                      | House of Representatives    | Gift      | 2012      | 2012-06-29T00:00:00 | true     | false   | 
| Kim, Donna Mercado   | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3557.pdf, Form] | Legislator, District 14                                      | Senate                      | Gift      | 2012      | 2012-07-02T00:00:00 | true     | false   | 
| Yamashita, Kyle T.   | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3558.pdf, Form] | Legislator, District 12                                      | House of Representatives    | Gift      | 2012      | 2012-07-02T00:00:00 | true     | false   | 
| Clerinx, Wendy Y.    | [http://files.hawaii.gov/ethics/disc/2012/KfxDis-3559.pdf, Form] | Director, Policy                                             | Office of the Governor      | Gift      | 2012      | 2012-07-02T00:00:00 | true     | false   | 
```