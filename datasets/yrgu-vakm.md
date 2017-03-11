# Right of Way Exception Data

## Dataset

* [Dataset URL](https://data.sfgov.org/api/views/yrgu-vakm/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/right-of-way-exception-data-2e2dc)
* [Metadata URL](https://data.sfgov.org/api/views/yrgu-vakm)
* Id = yrgu-vakm
* Name = Right of Way Exception Data
* Attribution = San Francisco Department of Public Works
* [Attribution Link](http://www.sfdpw.org)
* Category = City Infrastructure
* Tags = [exceptions, street, restrictions, permits]
* Created = 2012-09-25T00:09:14Z
* Publication Date = 2015-07-17T15:20:34Z
* Rows Updated = 2017-03-07T16:06:15Z

## Description

A table of restrictions and information about existing conditions in the public right of way.  including permits, moratorium streets, AWSS, SFMTA bluebook, 5 year plan, bike lanes, jurisdiction, monuments, etc.  AKA Street Restrictions, The Exception Table

## Columns

```ls
| Name               | Field Name         | Data Type     | Render Type   | Schema Type    | Included | 
| ================== | ================== | ============= | ============= | ============== | ======== | 
| ctrID              | ctrid              | text          | number        | series tag     | Yes      | 
| CNN                | cnn                | number        | number        | numeric metric | Yes      | 
| ExceptionCode      | exceptioncode      | text          | text          | series tag     | Yes      | 
| PermitType         | permittype         | text          | text          | series tag     | Yes      | 
| JobOrderNum        | jobordernum        | text          | text          | series tag     | Yes      | 
| ProjectName        | projectname        | text          | text          | series tag     | Yes      | 
| EffectiveDate      | effectivedate      | calendar_date | calendar_date | time           | Yes      | 
| ExpirationDate     | expirationdate     | calendar_date | calendar_date |                | No       | 
| ContactName        | contactname        | text          | text          | series tag     | Yes      | 
| ContactPhoneNumber | contactphonenumber | text          | text          | series tag     | Yes      | 
| Restriction_Tow    | restriction_tow    | text          | text          | series tag     | Yes      | 
| ModifiedDate       | modifieddate       | calendar_date | calendar_date |                | No       | 
| block              | block              | number        | text          | numeric metric | Yes      | 
| lot                | lot                | number        | text          | numeric metric | Yes      | 
```

## Time Field

```ls
Value = effectivedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = modifieddate,expirationdate
Annotation Fields = 
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

metric m:block p:integer l:block t:dataTypeName=number

metric m:lot p:integer l:lot t:dataTypeName=number

entity e:yrgu-vakm l:"Right of Way Exception Data" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/yrgu-vakm

property e:yrgu-vakm t:meta.view d:2017-03-07T16:32:58.274Z v:id=yrgu-vakm v:category="City Infrastructure" v:attributionLink=http://www.sfdpw.org v:averageRating=0 v:name="Right of Way Exception Data" v:attribution="San Francisco Department of Public Works"

property e:yrgu-vakm t:meta.view.license d:2017-03-07T16:32:58.274Z v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:yrgu-vakm t:meta.view.owner d:2017-03-07T16:32:58.274Z v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"

property e:yrgu-vakm t:meta.view.tableauthor d:2017-03-07T16:32:58.274Z v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```