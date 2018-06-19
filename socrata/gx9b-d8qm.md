# Centerline Rumble Strips (CARDS) Installations: Beginning 2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/centerline-rumble-strips-cards-installations-beginning-2012) |
| Metadata | [Link](https://data.ny.gov/api/views/gx9b-d8qm) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/gx9b-d8qm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/gx9b-d8qm/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | gx9b-d8qm |
| Name | Centerline Rumble Strips (CARDS) Installations: Beginning 2012 |
| Attribution | New York State Department of Transportation |
| Category | Transportation |
| Tags | cards, centerline rumble strips, rumble stripes |
| Created | 2014-10-02T15:22:51Z |
| Publication Date | 2016-04-27T22:03:22Z |

## Description

This data set shows the location of center line rumble strips installed across state highways in New York State by the Department of Transportation (NYS DOT).  It  includes the county and route where installed, the to and from reference markers definining the installation, the length in miles and the year each section was completed. Centerline Rumble Strips are installed to reduce fatal and injury accident resulting from "Run off the Road Crashes" (non-intersection head-on and opposite-direction sideswipe crashes). The official name for centerline rumble strips is Centerline Audible Roadway Delineators (CARDS).

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | county                | County                | text      | text        |
| Yes      | series tag     | from_reference_marker | From Reference Marker | text      | text        |
| Yes      | series tag     | to_reference_marker   | To Reference Marker   | text      | text        |
| Yes      | series tag     | route                 | Route                 | text      | text        |
| Yes      | numeric metric | length_in_miles       | Length in Miles       | number    | number      |
| Yes      | time           | year_constructed      | Year Constructed      | number    | number      |
```

## Time Field

```ls
Value = year_constructed
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gx9b-d8qm d:2014-01-01T00:00:00.000Z t:to_reference_marker=9W11051037 t:county=Albany t:route=US9W t:from_reference_marker=9W11051012 m:length_in_miles=2.47

series e:gx9b-d8qm d:2012-01-01T00:00:00.000Z t:to_reference_marker=9W11051071 t:county=Albany t:route=US9W t:from_reference_marker=9W11051084 m:length_in_miles=1.28

series e:gx9b-d8qm d:2014-01-01T00:00:00.000Z t:to_reference_marker="43 11021123" t:county=Albany t:route=NY85 t:from_reference_marker="43 11021103" m:length_in_miles=2
```

## Meta Commands

```ls
metric m:length_in_miles p:float l:"Length in Miles" d:"Distance in miles covered by the center line rumble strip installation project" t:dataTypeName=number

entity e:gx9b-d8qm l:"Centerline Rumble Strips (CARDS) Installations: Beginning 2012" t:attribution="New York State Department of Transportation" t:url=https://data.ny.gov/api/views/gx9b-d8qm

property e:gx9b-d8qm t:meta.view v:id=gx9b-d8qm v:category=Transportation v:attributionLink=https://www.dot.ny.gov/programs/rumblestrips/centerrumblestrips v:averageRating=0 v:name="Centerline Rumble Strips (CARDS) Installations: Beginning 2012" v:attribution="New York State Department of Transportation"

property e:gx9b-d8qm t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:gx9b-d8qm t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:gx9b-d8qm t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county | from_reference_marker | to_reference_marker | route | length_in_miles | year_constructed | 
| ====== | ===================== | =================== | ===== | =============== | ================ | 
| Albany | 9W11051012            | 9W11051037          | US9W  | 2.47            | 2014             | 
| Albany | 9W11051084            | 9W11051071          | US9W  | 1.28            | 2012             | 
| Albany | 43 11021103           | 43 11021123         | NY85  | 2               | 2014             | 
| Albany | 43 11021122           | 43 11021139         | NY85  | 1.7             | 2014             | 
| Albany | 85 11011077           | 85 11011103         | NY85  | 2.57            | 2013             | 
| Albany | 85 11011228           | 85 11011241         | NY85  | 1.32            | 2011             | 
| Albany | 85 11011122           | 85 11011144         | NY85  | 2.23            | 2013             | 
| Albany | 144 11021057          | 144 11021114        | NY144 | 5.67            | 2015             | 
| Albany | 146 11021116          | 146 11021134        | NY146 | 1.81            | 2013             | 
| Albany | 146 11021083          | 146 11021105        | NY146 | 2.21            | 2014             | 
```