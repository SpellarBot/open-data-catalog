# Right of Way Exception Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/right-of-way-exception-data-2e2dc) |
| Metadata | [Link](https://data.sfgov.org/api/views/yrgu-vakm) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/yrgu-vakm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/yrgu-vakm/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | yrgu-vakm |
| Name | Right of Way Exception Data |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | exceptions, street, restrictions, permits |
| Created | 2012-09-25T00:09:14Z |
| Publication Date | 2015-07-17T15:20:34Z |
| Rows Updated | 2017-03-23T15:04:47Z |

## Description

A table of restrictions and information about existing conditions in the public right of way.  including permits, moratorium streets, AWSS, SFMTA bluebook, 5 year plan, bike lanes, jurisdiction, monuments, etc.  AKA Street Restrictions, The Exception Table

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | ctrid              | ctrID              | text          | number        |
| Yes      | numeric metric | cnn                | CNN                | number        | number        |
| Yes      | series tag     | exceptioncode      | ExceptionCode      | text          | text          |
| Yes      | series tag     | permittype         | PermitType         | text          | text          |
| Yes      | series tag     | jobordernum        | JobOrderNum        | text          | text          |
| Yes      | series tag     | projectname        | ProjectName        | text          | text          |
| Yes      | time           | effectivedate      | EffectiveDate      | calendar_date | calendar_date |
| No       |                | expirationdate     | ExpirationDate     | calendar_date | calendar_date |
| Yes      | series tag     | contactname        | ContactName        | text          | text          |
| Yes      | series tag     | contactphonenumber | ContactPhoneNumber | text          | text          |
| Yes      | series tag     | restriction_tow    | Restriction_Tow    | text          | text          |
| No       |                | modifieddate       | ModifiedDate       | calendar_date | calendar_date |
| Yes      | series tag     | block              | block              | text          | text          |
| Yes      | series tag     | lot                | lot                | text          | text          |
```

## Time Field

```ls
Value = effectivedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expirationdate,modifieddate
```

## Data Commands

```ls
series e:yrgu-vakm d:1980-01-01T00:00:00.000Z t:contactname="Alex Demisch" t:exceptioncode=SFPARK t:contactphonenumber="(415) 701-4507" t:ctrid=625234 m:cnn=9122002

series e:yrgu-vakm d:1980-01-01T00:00:00.000Z t:contactname="Alex Demisch" t:exceptioncode=SFPARK t:contactphonenumber="(415) 701-4507" t:ctrid=625235 m:cnn=9122001

series e:yrgu-vakm d:1980-01-01T00:00:00.000Z t:contactname="Alex Demisch" t:exceptioncode=SFPARK t:contactphonenumber="(415) 701-4507" t:ctrid=625236 m:cnn=12318002
```

## Meta Commands

```ls
metric m:cnn p:integer l:CNN t:dataTypeName=number

entity e:yrgu-vakm l:"Right of Way Exception Data" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/yrgu-vakm

property e:yrgu-vakm t:meta.view v:id=yrgu-vakm v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Right of Way Exception Data" v:attribution="San Francisco Department of Public Works"

property e:yrgu-vakm t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:yrgu-vakm t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:yrgu-vakm t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```