# Stamford School Lookup

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stamford-school-lookup) |
| Metadata | [Link](https://data.ct.gov/api/views/a63s-zxeh) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/a63s-zxeh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/a63s-zxeh/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | a63s-zxeh |
| Name | Stamford School Lookup |
| Attribution | City of Stamford |
| Category | Education |
| Tags | stamford school lookup |
| Created | 2014-11-06T17:59:03Z |
| Publication Date | 2014-11-06T18:02:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type | Render Type |
| ======== | ============== | =========== | ========== | ========= | =========== |
| No       | time           | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | numeric metric | hn_start    | HN_Start   | number    | number      |
| Yes      | numeric metric | hn_end      | HN_End     | number    | number      |
| Yes      | series tag     | side        | Side       | text      | text        |
| Yes      | series tag     | elem_sch    | Elem_Sch   | text      | text        |
| Yes      | series tag     | mid_sch     | Mid_Sch    | text      | text        |
| Yes      | series tag     | h_sch       | H_Sch      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:a63s-zxeh d:2014-11-06T09:59:07.000Z t:h_sch="STAMFORD HIGH SCHOOL" t:side=Both t:elem_sch="JULIA A. STARK" t:mid_sch="DOLAN MIDDLE SCHOOL" m:hn_end=9999 m:hn_start=1

series e:a63s-zxeh d:2014-11-06T09:59:07.000Z t:h_sch="WESTHILL HIGH SCHOOL" t:side=Both t:elem_sch="ROXBURY ELEMENTARY SCHOOL" t:mid_sch="CLOONAN MIDDLE SCHOOL" m:hn_end=9999 m:hn_start=1

series e:a63s-zxeh d:2014-11-06T09:59:07.000Z t:h_sch="WESTHILL HIGH SCHOOL" t:side=Both t:elem_sch="STILLMEADOW ELEMENTARY SCHOOL" t:mid_sch="CLOONAN MIDDLE SCHOOL" m:hn_end=9999 m:hn_start=1
```

## Meta Commands

```ls
metric m:hn_start p:integer l:HN_Start t:dataTypeName=number

metric m:hn_end p:integer l:HN_End t:dataTypeName=number

entity e:a63s-zxeh l:"Stamford School Lookup" t:attribution="City of Stamford" t:url=https://data.ct.gov/api/views/a63s-zxeh

property e:a63s-zxeh t:meta.view v:id=a63s-zxeh v:category=Education v:averageRating=0 v:name="Stamford School Lookup" v:attribution="City of Stamford"

property e:a63s-zxeh t:meta.view.owner v:id=d2jw-b5qp v:screenName="City of Stamford" v:displayName="City of Stamford"

property e:a63s-zxeh t:meta.view.tableauthor v:id=d2jw-b5qp v:screenName="City of Stamford" v:roleName=publisher v:displayName="City of Stamford"
```

## Top Records

```ls
| :updated_at | hn_start | hn_end | side | elem_sch                       | mid_sch                     | h_sch                | 
| =========== | ======== | ====== | ==== | ============================== | =========================== | ==================== | 
| 1415267947  | 1        | 9999   | Both | JULIA A. STARK                 | DOLAN MIDDLE SCHOOL         | STAMFORD HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | ROXBURY ELEMENTARY SCHOOL      | CLOONAN MIDDLE SCHOOL       | WESTHILL HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | STILLMEADOW ELEMENTARY SCHOOL  | CLOONAN MIDDLE SCHOOL       | WESTHILL HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | DAVENPORT RIDGE                | TURN OF RIVER MIDDLE SCHOOL | WESTHILL HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | HART MAGNET SCHOOL             | CLOONAN MIDDLE SCHOOL       | WESTHILL HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | ROXBURY ELEMENTARY SCHOOL      | CLOONAN MIDDLE SCHOOL       | WESTHILL HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | K. T. MURPHY ELEMENTARY SCHOOL | TURN OF RIVER MIDDLE SCHOOL | WESTHILL HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | WESTOVER MAGNET SCHOOL         | CLOONAN MIDDLE SCHOOL       | WESTHILL HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | NORTHEAST ELEMENTARY SCHOOL    | TURN OF RIVER MIDDLE SCHOOL | WESTHILL HIGH SCHOOL | 
| 1415267947  | 1        | 9999   | Both | ROXBURY ELEMENTARY SCHOOL      | CLOONAN MIDDLE SCHOOL       | WESTHILL HIGH SCHOOL | 
```