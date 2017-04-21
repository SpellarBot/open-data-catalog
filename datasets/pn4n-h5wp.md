# Degrees and Other Formal Awards Granted by the State University of New York (SUNY): Beginning Academic Year 1949-50

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/degrees-and-other-formal-awards-granted-by-the-state-university-of-new-york-suny-beginn-19) |
| Metadata | [Link](https://data.ny.gov/api/views/pn4n-h5wp) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/pn4n-h5wp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/pn4n-h5wp/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | pn4n-h5wp |
| Name | Degrees and Other Formal Awards Granted by the State University of New York (SUNY): Beginning Academic Year 1949-50 |
| Attribution | SUNY System Administration, Office of Institutional Research |
| Category | Education |
| Tags | suny institutions, degrees and awards, higher education |
| Created | 2013-03-05T22:58:29Z |
| Publication Date | 2016-09-09T21:07:06Z |

## Description

This dataset records the number and type of degrees awarded by the State University of New York.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | academic_year              | Academic Year              | text      | text        |
| Yes      | numeric metric | undergraduate_certificates | Undergraduate Certificates | number    | number      |
| Yes      | numeric metric | associate_s_degrees        | Associate's Degrees        | number    | number      |
| Yes      | numeric metric | bachelor_s_degrees         | Bachelor's Degrees         | number    | number      |
| Yes      | numeric metric | master_s_degrees           | Master's Degrees           | number    | number      |
| Yes      | numeric metric | doctoral_degrees           | Doctoral Degrees           | number    | number      |
| Yes      | numeric metric | first_professional_degrees | First Professional Degrees | number    | number      |
| Yes      | numeric metric | graduate_certificates      | Graduate Certificates      | number    | number      |
```

## Time Field

```ls
Value = academic_year
Format & Zone = yyyy-MM
```

## Data Commands

```ls
series e:pn4n-h5wp d:2015-03-01T00:00:00.000Z m:bachelor_s_degrees=41335 m:doctoral_degrees=1460 m:undergraduate_certificates=2715 m:graduate_certificates=1040 m:master_s_degrees=10873 m:first_professional_degrees=1293 m:associate_s_degrees=36997

series e:pn4n-h5wp d:2014-02-01T00:00:00.000Z m:bachelor_s_degrees=41025 m:doctoral_degrees=1374 m:undergraduate_certificates=2705 m:graduate_certificates=994 m:master_s_degrees=10329 m:first_professional_degrees=1342 m:associate_s_degrees=36630

series e:pn4n-h5wp d:2013-01-01T00:00:00.000Z m:bachelor_s_degrees=40364 m:doctoral_degrees=1311 m:undergraduate_certificates=2683 m:graduate_certificates=931 m:master_s_degrees=10355 m:first_professional_degrees=1366 m:associate_s_degrees=36596
```

## Meta Commands

```ls
metric m:undergraduate_certificates p:integer l:"Undergraduate Certificates" t:dataTypeName=number

metric m:associate_s_degrees p:integer l:"Associate's Degrees" t:dataTypeName=number

metric m:bachelor_s_degrees p:integer l:"Bachelor's Degrees" t:dataTypeName=number

metric m:master_s_degrees p:integer l:"Master's Degrees" t:dataTypeName=number

metric m:doctoral_degrees p:integer l:"Doctoral Degrees" t:dataTypeName=number

metric m:first_professional_degrees p:integer l:"First Professional Degrees" d:"Per Integrated Postsecondary Education Data System's (IPEDS) definitional change, the First Professional category is now replaced by ""Doctoral/Professional Practice,"" which is slightly broader than First Professional (includes DPT, DNS, and DNP degrees)." t:dataTypeName=number

metric m:graduate_certificates p:integer l:"Graduate Certificates" t:dataTypeName=number

entity e:pn4n-h5wp l:"Degrees and Other Formal Awards Granted by the State University of New York (SUNY): Beginning Academic Year 1949-50" t:attribution="SUNY System Administration, Office of Institutional Research" t:url=https://data.ny.gov/api/views/pn4n-h5wp

property e:pn4n-h5wp t:meta.view v:id=pn4n-h5wp v:category=Education v:attributionLink=http://www.suny.edu/ v:averageRating=0 v:name="Degrees and Other Formal Awards Granted by the State University of New York (SUNY): Beginning Academic Year 1949-50" v:attribution="SUNY System Administration, Office of Institutional Research"

property e:pn4n-h5wp t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:pn4n-h5wp t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:pn4n-h5wp t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| academic_year | undergraduate_certificates | associate_s_degrees | bachelor_s_degrees | master_s_degrees | doctoral_degrees | first_professional_degrees | graduate_certificates | 
| ============= | ========================== | =================== | ================== | ================ | ================ | ========================== | ===================== | 
| 2014-15       | 2715                       | 36997               | 41335              | 10873            | 1460             | 1293                       | 1040                  | 
| 2013-14       | 2705                       | 36630               | 41025              | 10329            | 1374             | 1342                       | 994                   | 
| 2012-13       | 2683                       | 36596               | 40364              | 10355            | 1311             | 1366                       | 931                   | 
| 2011-12       | 2707                       | 36513               | 40004              | 10783            | 1298             | 1320                       | 1090                  | 
| 2010-11       | 2622                       | 34686               | 38500              | 10686            | 1257             | 1350                       | 999                   | 
| 2009-10       | 2441                       | 32583               | 36976              | 10386            | 1291             | 1243                       | 973                   | 
| 2008-09       | 1904                       | 30746               | 35553              | 10156            | 1280             | 1258                       | 937                   | 
| 2007-08       | 1962                       | 30482               | 34280              | 10023            | 1327             | 1221                       | 839                   | 
| 2006-07       | 1969                       | 31081               | 34013              | 10116            | 1257             | 1217                       | 837                   | 
| 2005-06       | 1904                       | 31326               | 33260              | 10522            | 1238             | 1227                       | 1171                  | 
```