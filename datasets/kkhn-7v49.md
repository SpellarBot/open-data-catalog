# OEIG Founded Complaints by Agency

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oeig-founded-complaints-by-agency-90cb8) |
| Metadata | [Link](https://data.illinois.gov/api/views/kkhn-7v49) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/kkhn-7v49/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/kkhn-7v49/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | kkhn-7v49 |
| Name | OEIG Founded Complaints by Agency |
| Created | 2011-09-13T15:31:03Z |
| Publication Date | 2011-09-13T15:31:03Z |

## Description

Founded Complaints by Agency from the Office of Executive Inspector General Annual Report, Fiscal Year 2011, Appendix F.

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag     | agency      | Agency     | text      | text        |
| Yes      | numeric metric | fy_2010     | FY 2010    | number    | number      |
| Yes      | numeric metric | fy_2011     | FY 2011    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kkhn-7v49 d:2011-09-13T08:31:04.000Z t:agency=Aging m:fy_2010=1 m:fy_2011=1

series e:kkhn-7v49 d:2011-09-13T08:31:04.000Z t:agency=Agriculture m:fy_2010=1 m:fy_2011=1

series e:kkhn-7v49 d:2011-09-13T08:31:04.000Z t:agency="Board of Education" m:fy_2010=1 m:fy_2011=0
```

## Meta Commands

```ls
metric m:fy_2010 p:integer l:"FY 2010" t:dataTypeName=number

metric m:fy_2011 p:integer l:"FY 2011" t:dataTypeName=number

entity e:kkhn-7v49 l:"OEIG Founded Complaints by Agency" t:url=https://data.illinois.gov/api/views/kkhn-7v49

property e:kkhn-7v49 t:meta.view v:id=kkhn-7v49 v:averageRating=0 v:name="OEIG Founded Complaints by Agency"

property e:kkhn-7v49 t:meta.view.owner v:id=4met-hnmi v:screenName=S.Reinke v:displayName=S.Reinke

property e:kkhn-7v49 t:meta.view.tableauthor v:id=4met-hnmi v:screenName=S.Reinke v:roleName=publisher v:displayName=S.Reinke
```

## Top Records

```ls
| :updated_at | agency                          | fy_2010 | fy_2011 | 
| =========== | =============================== | ======= | ======= | 
| 1315902664  | Aging                           | 1       | 1       | 
| 1315902664  | Agriculture                     | 1       | 1       | 
| 1315902664  | Board of Education              | 1       | 0       | 
| 1315902664  | Board of Higher Education       | 0       | 1       | 
| 1315902664  | Capital Development Board       | 1       | 1       | 
| 1315902664  | Central Management Services     | 2       | 2       | 
| 1315902664  | Children & Family Services      | 2       | 1       | 
| 1315902664  | Commerce & Economic Opportunity | 1       | 2       | 
| 1315902664  | Corrections                     | 1       | 6       | 
| 1315902664  | Eastern Illinois University     | 1       | 4       | 
```