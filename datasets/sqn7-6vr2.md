# IDPH Migrant Labor Camps

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-migrant-labor-camps-3c0c8) |
| Metadata | [Link](https://data.illinois.gov/api/views/sqn7-6vr2) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/sqn7-6vr2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/sqn7-6vr2/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | sqn7-6vr2 |
| Name | IDPH Migrant Labor Camps |
| Attribution | Division of Environmental Health |
| Category | Public Health |
| Tags | migrant, labor, camp |
| Created | 2012-08-01T21:50:27Z |
| Publication Date | 2017-03-21T15:07:32Z |

## Description

Updated August 2016

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type     | Render Type   |
| ======== | ============== | ================ | ================ | ============= | ============= |
| Yes      | series tag     | facilty_name     | Facilty Name     | text          | text          |
| Yes      | numeric metric | occupancy        | Occupancy        | number        | number        |
| Yes      | time           | from             | From             | calendar_date | calendar_date |
| No       |                | to               | To               | calendar_date | calendar_date |
| No       |                | facility_address | Facility Address | text          | text          |
| Yes      | series tag     | facility_city    | Facility City    | text          | text          |
| Yes      | series tag     | facility_state   | Facility State   | text          | text          |
| Yes      | series tag     | facility_zip     | Facility Zip     | text          | number        |
| Yes      | series tag     | facility_phone   | Facility Phone   | text          | text          |
| Yes      | series tag     | facility_county  | Facility County  | text          | text          |
| Yes      | series tag     | company_name     | Company Name     | text          | text          |
| No       |                | company_address  | Company Address  | text          | text          |
| Yes      | series tag     | company_city     | Company City     | text          | text          |
| Yes      | series tag     | company_state    | Company State    | text          | text          |
| Yes      | series tag     | company_zip      | Company Zip      | text          | number        |
| Yes      | series tag     | company_phone    | Company Phone    | text          | text          |
```

## Time Field

```ls
Value = from
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = to,facility_address,company_address
```

## Data Commands

```ls
series e:sqn7-6vr2 d:2016-02-01T00:00:00.000Z t:facility_city=FREEBURG t:company_state=IL t:facilty_name="ECKERT'S LAKESIDE" t:company_name="ECKERT ORCHARDS INC" t:company_phone="(618) 233-0513" t:facility_zip=62243 t:facility_phone="(618) 233-0513" t:facility_county="ST. CLAIR" t:facility_state=IL t:company_zip=62220 t:company_city=BELLEVILLE m:occupancy=18

series e:sqn7-6vr2 d:2016-05-01T00:00:00.000Z t:facility_city="ALTO PASS" t:company_state=IL t:facilty_name="RENDLEMAN ORCHARDS" t:company_name="RENDLEMAN ORCHARDS" t:company_phone="(618) 893-2771" t:facility_zip=62905 t:facility_phone="(618) 893-2771" t:facility_county=UNION t:facility_state=IL t:company_zip=62905 t:company_city="ALTO PASS" m:occupancy=24

series e:sqn7-6vr2 d:2016-06-15T00:00:00.000Z t:facility_city=RANTOUL t:company_state=IL t:facilty_name="NIGHTENGALE CAMP" t:company_name="UNIQUE STORAGE, INC." t:company_phone="(217) 898-5983" t:facility_zip=61866 t:facility_phone="(216) 898-5983" t:facility_county=CHAMPAIGN t:facility_state=IL t:company_zip=61866 t:company_city=RANTOUL m:occupancy=450
```

## Meta Commands

```ls
metric m:occupancy p:integer l:Occupancy t:dataTypeName=number

entity e:sqn7-6vr2 l:"IDPH Migrant Labor Camps" t:attribution="Division of Environmental Health" t:url=https://data.illinois.gov/api/views/sqn7-6vr2

property e:sqn7-6vr2 t:meta.view v:id=sqn7-6vr2 v:category="Public Health" v:attributionLink=http://www.dph.illinois.gov/topics-services/environmental-health-protection/abatement-structures-migrant-labor/migrant-labor-camps-field-sanitation v:averageRating=0 v:name="IDPH Migrant Labor Camps" v:attribution="Division of Environmental Health"

property e:sqn7-6vr2 t:meta.view.license v:name="Public Domain"

property e:sqn7-6vr2 t:meta.view.owner v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:displayName="IDPH Staff"

property e:sqn7-6vr2 t:meta.view.tableauthor v:id=vice-rsdw v:profileImageUrlMedium=/api/users/vice-rsdw/profile_images/THUMB v:profileImageUrlLarge=/api/users/vice-rsdw/profile_images/LARGE v:screenName="IDPH Staff" v:profileImageUrlSmall=/api/users/vice-rsdw/profile_images/TINY v:roleName=publisher v:displayName="IDPH Staff"
```

## Top Records

```ls
| facilty_name                     | occupancy | from                | to                  | facility_address                      | facility_city | facility_state | facility_zip | facility_phone | facility_county | company_name              | company_address              | company_city | company_state | company_zip | company_phone  | 
| ================================ | ========= | =================== | =================== | ===================================== | ============= | ============== | ============ | ============== | =============== | ========================= | ============================ | ============ | ============= | =========== | ============== | 
| ECKERT'S LAKESIDE                | 18        | 2016-02-01T00:00:00 | 2016-12-15T00:00:00 | 1350 WHITE OAKS CLUB RD.              | FREEBURG      | IL             | 62243        | (618) 233-0513 | ST. CLAIR       | ECKERT ORCHARDS INC       | 951 S. GREEN MOUNT RD.       | BELLEVILLE   | IL            | 62220       | (618) 233-0513 | 
| RENDLEMAN ORCHARDS               | 24        | 2016-05-01T00:00:00 | 2016-10-30T00:00:00 | 9680 HWY. 127N, P.O. BOX 159          | ALTO PASS     | IL             | 62905        | (618) 893-2771 | UNION           | RENDLEMAN ORCHARDS        | 9680 HWY. 127N, P.O. BOX 159 | ALTO PASS    | IL            | 62905       | (618) 893-2771 | 
| NIGHTENGALE CAMP                 | 450       | 2016-06-15T00:00:00 | 2016-10-15T00:00:00 | 100 NIGHTENGALE                       | RANTOUL       | IL             | 61866        | (216) 898-5983 | CHAMPAIGN       | UNIQUE STORAGE, INC.      | 217 W. FROST                 | RANTOUL      | IL            | 61866       | (217) 898-5983 | 
| CAMP SPRINGFIELD                 | 198       | 2016-05-23T00:00:00 | 2016-10-31T00:00:00 | 301 & 333 MILTON                      | SPRINGFIELD   | IL             | 62704        |                | SANGAMON        | MONSANTO COMPANY          | 4370 MT. PULASKI RD. N.      | ILLIOPOLIS   | IL            | 62539       | (956) 212-8394 | 
| FREY BROTHERS - BARNHILL CAMP    | 26        | 2016-06-01T00:00:00 | 2016-11-30T00:00:00 | U.S. HWY. 45 S.                       | BARNHILL      | IL             | 62809        |                | WAYNE           | FREY BROTHERS             | 111 COUNTY HWY. 15, SUITE A  | KEENES       | IL            | 62851       | (618) 835-2536 | 
| FREY BROTHERS - OAK GROVE SCHOOL | 68        | 2016-06-01T00:00:00 | 2016-11-10T00:00:00 | HWY 242 ON C.R. 100N                  | KEENES        | IL             | 62851        | (618) 648-2457 | WAYNE           | FREY BROTHERS             | 111 COUNTY HWY. 15, SUITE A  | KEENES       | IL            | 62851       | (618) 835-2536 | 
| J&S AGRICULTURE                  | 40        | 2016-06-01T00:00:00 | 2016-08-01T00:00:00 | VARIOUS ADDRESSES                     | GEORGETOWN    | IL             | 61846        | (217) 918-4428 | VERMILLION      | J&S AGRICULTURE           | 415 PANOLA                   | GEORGETOWN   | IL            | 61846       | (217) 918-4428 | 
| Young America - Jackson Citrus   | 80        | 2016-06-01T00:00:00 | 2016-08-20T00:00:00 | 801 S. University (various locations) | Normal        | IL             | 61761        | (309) 454-2338 | McLean          | Young America Realty      | 311 S. Main St.              | Normal       | IL            | 61761       | (309) 454-2338 | 
| YOUNG AMERICA - BECK'S HYBRIDS   | 225       | 2016-06-01T00:00:00 | 2016-08-20T00:00:00 | 801 S. UNIVERSITY                     | NORMAL        | IL             | 61761        | (309) 454-2338 | McLEAN          | YOUNG AMERICA REALTY      | 311 S. MAIN ST.              | NORMAL       | IL            | 61761       | (309) 454-2338 | 
| ECHO VALLEY                      | 40        | 2016-04-11T00:00:00 | 2016-10-20T00:00:00 | 144 PEACH RD.                         | CARBONDALE    | IL             | 62903        | (618) 684-2471 | JACKSON         | JOAS TROYER / LEROY YODER | 144 PEACH RD.                | CARBONDALE   | IL            | 62903       | (618) 684-3979 | 
```