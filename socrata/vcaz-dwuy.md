# Green Business Program

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/green-business-program-29e0c) |
| Metadata | [Link](https://data.hawaii.gov/api/views/vcaz-dwuy) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/vcaz-dwuy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/vcaz-dwuy/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | vcaz-dwuy |
| Name | Green Business Program |
| Attribution | DBEDT |
| Category | Economic Development |
| Tags | green business, hawaii, dbedt, hotels, offices, restaurants, grocery stores |
| Created | 2014-03-15T00:47:19Z |
| Publication Date | 2014-03-15T00:54:28Z |

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | agency           | Agency           | text      | html        |
| Yes      | series tag  | phone_number     | Phone Number     | phone     | phone       |
| Yes      | series tag  | website          | Website          | url       | url         |
| Yes      | series tag  | 1st_green_report | 1st Green Report | url       | url         |
| Yes      | series tag  | 2nd_green_report | 2nd Green Report | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:vcaz-dwuy d:2014-03-14T17:54:18.000Z t:phone_number="(808) 586-2424" t:2nd_green_report=http://energy.hawaii.gov/wp-content/uploads/2012/03/Final-DBEDT-Press-Packet-2012.pdf t:website=http://energy.hawaii.gov/green-business-program t:phone_type=Work t:1st_green_report=http://energy.hawaii.gov/wp-content/uploads/2011/10/DBEDT-Highlights-20091.pdf t:agency="<p>DBEDT, Department of Business, Economic Development, &amp; Tourism</p>" m:row_number.vcaz-dwuy=1
```

## Meta Commands

```ls
metric m:row_number.vcaz-dwuy p:long l:"Row Number"

entity e:vcaz-dwuy l:"Green Business Program" t:attribution=DBEDT t:url=https://data.hawaii.gov/api/views/vcaz-dwuy

property e:vcaz-dwuy t:meta.view v:id=vcaz-dwuy v:category="Economic Development" v:attributionLink=http://energy.hawaii.gov/green-business-program v:averageRating=0 v:name="Green Business Program" v:attribution=DBEDT

property e:vcaz-dwuy t:meta.view.license v:name="Public Domain"

property e:vcaz-dwuy t:meta.view.owner v:id=av98-wszh v:screenName="Jonathan Chin" v:displayName="Jonathan Chin"

property e:vcaz-dwuy t:meta.view.tableauthor v:id=av98-wszh v:screenName="Jonathan Chin" v:roleName=editor v:displayName="Jonathan Chin"
```

## Top Records

```ls
| :updated_at | agency                                                         | phone_number           | website                                                                   | 1st_green_report                                                                       | 2nd_green_report                                                                              | 
| =========== | ============================================================== | ====================== | ========================================================================= | ====================================================================================== | ============================================================================================= | 
| 1394819658  | DBEDT, Department of Business, Economic Development, & Tourism | [(808) 586-2424, Work] | [http://energy.hawaii.gov/green-business-program, Green Business Program] | [http://energy.hawaii.gov/wp-content/uploads/2011/10/DBEDT-Highlights-20091.pdf, 2009] | [http://energy.hawaii.gov/wp-content/uploads/2012/03/Final-DBEDT-Press-Packet-2012.pdf, 2012] | 
```