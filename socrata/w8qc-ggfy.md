# Golf Atx Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/golf-atx-locations) |
| Metadata | [Link](https://data.austintexas.gov/api/views/w8qc-ggfy) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/w8qc-ggfy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/w8qc-ggfy/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | w8qc-ggfy |
| Name | Golf Atx Locations |
| Category | Government |
| Created | 2015-10-06T17:56:24Z |
| Publication Date | 2017-03-22T18:56:00Z |

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | golf_course      | Golf Course      | text      | text        |
| Yes      | series tag  | zip_code         | Zip Code         | text      | text        |
| Yes      | series tag  | phone            | Phone            | text      | text        |
| Yes      | series tag  | tee_times        | Tee Times        | url       | url         |
| Yes      | series tag  | scorecard        | Scorecard        | url       | url         |
| Yes      | series tag  | facility_website | Facility Website | url       | url         |
| Yes      | series tag  | city             | City             | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w8qc-ggfy d:2015-10-07T08:36:36.000Z t:tee_times=http://www.greyrockgolfclub.com/booktt/ t:phone=512-288-4297 t:zip_code=78739 t:facility_website=http://www.greyrockgolfclub.com/ t:golf_course="Grey Rock Golf Club" m:row_number.w8qc-ggfy=1

series e:w8qc-ggfy d:2015-10-07T08:37:00.000Z t:tee_times="https://connect001.rectrac.com/wbwsc/txaustin_1.wsc/wbsearch.html?xxmod=gr&wbp=2&xxcourse=4" t:phone=512-477-6963 t:zip_code=78703 t:scorecard=http://austintexas.gov/sites/default/files/files/Parks/Golf/lionscard.pdf t:facility_website=http://www.austintexas.gov/department/lions-municipal-golf-course t:golf_course="Lions Municipal Golf Course" m:row_number.w8qc-ggfy=2

series e:w8qc-ggfy d:2015-10-07T08:37:13.000Z t:tee_times="https://connect001.rectrac.com/wbwsc/txaustin_1.wsc/wbsearch.html?xxmod=gr&wbp=2&xxcourse=3" t:phone=512-974-8333 t:zip_code=78723 t:scorecard=http://austintexas.gov/sites/default/files/files/Parks/Golf/130708_MW.pdf t:facility_website=http://www.austintexas.gov/department/morris-williams-golf-course t:golf_course="Morris Williams Golf Course" m:row_number.w8qc-ggfy=3
```

## Meta Commands

```ls
metric m:row_number.w8qc-ggfy p:long l:"Row Number"

entity e:w8qc-ggfy l:"Golf Atx Locations" t:url=https://data.austintexas.gov/api/views/w8qc-ggfy

property e:w8qc-ggfy t:meta.view v:id=w8qc-ggfy v:category=Government v:attributionLink=http://www.austintexas.gov/department/golf v:averageRating=0 v:name="Golf Atx Locations"

property e:w8qc-ggfy t:meta.view.license v:name="Public Domain"

property e:w8qc-ggfy t:meta.view.owner v:id=wpqw-45f6 v:screenName=Betty v:displayName=Betty

property e:w8qc-ggfy t:meta.view.tableauthor v:id=wpqw-45f6 v:screenName=Betty v:roleName=editor v:displayName=Betty
```

## Top Records

```ls
| :updated_at | golf_course                 | zip_code | phone          | tee_times                                                                                           | scorecard                                                                            | facility_website                                                          | city | 
| =========== | =========================== | ======== | ============== | =================================================================================================== | ==================================================================================== | ========================================================================= | ==== | 
| 1444206996  | Grey Rock Golf Club         | 78739    | 512-288-4297   | [http://www.greyrockgolfclub.com/booktt/, null]                                                     | [null, null]                                                                         | [http://www.greyrockgolfclub.com/, null]                                  |      | 
| 1444207020  | Lions Municipal Golf Course | 78703    | 512-477-6963   | [https://connect001.rectrac.com/wbwsc/txaustin_1.wsc/wbsearch.html?xxmod=gr&wbp=2&xxcourse=4, null] | [http://austintexas.gov/sites/default/files/files/Parks/Golf/lionscard.pdf, null]    | [http://www.austintexas.gov/department/lions-municipal-golf-course, null] |      | 
| 1444207033  | Morris Williams Golf Course | 78723    | 512-974-8333   | [https://connect001.rectrac.com/wbwsc/txaustin_1.wsc/wbsearch.html?xxmod=gr&wbp=2&xxcourse=3, null] | [http://austintexas.gov/sites/default/files/files/Parks/Golf/130708_MW.pdf, null]    | [http://www.austintexas.gov/department/morris-williams-golf-course, null] |      | 
| 1444207054  | Hancock Golf Course         | 78751    | 512-453-0276   | [https://connect001.rectrac.com/wbwsc/txaustin_1.wsc/wbsearch.html?xxmod=gr&wbp=2&xxcourse=5, null] | [http://austintexas.gov/sites/default/files/files/Parks/Golf/hancockcard.pdf, null]  | [http://www.austintexas.gov/department/hancock-golf-course, null]         |      | 
| 1490208953  | Jimmy Clay Golf Course      | 78744    | 512-974-4653   | [https://connect001.rectrac.com/wbwsc/txaustin_1.wsc/wbsearch.html?xxmod=gr&wbp=2&xxcourse=1, null] | [http://austintexas.gov/sites/default/files/files/Parks/Golf/130708_Clay.pdf, null]  | [http://www.austintexas.gov/department/jimmy-clay-golf-course, null]      |      | 
| 1490208958  | Roy Kizer Golf Course       | 78744    | 512-974-4653   | [https://connect001.rectrac.com/wbwsc/txaustin_1.wsc/wbsearch.html?xxmod=gr&wbp=2&xxcourse=2, null] | [http://austintexas.gov/sites/default/files/files/Parks/Golf/130708_Kizer.pdf, null] | [http://www.austintexas.gov/department/roy-kizer-golf-course, null]       |      | 
```