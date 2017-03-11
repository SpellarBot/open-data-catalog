# DBEDT Hawaii De Facto Population By County 2000-2010

## Dataset

* [Dataset URL](https://data.hawaii.gov/api/views/i7pr-uy4x/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/dbedt-hawaii-de-facto-population-by-county-2000-2010-a67b7)
* Id = i7pr-uy4x
* Name = DBEDT Hawaii De Facto Population By County 2000-2010
* Attribution = Department of Economic Development and Tourism
* Attribution Link = http://hawaii.gov/dbedt
* Category = Economic Development
* Tags = [people, population]
* Created = 2012-08-28T19:43:49Z
* Publication Date = 2012-08-29T01:28:08Z
* Rows Updated = 2012-08-28T19:44:29Z

## Description



## Columns

```ls
| Name                        | Field Name                  | Data Type | Render Type | Schema Type    | Included | 
| =========================== | =========================== | ========= | =========== | ============== | ======== | 
| updated_at                  | :updated_at                 | meta_data | meta_data   | time           | Yes      | 
| X Values                    | x_values                    | number    | number      | numeric metric | Yes      | 
| City and County of Honolulu | city_and_county_of_honolulu | number    | number      | numeric metric | Yes      | 
| Hawaii County               | hawaii_county               | number    | number      | numeric metric | Yes      | 
| Kauai County                | kauai_county                | number    | number      | numeric metric | Yes      | 
| Maui County                 | maui_county                 | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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
series e:i7pr-uy4x d:2012-08-28T12:43:50.000Z m:hawaii_county=137103 m:city_and_county_of_honolulu=913268 m:maui_county=138390 m:x_values=1990 m:kauai_county=68558

series e:i7pr-uy4x d:2012-08-28T12:43:50.000Z m:hawaii_county=141240 m:city_and_county_of_honolulu=901717 m:maui_county=139703 m:x_values=1991 m:kauai_county=69605

series e:i7pr-uy4x d:2012-08-28T12:43:50.000Z m:hawaii_county=146421 m:city_and_county_of_honolulu=912514 m:maui_county=146651 m:x_values=1992 m:kauai_county=66076
```

## Meta Commands

```ls
metric m:x_values p:integer l:"X Values" t:dataTypeName=number

metric m:city_and_county_of_honolulu p:integer l:"City and County of Honolulu" t:dataTypeName=number

metric m:hawaii_county p:integer l:"Hawaii County" t:dataTypeName=number

metric m:kauai_county p:integer l:"Kauai County" t:dataTypeName=number

metric m:maui_county p:integer l:"Maui County" t:dataTypeName=number

entity e:i7pr-uy4x l:"DBEDT Hawaii De Facto Population By County 2000-2010" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/i7pr-uy4x

property e:i7pr-uy4x t:meta.view d:2017-03-03T14:00:57.882Z v:id=i7pr-uy4x v:category="Economic Development" v:attributionLink=http://hawaii.gov/dbedt v:averageRating=0 v:name="DBEDT Hawaii De Facto Population By County 2000-2010" v:attribution="Department of Economic Development and Tourism"

property e:i7pr-uy4x t:meta.view.license d:2017-03-03T14:00:57.882Z v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:i7pr-uy4x t:meta.view.owner d:2017-03-03T14:00:57.882Z v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"

property e:i7pr-uy4x t:meta.view.tableauthor d:2017-03-03T14:00:57.882Z v:id=uaqq-pakk v:screenName="Douglas Oshiro" v:displayName="Douglas Oshiro"
```