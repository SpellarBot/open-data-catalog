# Seattle Traffic Cameras

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-traffic-cameras-cb8ff) |
| Metadata | [Link](https://data.seattle.gov/api/views/65fc-btcc) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/65fc-btcc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/65fc-btcc/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 65fc-btcc |
| Name | Seattle Traffic Cameras |
| Attribution | Department of Information Technology |
| Category | Transportation |
| Tags | transportation, cameras, traffic, street |
| Created | 2012-05-18T21:17:46Z |
| Publication Date | 2012-08-07T18:03:25Z |

## Description

Traffic caneras in Seattle owned by SDOT and WSDOT

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| No       | time           | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag     | ownershipcd | OWNERSHIPCD | text      | text        |
| Yes      | series tag     | cameralabel | CAMERALABEL | text      | text        |
| Yes      | series tag     | imageurl    | IMAGEURL    | url       | url         |
| Yes      | series tag     | videourl    | VIDEOURL    | text      | text        |
| Yes      | series tag     | weburl      | WEBURL      | text      | text        |
| Yes      | numeric metric | xpos        | XPOS        | number    | number      |
| Yes      | numeric metric | ypos        | YPOS        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:65fc-btcc d:2012-05-18T14:17:47.000Z t:videourl="rtmp://156.74.125.142:1935/live&file=15_Emerson.stream" t:weburl=NULL t:imageurl=http://www.seattle.gov/trafficcams/images/15W_Emerson.jpg t:ownershipcd=SDOT t:cameralabel="15th Ave W & W Emerson St" m:xpos=-122.37612 m:ypos=47.65408

series e:65fc-btcc d:2012-05-18T14:17:47.000Z t:videourl="rtmp://156.74.125.142:1935/live&file=15NW_65.stream" t:weburl=NULL t:imageurl=http://www.seattle.gov/trafficcams/images/15NW_65.jpg t:ownershipcd=SDOT t:cameralabel="15th Ave NW & NW 65th St - NS" m:xpos=-122.37621 m:ypos=47.6759

series e:65fc-btcc d:2012-05-18T14:17:47.000Z t:videourl="rtmp://156.74.125.142:1935/live&file=15_Market.stream" t:weburl=NULL t:imageurl=http://www.seattle.gov/trafficcams/images/15NW_Market.jpg t:ownershipcd=SDOT t:cameralabel="15th Ave NW & NW Market St - NS" m:xpos=-122.37631 m:ypos=47.66852
```

## Meta Commands

```ls
metric m:xpos p:float l:XPOS t:dataTypeName=number

metric m:ypos p:float l:YPOS t:dataTypeName=number

entity e:65fc-btcc l:"Seattle Traffic Cameras" t:attribution="Department of Information Technology" t:url=https://data.seattle.gov/api/views/65fc-btcc

property e:65fc-btcc t:meta.view v:id=65fc-btcc v:category=Transportation v:averageRating=0 v:name="Seattle Traffic Cameras" v:attribution="Department of Information Technology"

property e:65fc-btcc t:meta.view.license v:name="Public Domain"

property e:65fc-btcc t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:65fc-btcc t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | ownershipcd | cameralabel                     | imageurl                                                          | videourl                                               | weburl                                                   | xpos       | ypos     | 
| =========== | =========== | =============================== | ================================================================= | ====================================================== | ======================================================== | ========== | ======== | 
| 1337350667  | SDOT        | 15th Ave W & W Emerson St       | [http://www.seattle.gov/trafficcams/images/15W_Emerson.jpg, null] | rtmp://156.74.125.142:1935/live&file=15_Emerson.stream | NULL                                                     | -122.37612 | 47.65408 | 
| 1337350667  | SDOT        | 15th Ave NW & NW 65th St - NS   | [http://www.seattle.gov/trafficcams/images/15NW_65.jpg, null]     | rtmp://156.74.125.142:1935/live&file=15NW_65.stream    | NULL                                                     | -122.37621 | 47.67590 | 
| 1337350667  | SDOT        | 15th Ave NW & NW Market St - NS | [http://www.seattle.gov/trafficcams/images/15NW_Market.jpg, null] | rtmp://156.74.125.142:1935/live&file=15_Market.stream  | NULL                                                     | -122.37631 | 47.66852 | 
| 1337350667  | SDOT        | 1st Ave & Denny Way             | [http://www.seattle.gov/trafficcams/images/1_Denny.jpg, null]     | rtmp://156.74.125.142:1935/live&file=1_Denny.stream    | NULL                                                     | -122.35557 | 47.61851 | 
| 1337350667  | SDOT        | 15th Ave NW & NW Leary Way      | [http://www.seattle.gov/trafficcams/images/15NW_Leary.jpg, null]  | rtmp://156.74.125.142:1935/live&file=15_Leary.stream   | NULL                                                     | -122.37593 | 47.66360 | 
| 1337350667  | SDOT        | 23rd Ave E & E Madison St - NS  | [http://www.seattle.gov/trafficcams/images/23E_Madison.jpg, null] | rtmp://156.74.125.142:1935/live&file=23_Madison.stream | NULL                                                     | -122.30244 | 47.61939 | 
| 1337350667  | SDOT        | 23rd Ave E & E Cherry St - EW   | [http://www.seattle.gov/trafficcams/images/ECherry_23.jpg, null]  | rtmp://156.74.125.146:1935/live&file=Cherry_23.stream  | NULL                                                     | -122.30262 | 47.60797 | 
| 1337350667  | SDOT        | 15th Ave NW & NW Market St - EW | [http://www.seattle.gov/trafficcams/images/NWMarket_15.jpg, null] | rtmp://156.74.125.146:1935/live&file=Market_15.stream  | NULL                                                     | -122.37595 | 47.66860 | 
| 1337350667  | SDOT        | 25th Ave NE & NE 65th St        | [http://www.seattle.gov/trafficcams/images/25NE_65.jpg, null]     | rtmp://156.74.125.142:1935/live&file=25NE_65.stream    | NULL                                                     | -122.30073 | 47.67669 | 
| 1337350667  | WSDOT       | SR-520 East Highrise            | [http://images.wsdot.wa.gov/nw/520vc00398.jpg, null]              | NULL                                                   | http://www.seattle.gov/trafficcams/sr520_midspaneast.htm | -122.29969 | 47.59014 | 
```