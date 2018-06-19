# IEPA State Compost Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iepa-state-compost-facilities-dedd4) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/rmd3-p6jt) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rmd3-p6jt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/rmd3-p6jt/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | rmd3-p6jt |
| Name | IEPA State Compost Facilities |
| Attribution | IEPA |
| Category | Finance & Administration |
| Created | 2011-12-15T19:49:27Z |
| Publication Date | 2014-10-09T21:11:49Z |

## Description

Data last updated December 2011

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| No       |                | id            | ID            | text      | text        |
| Yes      | series tag     | county        | County        | text      | text        |
| Yes      | series tag     | company_name_ | Company Name: | text      | text        |
| Yes      | series tag     | phone_1       | Phone:        | text      | text        |
| Yes      | series tag     | municipality_ | Municipality: | text      | text        |
| Yes      | series tag     | company_state | Company State | text      | text        |
| Yes      | series tag     | operator      | Operator      | text      | text        |
| No       |                | address       | Address       | text      | text        |
| Yes      | series tag     | city          | City          | text      | text        |
| Yes      | series tag     | state         | State         | text      | text        |
| Yes      | series tag     | zip           | Zip           | text      | text        |
| Yes      | series tag     | phone_2       | Phone         | text      | text        |
| Yes      | numeric metric | totalwaste_   | TotalWaste    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,address
```

## Data Commands

```ls
series e:rmd3-p6jt d:2011-12-15T11:49:29.000Z t:company_state=Illinois t:zip=61350 t:phone_2=N/A t:phone_1=N/A t:county=LaSalle t:company_name_="States Land Improvement LSW Processing and Composting Facility (Active)" t:state=IL t:municipality_=Ottawa t:operator="States Land Improvement Corp." t:city=Ottawa m:totalwaste_=8500

series e:rmd3-p6jt d:2011-12-15T11:49:29.000Z t:company_state=Illinois t:zip=62948 t:phone_2=618-942-6104 t:phone_1=N/A t:county=Williamson t:company_name_="Ashalex Recycling Compost Site (Active)" t:state=IL t:municipality_=Marion t:operator="McVicker Excavating Inc." t:city=Herrin m:totalwaste_=0

series e:rmd3-p6jt d:2011-12-15T11:49:50.000Z t:company_state=Illinois t:zip=60429 t:phone_2=708-335-9600 t:phone_1=708-335-9620 t:county=Cook t:company_name_="Hazel Crest Composting (Active, now closed)" t:state=IL t:municipality_="Hazel Crest" t:operator="Village of Hazel Crest" t:city="Hazel Crest" m:totalwaste_=2100
```

## Meta Commands

```ls
metric m:totalwaste_ p:integer l:TotalWaste t:dataTypeName=number

entity e:rmd3-p6jt l:"IEPA State Compost Facilities" t:attribution=IEPA t:url=https://datacatalog.cookcountyil.gov/api/views/rmd3-p6jt

property e:rmd3-p6jt t:meta.view v:id=rmd3-p6jt v:category="Finance & Administration" v:averageRating=0 v:name="IEPA State Compost Facilities" v:attribution=IEPA

property e:rmd3-p6jt t:meta.view.license v:name="Public Domain"

property e:rmd3-p6jt t:meta.view.owner v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"

property e:rmd3-p6jt t:meta.view.tableauthor v:id=wyzd-r23j v:profileImageUrlMedium=/api/users/wyzd-r23j/profile_images/THUMB v:profileImageUrlLarge=/api/users/wyzd-r23j/profile_images/LARGE v:screenName="Cook County Government" v:profileImageUrlSmall=/api/users/wyzd-r23j/profile_images/TINY v:displayName="Cook County Government"
```

## Top Records

```ls
| :updated_at | id         | county      | company_name_                                                           | phone_1      | municipality_ | company_state | operator                                     | address                                | city        | state | zip        | phone_2      | totalwaste_ | 
| =========== | ========== | =========== | ======================================================================= | ============ | ============= | ============= | ============================================ | ====================================== | =========== | ===== | ========== | ============ | =========== | 
| 1323949769  | 0990800040 | LaSalle     | States Land Improvement LSW Processing and Composting Facility (Active) | N/A          | Ottawa        | Illinois      | States Land Improvement Corp.                | P.O. Box 682                           | Ottawa      | IL    | 61350      | N/A          | 8500        | 
| 1323949769  | 1990555107 | Williamson  | Ashalex Recycling Compost Site (Active)                                 | N/A          | Marion        | Illinois      | McVicker Excavating Inc.                     | 816 E. Clark Trail                     | Herrin      | IL    | 62948      | 618-942-6104 | 0           | 
| 1323949790  | 0311170002 | Cook        | Hazel Crest Composting (Active, now closed)                             | 708-335-9620 | Hazel Crest   | Illinois      | Village of Hazel Crest                       | 3000 W. 170th Place                    | Hazel Crest | IL    | 60429      | 708-335-9600 | 2100        | 
| 1323949790  | 0198270001 | Champaign   | Urbana Municipal Landscape Recycling Center (Active)                    | 217-384-2342 | Urbana        | Illinois      | City of Urbana, Public Works Dept.           | 706 S. Glover Ave.                     | Urbana      | IL    | 61802-4427 | 217-384-2393 | 2892        | 
| 1323949790  | 0270405005 | Clinton     | Clinton County Compost Inc. (Active)                                    | 877-504-9197 | Centralia     | Illinois      | Clinton County Compost Inc.                  | 22100 State Route 161                  | Centralia   | IL    | 62801      | 618-495-9028 | 7200        | 
| 1323949790  | 0316000034 | Cook        | Harbor View Compost Facility (Active)                                   | N/A          | Chicago       | Illinois      | Land and Lakes Yard Waste Reclamation Inc.** | 123 N. Northwest Highway, P.O. Box 778 | Park Ridge  | IL    | 60068-0778 | 847-825-5000 | 384         | 
| 1323949793  | 0971505058 | Lake        | Countryside Landscape Composting (New)                                  | N/A          | Round Lake    | Illinois      | RRW LLC                                      | 29947 North Rand Road                  | Wauconda    | IL    | 60084      | 847/526-1909 | 0           | 
| 1323949793  | 1970755021 | Will        | Christiansen Farms (Active)                                             | 708-258-6123 | Peotone       | Illinois      | Christiansen Farms                           | 12151 W. Wilmington Road               | Peotone     | IL    | 60468      | 708-258-6123 | 18212       | 
| 1323949793  | 0316000005 | Cook        | Land & Lakes #1 & #2 Compost Facility (Active)                          | 708-720-5100 | Chicago       | Illinois      | Land and Lakes Yard Waste Reclamation Inc.** | 123 N. Northwest Highway, P.O. Box 778 | Park Ridge  | IL    | 60068-0778 | 847-825-5000 | 62453       | 
| 1323949793  | 1618100014 | Rock Island | Upper Rock Island County Landfill Compost Site #2 (Active)              | 309-496-2396 | East Moline   | Illinois      | Upper Rock Island County Landfill Inc.**     | 17201 20th Ave. North                  | East Moline | IL    | 61244      | 309-496-2396 | 7550        | 
```