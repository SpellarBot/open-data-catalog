# City of Seattle Official Blogging Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cos-statistics-blogs) |
| Metadata | [Link](https://data.seattle.gov/api/views/njt7-eq96) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/njt7-eq96/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/njt7-eq96/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | njt7-eq96 |
| Name | City of Seattle Official Blogging Statistics |
| Attribution | webmaster@seattle.gov |
| Category | City Business |
| Tags | cos, statistics, blogs, pageviews, njt7-eq96 |
| Created | 2016-09-15T15:43:02Z |
| Publication Date | 2016-09-15T15:46:52Z |

## Description

This dataset contains statistics on the usage patterns of the official City of Seattle blogs. 2011 - Present. It replaces an internal spreadsheet. The information is used to compare pageview activity between blogs. Not all urls represented in the datasheet are active. Active blogs would have pageviews greater than zero for the most recent month uploaded. The format of this dataset is likely to change over time per approved requests to track additional automated information.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type     | Render Type   |
| ======== | ============== | ========== | ========= | ============= | ============= |
| Yes      | series tag     | url        | URL       | text          | text          |
| Yes      | numeric metric | pageviews  | Pageviews | number        | number        |
| Yes      | numeric metric | sessions   | Sessions  | number        | number        |
| Yes      | time           | date       | Date      | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:njt7-eq96 d:2014-10-01T00:00:00.000Z t:url=http://thebuyline.seattle.gov/ m:sessions=1367 m:pageviews=4367

series e:njt7-eq96 d:2011-06-01T00:00:00.000Z t:url=http://mayormcginn.seattle.gov/ m:sessions=4112 m:pageviews=5769

series e:njt7-eq96 d:2017-01-01T00:00:00.000Z t:url=http://alert.seattle.gov/ m:sessions=1533 m:pageviews=2374
```

## Meta Commands

```ls
metric m:pageviews p:integer l:Pageviews t:dataTypeName=number

metric m:sessions p:integer l:Sessions t:dataTypeName=number

entity e:njt7-eq96 l:"City of Seattle Official Blogging Statistics" t:attribution=webmaster@seattle.gov t:url=https://data.seattle.gov/api/views/njt7-eq96

property e:njt7-eq96 t:meta.view v:id=njt7-eq96 v:category="City Business" v:averageRating=0 v:name="City of Seattle Official Blogging Statistics" v:attribution=webmaster@seattle.gov

property e:njt7-eq96 t:meta.view.license v:name="Public Domain"

property e:njt7-eq96 t:meta.view.owner v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:displayName="Eckstine, Nate"

property e:njt7-eq96 t:meta.view.tableauthor v:id=seg8-ihrf v:profileImageUrlMedium=/api/users/seg8-ihrf/profile_images/THUMB v:profileImageUrlLarge=/api/users/seg8-ihrf/profile_images/LARGE v:screenName="Eckstine, Nate" v:profileImageUrlSmall=/api/users/seg8-ihrf/profile_images/TINY v:roleName=administrator v:displayName="Eckstine, Nate"
```

## Top Records

```ls
| url                                | pageviews | sessions | date                | 
| ================================== | ========= | ======== | =================== | 
| http://thebuyline.seattle.gov/     | 4367      | 1367     | 2014-10-01T00:00:00 | 
| http://mayormcginn.seattle.gov/    | 5769      | 4112     | 2011-06-01T00:00:00 | 
| http://alert.seattle.gov/          | 2374      | 1533     | 2017-01-01T00:00:00 | 
| http://sawant.seattle.gov/         | 2107      | 1417     | 2015-06-01T00:00:00 | 
| http://marriage.seattle.gov/       | 6         | 5        | 2015-01-01T00:00:00 | 
| http://Licata.seattle.gov/         | 1409      | 700      | 2012-02-01T00:00:00 | 
| http://humaninterests.seattle.gov/ | 732       | 505      | 2016-07-01T00:00:00 | 
| http://council.seattle.gov/        | 3769      | 2594     | 2016-08-01T00:00:00 | 
| http://cityclerk.seattle.gov/      | 910       | 469      | 2015-03-01T00:00:00 | 
| http://ois.seattle.gov/            | 0         | 0        | 2012-10-01T00:00:00 | 
```