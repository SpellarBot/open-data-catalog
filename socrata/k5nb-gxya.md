# Licensed Veterinary Technicians - updated 12/20/2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-veterinary-technicians-updated-12-20-2016) |
| Metadata | [Link](https://data.maryland.gov/api/views/k5nb-gxya) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/k5nb-gxya/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/k5nb-gxya/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | k5nb-gxya |
| Name | Licensed Veterinary Technicians - updated 12/20/2016 |
| Attribution | State of Maryland |
| Category | Agriculture |
| Tags | veterinary technicians, technicians |
| Created | 2016-12-20T20:46:47Z |
| Publication Date | 2016-12-20T20:55:42Z |

## Description

Currently licensed Veterinary Technicians

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | fname          | FIRST NAME     | text      | text        |
| Yes      | series tag  | lname          | LAST NAME      | text      | text        |
| Yes      | series tag  | license_number | LICENSE_NUMBER | text      | number      |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Data Commands

```ls
series e:k5nb-gxya d:2016-01-01T00:00:00.000Z t:lname=HOFFMANN t:license_number=664 t:fname=DENISE m:row_number.k5nb-gxya=1

series e:k5nb-gxya d:2016-01-01T00:00:00.000Z t:lname=LANE t:license_number=208 t:fname=KELLY m:row_number.k5nb-gxya=2

series e:k5nb-gxya d:2016-01-01T00:00:00.000Z t:lname=GOLESTANI t:license_number=812 t:fname="SEYED KAMRAN" m:row_number.k5nb-gxya=3
```

## Meta Commands

```ls
metric m:row_number.k5nb-gxya p:long l:"Row Number"

entity e:k5nb-gxya l:"Licensed Veterinary Technicians - updated 12/20/2016" t:attribution="State of Maryland" t:url=https://data.maryland.gov/api/views/k5nb-gxya

property e:k5nb-gxya t:meta.view v:id=k5nb-gxya v:category=Agriculture v:averageRating=0 v:name="Licensed Veterinary Technicians - updated 12/20/2016" v:attribution="State of Maryland"

property e:k5nb-gxya t:meta.view.license v:name="Public Domain"

property e:k5nb-gxya t:meta.view.owner v:id=5i5x-vf5f v:screenName=teachoaa v:displayName=teachoaa

property e:k5nb-gxya t:meta.view.tableauthor v:id=5i5x-vf5f v:screenName=teachoaa v:roleName=editor v:displayName=teachoaa
```

## Top Records

```ls
| fname        | lname      | license_number | 
| ============ | ========== | ============== | 
| DENISE       | HOFFMANN   | 664            | 
| KELLY        | LANE       | 208            | 
| SEYED KAMRAN | GOLESTANI  | 812            | 
| HEATHER      | CARTER     | 696            | 
| KRISTEN      | KALSTAD    | 589            | 
| LAURIE       | HAHN       | 582            | 
| FRANCES      | BANKS      | 175            | 
| ERIN         | THALHEIMER | 202            | 
| JANINE       | MOSES      | 815            | 
| SARAH        | RANKIN     | 648            | 
```