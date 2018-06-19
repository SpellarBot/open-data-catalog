# FY13 Land Water Grants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fy13-land-water-grants-f72f1) |
| Metadata | [Link](https://data.illinois.gov/api/views/ahhs-g66b) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/ahhs-g66b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/ahhs-g66b/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | ahhs-g66b |
| Name | FY13 Land Water Grants |
| Attribution | IL Department of Agriculture |
| Created | 2014-06-27T20:15:22Z |
| Publication Date | 2014-06-27T20:19:52Z |

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
| Yes      | series tag     | duration_in_days                | Duration (In Days)              | text          | text          |
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
series e:ahhs-g66b d:2012-11-08T00:00:00.000Z t:grantor_agency=IDOA t:grantee_zip_code=62301 t:description_of_purpose_of_award="Distrtict Operations & Partners for Conservation Cost Share" t:grantee="Adams County SWCD" m:grant_amount=61961

series e:ahhs-g66b d:2012-11-08T00:00:00.000Z t:grantor_agency=IDOA t:grantee_zip_code=62246 t:description_of_purpose_of_award="Distrtict Operations & Partners for Conservation Cost Share" t:grantee="Bond County SWCD" m:grant_amount=50661

series e:ahhs-g66b d:2012-11-08T00:00:00.000Z t:grantor_agency=IDOA t:grantee_zip_code=62353 t:description_of_purpose_of_award="Distrtict Operations & Partners for Conservation Cost Share" t:grantee="Brown County SWCD" m:grant_amount=58561
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" t:dataTypeName=money

entity e:ahhs-g66b l:"FY13 Land Water Grants" t:attribution="IL Department of Agriculture" t:url=https://data.illinois.gov/api/views/ahhs-g66b

property e:ahhs-g66b t:meta.view v:id=ahhs-g66b v:averageRating=0 v:name="FY13 Land Water Grants" v:attribution="IL Department of Agriculture"

property e:ahhs-g66b t:meta.view.owner v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"

property e:ahhs-g66b t:meta.view.tableauthor v:id=75n4-7w96 v:screenName="Rhonda Jachino" v:displayName="Rhonda Jachino"
```

## Top Records

```ls
| grantor_agency | grantee               | description_of_purpose_of_award                             | grant_amount | start_date          | completion_date     | duration_in_days | grantee_zip_code | 
| ============== | ===================== | =========================================================== | ============ | =================== | =================== | ================ | ================ | 
| IDOA           | Adams County SWCD     | Distrtict Operations & Partners for Conservation Cost Share | 61961.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 62301            | 
| IDOA           | Bond County SWCD      | Distrtict Operations & Partners for Conservation Cost Share | 50661.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 62246            | 
| IDOA           | Brown County SWCD     | Distrtict Operations & Partners for Conservation Cost Share | 58561.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 62353            | 
| IDOA           | Bureau County SWCD    | Distrtict Operations & Partners for Conservation Cost Share | 58161.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 61356            | 
| IDOA           | Calhoun County SWCD   | Distrtict Operations & Partners for Conservation Cost Share | 55061.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 62047            | 
| IDOA           | Carroll County SWCD   | Distrtict Operations & Partners for Conservation Cost Share | 56261.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 61053            | 
| IDOA           | Cass County SWCD      | Distrtict Operations & Partners for Conservation Cost Share | 53961.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 62691            | 
| IDOA           | Champaign County SWCD | Distrtict Operations & Partners for Conservation Cost Share | 115826.00    | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 61821            | 
| IDOA           | Christian County SWCD | Distrtict Operations & Partners for Conservation Cost Share | 50661.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 62568            | 
| IDOA           | Clark County SWCD     | Distrtict Operations & Partners for Conservation Cost Share | 64161.00     | 2012-11-08T00:00:00 | 2013-06-18T00:00:00 |                  | 62442            | 
```