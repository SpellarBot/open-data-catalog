# Downtown Brooklyn Partnership (DBP)/ Court-Livingston-Schermerhorn (CLS) Retail Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/downtown-brooklyn-partnership-dbp-court-livingston-schermerhorn-cls-retail-locations-90b39) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/8gqz-6v9v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/8gqz-6v9v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/8gqz-6v9v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 8gqz-6v9v |
| Name | Downtown Brooklyn Partnership (DBP)/ Court-Livingston-Schermerhorn (CLS) Retail Locations |
| Attribution | Downtown Brooklyn Partnership (DBP) |
| Category | Business |
| Tags | downtown, brooklyn, partnership, retail, retailer, locations, stores, businesses, business |
| Created | 2011-10-06T16:31:44Z |
| Publication Date | 2013-06-21T19:28:52Z |

## Description

List of retail location in the DBP/CLS district

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       | time        | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag  | business_name     | Business Name     | text      | text        |
| Yes      | series tag  | business_category | Business Category | text      | text        |
| Yes      | series tag  | street_address    | Street Address    | text      | text        |
| Yes      | series tag  | phone             | Phone             | text      | text        |
| Yes      | series tag  | website           | Website           | text      | text        |
| Yes      | series tag  | hours_mon_fri     | Hours Mon - Fri   | text      | text        |
| Yes      | series tag  | hours_sat         | Hours Sat         | text      | text        |
| Yes      | series tag  | hours_sun         | Hours Sun         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8gqz-6v9v d:2011-10-06T09:31:47.000Z t:business_name="Brooklyn Uniform Center" t:phone=718-875-7780 t:business_category="Apparel & Footwear" t:street_address="206 Livingston Street" m:row_number.8gqz-6v9v=1

series e:8gqz-6v9v d:2011-10-06T09:31:47.000Z t:business_name=Afrikart t:phone=718-935-0458 t:website="no website" t:business_category="Apparel & Footwear" t:street_address="295 Livingston Street" m:row_number.8gqz-6v9v=2

series e:8gqz-6v9v d:2011-10-06T09:31:47.000Z t:business_name="American Apparel" t:phone=718-855-4627 t:hours_mon_fri="F 11am - 10pm, 11am - 9pm" t:hours_sat="11am - 10pm" t:website=www.americanapparel.com t:business_category="Apparel & Footwear" t:hours_sun="11am - 9pm" t:street_address="112 Court Street" m:row_number.8gqz-6v9v=3
```

## Meta Commands

```ls
metric m:row_number.8gqz-6v9v p:long l:"Row Number"

entity e:8gqz-6v9v l:"Downtown Brooklyn Partnership (DBP)/ Court-Livingston-Schermerhorn (CLS)  Retail Locations" t:attribution="Downtown Brooklyn Partnership (DBP)" t:url=https://data.cityofnewyork.us/api/views/8gqz-6v9v

property e:8gqz-6v9v t:meta.view v:id=8gqz-6v9v v:category=Business v:averageRating=0 v:name="Downtown Brooklyn Partnership (DBP)/ Court-Livingston-Schermerhorn (CLS)  Retail Locations" v:attribution="Downtown Brooklyn Partnership (DBP)"

property e:8gqz-6v9v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:8gqz-6v9v t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | business_name                           | business_category  | street_address        | phone        | website                 | hours_mon_fri             | hours_sat    | hours_sun    | 
| =========== | ======================================= | ================== | ===================== | ============ | ======================= | ========================= | ============ | ============ | 
| 1317893507  | Brooklyn Uniform Center                 | Apparel & Footwear | 206 Livingston Street | 718-875-7780 |                         |                           |              |              | 
| 1317893507  | Afrikart                                | Apparel & Footwear | 295 Livingston Street | 718-935-0458 | no website              |                           |              |              | 
| 1317893507  | American Apparel                        | Apparel & Footwear | 112 Court Street      | 718-855-4627 | www.americanapparel.com | F 11am - 10pm, 11am - 9pm | 11am - 10pm  | 11am - 9pm   | 
| 1317893507  | Express Shoe Store & Repair             | Apparel & Footwear | 370 Livingston Street | 718-596-6921 | no website              |                           |              |              | 
| 1317893507  | Dunkin Donuts                           | Food Service       | 322 Livingston Street | 718-788-7888 | www.dunkindonuts.com    | 6am - 7:30pm              | 7am - 7:30pm | 7:30am - 7pm | 
| 1317893507  | Bella Pizza                             | Food Service       | 208 Livingston Street | 718-624-3996 |                         |                           |              |              | 
| 1317893507  | Webers Closeout Center                  | Discount           | 39 Bond Street        | 718-292-3605 |                         |                           |              |              | 
| 1317893507  | True Value Brunos Home Center           | Hardware           | 95 Court Street       | 718-858-5250 |                         | 8:30am - 6pm              | 9am - 3pm    | closed       | 
| 1317893507  | J & J Sunshine (Lans Hair &) Nail Salon | Beauty Services    | 368 Livingston Street | 718-875-6571 |                         | 10am - 7pm                | 10am - 7pm   | Closed       | 
| 1317893507  | United Artists                          | Movie Theatres     | 108 Court Street      | 718-246-8170 | www.regmovies.com       | 11am - 2am                | 11am - 2am   | 11am - 2am   | 
```