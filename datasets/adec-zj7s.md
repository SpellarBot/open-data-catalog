# New York State Parks Concession Contracts

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-york-state-parks-concession-contracts) |
| Metadata | [Link](https://data.ny.gov/api/views/adec-zj7s) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/adec-zj7s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/adec-zj7s/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | adec-zj7s |
| Name | New York State Parks Concession Contracts |
| Attribution | New York State Office of Parks, Recreation and Historic Preservation |
| Category | Recreation |
| Tags | parks and recreation, business opportunities, concessions |
| Created | 2014-01-30T12:37:33Z |
| Publication Date | 2015-12-10T20:04:02Z |

## Description

This dataset includes the name, concesson type and term of concession contracts active in New York State Parks during the most recent calendar year.

## Columns

```ls
| Included | Schema Type | Field Name | Name       | Data Type     | Render Type   |
| ======== | =========== | ========== | ========== | ============= | ============= |
| Yes      | series tag  | region     | Region     | text          | text          |
| Yes      | series tag  | facility   | Facility   | text          | text          |
| Yes      | series tag  | contract   | Contract # | text          | text          |
| Yes      | series tag  | name       | Name       | text          | text          |
| Yes      | series tag  | type       | Type       | text          | text          |
| No       |             | start_date | Start Date | calendar_date | calendar_date |
| Yes      | time        | end_date   | End Date   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_date
```

## Data Commands

```ls
series e:adec-zj7s d:2017-12-31T00:00:00.000Z t:region=Allegany t:facility="Long Point & Midway" t:contract=X001102 t:name="Ready About Sailing" t:type="Food, Beverage & Marine Fuel" m:row_number.adec-zj7s=1

series e:adec-zj7s d:2021-12-31T00:00:00.000Z t:region=Allegany t:facility=Allegany t:contract=X000996 t:name="J-Con Parks, Inc." t:type="Food, Beverage & Retail" m:row_number.adec-zj7s=2

series e:adec-zj7s d:2022-12-31T00:00:00.000Z t:region=Allegany t:facility="Allegany - Camp Turner" t:contract=X001119 t:name="Diocese of Buffalo" t:type="Group Camp" m:row_number.adec-zj7s=3
```

## Meta Commands

```ls
metric m:row_number.adec-zj7s p:long l:"Row Number"

entity e:adec-zj7s l:"New York State Parks Concession Contracts" t:attribution="New York State Office of Parks, Recreation and Historic Preservation" t:url=https://data.ny.gov/api/views/adec-zj7s

property e:adec-zj7s t:meta.view v:id=adec-zj7s v:category=Recreation v:attributionLink=http://nysparks.com/business/business-opportunities.aspx v:averageRating=0 v:name="New York State Parks Concession Contracts" v:attribution="New York State Office of Parks, Recreation and Historic Preservation"

property e:adec-zj7s t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:adec-zj7s t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:adec-zj7s t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| region   | facility                   | contract | name                                    | type                         | start_date          | end_date            | 
| ======== | ========================== | ======== | ======================================= | ============================ | =================== | =================== | 
| Allegany | Long Point & Midway        | X001102  | Ready About Sailing                     | Food, Beverage & Marine Fuel | 2013-04-01T00:00:00 | 2017-12-31T00:00:00 | 
| Allegany | Allegany                   | X000996  | J-Con Parks, Inc.                       | Food, Beverage & Retail      | 2012-03-21T00:00:00 | 2021-12-31T00:00:00 | 
| Allegany | Allegany - Camp Turner     | X001119  | Diocese of Buffalo                      | Group Camp                   | 2013-01-01T00:00:00 | 2022-12-31T00:00:00 | 
| Allegany | Allegany                   | X001107  | ASP Partners, LLC                       | Rental Cabins                | 2014-02-03T00:00:00 | 2034-02-03T00:00:00 | 
| Central  | Verona Beach               | XT001156 | Theodore Learned dba Teddy's Treats     | Food, Beverage & Retail      | 2014-06-28T00:00:00 | 2015-12-31T00:00:00 | 
| Central  | Green Lakes                | X001113  | Gance's Homemade, LLC                   | Food, Beverage & Catering    | 2013-01-01T00:00:00 | 2015-12-31T00:00:00 | 
| Central  | Bowman Lake                | XT001215 | Conover Family                          | Food & Beverage              | 2015-05-01T00:00:00 | 2015-12-31T00:00:00 | 
| Central  | Bowman Lake & Oquaga Creek | X001078  | R.Howse Properties, LLC                 | Rental Cabins                | 2012-05-01T00:00:00 | 2016-12-31T00:00:00 | 
| Central  | Chenango Valley            | XT001174 | Suzanne M. Skapik dba Suzys Snack Shack | Food & Beverage              | 2014-04-10T00:00:00 | 2016-12-31T00:00:00 | 
| Central  | Delta Lake                 | XT001155 | Deans Concessions                       | Food, Beverage & Sundry      | 2014-05-29T00:00:00 | 2016-12-31T00:00:00 | 
```