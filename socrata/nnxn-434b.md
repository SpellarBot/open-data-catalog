# Seattle Police Department Beats

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-police-department-beats-239d4) |
| Metadata | [Link](https://data.seattle.gov/api/views/nnxn-434b) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/nnxn-434b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/nnxn-434b/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | nnxn-434b |
| Name | Seattle Police Department Beats |
| Attribution | City of Seattle Department of Information Technology |
| Category | Public Safety |
| Tags | police precincts, police beats, boundaries, beats, precincts |
| Created | 2010-06-22T20:19:32Z |
| Publication Date | 2016-09-20T21:34:45Z |

## Description

Spatial data files of City of Seatle Police precincts and beats. Coordinate system is WGS84

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | file_type        | File Type        | text      | text        |
| Yes      | series tag  | file             | File             | document  | document    |
| Yes      | series tag  | applicable_years | Applicable Years | text      | text        |
| Yes      | series tag  | description      | Description      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nnxn-434b d:2011-06-22T08:40:02.000Z t:file.filename=spdbeat_WGS84.zip t:file.size=629802 t:file.content_type="application/zip; charset=binary" t:description="Shapefile for Seattle Police Department Beats - pre 2008 beat boundaries" t:file.file_id=MNDEv9hJVgydwFH91Ov6rgq0Ibf6lgQwTk9F99Qfkpk t:applicable_years="pre 2008" t:file_type="Shape File as Zip" m:row_number.nnxn-434b=1

series e:nnxn-434b d:2011-06-22T08:41:10.000Z t:file.filename=spdbeat_WGS84.kmz t:file.size=334973 t:file.content_type="application/zip; charset=binary" t:description="KMZ file  for Seattle Police Department Beats - pre 2008 beat boundaries" t:file.file_id=dTn_4IfnCSQB18fMaUNSDi0DZhYFOLDpW8gmlwaRyD4 t:applicable_years="pre 2008" t:file_type=KMZ m:row_number.nnxn-434b=2

series e:nnxn-434b d:2016-09-20T21:32:15.000Z t:file.filename=SPD_BEATS_WGS84.zip t:file.size=396327 t:file.content_type="application/zip; charset=binary" t:description="Shapefile for Seattle Police Department Beats - 2008-2015 beat boundaries" t:file.file_id=X4YxSMYBsG3tj7SwU4dXf1bHkxxFmba7HmrEmMsoZuI t:applicable_years=2008+ t:file_type="Shape File as Zip" m:row_number.nnxn-434b=3
```

## Meta Commands

```ls
metric m:row_number.nnxn-434b p:long l:"Row Number"

entity e:nnxn-434b l:"Seattle Police Department Beats" t:attribution="City of Seattle Department of Information Technology" t:url=https://data.seattle.gov/api/views/nnxn-434b

property e:nnxn-434b t:meta.view v:id=nnxn-434b v:category="Public Safety" v:averageRating=0 v:name="Seattle Police Department Beats" v:attribution="City of Seattle Department of Information Technology"

property e:nnxn-434b t:meta.view.license v:name="Public Domain"

property e:nnxn-434b t:meta.view.owner v:id=6bay-fiph v:screenName="6506 Baden, Toby" v:displayName="6506 Baden, Toby"

property e:nnxn-434b t:meta.view.tableauthor v:id=6bay-fiph v:screenName="6506 Baden, Toby" v:roleName=publisher v:displayName="6506 Baden, Toby"
```

## Top Records

```ls
| :updated_at | file_type         | file                                                                                                        | applicable_years | description                                                                           | 
| =========== | ================= | =========================================================================================================== | ================ | ===================================================================================== | 
| 1308732002  | Shape File as Zip | [application/zip; charset=binary, MNDEv9hJVgydwFH91Ov6rgq0Ibf6lgQwTk9F99Qfkpk, spdbeat_WGS84.zip, 629802]   | pre 2008         | Shapefile for Seattle Police Department Beats - pre 2008 beat boundaries              | 
| 1308732070  | KMZ               | [application/zip; charset=binary, dTn_4IfnCSQB18fMaUNSDi0DZhYFOLDpW8gmlwaRyD4, spdbeat_WGS84.kmz, 334973]   | pre 2008         | KMZ file for Seattle Police Department Beats - pre 2008 beat boundaries               | 
| 1474407135  | Shape File as Zip | [application/zip; charset=binary, X4YxSMYBsG3tj7SwU4dXf1bHkxxFmba7HmrEmMsoZuI, SPD_BEATS_WGS84.zip, 396327] | 2008+            | Shapefile for Seattle Police Department Beats - 2008-2015 beat boundaries             | 
| 1474407148  | KMZ               | [application/zip; charset=binary, BDOq2nBZjBqWKj1mUOMyr9YmfsVhSAuFRYasQ0eHWTA, spd_beats_wgs84.kmz, 214678] | 2008+            | KMZ file for Seattle Police Department Beats - 2008-2015 beat boundaries              | 
| 1474407256  | Shape File as Zip | [application/zip; charset=binary, 96d998d4-ae20-4ea8-b912-436e68982a0d, SPD_BEATS_WGS84.zip, 182924]        | Current          | Shapefile for Seattle Police Department (most current) - 2015-Present beat boundaries | 
| 1474407277  | KMZ               | [application/zip; charset=binary, 1140d056-aca8-4f3e-b790-836725cb028f, SPD_BEATS_WGS84.kmz, 223173]        | Current          | KMZ file for Seattle Police Department (most current) - 2015-Present beat boundaries  | 
```