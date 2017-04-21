# Surface Mounted Facility Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/surface-mounted-facility-permits-53d1f) |
| Metadata | [Link](https://data.sfgov.org/api/views/xu5w-5kgd) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/xu5w-5kgd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/xu5w-5kgd/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | xu5w-5kgd |
| Name | Surface Mounted Facility Permits |
| Attribution | San Francisco Department of Public Works |
| Category | City Infrastructure |
| Tags | surface, mounted, facility, permits, surface mounted facility, surface mounted, smf |
| Created | 2013-04-04T18:42:22Z |
| Publication Date | 2016-01-29T23:17:27Z |

## Description

Surface Mounted Facility Permits in the public right of way both approved and requested

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | permit_number               | Permit_Number               | text      | text        |
| Yes      | series tag  | applicant                   | Applicant                   | text      | text        |
| Yes      | series tag  | status                      | status                      | text      | text        |
| Yes      | series tag  | sub_status                  | Sub-Status                  | text      | text        |
| Yes      | series tag  | location                    | LocationDescription         | text      | text        |
| Yes      | series tag  | associatedexcavationpermits | AssociatedExcavationPermits | text      | text        |
| No       |             | x                           | X                           | number    | number      |
| No       |             | y                           | Y                           | number    | number      |
| No       |             | latitude                    | Latitude                    | number    | number      |
| No       |             | longitude                   | Longitude                   | number    | number      |
| Yes      | series tag  | bosdistrict                 | BOSDistrict                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = x,y,latitude,longitude
```

## Data Commands

```ls
series e:xu5w-5kgd d:2016-12-07T06:52:25.000Z t:permit_number=13SMF-0377 t:location="194 Mangels Ave" t:status=APPROVED t:applicant="SBC - Pacific Bell Engineering" t:associatedexcavationpermits=13SMF-0378 t:bosdistrict=08 m:row_number.xu5w-5kgd=1

series e:xu5w-5kgd d:2016-12-07T06:52:25.000Z t:permit_number=13SMF-0205 t:location="SPEAR ST: FOLSOM ST to HARRISON ST (300 - 399)" t:status=APPROVED t:applicant="San Francisco Municipal Transportation Agency" t:bosdistrict=06 m:row_number.xu5w-5kgd=2

series e:xu5w-5kgd d:2016-12-07T06:52:25.000Z t:permit_number=15SMF-0050 t:location="4494 MISSION ST" t:status=APPROVED t:applicant="Pacific Gas & Electric" t:associatedexcavationpermits=16EXC-1627,16EXC-3228,16EXC-3288 t:bosdistrict=11 m:row_number.xu5w-5kgd=3
```

## Meta Commands

```ls
metric m:row_number.xu5w-5kgd p:long l:"Row Number"

entity e:xu5w-5kgd l:"Surface Mounted Facility Permits" t:attribution="San Francisco Department of Public Works" t:url=https://data.sfgov.org/api/views/xu5w-5kgd

property e:xu5w-5kgd t:meta.view v:id=xu5w-5kgd v:category="City Infrastructure" v:attributionLink="http://sfdpw.org/index.aspx?page=1597" v:averageRating=0 v:name="Surface Mounted Facility Permits" v:attribution="San Francisco Department of Public Works"

property e:xu5w-5kgd t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:xu5w-5kgd t:meta.view.owner v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:displayName="Public Works"

property e:xu5w-5kgd t:meta.view.tableauthor v:id=rcpp-nrjq v:profileImageUrlMedium=/api/users/rcpp-nrjq/profile_images/THUMB v:profileImageUrlLarge=/api/users/rcpp-nrjq/profile_images/LARGE v:screenName="Public Works" v:profileImageUrlSmall=/api/users/rcpp-nrjq/profile_images/TINY v:roleName=editor v:displayName="Public Works"
```

## Top Records

```ls
| :updated_at | permit_number | applicant                                          | status    | sub_status | location                                                                                                         | associatedexcavationpermits                                                                                   | x             | y             | latitude         | longitude         | bosdistrict | 
| =========== | ============= | ================================================== | ========= | ========== | ================================================================================================================ | ============================================================================================================= | ============= | ============= | ================ | ================= | =========== | 
| 1481093545  | 13SMF-0377    | SBC - Pacific Bell Engineering                     | APPROVED  |            | 194 Mangels Ave                                                                                                  | 13SMF-0378                                                                                                    | 6000148.36454 | 2095245.72826 | 37.7331535727494 | -122.441871407094 | 08          | 
| 1481093545  | 13SMF-0205    | San Francisco Municipal Transportation Agency      | APPROVED  |            | SPEAR ST: FOLSOM ST to HARRISON ST (300 - 399)                                                                   |                                                                                                               | 6015501.82184 | 2115435.69008 | 37.7894537789551 | -122.390199973179 | 06          | 
| 1481093545  | 15SMF-0050    | Pacific Gas & Electric                             | APPROVED  |            | 4494 MISSION ST                                                                                                  | 16EXC-1627,16EXC-3228,16EXC-3288                                                                              | 6002372.54621 | 2092543.38511 | 37.7258600402335 | -122.433988722088 | 11          | 
| 1481093545  | 13SMF-0283    | San Francisco Municipal Transportation Agency      | APPROVED  |            | Sansome St (west side) between Pacific Ave and Broadway St; near the intersection of Broadway St and Sansome St. | 13EXC-6668,13SMF-0287,13SMF-0277,13SMF-0282,13SMF-0286,13SMF-0281,13SMF-0284,14EXC-4863,13SMF-0278,13SMF-0288 | 6012116.7803  | 2118604.88931 | 37.7979673094935 | -122.40213481077  | 03          | 
| 1481093545  | 14SMF-0104    | Department of Public Works - Infrastructure Divisi | REQUESTED |            | SLOAT BLVD: 22ND AVE to 23RD AVE \ CRESTLAKE DR (601 - 699) -- SOUTH --                                          | 14SMF-0103                                                                                                    | 5989505.77596 | 2095954.10048 | 37.7344863978703 | -122.478717075442 | 07          | 
| 1481093545  | 13SMF-0268    | SBC - Pacific Bell Engineering                     | APPROVED  |            | 810 Clayton St                                                                                                   | 14EXC-1983,14EXC-2964                                                                                         | 5998664.44724 | 2107498.80609 | 37.7667128590069 | -122.447883538173 | 05          | 
| 1481093545  | 13SMF-0362    | SBC - Pacific Bell Engineering                     | APPROVED  |            | 1301 Hampshire St (company address) physical location on 25th St                                                 | 14EXC-4504,14EXC-2765,13SMF-0361                                                                              | 6010462.88449 | 2101656.51464 | 37.7513385540688 | -122.406662786756 | 09          | 
| 1481093545  | 11SMF-0096    | SBC - Pacific Bell Engineering                     | APPROVED  |            | 4201 Irving St                                                                                                   | 13EXC-1518,13EXC-0839                                                                                         | 5982739.47918 | 2106253.66252 | 37.7623709376219 | -122.50287220644  | 04          | 
| 1481093545  | 13SMF-0394    | SBC - Pacific Bell Engineering                     | APPROVED  |            | 1 Foote Ave                                                                                                      | 14EXC-2359                                                                                                    | 5999162.69968 | 2087788.74523 | 37.7126222035127 | -122.444743290714 | 11          | 
| 1481093545  | 12SMF-0024    | SBC - Pacific Bell Engineering                     | APPROVED  |            | 253 Blanken Ave                                                                                                  | 13EXC-3064                                                                                                    | 6012365.67628 | 2087148.53243 | 37.7116089182417 | -122.399064450615 | 10          | 
```