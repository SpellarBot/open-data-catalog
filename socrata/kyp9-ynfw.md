# Bond Program Spending Summary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bond-program-spending-summary) |
| Metadata | [Link](https://data.austintexas.gov/api/views/kyp9-ynfw) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/kyp9-ynfw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/kyp9-ynfw/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | kyp9-ynfw |
| Name | Bond Program Spending Summary |
| Attribution | City of Austin |
| Category | Capital Planning |
| Tags | cip, bond, bonds |
| Created | 2014-07-07T16:09:57Z |
| Publication Date | 2016-10-03T22:11:35Z |

## Description

The table provides spending details on the City?s voter-approved bond programs. The information summarizes spending by fiscal year quarter starting with FY 13 Q3. Please see the Capital Planning Office website, www.austintexas.gov/cip, for more information about the City?s voter-approved bond programs. The fiscal year begins October 1 and ends September 30. The first fiscal quarter is October through December; the second quarter is January through March; the third fiscal quarter is April through June; and the fourth fiscal quarter is July through September. The following are definitions of terms used in the table. Allocated: The amount of funds designated by the City of Austin Budget Office to be spent per reporting category or proposition. Allocated funds are tied to bond sales, which must be performed in $5,000 increments. Appropriated: City Council authorizes the appropriation of funds, which gives staff the legal authority to expend the funds for a specific purpose. City Council may approve multiple installments of funding throughout the project?s phases. Available: The amount of funds allocated minus the amount encumbered and expended. Available funds are programmed for specific purposes. Encumbered: Commitments made to unperformed contracts for goods or services. Expenditure: Funds that have been paid for goods or services.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | row_id            | Row ID            | text          | number        |
| Yes      | time           | date              | Date              | calendar_date | calendar_date |
| Yes      | series tag     | fiscal_year       | Fiscal Year       | text          | text          |
| No       |                | fiscal_quarter    | Fiscal Quarter    | text          | text          |
| No       |                | bond_program_year | Bond Program Year | number        | text          |
| Yes      | series tag     | proposition       | Proposition       | text          | text          |
| Yes      | numeric metric | allocated         | Allocated         | money         | money         |
| Yes      | numeric metric | spent_1           | Expended          | money         | money         |
| Yes      | numeric metric | spent_2           | % Expended        | percent       | percent       |
| Yes      | numeric metric | encumbered_1      | Encumbered        | money         | money         |
| Yes      | numeric metric | encumbered_2      | % Encumbered      | percent       | percent       |
| Yes      | numeric metric | available_1       | Available         | money         | money         |
| Yes      | numeric metric | available_2       | % Available       | percent       | percent       |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_quarter,bond_program_year
```

## Data Commands

```ls
series e:kyp9-ynfw d:2013-06-30T00:00:00.000Z t:fiscal_year="FY 2013" t:row_id=1 t:proposition="Prop 1: Transportation" m:available_1=835421 m:spent_2=88 m:spent_1=90686257 m:encumbered_2=11 m:encumbered_1=11578322 m:available_2=1 m:allocated=103100000

series e:kyp9-ynfw d:2013-06-30T00:00:00.000Z t:fiscal_year="FY 2013" t:row_id=2 t:proposition="Prop 2: Drainage & Open Space" m:available_1=12958619 m:spent_2=83 m:spent_1=120574105 m:encumbered_2=8 m:encumbered_1=11467276 m:available_2=9 m:allocated=145000000

series e:kyp9-ynfw d:2013-06-30T00:00:00.000Z t:fiscal_year="FY 2013" t:row_id=3 t:proposition="Prop 3: Parks" m:available_1=10111639 m:spent_2=77 m:spent_1=65143310 m:encumbered_2=11 m:encumbered_1=9445050 m:available_2=12 m:allocated=84700000
```

## Meta Commands

```ls
metric m:allocated p:integer l:Allocated t:dataTypeName=money

metric m:spent_1 p:integer l:Expended t:dataTypeName=money

metric m:spent_2 p:integer l:"% Expended" t:dataTypeName=percent

metric m:encumbered_1 p:integer l:Encumbered t:dataTypeName=money

metric m:encumbered_2 p:integer l:"% Encumbered" t:dataTypeName=percent

metric m:available_1 p:integer l:Available t:dataTypeName=money

metric m:available_2 p:integer l:"% Available" t:dataTypeName=percent

entity e:kyp9-ynfw l:"Bond Program Spending Summary" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/kyp9-ynfw

property e:kyp9-ynfw t:meta.view v:id=kyp9-ynfw v:category="Capital Planning" v:averageRating=0 v:name="Bond Program Spending Summary" v:attribution="City of Austin"

property e:kyp9-ynfw t:meta.view.owner v:id=55xj-9sst v:screenName=zashburn v:displayName=zashburn

property e:kyp9-ynfw t:meta.view.tableauthor v:id=55xj-9sst v:screenName=zashburn v:roleName=editor_stories v:displayName=zashburn
```

## Top Records

```ls
| row_id | date                | fiscal_year | fiscal_quarter | bond_program_year | proposition                                  | allocated | spent_1   | spent_2 | encumbered_1 | encumbered_2 | available_1 | available_2 | 
| ====== | =================== | =========== | ============== | ================= | ============================================ | ========= | ========= | ======= | ============ | ============ | =========== | =========== | 
| 1      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2006              | Prop 1: Transportation                       | 103100000 | 90686257  | 88      | 11578322     | 11           | 835421      | 1           | 
| 2      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2006              | Prop 2: Drainage & Open Space                | 145000000 | 120574105 | 83      | 11467276     | 8            | 12958619    | 9           | 
| 3      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2006              | Prop 3: Parks                                | 84700000  | 65143310  | 77      | 9445050      | 11           | 10111639    | 12          | 
| 4      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2006              | Prop 4: Community & Cultural Facilities      | 31500000  | 25180730  | 80      | 522652       | 2            | 5796618     | 18          | 
| 5      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2006              | Prop 5: Affordable Housing                   | 55000000  | 50625927  | 92      | 2334337      | 4            | 2039736     | 4           | 
| 6      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2006              | Prop 6: New Central Library                  | 90000000  | 8588918   | 10      | 2404179      | 3            | 79006903    | 88          | 
| 7      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2006              | Prop 7: Public Safety Facilities             | 58100000  | 43579473  | 75      | 129870       | 0            | 14390656    | 25          | 
| 8      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2006              | Total 2006 Bond Program Summary              | 567400000 | 404378721 | 71      | 37881687     | 7            | 125139592   | 22          | 
| 9      | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2010              | Total 2010 Prop 1: Transportation & Mobility | 90000000  | 43776210  | 49      | 35361154     | 39           | 10862637    | 12          | 
| 10     | 2013-06-30T00:00:00 | FY 2013     | Q3             | 2012              | Prop 12: Transportation & Mobility           | 143299000 | 9149      | 0       | 870233       | 1            | 142419618   | 99          | 
```