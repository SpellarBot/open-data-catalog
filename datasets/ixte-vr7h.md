# Spending Disclosure - Fiscal Year 2013

## Dataset

* [Dataset URL](https://data.montgomerycountymd.gov/api/views/ixte-vr7h/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/spending-disclosure-fiscal-year-2013-620d4)
* Id = ixte-vr7h
* Name = Spending Disclosure - Fiscal Year 2013
* Attribution = Montgomery County Department of Finance
* Category = Finance/Tax/Property
* Tags = [financial, fiscal year 13, 2013, spending, $25, 000 or more]
* Created = 2013-08-30T19:38:39Z
* Publication Date = 2013-09-03T19:39:48Z
* Rows Updated = 2013-09-03T19:36:30Z

## Description

The purpose of this Spending Disclosure FY13 dataset is to allow the public to search and view summary information on payments made to recipients (referred to as suppliers) that received $25,000 or more in a fiscal year. Note that salary and benefit payments to employees, pension payments to retirees, and any information that is confidential under State or Federal law is excluded from disclosure.

## Columns

```ls
| Name          | Field Name    | Data Type | Render Type | Schema Type    | Included | 
| ============= | ============= | ========= | =========== | ============== | ======== | 
| updated_at    | :updated_at   | meta_data | meta_data   | time           | Yes      | 
| Supplier Name | supplier_name | text      | text        | series tag     | Yes      | 
| Zip Code      | zip_code      | text      | text        | series tag     | Yes      | 
| Department    | department    | text      | text        | series tag     | Yes      | 
| Amount        | amount        | money     | money       | numeric metric | Yes      | 
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
series e:ixte-vr7h d:2013-09-03T12:34:01.000Z t:zip_code=55170 t:department="Not Defined" t:supplier_name="US BANK" m:amount=1200000

series e:ixte-vr7h d:2013-09-03T12:34:01.000Z t:zip_code=75266 t:department=Police t:supplier_name=VERIZON m:amount=1869.45

series e:ixte-vr7h d:2013-09-03T12:34:01.000Z t:zip_code=60197 t:department=Police t:supplier_name="WEST GROUP" m:amount=292
```

## Meta Commands

```ls
entity e:ixte-vr7h l:"Spending Disclosure - Fiscal Year 2013" t:attribution="Montgomery County Department of Finance" t:url=https://data.montgomerycountymd.gov/api/views/ixte-vr7h

property e:ixte-vr7h t:meta.view d:2017-03-03T14:08:25.026Z v:id=ixte-vr7h v:category=Finance/Tax/Property v:averageRating=0 v:name="Spending Disclosure - Fiscal Year 2013" v:attribution="Montgomery County Department of Finance"

property e:ixte-vr7h t:meta.view.owner d:2017-03-03T14:08:25.026Z v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"

property e:ixte-vr7h t:meta.view.tableauthor d:2017-03-03T14:08:25.026Z v:id=qzhb-tftn v:screenName="Kathy Luh" v:roleName=administrator v:displayName="Kathy Luh"
```