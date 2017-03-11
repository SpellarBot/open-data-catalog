# Campaign Consultants - Vendor Payments

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/ewuz-v3y2/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/campaign-consultants-vendor-payments-066bd)
* [Metadata URL](https://data.sfgov.org/api/views/ewuz-v3y2)
* Id = ewuz-v3y2
* Name = Campaign Consultants - Vendor Payments
* Attribution = San Francisco Ethics Commission
* [Attribution Link](http://www.sfethics.org)
* Category = City Management and Ethics
* Tags = [campaign consultant, ethics, vendors, sub-vendors, payments]
* Created = 2013-07-19T23:10:46Z
* Publication Date = 2013-07-22T22:49:57Z
* Rows Updated = 2017-03-07T03:55:06Z

## Description

Campaign consultants must report economic consideration promised to or received by the filer during the reporting period from vendors and sub-vendors who provide campaign-related goods or services to the filer??s current clients.

## Columns

```ls
| Name                   | Field Name             | Data Type     | Render Type   | Schema Type    | Included | 
| ====================== | ====================== | ============= | ============= | ============== | ======== | 
| Consultant             | consultant             | text          | text          | series tag     | Yes      | 
| Vendor/Sub-vendor Name | vendor_sub_vendor_name | text          | text          | series tag     | Yes      | 
| Payments promised      | payments_promised      | money         | money         | numeric metric | Yes      | 
| Payments received      | payments_received      | money         | money         | numeric metric | Yes      | 
| Quarter Start Date     | quarter_start_date     | calendar_date | calendar_date | time           | Yes      | 
| Quarter End Date       | quarter_end_date       | calendar_date | calendar_date |                | No       | 
| Quarter                | quarter                | number        | text          | numeric metric | Yes      | 
| Year                   | year                   | number        | text          |                | No       | 
```

## Time Field

```ls
Value = quarter_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = quarter_end_date,year
Annotation Fields = 
```

## Data Commands

```ls
series e:ewuz-v3y2 d:2016-03-01T00:00:00.000Z t:consultant="Muir Consulting" t:vendor_sub_vendor_name="Spot On" m:payments_received=3250 m:payments_promised=3250 m:quarter=2

series e:ewuz-v3y2 d:2014-09-01T00:00:00.000Z t:consultant="Lester Connect" t:vendor_sub_vendor_name="Pacific Print Resource" m:payments_received=630.5 m:payments_promised=630.5 m:quarter=4

series e:ewuz-v3y2 d:2014-09-01T00:00:00.000Z t:consultant="Lester Connect" t:vendor_sub_vendor_name="Lizard Press" m:payments_received=875 m:payments_promised=875 m:quarter=4
```

## Meta Commands

```ls
metric m:quarter p:integer l:Quarter t:dataTypeName=number

entity e:ewuz-v3y2 l:"Campaign Consultants - Vendor Payments" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/ewuz-v3y2

property e:ewuz-v3y2 t:meta.view d:2017-03-08T01:47:05.697Z v:id=ewuz-v3y2 v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Campaign Consultants - Vendor Payments" v:attribution="San Francisco Ethics Commission"

property e:ewuz-v3y2 t:meta.view.license d:2017-03-08T01:47:05.697Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ewuz-v3y2 t:meta.view.owner d:2017-03-08T01:47:05.697Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"

property e:ewuz-v3y2 t:meta.view.tableauthor d:2017-03-08T01:47:05.697Z v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```