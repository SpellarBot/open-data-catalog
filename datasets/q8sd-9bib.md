# Designated Scenic Byways

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/q8sd-9bib/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/designated-scenic-byways)
* [Metadata URL](https://data.ny.gov/api/views/q8sd-9bib)
* Id = q8sd-9bib
* Name = Designated Scenic Byways
* Attribution = New York State Department of Transportation
* [Attribution Link](https://www.dot.ny.gov/display/programs/scenic-byways)
* Category = Transportation
* Tags = [scenic byways, national scenic byways, new york state scenic byways, cmp, corridor management plan, scenic roads, all american road]
* Created = 2013-02-14T21:48:27Z
* Publication Date = 2013-03-01T15:51:34Z
* Rows Updated = 2013-03-01T15:42:34Z

## Description

The New York State Scenic Byways program was created in 1992 by the State Legislature. The program encourages both economic development and resource conservation, recognizing that each of these aspects of a byway must be fostered to ensure the success of the other. This dataset is a listing of all designated State and National Scenic Byways in New York State with Scenic Byway Corridor Management Plans: Includes location, length, route description, designation and website. Information is current as of the publication date.

## Columns

```ls
| Name                       | Field Name               | Data Type | Render Type | Schema Type    | Included | 
| ========================== | ======================== | ========= | =========== | ============== | ======== | 
| updated_at                 | :updated_at              | meta_data | meta_data   | time           | No       | 
| Scenic Byway               | scenic_byway             | text      | text        | series tag     | Yes      | 
| Approximate Length (Miles) | approximate_length_miles | number    | number      | numeric metric | Yes      | 
| Region                     | region                   | text      | text        | series tag     | Yes      | 
| Connects                   | connects                 | text      | text        | series tag     | Yes      | 
| Primary Designation        | primary_designation      | text      | text        | series tag     | Yes      | 
| Secondary Designation      | secondary_designation    | text      | text        | series tag     | Yes      | 
| Tertiary Designation       | tertiary_designation     | number    | text        | numeric metric | Yes      | 
| For more information (URL) | for_more_information_url | url       | url         | series tag     | Yes      | 
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
series e:q8sd-9bib d:2013-02-14T13:48:29.000Z t:region="Great Lakes/ Canadian Border" t:primary_designation="National Scenic Byway (National Designation)" t:secondary_designation="State Scenic Byway" t:scenic_byway="Great Lakes Seaway Trail" t:connects="Ripley and Massena" m:approximate_length_miles=454

series e:q8sd-9bib d:2013-02-14T13:48:29.000Z t:region="Champlain and Hudson Valleys" t:primary_designation="All-American Road (National Designation)" t:secondary_designation="State Scenic Byway" t:scenic_byway="Lakes to Locks Passage" t:connects="Canadian Border and Waterford" m:approximate_length_miles=225

series e:q8sd-9bib d:2013-02-14T13:48:29.000Z t:region=Adirondacks t:primary_designation="State Scenic Byway" t:scenic_byway="Adirondack Trail" t:connects="Fonda and Malone" m:approximate_length_miles=179
```

## Meta Commands

```ls
metric m:approximate_length_miles p:integer l:"Approximate Length (Miles)" d:"Approximate total length of the byway measured in miles." t:dataTypeName=number

metric m:tertiary_designation l:"Tertiary Designation" d:"The tertiary designation of the byway (where applicable)." t:dataTypeName=number

entity e:q8sd-9bib l:"Designated Scenic Byways" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/q8sd-9bib

property e:q8sd-9bib t:meta.view d:2017-03-07T17:12:26.268Z v:id=q8sd-9bib v:category=Transportation v:attributionLink=https://www.dot.ny.gov/display/programs/scenic-byways v:averageRating=0 v:name="Designated Scenic Byways" v:attribution="New York State Department of Transportation"

property e:q8sd-9bib t:meta.view.owner d:2017-03-07T17:12:26.268Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:q8sd-9bib t:meta.view.tableauthor d:2017-03-07T17:12:26.268Z v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:q8sd-9bib t:meta.view.metadata.custom_fields.common_core d:2017-03-07T17:12:26.268Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```