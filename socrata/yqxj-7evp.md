# City of Austin Public Art Collection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-austin-public-art-collection) |
| Metadata | [Link](https://data.austintexas.gov/api/views/yqxj-7evp) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/yqxj-7evp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/yqxj-7evp/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | yqxj-7evp |
| Name | City of Austin Public Art Collection |
| Attribution | City of Austin |
| Category | Fun |
| Tags | art, culture, public, collection, aipp |
| Created | 2012-08-22T21:18:27Z |
| Publication Date | 2012-08-23T12:28:07Z |

## Description

This file contains the names and address of artworks commissioned through the Austin Art in Public Places Program

## Columns

```ls
| Included | Schema Type | Field Name                  | Name                        | Data Type | Render Type |
| ======== | =========== | =========================== | =========================== | ========= | =========== |
| No       | time        | :updated_at                 | updated_at                  | meta_data | meta_data   |
| Yes      | series tag  | artist_full_name            | Artist Full Name            | text      | text        |
| Yes      | series tag  | art_title                   | Art Title                   | text      | text        |
| Yes      | series tag  | art_location_name           | Art Location Name           | text      | text        |
| Yes      | series tag  | art_location_street_address | Art Location Street Address | text      | text        |
| Yes      | series tag  | art_location_city           | Art Location City           | text      | text        |
| Yes      | series tag  | art_location_state          | Art Location State          | text      | text        |
| Yes      | series tag  | art_location_zip            | Art Location Zip            | text      | text        |
| Yes      | series tag  | images                      | Images                      | text      | text        |
| Yes      | series tag  | web_detail_page             | Web Detail Page             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:yqxj-7evp d:2012-08-22T14:18:52.000Z t:art_location_city=Austin t:art_location_name="Town Lake Hike and Bike Trail" t:art_location_zip=78701 t:artist_full_name="Robert Phillips" t:web_detail_page="http://www.austintexas.gov/aipp/aipp_detail.cfm?art=107" t:images=http://assets.austintexas.gov/aipp/images/pic1993_007.jpg t:art_location_street_address="Possum Point - North Bank at Shoal Creek;" t:art_title="Opossum Temple and Voodoo Pew" t:art_location_state=TX m:row_number.yqxj-7evp=1

series e:yqxj-7evp d:2012-08-22T14:18:52.000Z t:art_location_city=Austin t:art_location_name="Learning & Research Center" t:art_location_zip=78719 t:artist_full_name="Belinda Casey" t:web_detail_page="http://www.austintexas.gov/aipp/aipp_detail.cfm?art=180" t:images=http://assets.austintexas.gov/aipp/images/pic1997_012.jpg t:art_location_street_address="2800  Star of Texas Rd.;" t:art_title=X t:art_location_state=TX m:row_number.yqxj-7evp=2

series e:yqxj-7evp d:2012-08-22T14:18:52.000Z t:art_location_city=Austin t:art_location_name="Todd Lane Service Center" t:artist_full_name="Doug Brown" t:web_detail_page="http://www.austintexas.gov/aipp/aipp_detail.cfm?art=187" t:images=http://assets.austintexas.gov/aipp/images/unsung_brown.jpg;http://assets.austintexas.gov/aipp/images/pic2001_001_2.jpg;http://assets.austintexas.gov/aipp/images/pic2001_001_3.jpg; t:art_location_street_address="4108 Todd Lane;" t:art_title="The Unsung" t:art_location_state=TX m:row_number.yqxj-7evp=3
```

## Meta Commands

```ls
metric m:row_number.yqxj-7evp p:long l:"Row Number"

entity e:yqxj-7evp l:"City of Austin Public Art Collection" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/yqxj-7evp

property e:yqxj-7evp t:meta.view v:id=yqxj-7evp v:category=Fun v:averageRating=0 v:name="City of Austin Public Art Collection" v:attribution="City of Austin"

property e:yqxj-7evp t:meta.view.owner v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:displayName="Melissa Alvarado"

property e:yqxj-7evp t:meta.view.tableauthor v:id=kzrv-d9p3 v:screenName="Melissa Alvarado" v:roleName=editor v:displayName="Melissa Alvarado"
```

## Top Records

```ls
| :updated_at | artist_full_name  | art_title                         | art_location_name              | art_location_street_address               | art_location_city | art_location_state | art_location_zip | images                                                                                                                                                                                  | web_detail_page                                         | 
| =========== | ================= | ================================= | ============================== | ========================================= | ================= | ================== | ================ | ======================================================================================================================================================================================= | ======================================================= | 
| 1345645132  | Robert Phillips   | Opossum Temple and Voodoo Pew     | Town Lake Hike and Bike Trail  | Possum Point - North Bank at Shoal Creek; | Austin            | TX                 | 78701            | http://assets.austintexas.gov/aipp/images/pic1993_007.jpg                                                                                                                               | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=107 | 
| 1345645132  | Belinda Casey     | X                                 | Learning & Research Center     | 2800 Star of Texas Rd.;                   | Austin            | TX                 | 78719            | http://assets.austintexas.gov/aipp/images/pic1997_012.jpg                                                                                                                               | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=180 | 
| 1345645132  | Doug Brown        | The Unsung                        | Todd Lane Service Center       | 4108 Todd Lane;                           | Austin            | TX                 |                  | http://assets.austintexas.gov/aipp/images/unsung_brown.jpg;http://assets.austintexas.gov/aipp/images/pic2001_001_2.jpg;http://assets.austintexas.gov/aipp/images/pic2001_001_3.jpg;     | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=187 | 
| 1345645132  | Lars A.Stanley    | Zilker Gardens Main Entry Gate    | Zilker Botanical Garden        | 2220 Barton Springs Rd.;                  | Austin            | TX                 | 78746            | http://assets.austintexas.gov/aipp/images/pic1995_002_1.jpg;http://assets.austintexas.gov/aipp/images/pic1995_002_2.jpg;http://assets.austintexas.gov/aipp/images/pic1995_002_3.jpg;    | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=116 | 
| 1345645132  | Beverly Penn      | Community Core Sample Project     | St. John's Multipurpose Center | Corner of Blessing and Wheatly Ave.;      | Austin            | TX                 |                  | http://assets.austintexas.gov/aipp/images/pic2003_001_1b.jpg;http://assets.austintexas.gov/aipp/images/pic2003_001_2b.jpg;http://assets.austintexas.gov/aipp/images/pic2003_001_3b.jpg; | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=192 | 
| 1345645132  | Bill Davenport    | Giant Mushroom Forest             | Auditorium Shores              | ;                                         | Austin            | Texas              | 78701            | http://assets.austintexas.gov/aipp/images/pic001_2009_1.jpg;http://assets.austintexas.gov/aipp/images/pic001_2009_2.jpg;http://assets.austintexas.gov/aipp/images/pic001_2009_3.jpg;    | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=538 | 
| 1345645132  | T. Paul Hernandez | Sanctuary of the Tribal Alligator | Hill Elementary School Park    | 8601 Tallwood Dr.;                        | Austin            | TX                 | 78759            | http://assets.austintexas.gov/aipp/images/pic1988_005_1.jpg;http://assets.austintexas.gov/aipp/images/pic1988_005_2.jpg;http://assets.austintexas.gov/aipp/images/pic1988_005_3.jpg;    | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=94  | 
| 1345645132  | Douglas Jaques    | Vision                            | City Municipal Building        | 124 West Eighth St.; 3rd Floor;           | Austin            | TX                 | 78701            | http://assets.austintexas.gov/aipp/images/pic1994_009.jpg                                                                                                                               | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=170 | 
| 1345645132  | Steve Wiman       | Community Core Sample Project     | St. John's Multipurpose Center | Corner of Blessing and Wheatly Ave.;      | Austin            | TX                 |                  | http://assets.austintexas.gov/aipp/images/pic2003_001_1b.jpg;http://assets.austintexas.gov/aipp/images/pic2003_001_2b.jpg;http://assets.austintexas.gov/aipp/images/pic2003_001_3b.jpg; | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=192 | 
| 1345645132  | W. Gary Smith     | Karst Circle                      | Circle C Fire/EMS Station      | 11401 Escarpment Blvd.;                   | Austin            | TX                 | 78749            | http://assets.austintexas.gov/aipp/images/pic2004_007_1.jpg                                                                                                                             | http://www.austintexas.gov/aipp/aipp_detail.cfm?art=502 | 
```