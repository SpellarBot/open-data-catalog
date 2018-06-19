# Solicitor Product List with Assigned Wholesaler

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/solicitor-product-list-with-assigned-wholesaler-4fa17) |
| Metadata | [Link](https://data.mo.gov/api/views/gfq7-aa86) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/gfq7-aa86/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/gfq7-aa86/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | gfq7-aa86 |
| Name | Solicitor Product List with Assigned Wholesaler |
| Category | Regulatory |
| Tags | liquor, alcohol license |
| Created | 2013-02-15T18:41:03Z |
| Publication Date | 2017-04-20T23:32:50Z |

## Description

Active list of products sold by the associated solicitor to the wholesaler.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | series tag     | solicitor_number  | Solicitor Number  | text          | number        |
| Yes      | series tag     | licensee_name     | Licensee Name     | text          | text          |
| Yes      | series tag     | brand_number      | Brand Number      | text          | text          |
| Yes      | series tag     | brand_name        | Brand Name        | text          | text          |
| Yes      | series tag     | class             | Class             | text          | text          |
| Yes      | series tag     | type              | Type              | text          | text          |
| Yes      | numeric metric | proof             | Proof             | number        | number        |
| Yes      | time           | effective_date    | Effective Date    | calendar_date | calendar_date |
| Yes      | series tag     | wholesaler_number | Wholesaler Number | text          | number        |
| Yes      | series tag     | wholesaler_name   | Wholesaler Name   | text          | text          |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:gfq7-aa86 d:2012-03-16T00:00:00.000Z t:wholesaler_name="STONE HILL WINE COMPANY INC.  HERMANN" t:licensee_name="STONE HILL WINE COMPANY INC." t:brand_number=WA000904 t:wholesaler_number=13755 t:class=8 t:solicitor_number=13755 t:type=01 t:brand_name="STONE HILL RESERVE CHARDONEL MISSOURI" m:proof=0

series e:gfq7-aa86 d:2016-04-14T00:00:00.000Z t:wholesaler_name="LOHR DISTRIBUTING COMPANY INC.ST LOUIS" t:licensee_name="STONE HILL WINE COMPANY INC." t:brand_number=WA000904 t:wholesaler_number=30097 t:class=8 t:solicitor_number=13755 t:type=01 t:brand_name="STONE HILL RESERVE CHARDONEL MISSOURI" m:proof=0

series e:gfq7-aa86 d:2016-04-14T00:00:00.000Z t:wholesaler_name="LOHR DISTRIBUTING CO. INC.    ST. LOUIS" t:licensee_name="STONE HILL WINE COMPANY INC." t:brand_number=WA000904 t:wholesaler_number=226108 t:class=8 t:solicitor_number=13755 t:type=01 t:brand_name="STONE HILL RESERVE CHARDONEL MISSOURI" m:proof=0
```

## Meta Commands

```ls
metric m:proof p:long l:Proof t:dataTypeName=number

entity e:gfq7-aa86 l:"Solicitor Product List with Assigned Wholesaler" t:url=https://data.mo.gov/api/views/gfq7-aa86

property e:gfq7-aa86 t:meta.view v:id=gfq7-aa86 v:category=Regulatory v:averageRating=0 v:name="Solicitor Product List with Assigned Wholesaler"

property e:gfq7-aa86 t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:gfq7-aa86 t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| solicitor_number | licensee_name                | brand_number | brand_name                            | class | type | proof | effective_date      | wholesaler_number | wholesaler_name                          | 
| ================ | ============================ | ============ | ===================================== | ===== | ==== | ===== | =================== | ================= | ======================================== | 
| 13755            | STONE HILL WINE COMPANY INC. | WA000904     | STONE HILL RESERVE CHARDONEL MISSOURI | 8     | 01   | 0.0   | 2012-03-16T00:00:00 | 13755             | STONE HILL WINE COMPANY INC. HERMANN     | 
| 13755            | STONE HILL WINE COMPANY INC. | WA000904     | STONE HILL RESERVE CHARDONEL MISSOURI | 8     | 01   | 0.0   | 2016-04-14T00:00:00 | 30097             | LOHR DISTRIBUTING COMPANY INC.ST LOUIS   | 
| 13755            | STONE HILL WINE COMPANY INC. | WA000904     | STONE HILL RESERVE CHARDONEL MISSOURI | 8     | 01   | 0.0   | 2016-04-14T00:00:00 | 226108            | LOHR DISTRIBUTING CO. INC. ST. LOUIS     | 
| 13755            | STONE HILL WINE COMPANY INC. | WA009173     | JACQUESSE KICK'N KOLADA               | 8     | 02   | 0.0   | 2016-04-14T00:00:00 | 30097             | LOHR DISTRIBUTING COMPANY INC.ST LOUIS   | 
| 13755            | STONE HILL WINE COMPANY INC. | WA009173     | JACQUESSE KICK'N KOLADA               | 8     | 02   | 0.0   | 2016-04-14T00:00:00 | 194998            | LOHR DISTRIBUTING COMPANY INC.KANSAS CIT | 
| 13755            | STONE HILL WINE COMPANY INC. | WA009173     | JACQUESSE KICK'N KOLADA               | 8     | 02   | 0.0   | 2016-04-14T00:00:00 | 226108            | LOHR DISTRIBUTING CO. INC. ST. LOUIS     | 
| 13755            | STONE HILL WINE COMPANY INC. | WA009174     | JACQUESSE KICK'N SANGRIA              | 8     | 02   | 0.0   | 2016-04-14T00:00:00 | 30097             | LOHR DISTRIBUTING COMPANY INC.ST LOUIS   | 
| 13755            | STONE HILL WINE COMPANY INC. | WA009174     | JACQUESSE KICK'N SANGRIA              | 8     | 02   | 0.0   | 2016-04-14T00:00:00 | 194998            | LOHR DISTRIBUTING COMPANY INC.KANSAS CIT | 
| 13755            | STONE HILL WINE COMPANY INC. | WA009174     | JACQUESSE KICK'N SANGRIA              | 8     | 02   | 0.0   | 2016-04-14T00:00:00 | 226108            | LOHR DISTRIBUTING CO. INC. ST. LOUIS     | 
| 13755            | STONE HILL WINE COMPANY INC. | WA013647     | STONE HILL VIDAL ICE WINE HERMANN     | 8     | 01   | 0.0   | 2014-05-30T00:00:00 | 13755             | STONE HILL WINE COMPANY INC. HERMANN     | 
```