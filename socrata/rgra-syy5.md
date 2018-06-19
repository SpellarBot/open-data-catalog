# 2015 Candidate Sites - We'll Sample 50

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-candidate-sites-well-sample-50) |
| Metadata | [Link](https://data.wa.gov/api/views/rgra-syy5) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/rgra-syy5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/rgra-syy5/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | rgra-syy5 |
| Name | 2015 Candidate Sites - We'll Sample 50 |
| Attribution | Department of Ecology |
| Created | 2015-01-30T20:19:49Z |
| Publication Date | 2015-01-30T20:22:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | site_id               | SITE_ID               | text      | text        |
| Yes      | series tag     | stream_channel        | STREAM CHANNEL        | text      | text        |
| Yes      | series tag     | sample_sequence       | SAMPLE SEQUENCE       | text      | text        |
| Yes      | series tag     | sequence_group        | SEQUENCE GROUP        | text      | text        |
| Yes      | numeric metric | revised_strahler      | REVISED STRAHLER      | number    | number      |
| Yes      | series tag     | publicorprivate       | PUBLICorPRIVATE       | text      | text        |
| Yes      | series tag     | conservation_district | CONSERVATION DISTRICT | text      | text        |
| Yes      | series tag     | county                | COUNTY                | text      | text        |
| Yes      | series tag     | section               | Section               | text      | text        |
```

## Time Field

```ls
Value = 2015
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rgra-syy5 d:2015-01-01T00:00:00.000Z t:publicorprivate=Public t:sample_sequence="OLD_SIZE 0_SEQUENCE_01" t:sequence_group="ORIGINAL PICK" t:county="Yakima Co" t:conservation_district="South Yakima" t:site_id=WAM06600-012453 t:section=08N.23E.12 t:stream_channel="YAKIMA RIVER TRIBUTARY" m:revised_strahler=0

series e:rgra-syy5 d:2015-01-01T00:00:00.000Z t:publicorprivate=Public t:sample_sequence="OLD_SIZE 0_SEQUENCE_02" t:sequence_group="ORIGINAL PICK" t:county="Kittitas Co" t:conservation_district="Kittitas County" t:site_id=WAM06600-034366 t:section=20N.13E.30 t:stream_channel="LOG CREEK TRIBUTARY" m:revised_strahler=0

series e:rgra-syy5 d:2015-01-01T00:00:00.000Z t:publicorprivate=Public t:sample_sequence="OLD_SIZE 0_SEQUENCE_03" t:sequence_group="ORIGINAL PICK" t:county="Yakima Co" t:conservation_district="South Yakima" t:site_id=WAM06600-034965 t:section=09N.22E.21 t:stream_channel="YAKIMA RIVER TRIBUTARY" m:revised_strahler=0
```

## Meta Commands

```ls
metric m:revised_strahler p:integer l:"REVISED STRAHLER" t:dataTypeName=number

entity e:rgra-syy5 l:"2015 Candidate Sites - We'll Sample 50" t:attribution="Department of Ecology" t:url=https://data.wa.gov/api/views/rgra-syy5

property e:rgra-syy5 t:meta.view v:id=rgra-syy5 v:attributionLink=http://tinyurl.com/WatershedHealth v:averageRating=0 v:name="2015 Candidate Sites - We'll Sample 50" v:attribution="Department of Ecology"

property e:rgra-syy5 t:meta.view.owner v:id=h9w5-qfr2 v:profileImageUrlMedium=/api/users/h9w5-qfr2/profile_images/THUMB v:profileImageUrlLarge=/api/users/h9w5-qfr2/profile_images/LARGE v:screenName=glenn.merritt@ecy.wa.gov v:profileImageUrlSmall=/api/users/h9w5-qfr2/profile_images/TINY v:displayName=glenn.merritt@ecy.wa.gov

property e:rgra-syy5 t:meta.view.tableauthor v:id=h9w5-qfr2 v:profileImageUrlMedium=/api/users/h9w5-qfr2/profile_images/THUMB v:profileImageUrlLarge=/api/users/h9w5-qfr2/profile_images/LARGE v:screenName=glenn.merritt@ecy.wa.gov v:profileImageUrlSmall=/api/users/h9w5-qfr2/profile_images/TINY v:roleName=publisher v:displayName=glenn.merritt@ecy.wa.gov
```

## Top Records

```ls
| site_id         | stream_channel          | sample_sequence        | sequence_group | revised_strahler | publicorprivate | conservation_district | county      | section    | 
| =============== | ======================= | ====================== | ============== | ================ | =============== | ===================== | =========== | ========== | 
| WAM06600-012453 | YAKIMA RIVER TRIBUTARY  | OLD_SIZE 0_SEQUENCE_01 | ORIGINAL PICK  | 0                | Public          | South Yakima          | Yakima Co   | 08N.23E.12 | 
| WAM06600-034366 | LOG CREEK TRIBUTARY     | OLD_SIZE 0_SEQUENCE_02 | ORIGINAL PICK  | 0                | Public          | Kittitas County       | Kittitas Co | 20N.13E.30 | 
| WAM06600-034965 | YAKIMA RIVER TRIBUTARY  | OLD_SIZE 0_SEQUENCE_03 | ORIGINAL PICK  | 0                | Public          | South Yakima          | Yakima Co   | 09N.22E.21 | 
| WAM06600-037710 | COOKE CREEK TRIBUTARY   | OLD_SIZE 0_SEQUENCE_04 | ORIGINAL PICK  | 0                | Public          | Kittitas County       | Kittitas Co | 19N.20E.10 | 
| WAM06600-038094 | COLEMAN CREEK TRIBUTARY | OLD_SIZE 0_SEQUENCE_05 | ORIGINAL PICK  | 0                | Public          | Kittitas County       | Kittitas Co | 20N.20E.17 | 
| WAM06600-040922 | YAKIMA RIVER TRIBUTARY  | OLD_SIZE 0_SEQUENCE_06 | SPARE          | 0                | Private         | Kittitas County       | Kittitas Co | 17N.18E.09 | 
| WAM06600-000942 | BEAR CREEK              | OLD_SIZE 1_SEQUENCE_01 | ORIGINAL PICK  | 1                | Private         | Kittitas County       | Kittitas Co | 21N.14E.27 | 
| WAM06600-003734 | WATERING TROUGH         | OLD_SIZE 1_SEQUENCE_02 | ORIGINAL PICK  | 1                | Public          | North Yakima          | Yakima Co   | 15N.16E.11 | 
| WAM06600-004334 | PEARSON CREEK TRIBUTARY | OLD_SIZE 1_SEQUENCE_03 | ORIGINAL PICK  | 1                | Public          | Kittitas County       | Kittitas Co | 21N.19E.28 | 
| WAM06600-004981 | SPRING CREEK TRIBUTARY  | OLD_SIZE 1_SEQUENCE_04 | ORIGINAL PICK  | 1                | Private         | Benton                | Benton Co   | 09N.25E.19 | 
```