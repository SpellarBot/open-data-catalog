# Facilities Management - Electricity Usage, 2121 Euclid Av Facility, by Month - Fiscal Year 2008 through February 2012

## Dataset

* [Dataset URL](https://datacatalog.cookcountyil.gov/api/views/avst-7ttu/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/facilities-management-electricity-usage-2121-euclid-av-facility-by-month-fiscal-year-200-2-bd509)
* Id = avst-7ttu
* Name = Facilities Management - Electricity Usage, 2121 Euclid Av Facility, by Month - Fiscal Year 2008 through February 2012
* Attribution = Cook County Department of Facilities Management
* Attribution Link = http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management
* Category = Finance & Administration
* Created = 2012-03-20T20:02:50Z
* Publication Date = 2014-10-09T22:33:33Z
* Rows Updated = 2014-10-09T22:33:27Z

## Description



## Columns

```ls
| Name        | Field Name  | Data Type | Render Type | Schema Type    | Included | 
| =========== | =========== | ========= | =========== | ============== | ======== | 
| Month       | month       | text      | text        | series tag     | Yes      | 
| Fiscal Year | fiscal_year | number    | text        | time           | Yes      | 
| Usage (kWh) | usage_kwh   | text      | text        | series tag     | Yes      | 
| Cost        | cost        | money     | money       | numeric metric | Yes      | 
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:avst-7ttu d:2011-01-01T00:00:00.000Z t:usage_kwh=546,355.20 t:month=April m:cost=49837.92

series e:avst-7ttu d:2008-01-01T00:00:00.000Z t:usage_kwh=880,914.24 t:month=January m:cost=68450.91

series e:avst-7ttu d:2010-01-01T00:00:00.000Z t:usage_kwh=683,354.61 t:month=August m:cost=64074.54
```

## Meta Commands

```ls
entity e:avst-7ttu l:"Facilities Management - Electricity Usage, 2121 Euclid Av Facility, by Month - Fiscal Year 2008 through February 2012" t:attribution="Cook County Department of Facilities Management" t:url=https://datacatalog.cookcountyil.gov/api/views/avst-7ttu

property e:avst-7ttu t:meta.view d:2017-03-03T13:47:11.070Z v:id=avst-7ttu v:category="Finance & Administration" v:attributionLink=http://www.cookcountygov.com/portal/server.pt/community/facilities_management/294/facilities_management v:averageRating=0 v:name="Facilities Management - Electricity Usage, 2121 Euclid Av Facility, by Month - Fiscal Year 2008 through February 2012" v:attribution="Cook County Department of Facilities Management"

property e:avst-7ttu t:meta.view.license d:2017-03-03T13:47:11.070Z v:name="Public Domain"

property e:avst-7ttu t:meta.view.owner d:2017-03-03T13:47:11.070Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:avst-7ttu t:meta.view.tableauthor d:2017-03-03T13:47:11.070Z v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```