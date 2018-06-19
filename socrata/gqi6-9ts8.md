# Hawaii's Registered Livestock Brands

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hawaiis-registered-livestock-brands-ce024) |
| Metadata | [Link](https://data.hawaii.gov/api/views/gqi6-9ts8) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/gqi6-9ts8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/gqi6-9ts8/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | gqi6-9ts8 |
| Name | Hawaii's Registered Livestock Brands |
| Attribution | Hawaii Department of Agriculture |
| Category | Health |
| Tags | livestock, brands, registered |
| Created | 2012-11-08T23:10:45Z |
| Publication Date | 2012-12-05T20:59:12Z |

## Description

Listing of livestock brands registered with the Department of Agriculture Animal Disease Control Branch for year 2011. To include annual supplements for years 2012-2014.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | ranchname   | RanchName  | text      | text        |
| Yes      | series tag  | firstname   | FirstName  | text      | text        |
| Yes      | series tag  | lastname    | LastName   | text      | text        |
| Yes      | series tag  | brand_type  | Brand Type | text      | text        |
| Yes      | series tag  | reg_number  | Reg #      | text      | number      |
| Yes      | series tag  | island      | Island     | text      | text        |
| Yes      | series tag  | image       | Brand      | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:gqi6-9ts8 d:2012-11-08T15:10:48.000Z t:image=http://hawaii.gov/hdoa/brands/AbreuD1.gif t:brand_type="Numeral Combination" t:lastname=ABREU t:firstname=DAVID t:reg_number=413 t:island=K m:row_number.gqi6-9ts8=1

series e:gqi6-9ts8 d:2012-11-08T15:10:48.000Z t:image=http://hawaii.gov/hdoa/brands/AbreuW4.gif t:brand_type="Letter Combination" t:lastname=ABREU t:firstname=WALTER t:reg_number=142 t:island=K m:row_number.gqi6-9ts8=2

series e:gqi6-9ts8 d:2012-11-08T15:10:48.000Z t:image=http://hawaii.gov/hdoa/brands/AbreuW5.jpg t:brand_type="Letter Combination" t:lastname=ABREU t:ranchname=WALKING-O-RANCH t:firstname="WILLIAM O." t:reg_number=7 t:island=M m:row_number.gqi6-9ts8=3
```

## Meta Commands

```ls
metric m:row_number.gqi6-9ts8 p:long l:"Row Number"

entity e:gqi6-9ts8 l:"Hawaii's Registered Livestock Brands" t:attribution="Hawaii Department of Agriculture" t:url=https://data.hawaii.gov/api/views/gqi6-9ts8

property e:gqi6-9ts8 t:meta.view v:id=gqi6-9ts8 v:category=Health v:averageRating=0 v:name="Hawaii's Registered Livestock Brands" v:attribution="Hawaii Department of Agriculture"

property e:gqi6-9ts8 t:meta.view.owner v:id=t6a8-bm3j v:screenName="DOA Open Data Coordinator" v:displayName="DOA Open Data Coordinator"

property e:gqi6-9ts8 t:meta.view.tableauthor v:id=t6a8-bm3j v:screenName="DOA Open Data Coordinator" v:roleName=publisher v:displayName="DOA Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | ranchname          | firstname  | lastname  | brand_type            | reg_number | island | image                                              | 
| =========== | ================== | ========== | ========= | ===================== | ========== | ====== | ================================================== | 
| 1352387448  |                    | DAVID      | ABREU     | Numeral Combination   | 413        | K      | [http://hawaii.gov/hdoa/brands/AbreuD1.gif, null]  | 
| 1352387448  |                    | WALTER     | ABREU     | Letter Combination    | 142        | K      | [http://hawaii.gov/hdoa/brands/AbreuW4.gif, null]  | 
| 1352387448  | WALKING-O-RANCH    | WILLIAM O. | ABREU     | Letter Combination    | 7          | M      | [http://hawaii.gov/hdoa/brands/AbreuW5.jpg, null]  | 
| 1352387448  | ADACHI RANCH       | ARTHUR S.  | ADACHI    | Letter Combination    | 326        | O      | [http://hawaii.gov/hdoa/brands/AdachiA7.gif, null] | 
| 1352387448  | ADRIAN RANCH       | JOHN F.    | ADRIAN    | Letter Combination    | 475        | H      | [http://hawaii.gov/hdoa/brands/AdrianJ8.gif, null] | 
| 1352387448  |                    | EDWIN P.   | AGUIAR    | Letter Combination    | 396        | H      | [http://hawaii.gov/hdoa/brands/AguiarE9.gif, null] | 
| 1352387448  |                    | HANSEL     | AHKOI     | Letter Combination    | 152        | M      | [http://hawaii.gov/hdoa/brands/AhkoiH13.gif, null] | 
| 1352387448  |                    | RANDOLPH   | AHUNA JR. | Letters with Numerals | 343        | H      | [http://hawaii.gov/hdoa/brands/AhunaR14.gif, null] | 
| 1352387448  | EKOLU K OHANA FARM | WILLIAM T. | AIONA     | Open Figures          | 502        | H      | [http://hawaii.gov/hdoa/brands/AionaW15.gif, null] | 
| 1352387448  | A & S FARMS        | SPENCER N. | AKANA     | Letter Combination    | 247        | H      | [http://hawaii.gov/hdoa/brands/AkanaS16.jpg, null] | 
```