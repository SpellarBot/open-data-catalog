# HGBP Grocery Stores

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hgbp-grocery-stores-f7749) |
| Metadata | [Link](https://data.hawaii.gov/api/views/c9pg-qedp) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/c9pg-qedp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/c9pg-qedp/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | c9pg-qedp |
| Name | HGBP Grocery Stores |
| Attribution | DBEDT, State of Energy |
| Category | Economic Development |
| Tags | green grocery store, dbedt, sustainabe |
| Created | 2013-08-22T01:04:45Z |
| Publication Date | 2014-04-03T00:35:12Z |

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                       | Data Type | Render Type |
| ======== | =========== | ========================== | ========================== | ========= | =========== |
| No       | time        | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag  | grocery_store_name         | Grocery Store Name         | html      | html        |
| Yes      | series tag  | grocery_store_phone_number | Grocery Store Phone Number | phone     | phone       |
| Yes      | series tag  | grocery_store_website      | Grocery Store Website      | url       | url         |
| Yes      | series tag  | logo                       | Logo                       | photo     | photo       |
| Yes      | series tag  | green_report               | Green Report               | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:c9pg-qedp d:2013-08-21T18:13:20.000Z t:logo=QkM6P3qksapgAqEbZ2UNrh7hXVwECsc_nUaXk9v2sbs t:grocery_store_website=http://www.wholefoodsmarket.com t:phone_number="(808) 872-3310" t:phone_type=Work t:grocery_store_name="<p><span>Whole Foods Market- Maui</span></p>" t:green_report=http://energy.hawaii.gov/wp-content/uploads/2011/10/Whole-Foods-Market-Maui-Highlights-2011.pdf m:row_number.c9pg-qedp=1

series e:c9pg-qedp d:2014-04-02T17:35:05.000Z t:logo=Kbn3N49NoaizBNDT0FXLU0BtvaJDmFM7S5qa3qmkpjc t:grocery_store_website=http://www.wholefoodsmarket.com t:phone_number="(808) 738-0820" t:phone_type=Work t:grocery_store_name="<p><span>Whole Foods Market- Kahala</span></p>" t:green_report=http://energy.hawaii.gov/wp-content/uploads/2011/10/Whole-Foods-Market-Kahala-Highlights-2010.pdf m:row_number.c9pg-qedp=2
```

## Meta Commands

```ls
metric m:row_number.c9pg-qedp p:long l:"Row Number"

entity e:c9pg-qedp l:"HGBP Grocery Stores" t:attribution="DBEDT, State of Energy" t:url=https://data.hawaii.gov/api/views/c9pg-qedp

property e:c9pg-qedp t:meta.view v:id=c9pg-qedp v:category="Economic Development" v:averageRating=0 v:name="HGBP Grocery Stores" v:attribution="DBEDT, State of Energy"

property e:c9pg-qedp t:meta.view.owner v:id=av98-wszh v:screenName="Jonathan Chin" v:displayName="Jonathan Chin"

property e:c9pg-qedp t:meta.view.tableauthor v:id=av98-wszh v:screenName="Jonathan Chin" v:roleName=editor v:displayName="Jonathan Chin"
```

## Top Records

```ls
| :updated_at | grocery_store_name         | grocery_store_phone_number | grocery_store_website                   | logo                                        | green_report                                                                                              | 
| =========== | ========================== | ========================== | ======================================= | =========================================== | ========================================================================================================= | 
| 1377108800  | Whole Foods Market- Maui   | [(808) 872-3310, Work]     | [http://www.wholefoodsmarket.com, null] | QkM6P3qksapgAqEbZ2UNrh7hXVwECsc_nUaXk9v2sbs | [http://energy.hawaii.gov/wp-content/uploads/2011/10/Whole-Foods-Market-Maui-Highlights-2011.pdf, 2011]   | 
| 1396460105  | Whole Foods Market- Kahala | [(808) 738-0820, Work]     | [http://www.wholefoodsmarket.com, null] | Kbn3N49NoaizBNDT0FXLU0BtvaJDmFM7S5qa3qmkpjc | [http://energy.hawaii.gov/wp-content/uploads/2011/10/Whole-Foods-Market-Kahala-Highlights-2010.pdf, 2010] | 
```