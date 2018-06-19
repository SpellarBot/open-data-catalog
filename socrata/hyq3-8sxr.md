# Homeless Shelters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/homeless-shelters-bee9d) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/hyq3-8sxr) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/hyq3-8sxr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/hyq3-8sxr/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | hyq3-8sxr |
| Name | Homeless Shelters |
| Attribution | Human Services / Homeless Services |
| Category | Health |
| Tags | homeless, shelter |
| Created | 2011-12-14T18:09:31Z |
| Publication Date | 2014-03-27T23:52:59Z |

## Description

This data set shows the location of Baltimore City's Tansitional and Emergency "Homeless" Shelter Facilities. However, this is not a complete list. It is the most recent update (2008), and is subjected to change. The purpose of this data set is to aid Baltimore City organizations to best identify facilities to aid the homeless population. The data is broken down into two categories: Emergency Shelter and Transitional Housing. Please find the two definitions below. The first is simply ??_??_??_shelter??_?? and the second is a more involved program that is typically a longer stay. Emergency Shelter: Any facility with overnight sleeping accommodations, the primary purpose of which is to provide temporary shelter for the homeless in general or for specific populations of homeless persons. The length of stay can range from one night up to as much as six months. Transitional Housing: a project that is designed to provide housing and appropriate support services to homeless persons to facilitate movement to independent living within 24 months. These data set was provided by Greg Sileo, Director of the Mayor's Office of Baltimore Homeless Services.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | type            | type            | text      | text        |
| Yes      | series tag  | zipcode         | zipCode         | text      | text        |
| Yes      | series tag  | neighborhood    | neighborhood    | text      | text        |
| Yes      | series tag  | councildistrict | councilDistrict | text      | number      |
| Yes      | series tag  | policedistrict  | policeDistrict  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hyq3-8sxr d:2011-12-14T10:09:51.000Z t:councildistrict=10 t:zipcode=21230 t:name="American Rescue Workers" t:neighborhood=SBIC t:policedistrict=SOUTHERN t:type=Emergency m:row_number.hyq3-8sxr=1

series e:hyq3-8sxr d:2011-12-14T10:09:51.000Z t:councildistrict=12 t:zipcode=21202 t:name="Aunt CC's Harbor House" t:neighborhood=Oldtown t:policedistrict=EASTERN t:type=Emergency m:row_number.hyq3-8sxr=2

series e:hyq3-8sxr d:2011-12-14T10:09:51.000Z t:councildistrict=12 t:zipcode=21202 t:name="Baltimore Rescue Mission" t:neighborhood=Jonestown t:policedistrict=SOUTHEASTERN t:type=Emergency m:row_number.hyq3-8sxr=3
```

## Meta Commands

```ls
metric m:row_number.hyq3-8sxr p:long l:"Row Number"

entity e:hyq3-8sxr l:"Homeless Shelters" t:attribution="Human Services / Homeless Services" t:url=https://data.baltimorecity.gov/api/views/hyq3-8sxr

property e:hyq3-8sxr t:meta.view v:id=hyq3-8sxr v:category=Health v:attributionLink="http://www.baltimorecity.gov/Default.aspx?tabid=1550" v:averageRating=0 v:name="Homeless Shelters" v:attribution="Human Services / Homeless Services"

property e:hyq3-8sxr t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:hyq3-8sxr t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:hyq3-8sxr t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                     | type                  | zipcode | neighborhood        | councildistrict | policedistrict | 
| =========== | ======================== | ===================== | ======= | =================== | =============== | ============== | 
| 1323857391  | American Rescue Workers  | Emergency             | 21230   | SBIC                | 10              | SOUTHERN       | 
| 1323857391  | Aunt CC's Harbor House   | Emergency             | 21202   | Oldtown             | 12              | EASTERN        | 
| 1323857391  | Baltimore Rescue Mission | Emergency             | 21202   | Jonestown           | 12              | SOUTHEASTERN   | 
| 1323857391  | Christ Lutheran Place    | Emergency             | 21230   | Otterbein           | 11              | SOUTHERN       | 
| 1323857391  | Code Blue J, H & R       | Emergency (temporary) | 21202   | Jonestown           | 12              | SOUTHEASTERN   | 
| 1323857391  | Collington Square        | Emergency             | 21213   | Broadway East       | 13              | EASTERN        | 
| 1323857391  | Helping Up               | Emergency             | 21202   | Jonestown           | 12              | SOUTHEASTERN   | 
| 1323857391  | House of Ruth ES         | Emergency             |         |                     |                 |                | 
| 1323857391  | Interfaith ES            | Emergency             | 21217   | Sandtown-Winchester | 9               | WESTERN        | 
| 1323857391  | Karis House              | Emergency             | 21202   | Jonestown           | 12              | SOUTHEASTERN   | 
```