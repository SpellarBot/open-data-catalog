# Marketing FY13

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/marketing-fy13-490f9) |
| Metadata | [Link](https://data.illinois.gov/api/views/7fnj-w8cj) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/7fnj-w8cj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/7fnj-w8cj/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 7fnj-w8cj |
| Name | Marketing FY13 |
| Created | 2014-06-27T20:34:35Z |
| Publication Date | 2014-06-27T20:35:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | ============== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag     | grantor_agency                  | Grantor Agency                  | text          | text          |
| Yes      | series tag     | grantee                         | Grantee                         | text          | text          |
| Yes      | series tag     | description_of_purpose_of_award | Description of Purpose of Award | text          | text          |
| Yes      | numeric metric | grant_amount                    | Grant Amount                    | money         | money         |
| Yes      | time           | start_date                      | Start Date                      | calendar_date | calendar_date |
| No       |                | completion_date                 | Completion Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | duration_in_days                | Duration (in days)              | number        | number        |
| Yes      | series tag     | grantee_zip_code                | Grantee Zip Code                | text          | number        |
```

## Time Field

```ls
Value = start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = completion_date
```

## Data Commands

```ls
series e:7fnj-w8cj d:2012-07-01T00:00:00.000Z t:grantor_agency="Illinois Department of Agriculture" t:grantee_zip_code=60035 t:description_of_purpose_of_award="National Organic Certification Cost Share Program" t:grantee="Nurturing Buddha LLC" m:grant_amount=750 m:duration_in_days=364

series e:7fnj-w8cj d:2012-07-01T00:00:00.000Z t:grantor_agency="Illinois Department of Agriculture" t:grantee_zip_code=60609 t:description_of_purpose_of_award="National Organic Certification Cost Share Program" t:grantee="GOOD FOOD ORGANICS" m:grant_amount=750 m:duration_in_days=364

series e:7fnj-w8cj d:2012-07-01T00:00:00.000Z t:grantor_agency="Illinois Department of Agriculture" t:grantee_zip_code=61739 t:description_of_purpose_of_award="National Organic Certification Cost Share Program" t:grantee="FRIEDMAN SCOTT" m:grant_amount=750 m:duration_in_days=364
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" t:dataTypeName=money

metric m:duration_in_days p:integer l:"Duration (in days)" t:dataTypeName=number

entity e:7fnj-w8cj l:"Marketing FY13" t:url=https://data.illinois.gov/api/views/7fnj-w8cj

property e:7fnj-w8cj t:meta.view v:id=7fnj-w8cj v:averageRating=0 v:name="Marketing FY13"

property e:7fnj-w8cj t:meta.view.owner v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"

property e:7fnj-w8cj t:meta.view.tableauthor v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"
```

## Top Records

```ls
| grantor_agency                     | grantee                    | description_of_purpose_of_award                   | grant_amount | start_date          | completion_date     | duration_in_days | grantee_zip_code | 
| ================================== | ========================== | ================================================= | ============ | =================== | =================== | ================ | ================ | 
| Illinois Department of Agriculture | Nurturing Buddha LLC       | National Organic Certification Cost Share Program | 750.00       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 60035            | 
| Illinois Department of Agriculture | GOOD FOOD ORGANICS         | National Organic Certification Cost Share Program | 750.00       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 60609            | 
| Illinois Department of Agriculture | FRIEDMAN SCOTT             | National Organic Certification Cost Share Program | 750.00       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 61739            | 
| Illinois Department of Agriculture | NEEDHAM ALEXANDER          | National Organic Certification Cost Share Program | 750.00       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 60030            | 
| Illinois Department of Agriculture | CHERNISS JON               | National Organic Certification Cost Share Program | 697.50       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 61802            | 
| Illinois Department of Agriculture | HAYNES LISA/TOMAHNOUS FARM | National Organic Certification Cost Share Program | 622.50       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 61853            | 
| Illinois Department of Agriculture | THRONEBURG MONTE/KASAMON   | National Organic Certification Cost Share Program | 693.75       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 62510            | 
| Illinois Department of Agriculture | ABELEI INC                 | National Organic Certification Cost Share Program | 750.00       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 60542            | 
| Illinois Department of Agriculture | GREAT AMERICAN LAND CO     | National Organic Certification Cost Share Program | 750.00       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 62469            | 
| Illinois Department of Agriculture | METROPOLIS COFFEE CO       | National Organic Certification Cost Share Program | 750.00       | 2012-07-01T00:00:00 | 2013-06-30T00:00:00 | 364              | 60640            | 
```