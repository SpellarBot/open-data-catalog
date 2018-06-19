# Microsite-ssmma

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/microsite-ssmma-06b91) |
| Metadata | [Link](https://data.illinois.gov/api/views/fhzt-n87t) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/fhzt-n87t/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/fhzt-n87t/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | fhzt-n87t |
| Name | Microsite-ssmma |
| Created | 2013-01-28T21:19:59Z |
| Publication Date | 2013-02-21T22:34:53Z |

## Description

Control file for the SSMMA Microsite

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | featured_stat        | featured stat        | text      | text        |
| Yes      | series tag  | featured_description | featured description | text      | text        |
| Yes      | series tag  | featured_title       | featured title       | text      | text        |
| Yes      | series tag  | featured_agency      | featured agency      | text      | text        |
| Yes      | series tag  | agency_icon          | agency icon          | photo     | photo       |
| Yes      | series tag  | featured_text        | featured text        | text      | text        |
| Yes      | series tag  | featured_thumbnail   | featured thumbnail   | photo     | photo       |
| Yes      | series tag  | featured_link        | featured link        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fhzt-n87t d:2013-02-21T13:57:14.000Z t:featured_description="Miles of existing and proposed regional and local multi-use trails" t:featured_agency="South Suburban Mayors and Managers Association" t:featured_text="As a critically important infrastructure asset, the Chicago Southland?s expansive network of multi-use trail yields high returns in public health, stimulates positive economic investment, and connects communities to the natural environment throughout the region." t:featured_stat=1,848 t:featured_title="Examine the ever-expanding network of multi-use trails which is planned to double in the Chicago Southland region" t:featured_link=4n29-iu8g t:featured_thumbnail=bp6yA7cfhGxd8ZfjdLIfVPRN5wX-TOH1ge9IR2Qg9CI t:agency_icon=ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek m:row_number.fhzt-n87t=1

series e:fhzt-n87t d:2013-02-21T14:01:02.000Z t:featured_description="Available buildings and/or land in the Chicago Southland region" t:featured_agency="South Suburban Mayors and Managers Association" t:featured_text="As an invaluable tool among real estate professionals and property developers, the Location One Information System (LOIS) provides real-time, detailed geographic and economic data on available buildings and/or land. This dataset is further populated with SSMMA?s aggregation of available buildings and/or land which in turn provides a more expansive list of development opportunities in the Chicago Southland region." t:featured_stat=1,178 t:featured_title="Explore the ample investment opportunities across the Chicago Southland region" t:featured_link=4q8x-gsxz t:featured_thumbnail=hB2fikLoj3Lz4DMIhVpRogcXs8Wc8VlN2YTw57D47Wg t:agency_icon=ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek m:row_number.fhzt-n87t=2

series e:fhzt-n87t d:2013-02-21T14:01:27.000Z t:featured_description="Parcels zoned for residential within half-mile distance from existing and proposed Metra transit stations" t:featured_agency="South Suburban Mayors and Managers Association" t:featured_text="As part of the Chicago Southland Transit Corridor project in 2011, SSMMA has classified zoning at the parcel level of parcels found within a half-mile radius around potential transit-oriented development areas in the Chicago Southland region." t:featured_stat=67% t:featured_title="Scout the transit-oriented development opportunities among the 36 existing and 9 proposed Metra train stations in the Chicago Southland region" t:featured_link=jtrb-dted t:featured_thumbnail=iLJ6eUh1DowxfKLDQPP6FwB8wbPrV3bH4XWRd4A0rJg t:agency_icon=ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek m:row_number.fhzt-n87t=3
```

## Meta Commands

```ls
metric m:row_number.fhzt-n87t p:long l:"Row Number"

entity e:fhzt-n87t l:Microsite-ssmma t:url=https://data.illinois.gov/api/views/fhzt-n87t

property e:fhzt-n87t t:meta.view v:id=fhzt-n87t v:averageRating=0 v:name=Microsite-ssmma

property e:fhzt-n87t t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:fhzt-n87t t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | featured_stat | featured_description                                                                                      | featured_title                                                                                                                                 | featured_agency                                | agency_icon                                 | featured_text                                                                                                                                                                                                                                                                                                                                                                                                                    | featured_thumbnail                          | featured_link | 
| =========== | ============= | ========================================================================================================= | ============================================================================================================================================== | ============================================== | =========================================== | ================================================================================================================================================================================================================================================================================================================================================================================================================================ | =========================================== | ============= | 
| 1361455034  | 1,848         | Miles of existing and proposed regional and local multi-use trails                                        | Examine the ever-expanding network of multi-use trails which is planned to double in the Chicago Southland region                              | South Suburban Mayors and Managers Association | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | As a critically important infrastructure asset, the Chicago Southland?s expansive network of multi-use trail yields high returns in public health, stimulates positive economic investment, and connects communities to the natural environment throughout the region.                                                                                                                                                           | bp6yA7cfhGxd8ZfjdLIfVPRN5wX-TOH1ge9IR2Qg9CI | 4n29-iu8g     | 
| 1361455262  | 1,178         | Available buildings and/or land in the Chicago Southland region                                           | Explore the ample investment opportunities across the Chicago Southland region                                                                 | South Suburban Mayors and Managers Association | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | As an invaluable tool among real estate professionals and property developers, the Location One Information System (LOIS) provides real-time, detailed geographic and economic data on available buildings and/or land. This dataset is further populated with SSMMA?s aggregation of available buildings and/or land which in turn provides a more expansive list of development opportunities in the Chicago Southland region. | hB2fikLoj3Lz4DMIhVpRogcXs8Wc8VlN2YTw57D47Wg | 4q8x-gsxz     | 
| 1361455287  | 67%           | Parcels zoned for residential within half-mile distance from existing and proposed Metra transit stations | Scout the transit-oriented development opportunities among the 36 existing and 9 proposed Metra train stations in the Chicago Southland region | South Suburban Mayors and Managers Association | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | As part of the Chicago Southland Transit Corridor project in 2011, SSMMA has classified zoning at the parcel level of parcels found within a half-mile radius around potential transit-oriented development areas in the Chicago Southland region.                                                                                                                                                                               | iLJ6eUh1DowxfKLDQPP6FwB8wbPrV3bH4XWRd4A0rJg | jtrb-dted     | 
| 1361457286  | 50,238        | Total acres of natural areas in the Chicago Southland region                                              | View the environmental assets and green infrastructure existing within the Chicago Southland region                                            | South Suburban Mayors and Managers Association | ukqSqkxhZaIFdEsBb1IMOW8Q_BoQecuZ_aUlcJBiWek | City and County owned and/or managed natural areas in the Chicago Southland region will gain in significance as federal initiatives such as the Governor Quinn?s Millennium Reserve project aims to restore and/or enhance natural resource linkages and connect local citizens to the natural assets throughout the region.                                                                                                     | yuEY5PX7o9RUX25lnySjcPI46gSI6pL1tYgWkUrA3vc | tkef-fgt6     | 
```