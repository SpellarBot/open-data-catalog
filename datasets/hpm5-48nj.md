# NORA Sold Properties

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nora-sold-properties) |
| Metadata | [Link](https://data.nola.gov/api/views/hpm5-48nj) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/hpm5-48nj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/hpm5-48nj/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | hpm5-48nj |
| Name | NORA Sold Properties |
| Attribution | New Orleans Redevelopment Authority (NORA) |
| Category | Housing, Land Use, and Blight |
| Tags | redevelopment, sold, properties |
| Created | 2013-02-06T17:51:42Z |
| Publication Date | 2017-04-04T19:12:03Z |

## Description

This data set is a listing of all properties sold by NORA through the following disposition channels.-Auction: Properties put up for auction and sold to the highest bidder.-Development: Properties offered via request for proposals to create affordable housing.-Lot Next Door: Properties sold to adjacent owners.-Alternate Land Use: Properties sold for purposes of creating green space and used for activities such as community gardens.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | series tag     | identifier          | Identifier          | text          | text          |
| Yes      | series tag     | zip_code            | Zip code            | text          | text          |
| Yes      | numeric metric | geopin              | Geopin              | number        | text          |
| Yes      | series tag     | council_district    | Council District    | text          | text          |
| Yes      | series tag     | disposition_channel | Disposition Channel | text          | text          |
| Yes      | time           | sale_date           | Sale Date           | calendar_date | calendar_date |
```

## Time Field

```ls
Value = sale_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hpm5-48nj d:2002-04-25T00:00:00.000Z t:zip_code=70113 t:disposition_channel=Development t:council_district=B t:identifier=ORA800017 m:geopin=41037049

series e:hpm5-48nj d:2002-10-31T00:00:00.000Z t:zip_code=70113 t:disposition_channel=Development t:council_district=B t:identifier=ORA800011 m:geopin=41192892

series e:hpm5-48nj d:2005-01-13T00:00:00.000Z t:zip_code=70116 t:disposition_channel=Development t:council_district=D t:identifier=ORA900797 m:geopin=41070186
```

## Meta Commands

```ls
metric m:geopin p:integer l:Geopin t:dataTypeName=number

entity e:hpm5-48nj l:"NORA Sold Properties" t:attribution="New Orleans Redevelopment Authority (NORA)" t:url=https://data.nola.gov/api/views/hpm5-48nj

property e:hpm5-48nj t:meta.view v:id=hpm5-48nj v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="NORA Sold Properties" v:attribution="New Orleans Redevelopment Authority (NORA)"

property e:hpm5-48nj t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:hpm5-48nj t:meta.view.owner v:id=c4j8-jv6s v:profileImageUrlMedium=/api/users/c4j8-jv6s/profile_images/THUMB v:profileImageUrlLarge=/api/users/c4j8-jv6s/profile_images/LARGE v:screenName=ssmadden v:profileImageUrlSmall=/api/users/c4j8-jv6s/profile_images/TINY v:lastNotificationSeenAt=1491333102 v:displayName=ssmadden

property e:hpm5-48nj t:meta.view.tableauthor v:id=c4j8-jv6s v:profileImageUrlMedium=/api/users/c4j8-jv6s/profile_images/THUMB v:profileImageUrlLarge=/api/users/c4j8-jv6s/profile_images/LARGE v:screenName=ssmadden v:profileImageUrlSmall=/api/users/c4j8-jv6s/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491333102 v:displayName=ssmadden

property e:hpm5-48nj t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| identifier | zip_code | geopin   | council_district | disposition_channel | sale_date           | 
| ========== | ======== | ======== | ================ | =================== | =================== | 
| ORA800017  | 70113    | 41037049 | B                | Development         | 2002-04-25T00:00:00 | 
| ORA800011  | 70113    | 41192892 | B                | Development         | 2002-10-31T00:00:00 | 
| ORA900797  | 70116    | 41070186 | D                | Development         | 2005-01-13T00:00:00 | 
| ORA900793  | 70113    | 41040766 | B                | Development         | 2005-01-13T00:00:00 | 
| ORA800027  | 70113    | 41039051 | B                | Development         | 2005-01-27T00:00:00 | 
| ORA900124  | 70117    | 41059926 | D                | Development         | 2006-12-20T00:00:00 | 
| ORL071586  | 70122    | 41108267 | D                | Lot Next Door       | 2009-08-27T00:00:00 | 
| ORL069398  | 70119    | 41080680 | D                | Development         | 2009-09-25T00:00:00 | 
| ORL076981  | 70119    | 41077847 | D                | Development         | 2009-09-25T00:00:00 | 
| ORL095408  | 70124    | 41192607 | A                | Auction             | 2009-10-22T00:00:00 | 
```