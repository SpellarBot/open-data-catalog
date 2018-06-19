# SDOT Street Ends

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sdot-street-ends) |
| Metadata | [Link](https://data.seattle.gov/api/views/ef3j-zuiv) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/ef3j-zuiv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/ef3j-zuiv/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | ef3j-zuiv |
| Name | SDOT Street Ends |
| Tags | sdot asset status and condition report, assets |
| Created | 2017-01-13T21:17:20Z |
| Publication Date | 2017-01-25T22:14:15Z |

## Description

The data includes 149 shoreline street ends located within the Seattle City Limits.  The information includes the nearest cross street, common place name, right-of-way width, status of the street end (Vacated, Public Access, In Water Use, Industrial and Residential).

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | objectid      | OBJECTID      | text      | number      |
| Yes      | numeric metric | perimeter     | PERIMETER     | number    | number      |
| Yes      | numeric metric | stend_        | STEND_        | number    | number      |
| Yes      | series tag     | stend_id      | STEND_ID      | text      | number      |
| Yes      | numeric metric | symbol        | SYMBOL        | number    | number      |
| Yes      | numeric metric | no_           | NO_           | number    | number      |
| Yes      | series tag     | access_cod    | ACCESS_COD    | text      | text        |
| Yes      | series tag     | vaca          | VACA          | text      | text        |
| Yes      | series tag     | text_place    | TEXT_PLACE    | text      | text        |
| Yes      | numeric metric | r_w           | R_W           | number    | number      |
| Yes      | series tag     | status        | STATUS        | text      | text        |
| Yes      | series tag     | cpn_placename | CPN_PLACENAME | text      | text        |
| Yes      | series tag     | cpn_type      | CPN_TYPE      | text      | text        |
| Yes      | series tag     | cpn_cat       | CPN_CAT       | text      | text        |
| Yes      | numeric metric | source        | SOURCE        | number    | number      |
| Yes      | series tag     | st_no         | ST_NO         | text      | number      |
| Yes      | series tag     | st_pre        | ST_PRE        | text      | text        |
| Yes      | series tag     | st_nm         | ST_NM         | text      | text        |
| Yes      | series tag     | st_type       | ST_TYPE       | text      | text        |
| Yes      | series tag     | st_suf        | ST_SUF        | text      | text        |
| Yes      | series tag     | st_type_2     | ST_TYPE_2     | text      | text        |
| Yes      | series tag     | imageurl      | IMAGEURL      | text      | text        |
| Yes      | numeric metric | imagefile     | IMAGEFILE     | number    | text        |
| Yes      | series tag     | hyperlink     | HYPERLINK     | text      | text        |
| Yes      | series tag     | imageurl1     | IMAGEURL1     | text      | text        |
| Yes      | series tag     | imagefile1    | IMAGEFILE1    | text      | text        |
| Yes      | series tag     | hyperlink1    | HYPERLINK1    | text      | text        |
| Yes      | series tag     | imageurl2     | IMAGEURL2     | text      | text        |
| Yes      | series tag     | imagefile2    | IMAGEFILE2    | text      | text        |
| Yes      | series tag     | hyperlink2    | HYPERLINK2    | text      | text        |
| Yes      | series tag     | directions    | DIRECTIONS    | text      | text        |
| Yes      | series tag     | stewardship   | STEWARDSHIP   | text      | text        |
| Yes      | series tag     | prstatus      | PRSTATUS      | text      | text        |
| Yes      | series tag     | projectyr     | PROJECTYR     | text      | text        |
| Yes      | series tag     | mstatus       | MSTATUS       | text      | text        |
| Yes      | series tag     | procat        | PROCAT        | text      | text        |
| Yes      | series tag     | access_code   | ACCESS_CODE   | text      | text        |
| Yes      | series tag     | name          | NAME          | text      | text        |
| Yes      | series tag     | site_status   | SITE_STATUS   | text      | text        |
| Yes      | series tag     | description   | DESCRIPTION   | text      | text        |
| Yes      | numeric metric | area          | AREA          | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ef3j-zuiv d:2017-01-13T21:17:20.000Z t:stend_id=91 t:site_status="Worth a visit" t:access_code=A t:cpn_type=ROW t:status="PUBLIC ACCESS" t:cpn_placename="CREMONA ST END" t:description="Contiguous with the green space by the ship canal trail, benches afford a view of the Ship Canal." t:hyperlink=http://www.seattle.gov/transportation/images/stuse/shoreline/94.jpg t:name="Cremona St" t:st_type=ST t:cpn_cat=STE t:text_place=CL t:access_cod=A t:objectid=1 t:imageurl=http://www.seattle.gov/transportation/images/stuse/shoreline/ t:st_nm=CREMONA m:r_w=66 m:symbol=107 m:source=17 m:perimeter=0 m:imagefile=94 m:stend_=143 m:no_=94

series e:ef3j-zuiv d:2017-01-13T21:17:20.000Z t:stend_id=18 t:access_code=A t:cpn_type=ROW t:status="PUBLIC ACCESS" t:cpn_placename="SW SPOKANE ST D END" t:st_pre=SW t:hyperlink=http://www.seattle.gov/transportation/images/stuse/shoreline/19.jpg t:name="SW Spokane St E" t:st_type=ST t:cpn_cat=STE t:text_place=UC t:access_cod=A t:objectid=2 t:imageurl=http://www.seattle.gov/transportation/images/stuse/shoreline/ t:st_nm=SPOKANE m:r_w=0 m:symbol=107 m:source=17 m:perimeter=0 m:imagefile=19 m:stend_=70 m:no_=19

series e:ef3j-zuiv d:2017-01-13T21:17:20.000Z t:stend_id=38 t:site_status="Worth a visit" t:access_code=A t:cpn_type=ROW t:status="PUBLIC ACCESS" t:cpn_placename="75TH AVE S END" t:st_suf=S t:description="There's no water access at this site, but through the Parks Levy, the site was just improved with a bench for a view of the water." t:hyperlink=http://www.seattle.gov/transportation/images/stuse/shoreline/39.jpg t:name="75th Ave S" t:st_type=AVE t:cpn_cat=STE t:text_place=CL t:access_cod=A t:objectid=3 t:imageurl=http://www.seattle.gov/transportation/images/stuse/shoreline/ t:st_nm=75TH m:r_w=50 m:symbol=107 m:source=17 m:perimeter=0 m:imagefile=39 m:stend_=89 m:no_=39
```

## Meta Commands

```ls
metric m:perimeter p:integer l:PERIMETER d:PERIMETER t:dataTypeName=number

metric m:stend_ p:integer l:STEND_ d:STEND_ t:dataTypeName=number

metric m:symbol p:integer l:SYMBOL d:SYMBOL t:dataTypeName=number

metric m:no_ p:integer l:NO_ d:NO_ t:dataTypeName=number

metric m:r_w p:integer l:R_W d:R_W t:dataTypeName=number

metric m:source p:integer l:SOURCE d:SOURCE t:dataTypeName=number

metric m:imagefile p:integer l:IMAGEFILE d:IMAGEFILE t:dataTypeName=number

metric m:area p:long l:AREA d:AREA t:dataTypeName=number

entity e:ef3j-zuiv l:"SDOT Street Ends" t:url=https://data.seattle.gov/api/views/ef3j-zuiv

property e:ef3j-zuiv t:meta.view v:id=ef3j-zuiv v:averageRating=0 v:name="SDOT Street Ends"

property e:ef3j-zuiv t:meta.view.owner v:id=geh9-fb2x v:screenName="SDOT GIS" v:displayName="SDOT GIS"

property e:ef3j-zuiv t:meta.view.tableauthor v:id=geh9-fb2x v:screenName="SDOT GIS" v:roleName=publisher v:displayName="SDOT GIS"
```

## Top Records

```ls
| :updated_at | objectid | perimeter | stend_ | stend_id | symbol | no_ | access_cod | vaca | text_place | r_w | status        | cpn_placename       | cpn_type | cpn_cat | source | st_no | st_pre | st_nm   | st_type | st_suf | st_type_2 | imageurl                                                      | imagefile | hyperlink                                                            | imageurl1 | imagefile1 | hyperlink1 | imageurl2 | imagefile2 | hyperlink2 | directions | stewardship | prstatus | projectyr | mstatus | procat | access_code | name            | site_status                | description                                                                                                                        | area | 
| =========== | ======== | ========= | ====== | ======== | ====== | === | ========== | ==== | ========== | === | ============= | =================== | ======== | ======= | ====== | ===== | ====== | ======= | ======= | ====== | ========= | ============================================================= | ========= | ==================================================================== | ========= | ========== | ========== | ========= | ========== | ========== | ========== | =========== | ======== | ========= | ======= | ====== | =========== | =============== | ========================== | ================================================================================================================================== | ==== | 
| 0           | 1        | 0         | 143    | 91       | 107    | 94  | A          |      | CL         | 66  | PUBLIC ACCESS | CREMONA ST END      | ROW      | STE     | 17     |       |        | CREMONA | ST      |        |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 94        | http://www.seattle.gov/transportation/images/stuse/shoreline/94.jpg  |           |            |            |           |            |            |            |             |          |           |         |        | A           | Cremona St      | Worth a visit              | Contiguous with the green space by the ship canal trail, benches afford a view of the Ship Canal.                                  |      | 
| 0           | 2        | 0         | 70     | 18       | 107    | 19  | A          |      | UC         | 0   | PUBLIC ACCESS | SW SPOKANE ST D END | ROW      | STE     | 17     |       | SW     | SPOKANE | ST      |        |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 19        | http://www.seattle.gov/transportation/images/stuse/shoreline/19.jpg  |           |            |            |           |            |            |            |             |          |           |         |        | A           | SW Spokane St E |                            |                                                                                                                                    |      | 
| 0           | 3        | 0         | 89     | 38       | 107    | 39  | A          |      | CL         | 50  | PUBLIC ACCESS | 75TH AVE S END      | ROW      | STE     | 17     |       |        | 75TH    | AVE     | S      |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 39        | http://www.seattle.gov/transportation/images/stuse/shoreline/39.jpg  |           |            |            |           |            |            |            |             |          |           |         |        | A           | 75th Ave S      | Worth a visit              | There's no water access at this site, but through the Parks Levy, the site was just improved with a bench for a view of the water. |      | 
| 0           | 4        | 0         | 50     | 71       | 107    | 73  | C          |      | CL         | 75  | IN WATER USE  | E ALLISON ST E END  | ROW      | STE     | 17     |       | E      | ALLISON | ST      |        |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 73        | http://www.seattle.gov/transportation/images/stuse/shoreline/73.jpg  |           |            |            |           |            |            |            |             |          |           |         |        | C           | E Allison St    | Not yet ready for visitors |                                                                                                                                    |      | 
| 0           | 5        | 0         | 39     | 123      | 107    | 130 | B          |      | CR         | 30  | RESIDENTIAL   | NE 31ST ST W END    | ROW      | STE     | 17     |       | NE     | 31ST    | ST      |        |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 130       | http://www.seattle.gov/transportation/images/stuse/shoreline/130.jpg |           |            |            |           |            |            |            |             |          |           |         |        | B           | NE 31st St W    | Worth a visit              | In need of improvement, but provides access to the shore behind a wall of vegetation                                               |      | 
| 0           | 6        | 0         | 132    | 85       | 107    | 87  | A          | V    | CL         | 60  | VACATED       | GALER ST END        | ROW      | STE     | 17     |       |        | GALER   | ST      |        |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 87        | http://www.seattle.gov/transportation/images/stuse/shoreline/87.jpg  |           |            |            |           |            |            |            |             |          |           |         |        | A           | Galer St        | Worth a visit              | A vegetated slope to the water, in need of renewed landscaping and seating.                                                        |      | 
| 0           | 7        | 0         | 61     | 10       | 107    | 10  | B          |      | CL         | 100 | PUBLIC ACCESS | SW BRONSON WY END   | ROW      | STE     | 17     |       | SW     | BRONSON | WY      |        |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 10        | http://www.seattle.gov/transportation/images/stuse/shoreline/10.jpg  |           |            |            |           |            |            |            |             |          |           |         |        | B           | SW Bronson Way  | Worth a visit              | Ample benches provide an opportunity to relax with spectacular views of the city.                                                  |      | 
| 0           | 8        | 0         | 54     | 3        | 107    | 3   | A          |      | CR         | 100 | PUBLIC ACCESS | SW BARTON ST END    | ROW      | STE     | 17     |       | SW     | BARTON  | ST      |        |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 3         | http://www.seattle.gov/transportation/images/stuse/shoreline/3.jpg   |           |            |            |           |            |            |            |             |          |           |         |        | A           | SW Barton St    | Worth a visit              | Tucked in next to the Fauntleroy ferry terminal, this is a great restored site with access to a sandy shore.                       |      | 
| 0           | 9        | 0         | 20     | 134      | 107    | 139 | B          |      | CR         | 80  | INDUSTRIAL    | NW 40TH ST END      | ROW      | STE     | 17     |       | NW     | 40TH    | ST      |        |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 139       | http://www.seattle.gov/transportation/images/stuse/shoreline/139.jpg |           |            |            |           |            |            |            |             |          |           |         |        | B           | NW 40th St      | Not yet ready for visitors |                                                                                                                                    |      | 
| 0           | 10       | 0         | 64     | 11       | 107    | 12  | C          |      | CL         | 100 | INDUSTRIAL    | CHELAN AVE SW E END | ROW      | STE     | 17     |       |        | CHELAN  | AVE     | SW     |           | http://www.seattle.gov/transportation/images/stuse/shoreline/ | 12        | http://www.seattle.gov/transportation/images/stuse/shoreline/12.jpg  |           |            |            |           |            |            |            |             |          |           |         |        | C           | Chelan Ave SW E | Not yet ready for visitors |                                                                                                                                    |      | 
```