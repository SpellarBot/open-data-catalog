# Airport Part 77 Surfaces - Approach

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/airport-part-77-surfaces-approach) |
| Metadata | [Link](https://data.iowa.gov/api/views/fm88-xmhg) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/fm88-xmhg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/fm88-xmhg/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | fm88-xmhg |
| Name | Airport Part 77 Surfaces - Approach |
| Attribution | Iowa Department of Transportation - Office of Aviation |
| Category | Transportation & Utilities |
| Tags | aviation, runway, airfield, imaginary surface, apprach, iowa dot, iowa department of transportation |
| Created | 2016-06-09T08:40:19Z |
| Publication Date | 2016-06-09T08:41:25Z |

## Description

The approach surface is longitudinally centered on the extended runway centerline and extends outward and upward from each end of the primary surface.  An approach surface is applied to the end of each runway based upon the type of approach available.  (Slopes can vary from 20:1, 34:1, 40:1 or 50:1)

## Columns

```ls
| Included | Schema Type    | Field Name  | Name       | Data Type  | Render Type |
| ======== | ============== | =========== | ========== | ========== | =========== |
| No       | time           | :updated_at | updated_at | meta_data  | meta_data   |
| Yes      | series tag     | faacode     | FAACODE    | text       | text        |
| Yes      | series tag     | assoccity   | ASSOCCITY  | text       | text        |
| Yes      | series tag     | fac_name    | FAC_NAME   | text       | text        |
| Yes      | numeric metric | arpelev     | ARPELEV    | number     | number      |
| Yes      | series tag     | part77surf  | PART77SURF | text       | text        |
| Yes      | series tag     | surf_desc   | SURF_DESC  | text       | text        |
| Yes      | numeric metric | innerelev   | INNERELEV  | number     | number      |
| Yes      | numeric metric | outerelev   | OUTERELEV  | number     | number      |
| Yes      | numeric metric | surfwidth   | SURFWIDTH  | number     | number      |
| Yes      | series tag     | surf_ratio  | SURF_RATIO | text       | text        |
| Yes      | series tag     | app_type    | APP_TYPE   | text       | text        |
| Yes      | numeric metric | app_inrwd   | APP_INRWD  | number     | number      |
| Yes      | numeric metric | app_outwd   | APP_OUTWD  | number     | number      |
| Yes      | numeric metric | app_srflng  | APP_SRFLNG | number     | number      |
| Yes      | series tag     | notes       | NOTES      | text       | text        |
| Yes      | series tag     | merge       | MERGE      | text       | text        |
| Yes      | numeric metric | shape_area  | SHAPE.AREA | number     | number      |
| Yes      | numeric metric | shape_len   | SHAPE.LEN  | number     | number      |
| Yes      | series tag     | objectid    | OBJECTID   | text       | number      |
| No       |                | shape       | SHAPE      | geospatial | geospatial  |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = shape
```

## Data Commands

```ls
series e:fm88-xmhg d:2016-06-09T08:40:19.000Z t:assoccity=Montezuma t:shape.longitude=-92.53239292999996 t:surf_desc="Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification." t:app_type="Visual Runway" t:merge="7C5Ap 18" t:faacode=7C5 t:part77surf="Approach Surface" t:shape.needs_recoding=false t:surf_ratio=20:1 t:fac_name="MONTEZUMA SIG FIELD" t:shape.latitude=41.56486944100004 t:objectid=1 t:notes="All elevations are in feet MSL" m:shape_area=348386.41347002605 m:outerelev=1129 m:app_inrwd=250 m:app_outwd=1250 m:arpelev=929 m:app_srflng=5000 m:innerelev=929 m:surfwidth=0

series e:fm88-xmhg d:2016-06-09T08:40:19.000Z t:assoccity=Montezuma t:shape.longitude=-92.53414855899996 t:surf_desc="Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification." t:app_type="Visual Runway" t:merge="7C5Ap 36" t:faacode=7C5 t:part77surf="Approach Surface" t:shape.needs_recoding=false t:surf_ratio=20:1 t:fac_name="MONTEZUMA SIG FIELD" t:shape.latitude=41.545030532000055 t:objectid=2 t:notes="All elevations are in feet MSL" m:shape_area=348386.41460108 m:outerelev=1129 m:app_inrwd=250 m:app_outwd=1250 m:arpelev=929 m:app_srflng=5000 m:innerelev=929 m:surfwidth=0

series e:fm88-xmhg d:2016-06-09T08:40:19.000Z t:assoccity=Burlington t:shape.longitude=-91.12677187299994 t:surf_desc="Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification." t:app_type="Visual Runway" t:merge="BRLAp 18" t:faacode=BRL t:part77surf="Approach Surface" t:shape.needs_recoding=false t:surf_ratio=20:1 t:fac_name="BURLINGTON - SOUTHEAST IOWA REGIONAL" t:shape.latitude=40.801391169000055 t:objectid=3 t:notes="All elevations are in feet MSL" m:shape_area=580643.714282059 m:outerelev=898 m:app_inrwd=500 m:app_outwd=1500 m:arpelev=698 m:app_srflng=5000 m:innerelev=698 m:surfwidth=0
```

## Meta Commands

```ls
metric m:arpelev p:integer l:ARPELEV d:"Airport Elevation (FT MSL)" t:dataTypeName=number

metric m:innerelev p:integer l:INNERELEV d:"Inner Elevation (FT MSL)" t:dataTypeName=number

metric m:outerelev p:integer l:OUTERELEV d:"Outer Elevation (FT MSL)" t:dataTypeName=number

metric m:surfwidth p:integer l:SURFWIDTH d:"Surface Widht (FT)" t:dataTypeName=number

metric m:app_inrwd p:integer l:APP_INRWD d:"Approach Inward" t:dataTypeName=number

metric m:app_outwd p:integer l:APP_OUTWD d:"Approach Outward" t:dataTypeName=number

metric m:app_srflng p:integer l:APP_SRFLNG d:"Approach Surface Length (FT)" t:dataTypeName=number

metric m:shape_area p:decimal l:SHAPE.AREA d:"Area (SqM)" t:dataTypeName=number

metric m:shape_len p:long l:SHAPE.LEN d:"Perimeter (Meter)" t:dataTypeName=number

entity e:fm88-xmhg l:"Airport Part 77 Surfaces - Approach" t:attribution="Iowa Department of Transportation - Office of Aviation" t:url=https://data.iowa.gov/api/views/fm88-xmhg

property e:fm88-xmhg t:meta.view v:id=fm88-xmhg v:category="Transportation & Utilities" v:attributionLink=https://gis.iowadot.gov/public/rest/services/Aviation/Airport_Part77_Surfaces/MapServer/4 v:averageRating=0 v:name="Airport Part 77 Surfaces - Approach" v:attribution="Iowa Department of Transportation - Office of Aviation"

property e:fm88-xmhg t:meta.view.owner v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:displayName="Iowa Department of Transportation"

property e:fm88-xmhg t:meta.view.tableauthor v:id=2cmj-63jw v:profileImageUrlMedium=/api/users/2cmj-63jw/profile_images/THUMB v:profileImageUrlLarge=/api/users/2cmj-63jw/profile_images/LARGE v:screenName="Iowa Department of Transportation" v:profileImageUrlSmall=/api/users/2cmj-63jw/profile_images/TINY v:roleName=administrator v:displayName="Iowa Department of Transportation"
```

## Top Records

```ls
| :updated_at | faacode | assoccity  | fac_name                             | arpelev | part77surf       | surf_desc                                                                                                                             | innerelev | outerelev | surfwidth | surf_ratio | app_type                        | app_inrwd | app_outwd | app_srflng | notes                          | merge    | shape_area                                | shape_len | objectid | shape                                                                                                                                                                                                                                                                                    | 
| =========== | ======= | ========== | ==================================== | ======= | ================ | ===================================================================================================================================== | ========= | ========= | ========= | ========== | =============================== | ========= | ========= | ========== | ============================== | ======== | ========================================= | ========= | ======== | ======================================================================================================================================================================================================================================================================================== | 
| 0           | 7C5     | Montezuma  | MONTEZUMA SIG FIELD                  | 929     | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 929       | 1129      | 0         | 20:1       | Visual Runway                   | 250       | 1250      | 5000       | All elevations are in feet MSL | 7C5Ap 18 | 348386.4134700260474346578121185302734375 |           | 1        | [null, 41.56486944100004, -92.53239292999996, null, false, {rings=[[[-92.53239292999996, 41.56486944100004], [-92.53417075799996, 41.55113894400006], [-92.53508442799995, 41.55113706600008], [-92.53696225399995, 41.56486005100004], [-92.53239292999996, 41.56486944100004]]]}]      | 
| 0           | 7C5     | Montezuma  | MONTEZUMA SIG FIELD                  | 929     | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 929       | 1129      | 0         | 20:1       | Visual Runway                   | 250       | 1250      | 5000       | All elevations are in feet MSL | 7C5Ap 36 | 348386.414601080003194510936737060546875  |           | 2        | [null, 41.545030532000055, -92.53414855899996, null, false, {rings=[[[-92.53414855899996, 41.545030532000055], [-92.53227191199994, 41.531307491000064], [-92.53683885199996, 41.531298106000065], [-92.53506214199996, 41.54502865500007], [-92.53414855899996, 41.545030532000055]]]}] | 
| 0           | BRL     | Burlington | BURLINGTON - SOUTHEAST IOWA REGIONAL | 698     | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 698       | 898       | 0         | 20:1       | Visual Runway                   | 500       | 1500      | 5000       | All elevations are in feet MSL | BRLAp 18 | 580643.714282058994285762310028076171875  |           | 3        | [null, 40.801391169000055, -91.12677187299994, null, false, {rings=[[[-91.12677187299994, 40.801391169000055], [-91.12135323099994, 40.801428789000056], [-91.12211253799995, 40.787695375000055], [-91.12572423899996, 40.78767346600006], [-91.12677187299994, 40.801391169000055]]]}] | 
| 0           | BRL     | Burlington | BURLINGTON - SOUTHEAST IOWA REGIONAL | 698     | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 698       | 898       | 0         | 34:1       | Non-Precision Instrument Runway | 500       | 3500      | 10000      | All elevations are in feet MSL | BRLAp 12 | 1858060.7304110000841319561004638671875   |           | 4        | [null, 40.80103769600004, -91.17115257199998, null, false, {rings=[[[-91.17115257199998, 40.80103769600004], [-91.16492340599996, 40.809399162000034], [-91.13615964599995, 40.792287550000026], [-91.13704991799995, 40.79109330700004], [-91.17115257199998, 40.80103769600004]]]}]    | 
| 0           | BRL     | Burlington | BURLINGTON - SOUTHEAST IOWA REGIONAL | 698     | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 698       | 898       | 0         | 34:1       | Non-Precision Instrument Runway | 500       | 3500      | 10000      | All elevations are in feet MSL | BRLAp 30 | 1858060.80195031990297138690948486328125  |           | 5        | [null, 40.77522161700006, -91.08557528099999, null, false, {rings=[[[-91.08557528099999, 40.77522161700006], [-91.09181136499996, 40.76686459600006], [-91.12055222699996, 40.78398744700007], [-91.11966174899999, 40.78518155900008], [-91.08557528099999, 40.77522161700006]]]}]      | 
| 0           | AMW     | Ames       | AMES MUNICIPAL                       | 955     | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 955       | 1155      | 0         | 34:1       | Non-Precision Instrument Runway | 500       | 3500      | 10000      | All elevations are in feet MSL | AMWAp 13 | 1858060.78459899011068046092987060546875  |           | 6        | [null, 42.02205884400007, -93.64768695699996, null, false, {rings=[[[-93.64768695699996, 42.02205884400007], [-93.62619842699996, 41.99939259700005], [-93.62752689999996, 41.99844279800004], [-93.65698649899997, 42.01540820900004], [-93.64768695699996, 42.02205884400007]]]}]      | 
| 0           | AMW     | Ames       | AMES MUNICIPAL                       | 955     | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 955       | 1155      | 0         | 34:1       | Non-Precision Instrument Runway | 500       | 3500      | 10000      | All elevations are in feet MSL | AMWAp 19 | 2090318.3690936299972236156463623046875   |           | 7        | [null, 42.025898865000045, -93.61418210599999, null, false, {rings=[[[-93.61418210599999, 42.025898865000045], [-93.60183496399998, 42.02314872800008], [-93.61677909799994, 41.99782700000003], [-93.62030552999994, 41.99861243400005], [-93.61418210599999, 42.025898865000045]]]}]   | 
| 0           | AMW     | Ames       | AMES MUNICIPAL                       | 955     | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 955       | 1155      | 0         | 34:1       | Non-Precision Instrument Runway | 500       | 3500      | 10000      | All elevations are in feet MSL | AMWAp 31 | 1858060.77876574010588228702545166015625  |           | 8        | [null, 41.99167886600003, -93.61628840399999, null, false, {rings=[[[-93.61628840399999, 41.99167886600003], [-93.58685055999996, 41.974702947000026], [-93.59614954099999, 41.96805718600007], [-93.61761686299997, 41.99072918100006], [-93.61628840399999, 41.99167886600003]]]}]     | 
| 0           | BNW     | Boone      | BOONE MUNICIPAL                      | 1160    | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 1160      | 1360      | 0         | 34:1       | Non-Precision Instrument Runway | 500       | 3500      | 10000      | All elevations are in feet MSL | BNWAp 15 | 1858060.919253109954297542572021484375    |           | 9        | [null, 42.07565463800006, -93.87528595499998, null, false, {rings=[[[-93.87528595499998, 42.07565463800006], [-93.86419705999998, 42.080560915000035], [-93.85014047399994, 42.05485351800007], [-93.85172422299996, 42.054152877000035], [-93.87528595499998, 42.07565463800006]]]}]    | 
| 0           | BNW     | Boone      | BOONE MUNICIPAL                      | 1160    | Approach Surface | Surface extends from end of primary surface; slope ratio, length and width dependent on approach procedure and runway classification. | 1160      | 1360      | 0         | 20:1       | Visual Runway                   | 250       | 1250      | 5000       | All elevations are in feet MSL | BNWAp 20 | 348386.426542454981245100498199462890625  |           | 10       | [null, 42.055056980000074, -93.84734129599997, null, false, {rings=[[[-93.84734129599997, 42.055056980000074], [-93.84112377799994, 42.06805010100004], [-93.83696154499995, 42.06658147300004], [-93.84650897499995, 42.054763311000045], [-93.84734129599997, 42.055056980000074]]]}]  | 
```