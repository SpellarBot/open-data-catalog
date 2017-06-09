# Survey Markers - Retired

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/survey-markers-retired) |
| Metadata | [Link](https://data.iowa.gov/api/views/hvmg-f4t6) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/hvmg-f4t6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/hvmg-f4t6/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | hvmg-f4t6 |
| Name | Survey Markers - Retired |
| Attribution | Iowa Department of Transportation - Office of Design |
| Category | Transportation & Utilities |
| Tags | reference, survey, retired, control monument, cadastre, iowa dot, iowa department of transportation |
| Created | 2016-07-06T18:42:17Z |
| Publication Date | 2016-07-06T18:56:50Z |

## Description

This layer contains the archived records for survey markers that are considered retired.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       |                | id                | ID                | text      | number      |
| Yes      | series tag     | survey_id         | SURVEY_ID         | text      | text        |
| No       |                | xcoord            | XCOORD            | number    | number      |
| No       |                | ycoord            | YCOORD            | number    | number      |
| No       |                | zcoord            | ZCOORD            | number    | number      |
| Yes      | series tag     | feature_type      | FEATURE_TYPE      | text      | text        |
| Yes      | series tag     | description       | DESCRIPTION       | text      | text        |
| Yes      | series tag     | project_number    | PROJECT_NUMBER    | text      | text        |
| Yes      | series tag     | proj_dir_url      | PROJ_DIR_URL      | text      | text        |
| Yes      | series tag     | horiz_datum       | HORIZ_DATUM       | text      | text        |
| Yes      | series tag     | network           | NETWORK           | text      | text        |
| Yes      | series tag     | coord_system      | COORD_SYSTEM      | text      | text        |
| Yes      | series tag     | vert_datum        | VERT_DATUM        | text      | text        |
| Yes      | series tag     | owner             | OWNER             | text      | text        |
| Yes      | time           | date_added        | DATE_ADDED        | text      | text        |
| Yes      | series tag     | uploader_name     | UPLOADER_NAME     | text      | text        |
| Yes      | series tag     | precision_quality | PRECISION_QUALITY | text      | text        |
| Yes      | series tag     | ls_certified      | LS_CERTIFIED      | text      | text        |
| Yes      | series tag     | status            | STATUS            | text      | text        |
| No       |                | capturedateyear   | CAPTUREDATEYEAR   | number    | number      |
| Yes      | numeric metric | capturedatemonth  | CAPTUREDATEMONTH  | number    | number      |
| Yes      | numeric metric | capturedateday    | CAPTUREDATEDAY    | number    | number      |
```

## Time Field

```ls
Value = date_added
Format & Zone = MM/dd/yyyy HH:mm
```

## Series Fields

```ls
Excluded Fields = id,xcoord,ycoord,zcoord,capturedateyear
```

## Data Commands

```ls
series e:hvmg-f4t6 d:2015-08-18T15:27:00.000Z t:horiz_datum="NAD83(2011) (EPOCH2010.00)" t:precision_quality=A t:feature_type=CP t:proj_dir_url=pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ t:coord_system="IA North US Feet" t:status=R t:description="FND WRIGHT CO. SURVEY MONUMENT 0011" t:ls_certified=N t:owner="Office of Design" t:project_number="STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2" t:vert_datum="NAVD88 (Computed using Geoid12A)" t:survey_id=11 t:network="IaRTN 2013 Adjustment" m:capturedatemonth=12 m:capturedateday=16

series e:hvmg-f4t6 d:2015-08-18T15:27:00.000Z t:horiz_datum="NAD83(2011) (EPOCH2010.00)" t:precision_quality=A t:feature_type=FENO t:proj_dir_url=pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ t:coord_system="IA North US Feet" t:status=R t:description="O SET FENO TYPE MONUMENT" t:ls_certified=N t:owner="Office of Design" t:project_number="STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2" t:vert_datum="NAVD88 (Computed using Geoid12A)" t:survey_id=2 t:network="IaRTN 2013 Adjustment" m:capturedatemonth=12 m:capturedateday=16

series e:hvmg-f4t6 d:2015-08-18T15:31:00.000Z t:horiz_datum="NAD83(2011) (EPOCH2010.00)" t:precision_quality=A t:feature_type=CP t:proj_dir_url=pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ t:coord_system="IA North US Feet" t:status=R t:description="FND WRIGHT CO. SURVEY MONUMENT 0011" t:ls_certified=N t:owner="Office of Design" t:project_number="STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2" t:vert_datum="NAVD88 (Computed using Geoid12A)" t:survey_id=11 t:network="IaRTN 2013 Adjustment" m:capturedatemonth=12 m:capturedateday=16
```

## Meta Commands

```ls
metric m:capturedatemonth p:integer l:CAPTUREDATEMONTH d:"Capture Date - Month" t:dataTypeName=number

metric m:capturedateday p:integer l:CAPTUREDATEDAY d:"Capture Date - Day" t:dataTypeName=number

entity e:hvmg-f4t6 l:"Survey Markers - Retired" t:attribution="Iowa Department of Transportation - Office of Design" t:url=https://data.iowa.gov/api/views/hvmg-f4t6

property e:hvmg-f4t6 t:meta.view d:2017-06-09T13:59:10.619Z v:id=hvmg-f4t6 v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Survey/Survey_Markers/MapServer/1 v:averageRating=0 v:name="Survey Markers - Retired" v:attribution="Iowa Department of Transportation - Office of Design"

property e:hvmg-f4t6 t:meta.view.owner d:2017-06-09T13:59:10.619Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:hvmg-f4t6 t:meta.view.tableauthor d:2017-06-09T13:59:10.619Z v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| id   | survey_id | xcoord                                 | ycoord                                  | zcoord                                          | feature_type | description                         | project_number                                     | proj_dir_url                                                                    | horiz_datum                | network               | coord_system         | vert_datum                       | owner            | date_added       | uploader_name | precision_quality | ls_certified | status | capturedateyear | capturedatemonth | capturedateday | 
| ==== | ========= | ====================================== | ======================================= | =============================================== | ============ | =================================== | ================================================== | =============================================================================== | ========================== | ===================== | ==================== | ================================ | ================ | ================ | ============= | ================= | ============ | ====== | =============== | ================ | ============== | 
| 5301 | 11        | 4889861.280000000260770320892333984375 | 3777689.3070000000298023223876953125    | 1180.421000000000049112713895738124847412109375 | CP           | FND WRIGHT CO. SURVEY MONUMENT 0011 | STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2 | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IA North US Feet     | NAVD88 (Computed using Geoid12A) | Office of Design | 08/18/2015 15:27 |               | A                 | N            | R      | 2014            | 12               | 16             | 
| 5302 | 2         | 4889971.083999999798834323883056640625 | 3772981.0430000000633299350738525390625 | 1172.74800000000004729372449219226837158203125  | FENO         | O SET FENO TYPE MONUMENT            | STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2 | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IA North US Feet     | NAVD88 (Computed using Geoid12A) | Office of Design | 08/18/2015 15:27 |               | A                 | N            | R      | 2014            | 12               | 16             | 
| 5303 | 11        | 4889861.280000000260770320892333984375 | 3777689.3070000000298023223876953125    | 1180.421000000000049112713895738124847412109375 | CP           | FND WRIGHT CO. SURVEY MONUMENT 0011 | STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2 | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IA North US Feet     | NAVD88 (Computed using Geoid12A) | Office of Design | 08/18/2015 15:31 |               | A                 | N            | R      | 2014            | 12               | 16             | 
| 5304 | 2         | 4889971.083999999798834323883056640625 | 3772981.0430000000633299350738525390625 | 1172.74800000000004729372449219226837158203125  | FENO         | O SET FENO TYPE MONUMENT            | STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2 | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IA North US Feet     | NAVD88 (Computed using Geoid12A) | Office of Design | 08/18/2015 15:31 |               | A                 | N            | R      | 2014            | 12               | 16             | 
| 5305 | 11        | 4889861.280000000260770320892333984375 | 3777689.3070000000298023223876953125    | 1180.421000000000049112713895738124847412109375 | CP           | FND WRIGHT CO. SURVEY MONUMENT 0011 | STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2 | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IA North US Feet     | NAVD88 (Computed using Geoid12A) | Office of Design | 08/18/2015 15:35 |               | A                 | N            | R      | 2014            | 12               | 16             | 
| 5306 | 2         | 4889971.083999999798834323883056640625 | 3772981.0430000000633299350738525390625 | 1172.74800000000004729372449219226837158203125  | FENO         | O SET FENO TYPE MONUMENT            | STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2 | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IA North US Feet     | NAVD88 (Computed using Geoid12A) | Office of Design | 08/18/2015 15:35 |               | A                 | N            | R      | 2014            | 12               | 16             | 
| 5307 | 11        | 4889861.280000000260770320892333984375 | 3777689.3070000000298023223876953125    | 1180.421000000000049112713895738124847412109375 | CP           | FND WRIGHT CO. SURVEY MONUMENT 0011 | STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2 | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IA North US Feet     | NAVD88 (Computed using Geoid12A) | Office of Design | 08/18/2015 15:49 |               | A                 | N            | R      | 2014            | 12               | 16             | 
| 5308 | 2         | 4889971.083999999798834323883056640625 | 3772981.0430000000633299350738525390625 | 1172.74800000000004729372449219226837158203125  | FENO         | O SET FENO TYPE MONUMENT            | STPN-069-7(41)--2J-99 PIN 08-99-069-010 Sap-0656.2 | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9906901013\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IA North US Feet     | NAVD88 (Computed using Geoid12A) | Office of Design | 08/18/2015 15:49 |               | A                 | N            | R      | 2014            | 12               | 16             | 
| 5318 | 1         | 14270888.89100000075995922088623046875 | 8504572.57300000078976154327392578125   | 1168.812000000000125510268844664096832275390625 | CP           | FENO MON                            | STPN-175-2(7)--2J-97                               | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9717501016\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IaRCS ZONE 4 US Feet | NAVD88 (Computed using Geoid12A) | Office of Design | 09/03/2015 09:45 |               | A                 | Y            | R      | 2014            | 8                | 0              | 
| 5319 | 2         | 14269651.8220000006258487701416015625  | 8503648.14399999938905239105224609375   | 1175.245000000000118234311230480670928955078125 | CP           | REBAR                               | STPN-175-2(7)--2J-97                               | pw:\\projectwise.dot.int.lan:PWMain\Documents\Projects\9717501016\PrelimSurvey\ | NAD83(2011) (EPOCH2010.00) | IaRTN 2013 Adjustment | IaRCS ZONE 4 US Feet | NAVD88 (Computed using Geoid12A) | Office of Design | 09/03/2015 09:45 |               | A                 | Y            | R      | 2014            | 8                | 0              | 
```