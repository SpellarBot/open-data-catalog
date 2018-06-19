# Grand Street BID Business Directory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/grand-street-bid-business-directory-fb381) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/656a-faqy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/656a-faqy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/656a-faqy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 656a-faqy |
| Name | Grand Street BID Business Directory |
| Attribution | Grand Street BID |
| Category | Business |
| Tags | business, restaurant, shopping, art |
| Created | 2011-09-28T21:22:54Z |
| Publication Date | 2013-06-21T19:28:02Z |

## Description

Business Directory for the Grand Street (East Williamsburg) Business Improvement District (BID).  
A BID delivers supplemental services, public safety, visitor services, marketing and promotional programs, capital improvements and beautification to a designated area.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | business_name | Business Name | text      | text        |
| Yes      | series tag  | tel           | Tel           | text      | text        |
| Yes      | series tag  | website       | website       | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:656a-faqy d:2011-09-28T14:22:57.000Z t:business_name="Grand Animal Clinic" t:tel=718-388-4746 m:row_number.656a-faqy=1

series e:656a-faqy d:2011-09-28T14:22:57.000Z t:business_name="Lee's Furniture" t:tel=718-388-2743 m:row_number.656a-faqy=2

series e:656a-faqy d:2011-09-28T14:22:57.000Z t:business_name="Williams & Bailey" t:website=http://www.willliamsandbaileyny.com t:tel=718-782-3500 m:row_number.656a-faqy=3
```

## Meta Commands

```ls
metric m:row_number.656a-faqy p:long l:"Row Number"

entity e:656a-faqy l:"Grand Street BID Business Directory" t:attribution="Grand Street BID" t:url=https://data.cityofnewyork.us/api/views/656a-faqy

property e:656a-faqy t:meta.view v:id=656a-faqy v:category=Business v:averageRating=0 v:name="Grand Street BID Business Directory" v:attribution="Grand Street BID"

property e:656a-faqy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:656a-faqy t:meta.view.tableauthor v:id=rnig-m3uj v:profileImageUrlMedium=/api/users/rnig-m3uj/profile_images/THUMB v:profileImageUrlLarge=/api/users/rnig-m3uj/profile_images/LARGE v:screenName="Jorge J." v:profileImageUrlSmall=/api/users/rnig-m3uj/profile_images/TINY v:displayName="Jorge J."
```

## Top Records

```ls
| :updated_at | business_name         | tel          | website                                     | 
| =========== | ===================== | ============ | =========================================== | 
| 1317219777  | Grand Animal Clinic   | 718-388-4746 | [null, null]                                | 
| 1317219777  | Lee's Furniture       | 718-388-2743 | [null, null]                                | 
| 1317219777  | Williams & Bailey     | 718-782-3500 | [http://www.willliamsandbaileyny.com, null] | 
| 1317219777  | Open Grill 24/7 Deli  | 718-599-0937 | [null, null]                                | 
| 1317219777  | Rocio's Bakery        | 718-384-0773 | [null, null]                                | 
| 1317219777  | Singa's Famous Pizza  | 718-782-2100 | [http://www.singaspizzas.com, null]         | 
| 1317219777  | New Apolo Restaurant  | 718-387-1773 | [null, null]                                | 
| 1317219777  | Redd's Tavern         | 718-218-9429 | [null, null]                                | 
| 1317219777  | Curry Heaven, Inc.    | 718-388-3021 | [null, null]                                | 
| 1317219777  | Flash Haircuts Unisex | 718-782-4246 | [null, null]                                | 
```