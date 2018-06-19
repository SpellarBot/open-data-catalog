# CTA - List of Fare Media Sales Outlets (deprecated August 2014)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cta-list-of-fare-media-sales-outlets-deprecated-august-2014-d77d5) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/ag7u-gr9m) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/ag7u-gr9m/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/ag7u-gr9m/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | ag7u-gr9m |
| Name | CTA - List of Fare Media Sales Outlets (deprecated August 2014) |
| Category | Transportation |
| Tags | cta, chicago transit authority, ventra, bus, rail, deprecated |
| Created | 2011-10-13T21:52:37Z |
| Publication Date | 2013-10-14T18:37:54Z |

## Description

List of physical locations where fare media were sold through approximately July 2014, prior to the implementation of Ventra cards.  The locations for Ventra card sales/reloading are more extensive and not yet available in dataset format.  Please see http://www.transitchicago.com/ventra for information on the Ventra program and https://www.ventrachicago.com/retailers/locations to find Ventra retail locations.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | name                 | NAME                 | text      | text        |
| Yes      | series tag     | outlet_type          | OUTLET TYPE          | text      | text        |
| Yes      | series tag     | street_address       | STREET ADDRESS       | text      | text        |
| Yes      | series tag     | phone_number         | PHONE NUMBER         | phone     | phone       |
| Yes      | series tag     | payments_accepted    | PAYMENTS ACCEPTED    | text      | text        |
| Yes      | series tag     | fare_media_available | FARE MEDIA AVAILABLE | text      | text        |
| No       |                | lat                  | LAT                  | number    | number      |
| Yes      | numeric metric | lon                  | LON                  | number    | number      |
| Yes      | series tag     | city                 | CITY                 | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = lat
```

## Data Commands

```ls
series e:ag7u-gr9m d:2014-01-01T00:00:00.000Z t:payments_accepted=Varies t:outlet_type="Ventra Retail Location" t:fare_media_available=Varies t:name="CVS Store 5797" t:street_address="26w212 Geneva Road" t:city="Carol Stream" m:lon=-88.136724

series e:ag7u-gr9m d:2014-01-01T00:00:00.000Z t:payments_accepted=Varies t:outlet_type="Ventra Retail Location" t:fare_media_available=Varies t:name="Jewel-Osco Store 3114" t:street_address="3128 W 103rd Street" t:city=Chicago m:lon=-87.7001574

series e:ag7u-gr9m d:2014-01-01T00:00:00.000Z t:payments_accepted=Varies t:outlet_type="Ventra Retail Location" t:fare_media_available=Varies t:name="St John Fisher" t:street_address="10200 S Washtenaw" t:city=Chicago m:lon=-87.6430502
```

## Meta Commands

```ls
metric m:lon p:double l:LON t:dataTypeName=number

entity e:ag7u-gr9m l:"CTA - List of Fare Media Sales Outlets (deprecated August 2014)" t:url=https://data.cityofchicago.org/api/views/ag7u-gr9m

property e:ag7u-gr9m t:meta.view v:id=ag7u-gr9m v:category=Transportation v:averageRating=0 v:name="CTA - List of Fare Media Sales Outlets (deprecated August 2014)"

property e:ag7u-gr9m t:meta.view.owner v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:displayName="cta web"

property e:ag7u-gr9m t:meta.view.tableauthor v:id=6bsn-5494 v:profileImageUrlMedium=/api/users/6bsn-5494/profile_images/THUMB v:profileImageUrlLarge=/api/users/6bsn-5494/profile_images/LARGE v:screenName="cta web" v:profileImageUrlSmall=/api/users/6bsn-5494/profile_images/TINY v:roleName=designer v:displayName="cta web"
```

## Top Records

```ls
| name                      | outlet_type            | street_address             | phone_number         | payments_accepted | fare_media_available                              | lat        | lon         | city         | 
| ========================= | ====================== | ========================== | ==================== | ================= | ================================================= | ========== | =========== | ============ | 
| CVS Store 5797            | Ventra Retail Location | 26w212 Geneva Road         | [null, null]         | Varies            | Varies                                            | 41.888273  | -88.136724  | Carol Stream | 
| Jewel-Osco Store 3114     | Ventra Retail Location | 3128 W 103rd Street        | [null, null]         | Varies            | Varies                                            | 41.7062536 | -87.7001574 | Chicago      | 
| St John Fisher            | Ventra Retail Location | 10200 S Washtenaw          | [null, null]         | Varies            | Varies                                            | 41.7068154 | -87.6430502 | Chicago      | 
| Walgreens - Store # 11492 | Food Store             | 5414 South Archer          | [773-581-1664, null] | Varies            | Purchase Chicago Cards, Transit Cards and Passes. | 41.79876   | -87.742971  | Chicago      | 
| Walgreens Store 15065     | Food Store             | 1601 N Milwaukee Ave       | [773-342-9161, null] | Varies            | Purchase Chicago Cards, Transit Cards and Passes. | 41.910704  | -87.677792  | Chicago      | 
| Walmart Store 5646        | Food Store             | 2551 W Cermak Rd           | [773-475-4209, null] | Varies            | Purchase Chicago Cards, Transit Cards and Passes. | 41.851921  | -87.689926  | Chicago      | 
| Woof World                | Ventra Retail Location | 27W230 Beecher Avenue      | [null, null]         | Varies            | Varies                                            | 41.8693559 | -88.1629239 | Winfield     | 
| Jewel - Store #3187       | Food Store             | 11730 S. Marshfield Av.    | [773-568-8157, null] | Varies            | Purchase Chicago Cards, Transit Cards and Passes. | 41.680334  | -87.662438  | Chicago      | 
| CVS - Store # 2809        | Food Store             | 2815 N. Western Avenue     | [773-486-4105, null] | Varies            | Purchase Transit Cards and Passes.                | 41.93266   | -87.687918  | Chicago      | 
| New 47th & Lake Park C E  | Ventra Retail Location | 1400 E. 47th Street Unit H | [null, null]         | Varies            | Varies                                            | 41.8096904 | -87.5925059 | Chicago      | 
```