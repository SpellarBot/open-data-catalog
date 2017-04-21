# Fulton Street Mall businesses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fulton-street-mall-businesses-5b4e1) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jvce-szsb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jvce-szsb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jvce-szsb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jvce-szsb |
| Name | Fulton Street Mall businesses |
| Attribution | Fulton Mall Improvement Association |
| Category | Business |
| Tags | brooklyn, fulton street, mall, business list, directory |
| Created | 2011-10-06T17:35:52Z |
| Publication Date | 2013-06-21T19:28:45Z |

## Description

Listing of businesses in the Fulton Mall Improvement Association

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | store       | Store      | text      | text        |
| Yes      | series tag  | phone_      | Phone #    | text      | text        |
| Yes      | series tag  | type        | Type       | text      | text        |
| Yes      | series tag  | website     | Website    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jvce-szsb d:2011-10-06T10:35:55.000Z t:store=Aeropostale t:website=www.aeropostale.com t:type="Childrens, Mens and Womans Apparel" t:phone_=718-643-9190 m:row_number.jvce-szsb=1

series e:jvce-szsb d:2011-10-06T10:35:55.000Z t:store="Afzal Perfume" t:type="Jewelry and Accessories" t:phone_="(917) 238-5885" m:row_number.jvce-szsb=2

series e:jvce-szsb d:2011-10-06T10:35:55.000Z t:store="Ashley Stewart" t:website=www.ashleystewart.com t:type="Women's Apparel" t:phone_="(718) 246-1067" m:row_number.jvce-szsb=3
```

## Meta Commands

```ls
metric m:row_number.jvce-szsb p:long l:"Row Number"

entity e:jvce-szsb l:"Fulton Street Mall businesses" t:attribution="Fulton Mall Improvement Association" t:url=https://data.cityofnewyork.us/api/views/jvce-szsb

property e:jvce-szsb t:meta.view v:id=jvce-szsb v:category=Business v:averageRating=0 v:name="Fulton Street Mall businesses" v:attribution="Fulton Mall Improvement Association"

property e:jvce-szsb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jvce-szsb t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | store                | phone_         | type                                                   | website               | 
| =========== | ==================== | ============== | ====================================================== | ===================== | 
| 1317897355  | Aeropostale          | 718-643-9190   | Childrens, Mens and Womans Apparel                     | www.aeropostale.com   | 
| 1317897355  | Afzal Perfume        | (917) 238-5885 | Jewelry and Accessories                                |                       | 
| 1317897355  | Ashley Stewart       | (718) 246-1067 | Women's Apparel                                        | www.ashleystewart.com | 
| 1317897355  | Ameritel - T-Mobile  | (718) 254-0312 | Electronics                                            |                       | 
| 1317897355  | America's Food Court | (718) 852-2828 | Food                                                   |                       | 
| 1317897355  | Aldo                 | 718) 852-2337  | Women's and Men's Apparel and Footwear                 | www.aldoshoes.com     | 
| 1317897356  | NY Baby              | (718)-643-0692 | Baby and Children's Furniture, Apparel and Accessories | www.nybabystore.com   | 
| 1317897356  | Metro PCS            | (718) 624-6727 | Electronics                                            | www.metropcs.com      | 
| 1317897356  | Porta Bella          | (212) 239-7380 | Men's Apparel                                          |                       | 
| 1317897356  | Sarit Shoes          | (718) 855-1655 | Women's Footwear                                       |                       | 
```