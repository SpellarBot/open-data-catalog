# Hawaii State Ethics Commission's Organizations' Expenditure Statements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaii-state-ethics-commissions-organizations-expenditure-statements-36b1b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/mq8q-3qtk) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/mq8q-3qtk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/mq8q-3qtk/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | mq8q-3qtk |
| Name | Hawaii State Ethics Commission's Organizations' Expenditure Statements |
| Created | 2013-11-13T23:09:11Z |
| Publication Date | 2017-04-18T02:22:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name              | Data Type     | Render Type   |
| ======== | ============== | ================ | ================= | ============= | ============= |
| Yes      | series tag     | organization     | Organization Name | text          | text          |
| Yes      | series tag     | expenditure_form | View              | url           | url           |
| Yes      | numeric metric | compensation     | Compensation      | money         | money         |
| Yes      | numeric metric | total            | Total Expense     | money         | money         |
| Yes      | series tag     | period           | Lobby Period      | text          | text          |
| No       |                | lobyear          | Year              | number        | text          |
| Yes      | time           | received_date    | Date Filed        | calendar_date | calendar_date |
| Yes      | series tag     | original         | Original          | checkbox      | checkbox      |
| Yes      | series tag     | amended          | Amended           | checkbox      | checkbox      |
```

## Time Field

```ls
Value = received_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lobyear
```

## Data Commands

```ls
series e:mq8q-3qtk d:2017-03-30T00:00:00.000Z t:amended=false t:organization="Charter Communication, Inc." t:original=true t:expenditure_form=http://files.hawaii.gov/ethics/orgexp/2017/Kfx10-14468.PDF t:period="Jan. 1-Feb. 28, 2017" m:compensation=2100 m:total=2100

series e:mq8q-3qtk d:2013-03-28T00:00:00.000Z t:amended=false t:organization="Apple Inc." t:original=true t:expenditure_form=http://files.hawaii.gov/ethics/orgexp/2013/ORG-1272-2013-01_Kfx10-2792.pdf t:period="Jan. 1-Feb. 28, 2013" m:compensation=0 m:total=400

series e:mq8q-3qtk d:2013-05-07T00:00:00.000Z t:amended=true t:organization="Apple Inc." t:original=true t:expenditure_form=http://files.hawaii.gov/ethics/orgexp/2013/ORG-1272-2013-01_Kfx10-3204.pdf t:period="Jan. 1-Feb. 28, 2013" m:compensation=0 m:total=420
```

## Meta Commands

```ls
metric m:compensation p:double l:Compensation t:dataTypeName=money

metric m:total p:double l:"Total Expense" t:dataTypeName=money

entity e:mq8q-3qtk l:"Hawaii State Ethics Commission's Organizations' Expenditure Statements" t:url=https://data.hawaii.gov/api/views/mq8q-3qtk

property e:mq8q-3qtk t:meta.view v:id=mq8q-3qtk v:averageRating=0 v:name="Hawaii State Ethics Commission's Organizations' Expenditure Statements"

property e:mq8q-3qtk t:meta.view.owner v:id=ikz2-vjne v:screenName=PatrickLui v:displayName=PatrickLui

property e:mq8q-3qtk t:meta.view.tableauthor v:id=ikz2-vjne v:screenName=PatrickLui v:roleName=editor v:displayName=PatrickLui
```

## Top Records

```ls
| organization                   | expenditure_form                                                                     | compensation | total    | period                  | lobyear | received_date       | original | amended | 
| ============================== | ==================================================================================== | ============ | ======== | ======================= | ======= | =================== | ======== | ======= | 
| Charter Communication, Inc.    | [http://files.hawaii.gov/ethics/orgexp/2017/Kfx10-14468.PDF, Form]                   | 2100.00      | 2100.00  | Jan. 1-Feb. 28, 2017    | 2017    | 2017-03-30T00:00:00 | true     | false   | 
| Apple Inc.                     | [http://files.hawaii.gov/ethics/orgexp/2013/ORG-1272-2013-01_Kfx10-2792.pdf, Form]   | 0.00         | 400.00   | Jan. 1-Feb. 28, 2013    | 2013    | 2013-03-28T00:00:00 | true     | false   | 
| Apple Inc.                     | [http://files.hawaii.gov/ethics/orgexp/2013/ORG-1272-2013-01_Kfx10-3204.pdf, Form]   | 0.00         | 420.00   | Jan. 1-Feb. 28, 2013    | 2013    | 2013-05-07T00:00:00 | true     | true    | 
| Apple Inc.                     | [http://files.hawaii.gov/ethics/orgexp/2013/ORG-1272-2013-02.pdf, Form]              | 2605.00      | 2605.00  | Mar. 1-Apr. 30, 2013    | 2013    | 2013-05-28T00:00:00 | true     | false   | 
| Apple Inc.                     | [http://files.hawaii.gov/ethics/orgexp/2016/ORG-1272-2016-SS1_Kfx10-12475.pdf, Form] | 0.00         | 0.00     | 2016 Special Session #1 | 2016    | 2016-07-25T00:00:00 | true     | false   | 
| Automated HealthCare Solutions | [http://files.hawaii.gov/ethics/orgexp/2013/ORG-1278-2013-01_Kfx10-2680.pdf, Form]   | 5796.75      | 5796.75  | Jan. 1-Feb. 28, 2013    | 2013    | 2013-03-28T00:00:00 | false    | false   | 
| Automated HealthCare Solutions | [http://files.hawaii.gov/ethics/orgexp/2013/ORG-1278-2013-01_Kfx10-2970.pdf, Form]   | 5796.75      | 5796.75  | Jan. 1-Feb. 28, 2013    | 2013    | 2013-03-28T00:00:00 | true     | false   | 
| Automated HealthCare Solutions | [http://files.hawaii.gov/ethics/orgexp/2013/ORG-1278-2013-02.pdf, Form]              | 3283.71      | 3283.71  | Mar. 1-Apr. 30, 2013    | 2013    | 2013-05-31T00:00:00 | true     | false   | 
| Automated HealthCare Solutions | [http://files.hawaii.gov/ethics/orgexp/2013/ORG-1278-2013-02-A.pdf, Form]            | 8283.71      | 8283.71  | Mar. 1-Apr. 30, 2013    | 2013    | 2013-05-31T00:00:00 | true     | true    | 
| Automated HealthCare Solutions | [http://files.hawaii.gov/ethics/orgexp/2016/ORG-1278-2016-03_Kfx10-14120.pdf, Form]  | 5331.83      | 11998.55 | May 1-Dec. 31, 2016     | 2016    | 2017-02-16T00:00:00 | true     | false   | 
```