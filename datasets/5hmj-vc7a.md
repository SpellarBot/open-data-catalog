# Grant Information Collection Act Combined 4th Quarter 2015 And 1st Quarter 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grant-information-collection-act-combined-4th-quarter-2015-and-1st-quarter-2016) |
| Metadata | [Link](https://data.illinois.gov/api/views/5hmj-vc7a) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/5hmj-vc7a/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/5hmj-vc7a/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 5hmj-vc7a |
| Name | Grant Information Collection Act Combined 4th Quarter 2015 And 1st Quarter 2016 |
| Attribution | Illinois Arts Council Agency |
| Tags | illinois arts council agency, iaca, 4th quarter 2015. 1st quarter 2016 |
| Created | 2016-11-01T20:55:30Z |
| Publication Date | 2016-11-01T21:00:41Z |

## Description

There were no 4th Quarter 2015 Grants. 4th Quarter 2015 was therefore combined with 1st Quarter 2016

## Columns

```ls
| Included | Schema Type    | Field Name | Name             | Data Type     | Render Type   |
| ======== | ============== | ========== | ================ | ============= | ============= |
| Yes      | series tag     | flname     | FLName           | text          | text          |
| Yes      | series tag     | title      | Title            | text          | text          |
| Yes      | numeric metric | grant      | Grant            | money         | money         |
| Yes      | time           | dvo        | Grant Award Date | calendar_date | calendar_date |
| No       |                | beg        | Beg              | calendar_date | calendar_date |
| No       |                | end        | End              | calendar_date | calendar_date |
```

## Time Field

```ls
Value = dvo
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = beg,end
```

## Data Commands

```ls
series e:5hmj-vc7a d:2016-03-11T00:00:00.000Z t:title="for Community Arts Access Program" t:flname="Evanston Arts Council" m:grant=9115

series e:5hmj-vc7a d:2016-02-04T00:00:00.000Z t:title="for Community Arts Access Program" t:flname="Highland Park Cultural Arts Commission" m:grant=4365

series e:5hmj-vc7a d:2016-02-22T00:00:00.000Z t:title="for Community Arts Access Program" t:flname="Chicago Dept of Cultural Aff/Spec Events" m:grant=138650
```

## Meta Commands

```ls
metric m:grant p:integer l:Grant t:dataTypeName=money

entity e:5hmj-vc7a l:"Grant Information Collection Act Combined 4th Quarter 2015 And 1st Quarter 2016" t:attribution="Illinois Arts Council Agency" t:url=https://data.illinois.gov/api/views/5hmj-vc7a

property e:5hmj-vc7a t:meta.view v:id=5hmj-vc7a v:attributionLink=http://arts.illinois.gov v:averageRating=0 v:name="Grant Information Collection Act Combined 4th Quarter 2015 And 1st Quarter 2016" v:attribution="Illinois Arts Council Agency"

property e:5hmj-vc7a t:meta.view.owner v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"

property e:5hmj-vc7a t:meta.view.tableauthor v:id=5ugp-negb v:screenName="George Tarasuk" v:displayName="George Tarasuk"
```

## Top Records

```ls
| flname                                   | title                                                          | grant  | dvo                 | beg                 | end                 | 
| ======================================== | ============================================================== | ====== | =================== | =================== | =================== | 
| Evanston Arts Council                    | for Community Arts Access Program                              | 9115   | 2016-03-11T00:00:00 | 2016-02-01T00:00:00 | 2016-08-31T00:00:00 | 
| Highland Park Cultural Arts Commission   | for Community Arts Access Program                              | 4365   | 2016-02-04T00:00:00 | 2016-02-01T00:00:00 | 2016-08-31T00:00:00 | 
| Chicago Dept of Cultural Aff/Spec Events | for Community Arts Access Program                              | 138650 | 2016-02-22T00:00:00 | 2016-02-01T00:00:00 | 2016-08-31T00:00:00 | 
| South Elem School #18144                 | for a four-week theatre residency with Lookingglass Theatre Co | 5240   | 2016-02-04T00:00:00 | 2016-02-01T00:00:00 | 2016-08-15T00:00:00 | 
| Oak Park Area Arts Council               | ArtsFunds                                                      | 9120   | 2016-02-04T00:00:00 | 2016-02-01T00:00:00 | 2016-08-31T00:00:00 | 
| Springfield Area Arts Council            | for Community Arts Access Program                              | 6745   | 2016-02-04T00:00:00 | 2016-02-01T00:00:00 | 2016-08-31T00:00:00 | 
| Quad City Arts                           | for Poetry Out Loud project support                            | 2500   | 2016-02-04T00:00:00 | 2016-02-01T00:00:00 | 2016-06-30T00:00:00 | 
| Convent of the Sacred Heart              | for a four-week music residency with Michael Miles             | 4605   | 2016-02-04T00:00:00 | 2016-02-01T00:00:00 | 2016-08-15T00:00:00 | 
| Decatur Area Arts Council                | for Community Arts Access Program                              | 8165   | 2016-01-26T00:00:00 | 2016-02-01T00:00:00 | 2016-08-31T00:00:00 | 
| Springfield Area Arts Council            | for Poetry Out Loud project support                            | 18000  | 2016-02-04T00:00:00 | 2016-02-01T00:00:00 | 2016-06-30T00:00:00 | 
```