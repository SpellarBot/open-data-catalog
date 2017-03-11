# No. of Transactions VS No. of Customers For FY 2014

## Dataset

* [Dataset URL](https://data.ct.gov/api/views/aspx-imar/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/no-of-transactions-vs-no-of-customers-for-fy-2014)
* [Metadata URL](https://data.ct.gov/api/views/aspx-imar)
* Id = aspx-imar
* Name = No. of Transactions VS No. of Customers For FY 2014
* Attribution = Department of Motor Vehicles
* [Attribution Link](http://www.ct.gov/dmv)
* Category = Transportation
* Tags = [dmv]
* Created = 2014-10-01T12:44:47Z
* Publication Date = 2014-10-02T20:02:32Z
* Rows Updated = 2014-10-01T12:46:14Z

## Description



## Columns

```ls
| Name                | Field Name         | Data Type | Render Type | Schema Type    | Included | 
| =================== | ================== | ========= | =========== | ============== | ======== | 
| updated_at          | :updated_at        | meta_data | meta_data   | time           | No       | 
| BRANCH              | branch             | text      | text        | series tag     | Yes      | 
| No. of Transactions | no_of_transactions | number    | number      | numeric metric | Yes      | 
| No. of Customers    | no_of_customers    | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:aspx-imar d:2014-10-01T05:44:50.000Z t:branch="Middletown PLC" m:no_of_transactions=9065 m:no_of_customers=8574

series e:aspx-imar d:2014-10-01T05:44:50.000Z t:branch="Milford PLC" m:no_of_transactions=13506 m:no_of_customers=12757

series e:aspx-imar d:2014-10-01T05:44:50.000Z t:branch="Derby PLC" m:no_of_transactions=16588 m:no_of_customers=15325
```

## Meta Commands

```ls
metric m:no_of_transactions p:integer l:"No. of Transactions" t:dataTypeName=number

metric m:no_of_customers p:integer l:"No. of Customers" t:dataTypeName=number

entity e:aspx-imar l:"No. of Transactions VS No. of Customers For FY 2014" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/aspx-imar

property e:aspx-imar t:meta.view d:2017-03-08T01:11:20.540Z v:id=aspx-imar v:category=Transportation v:attributionLink=http://www.ct.gov/dmv v:averageRating=0 v:name="No. of Transactions VS No. of Customers For FY 2014" v:attribution="Department of Motor Vehicles"

property e:aspx-imar t:meta.view.owner d:2017-03-08T01:11:20.540Z v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel

property e:aspx-imar t:meta.view.tableauthor d:2017-03-08T01:11:20.540Z v:id=fd5k-6njr v:screenName=APatel v:roleName=editor v:displayName=APatel
```