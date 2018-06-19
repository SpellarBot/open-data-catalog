# Treasurer - 2010 Annual Tax Sale Registered Buyers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/treasurer-2010-annual-tax-sale-registered-buyers-c336b) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/g322-ktce) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/g322-ktce/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/g322-ktce/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | g322-ktce |
| Name | Treasurer - 2010 Annual Tax Sale Registered Buyers |
| Attribution | Cook County Treasurer's Office |
| Category | Property & Taxation |
| Created | 2012-09-05T20:11:02Z |
| Publication Date | 2014-10-09T23:18:14Z |

## Description

2010 Tax Sale Registered Buyers. They are registered to purchase taxes on property that have not been paid for 2 years

## Columns

```ls
| Included | Schema Type | Field Name | Name      | Data Type | Render Type |
| ======== | =========== | ========== | ========= | ========= | =========== |
| Yes      | series tag  | buyerid    | BuyerID   | text      | text        |
| Yes      | series tag  | buyername  | BuyerName | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:g322-ktce d:2010-01-01T00:00:00.000Z t:buyername="GENERAL TAX   LIEN LLC" t:buyerid=1000001 m:row_number.g322-ktce=1

series e:g322-ktce d:2010-01-01T00:00:00.000Z t:buyername="INTERSTATE FUNDING CORP" t:buyerid=1000002 m:row_number.g322-ktce=2

series e:g322-ktce d:2010-01-01T00:00:00.000Z t:buyername=PHOENIXBOND&INDEMNITYCO t:buyerid=1000003 m:row_number.g322-ktce=3
```

## Meta Commands

```ls
metric m:row_number.g322-ktce p:long l:"Row Number"

entity e:g322-ktce l:"Treasurer - 2010 Annual Tax Sale Registered Buyers" t:attribution="Cook County Treasurer's Office" t:url=https://datacatalog.cookcountyil.gov/api/views/g322-ktce

property e:g322-ktce t:meta.view v:id=g322-ktce v:category="Property & Taxation" v:attributionLink=http://www.cookcountytreasurer.com/ v:averageRating=0 v:name="Treasurer - 2010 Annual Tax Sale Registered Buyers" v:attribution="Cook County Treasurer's Office"

property e:g322-ktce t:meta.view.owner v:id=vtsd-afsj v:screenName=wlinder v:displayName=wlinder

property e:g322-ktce t:meta.view.tableauthor v:id=vtsd-afsj v:screenName=wlinder v:roleName=publisher v:displayName=wlinder
```

## Top Records

```ls
| buyerid | buyername               | 
| ======= | ======================= | 
| 1000001 | GENERAL TAX LIEN LLC    | 
| 1000002 | INTERSTATE FUNDING CORP | 
| 1000003 | PHOENIXBOND&INDEMNITYCO | 
| 1000004 | MUNICIPAL POINT FUNDING | 
| 1000005 | LIONCREST HOMEOWNERS    | 
| 1000006 | FIRM ASSETS LLC         | 
| 1000007 | ANDREEVA MARINA         | 
| 1000008 | WESTERN SITES LLC       | 
| 1000009 | OAK PARK INVESTMENTS    | 
| 1000010 | BELMONT REALTY CORP     | 
```