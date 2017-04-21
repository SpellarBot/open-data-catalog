# Recommended Fishing Rivers And Streams

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recommended-fishing-rivers-and-streams) |
| Metadata | [Link](https://data.ny.gov/api/views/jcxg-7gnm) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/jcxg-7gnm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/jcxg-7gnm/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | jcxg-7gnm |
| Name | Recommended Fishing Rivers And Streams |
| Attribution | New York State Department of Environmental Conservation |
| Category | Recreation |
| Tags | river, stream, fish, angler |
| Created | 2013-02-15T15:34:18Z |
| Publication Date | 2015-06-26T19:52:14Z |

## Description

This data displays the access  locations of rivers and streams for fishing in New York State, as determined by fisheries biologists working for the New York State Department of Environmental Conservation. Although every effort has been made to ensure the accuracy of information, errors may be reflected in the data supplied. The user must be aware of data conditions and bear responsibility for the appropriate use of the information with respect to possible errors, original map scale, collection methodology, currency of data, and other conditions.

## Columns

```ls
| Included | Schema Type | Field Name  | Name                              | Data Type | Render Type |
| ======== | =========== | =========== | ================================= | ========= | =========== |
| No       | time        | :updated_at | updated_at                        | meta_data | meta_data   |
| Yes      | series tag  | name        | Waterbody Name                    | text      | text        |
| Yes      | series tag  | fish_spec   | Fish Species Present at Waterbody | text      | text        |
| Yes      | series tag  | comments    | Comments                          | text      | text        |
| Yes      | series tag  | spec_regs   | Special Regulations on Waterbody  | url       | url         |
| Yes      | series tag  | county      | County                            | text      | text        |
| Yes      | series tag  | public_acc  | Types of Public Access            | text      | text        |
| Yes      | series tag  | access_own  | Public Fishing Access Owner       | text      | text        |
| Yes      | series tag  | site_wl     | Waterbody Information             | url       | url         |
| No       |             | point_x     | Longitude                         | number    | number      |
| No       |             | point_y     | Latitude                          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = point_x,point_y
```

## Data Commands

```ls
series e:jcxg-7gnm d:2013-02-20T18:55:58.000Z t:fish_spec="Brown Trout* - Sunfish" t:county=Chemung t:access_own="Public Easement" t:name="Cayuta Creek" t:spec_regs=http://www.dec.ny.gov/outdoor/31435.html t:public_acc="Shore Fishing - Public Fishing Rights" t:site_wl=http://www.dec.ny.gov/docs/fish_marine_pdf/pfrcayutack.pdf t:comments=None m:row_number.jcxg-7gnm=1

series e:jcxg-7gnm d:2013-02-20T18:55:58.000Z t:fish_spec="Brook Trout - Brown Trout*" t:county=Tompkins t:access_own="Public Easement - Potato Hill State Forest (DEC)" t:name="West Branch Owego Creek" t:spec_regs=http://www.dec.ny.gov/outdoor/31498.html t:public_acc="Shore Fishing - Public Fishing Rights" t:site_wl=http://www.dec.ny.gov/outdoor/71802.html t:comments=None m:row_number.jcxg-7gnm=2

series e:jcxg-7gnm d:2013-02-20T18:55:58.000Z t:fish_spec="Brown Trout - Rainbow Trout" t:county=Livingston t:access_own="Springwater Town Park - Public Easement" t:name="Springwater Creek" t:spec_regs=http://www.dec.ny.gov/outdoor/31505.html t:public_acc="Shore Fishing - Public Fishing Rights" t:site_wl=http://www.dec.ny.gov/docs/fish_marine_pdf/pfrsprngwtck.pdf t:comments="City of Rochester permit required north of Kellogg Rd (585-428-6680)." m:row_number.jcxg-7gnm=3
```

## Meta Commands

```ls
metric m:row_number.jcxg-7gnm p:long l:"Row Number"

entity e:jcxg-7gnm l:"Recommended Fishing Rivers And Streams" t:attribution="New York State Department of Environmental Conservation" t:url=https://data.ny.gov/api/views/jcxg-7gnm

property e:jcxg-7gnm t:meta.view v:id=jcxg-7gnm v:category=Recreation v:attributionLink=http://www.dec.ny.gov/outdoor/7749.html v:averageRating=0 v:name="Recommended Fishing Rivers And Streams" v:attribution="New York State Department of Environmental Conservation"

property e:jcxg-7gnm t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:jcxg-7gnm t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:jcxg-7gnm t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | name                    | fish_spec                                                                   | comments                                                              | spec_regs                                        | county     | public_acc                                | access_own                                       | site_wl                                                              | point_x       | point_y      | 
| =========== | ======================= | =========================================================================== | ===================================================================== | ================================================ | ========== | ========================================= | ================================================ | ==================================================================== | ============= | ============ | 
| 1361386558  | Cayuta Creek            | Brown Trout* - Sunfish                                                      | None                                                                  | [http://www.dec.ny.gov/outdoor/31435.html, null] | Chemung    | Shore Fishing - Public Fishing Rights     | Public Easement                                  | [http://www.dec.ny.gov/docs/fish_marine_pdf/pfrcayutack.pdf, null]   | -76.611963564 | 42.227337629 | 
| 1361386558  | West Branch Owego Creek | Brook Trout - Brown Trout*                                                  | None                                                                  | [http://www.dec.ny.gov/outdoor/31498.html, null] | Tompkins   | Shore Fishing - Public Fishing Rights     | Public Easement - Potato Hill State Forest (DEC) | [http://www.dec.ny.gov/outdoor/71802.html, null]                     | -76.244183074 | 42.342364928 | 
| 1361386558  | Springwater Creek       | Brown Trout - Rainbow Trout                                                 | City of Rochester permit required north of Kellogg Rd (585-428-6680). | [http://www.dec.ny.gov/outdoor/31505.html, null] | Livingston | Shore Fishing - Public Fishing Rights     | Springwater Town Park - Public Easement          | [http://www.dec.ny.gov/docs/fish_marine_pdf/pfrsprngwtck.pdf, null]  | -77.602341462 | 42.634651912 | 
| 1361386558  | Irondequoit Creek       | Brown Trout* - Chinook Salmon - Coho Salmon - Steelhead*                    | None                                                                  | [http://www.dec.ny.gov/outdoor/31420.html, null] | Monroe     | Shore Fishing                             | Ellison County Park                              | [http://www.dec.ny.gov/docs/fish_marine_pdf/pfrirondiqck.pdf, null]  | -77.521331332 | 43.150610148 | 
| 1361386558  | Black Creek             | Northern Pike                                                               | None                                                                  | [null, null]                                     | Monroe     | Shore Fishing - Boat Launch (Hand Launch) | Black Creek Waterway Access (DEC)                | [http://www.dec.ny.gov/outdoor/23886.html, null]                     | -77.680819269 | 43.094731591 | 
| 1361386558  | Cryder Creek            | Brook Trout - Brown Trout*                                                  | None                                                                  | [http://www.dec.ny.gov/outdoor/31494.html, null] | Allegany   | Shore Fishing - Public Fishing Rights     | Public Easement                                  | [http://www.dec.ny.gov/docs/fish_marine_pdf/crydercreek.pdf, null]   | -77.774019415 | 42.036298217 | 
| 1361386558  | Oatka Creek             | Brown Trout*                                                                | None                                                                  | [http://www.dec.ny.gov/outdoor/31448.html, null] | Genesee    | Shore Fishing - Public Fishing Rights     | Public Easement                                  | [http://www.dec.ny.gov/docs/fish_marine_pdf/pfroatkacreek.pdf, null] | -77.944782026 | 43.013874737 | 
| 1361386558  | Mill Creek              | Brook Trout - Brown Trout                                                   | None                                                                  | [http://www.dec.ny.gov/outdoor/31494.html, null] | Steuben    | Shore Fishing - Public Fishing Rights     | Public Easement                                  | [http://www.dec.ny.gov/docs/fish_marine_pdf/pfrmillckr8.pdf, null]   | -77.612254518 | 42.543555961 | 
| 1361386558  | Sandy Creek             | Brown Trout - Chinook Salmon* - Coho Salmon* - Steelhead*                   | None                                                                  | [http://www.dec.ny.gov/outdoor/31420.html, null] | Monroe     | Shore Fishing - Public Fishing Rights     | Public Easement                                  | [http://www.dec.ny.gov/docs/fish_marine_pdf/pfrsandycreek.pdf, null] | -77.964620723 | 43.297090234 | 
| 1361386558  | Oak Orchard Creek       | Atlantic Salmon - Brown Trout - Chinook Salmon* - Coho Salmon* - Steelhead* | Privately owned campground available.                                 | [http://www.dec.ny.gov/outdoor/31420.html, null] | Orleans    | Shore Fishing - Footpath                  | DEC                                              | [http://www.dec.ny.gov/docs/fish_marine_pdf/pfroakorchrv.pdf, null]  | -78.239453738 | 43.337392769 | 
```