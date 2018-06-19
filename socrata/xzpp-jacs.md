# Bulk Cargo Annual Imports and Exports Through Port Authority of NY NJ Maritime Terminals: Beginning 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bulk-cargo-annual-imports-and-exports-through-port-authority-of-ny-nj-maritime-terminals-2) |
| Metadata | [Link](https://data.ny.gov/api/views/xzpp-jacs) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/xzpp-jacs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/xzpp-jacs/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | xzpp-jacs |
| Name | Bulk Cargo Annual Imports and Exports Through Port Authority of NY NJ Maritime Terminals: Beginning 2000 |
| Attribution | Port Authority of NY & NJ, Port Commerce Department |
| Category | Transportation |
| Tags | bulk, breakbulk, port authority, port, maritime |
| Created | 2013-05-10T11:11:15Z |
| Publication Date | 2013-05-10T19:36:32Z |

## Description

This dataset describes the total volume annually of Import and Export Bulk cargo moved through maritime terminals located within Port Authority property in the Port of New York and New Jersey in metric tons

## Columns

```ls
| Included | Schema Type    | Field Name | Name              | Data Type | Render Type |
| ======== | ============== | ========== | ================= | ========= | =========== |
| Yes      | time           | year       | Year              | number    | number      |
| Yes      | series tag     | type       | Type of Cargo     | text      | text        |
| Yes      | numeric metric | volume     | Bulk Cargo Volume | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xzpp-jacs d:2012-01-01T00:00:00.000Z t:type=Imports m:volume=350588558

series e:xzpp-jacs d:2011-01-01T00:00:00.000Z t:type=Imports m:volume=39667658

series e:xzpp-jacs d:2010-01-01T00:00:00.000Z t:type=Imports m:volume=40015551
```

## Meta Commands

```ls
metric m:volume p:integer l:"Bulk Cargo Volume" d:"In metric tons" t:dataTypeName=number

entity e:xzpp-jacs l:"Bulk Cargo Annual Imports and Exports Through Port Authority of NY NJ Maritime Terminals:  Beginning 2000" t:attribution="Port Authority of NY & NJ, Port Commerce Department" t:url=https://data.ny.gov/api/views/xzpp-jacs

property e:xzpp-jacs t:meta.view v:id=xzpp-jacs v:category=Transportation v:attributionLink=http://www.panynj.gov/port/pdf/port-trade-statistics-summary-2001-2011.pdf v:averageRating=0 v:name="Bulk Cargo Annual Imports and Exports Through Port Authority of NY NJ Maritime Terminals:  Beginning 2000" v:attribution="Port Authority of NY & NJ, Port Commerce Department"

property e:xzpp-jacs t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:xzpp-jacs t:meta.view.tableauthor v:id=kp2w-wfdr v:screenName="Ann Bevins" v:roleName=publisher v:displayName="Ann Bevins"

property e:xzpp-jacs t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | type    | volume    | 
| ==== | ======= | ========= | 
| 2012 | Imports | 350588558 | 
| 2011 | Imports | 39667658  | 
| 2010 | Imports | 40015551  | 
| 2009 | Imports | 402148993 | 
| 2008 | Imports | 45295759  | 
| 2007 | Imports | 47116316  | 
| 2006 | Imports | 49168042  | 
| 2005 | Imports | 53449638  | 
| 2004 | Imports | 51768248  | 
| 2003 | Imports | 51953591  | 
```