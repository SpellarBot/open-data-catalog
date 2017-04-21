# Dataset for Oregon Libraries Map - Fall 2016

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dataset-for-oregon-libraries-map-fall-2016) |
| Metadata | [Link](https://data.oregon.gov/api/views/wzga-5zdi) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/wzga-5zdi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/wzga-5zdi/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | wzga-5zdi |
| Name | Dataset for Oregon Libraries Map - Fall 2016 |
| Attribution | Oregon State Library |
| Tags | library, libraries |
| Created | 2016-12-02T19:47:29Z |
| Publication Date | 2016-12-02T19:58:27Z |

## Description

Data used to create map of libraries in Oregon.

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type | Render Type |
| ======== | =========== | ========================= | ========================= | ========= | =========== |
| Yes      | series tag  | library_full_name         | Library Full Name         | text      | text        |
| Yes      | series tag  | library_name              | Library Name              | text      | text        |
| Yes      | series tag  | branch_name               | Branch Name               | text      | text        |
| Yes      | series tag  | county                    | County                    | text      | text        |
| Yes      | series tag  | zip_code                  | Zip Code                  | text      | text        |
| Yes      | series tag  | type_of_library           | Type of Library           | text      | text        |
| No       |             | mailing_address           | Mailing Address           | text      | text        |
| Yes      | series tag  | mailing_city              | Mailing City              | text      | text        |
| Yes      | series tag  | mailing_county            | Mailing County            | text      | text        |
| Yes      | series tag  | mailing_state             | Mailing State             | text      | text        |
| Yes      | series tag  | mailing_zip_code          | Mailing Zip Code          | text      | text        |
| Yes      | series tag  | phone_number              | Phone Number              | text      | text        |
| Yes      | series tag  | fax_number                | FAX Number                | text      | text        |
| Yes      | series tag  | website                   | Website                   | text      | text        |
| Yes      | series tag  | library_system_membership | Library System Membership | text      | text        |
| Yes      | series tag  | director_s_first_name     | Director's First Name     | text      | text        |
| Yes      | series tag  | director_s_last_name      | Director's Last Name      | text      | text        |
| Yes      | series tag  | director_s_phone_number   | Director's Phone Number   | text      | text        |
| Yes      | series tag  | director_s_email_address  | Director's Email Address  | text      | text        |
```

## Time Field

```ls
Value = 2016
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:wzga-5zdi d:2016-01-01T00:00:00.000Z t:library_name="Dayville City Library" t:director_s_last_name=Bogardus t:phone_number="(541) 987-2188" t:zip_code=97825 t:county=Grant t:mailing_state=OR t:director_s_first_name=Rebecca t:mailing_city=Dayville t:library_full_name="Dayville City Library" t:mailing_county=Grant t:type_of_library=Volunteer t:mailing_zip_code=97825 m:row_number.wzga-5zdi=1

series e:wzga-5zdi d:2016-01-01T00:00:00.000Z t:library_name="Mount Angel Abbey" t:fax_number=503-845-3500 t:director_s_last_name=Ertalt t:phone_number=503-845-3102 t:zip_code=97373-9999 t:website=http://www.mountangelabbey.org/library t:director_s_first_name=Victoria t:director_s_email_address=victoria.ertelt@mtangel.edu t:library_full_name="Mount Angel Abbey" t:type_of_library=Academic m:row_number.wzga-5zdi=2

series e:wzga-5zdi d:2016-01-01T00:00:00.000Z t:library_name="Eastern Oregon University" t:fax_number=541-962-3335 t:director_s_last_name=Clay t:phone_number=541-962-3540 t:zip_code=97850-2899 t:website=http://pierce.eou.edu t:director_s_first_name=Karen t:director_s_email_address=kclay@eou.edu t:library_full_name="Eastern Oregon University" t:director_s_phone_number=541-962-3792 t:type_of_library=Academic m:row_number.wzga-5zdi=3
```

## Meta Commands

```ls
metric m:row_number.wzga-5zdi p:long l:"Row Number"

entity e:wzga-5zdi l:"Dataset for Oregon Libraries Map - Fall 2016" t:attribution="Oregon State Library" t:url=https://data.oregon.gov/api/views/wzga-5zdi

property e:wzga-5zdi t:meta.view v:id=wzga-5zdi v:attributionLink=http://www.oregon.gov/osl/LD/Pages/directories.aspx v:averageRating=0 v:name="Dataset for Oregon Libraries Map - Fall 2016" v:attribution="Oregon State Library"

property e:wzga-5zdi t:meta.view.owner v:id=fgk3-ipqb v:profileImageUrlMedium=/api/users/fgk3-ipqb/profile_images/THUMB v:profileImageUrlLarge=/api/users/fgk3-ipqb/profile_images/LARGE v:screenName="Darci Hanning" v:profileImageUrlSmall=/api/users/fgk3-ipqb/profile_images/TINY v:displayName="Darci Hanning"

property e:wzga-5zdi t:meta.view.tableauthor v:id=fgk3-ipqb v:profileImageUrlMedium=/api/users/fgk3-ipqb/profile_images/THUMB v:profileImageUrlLarge=/api/users/fgk3-ipqb/profile_images/LARGE v:screenName="Darci Hanning" v:profileImageUrlSmall=/api/users/fgk3-ipqb/profile_images/TINY v:roleName=editor v:displayName="Darci Hanning"
```

## Top Records

```ls
| library_full_name                                         | library_name                    | branch_name                       | county     | zip_code   | type_of_library | mailing_address                         | mailing_city | mailing_county | mailing_state | mailing_zip_code | phone_number          | fax_number     | website                                | library_system_membership | director_s_first_name | director_s_last_name | director_s_phone_number | director_s_email_address    | 
| ========================================================= | =============================== | ================================= | ========== | ========== | =============== | ======================================= | ============ | ============== | ============= | ================ | ===================== | ============== | ====================================== | ========================= | ===================== | ==================== | ======================= | =========================== | 
| Dayville City Library                                     | Dayville City Library           |                                   | Grant      | 97825      | Volunteer       | PO Box 321                              | Dayville     | Grant          | OR            | 97825            | (541) 987-2188        |                |                                        |                           | Rebecca               | Bogardus             |                         |                             | 
| Mount Angel Abbey                                         | Mount Angel Abbey               |                                   |            | 97373-9999 | Academic        |                                         |              |                |               |                  | 503-845-3102          | 503-845-3500   | http://www.mountangelabbey.org/library |                           | Victoria              | Ertalt               |                         | victoria.ertelt@mtangel.edu | 
| Eastern Oregon University                                 | Eastern Oregon University       |                                   |            | 97850-2899 | Academic        |                                         |              |                |               |                  | 541-962-3540          | 541-962-3335   | http://pierce.eou.edu                  |                           | Karen                 | Clay                 | 541-962-3792            | kclay@eou.edu               | 
| Jackson County Library Services -Gold Hill Branch Library | Jackson County Library Services | Gold Hill Branch Library          | Jackson    | 97525      | Public          | PO Box 258                              | Gold Hill    | Jackson        |               | 97525            | (541) 855-1994        | (541) 855-1994 | http://www.jcls.org                    | NONE                      | Cindy                 | Oldfield             | (541) 855-1994          | coldfield@jcls.org          | 
| Klamath County Library -Gilchrist Branch Library          | Klamath County Library          | Gilchrist Branch Library          | Klamath    | 97737      | Public          |                                         |              |                |               |                  | (541) 433-2186        | (541) 433-2186 | http://www.klamathlibrary.org          | NONE                      | Christy               | Davis                | (541) 882-8894 ext 23   | cdavis@klamathlibrary.org   | 
| University Of Oregon -Pine Mountain Observatory Library   | University Of Oregon            | Pine Mountain Observatory Library |            | 97701      | Academic        |                                         |              |                |               |                  | 541-382-8331          |                |                                        |                           |                       |                      |                         |                             | 
| Wallowa County Library -Imnaha Station Library            | Wallowa County Library          | Imnaha Station Library            | Wallowa    | 97842      | Public          |                                         |              |                |               |                  | (541) 577-2308        |                |                                        | NONE                      | Keith                 | Kirts                | (541) 577-2308          | imnahalib@gmail.com         | 
| Wallowa County Library -Troy Station Library              | Wallowa County Library          | Troy Station Library              | Wallowa    | 97828      | Public          |                                         |              |                |               |                  | (541) 828-7788        |                |                                        | NONE                      | Curry                 | Jane                 | (541) 828-7788          |                             | 
| Lake County Library -Paisley Branch Library               | Lake County Library             | Paisley Branch Library            | Lake       | 97636      | Public          | PO Box 99                               | Paisley      | Lake           |               | 97636            | (541) 943-3911        |                | http://www.lakecountylibrary.org/      | NONE                      | Amy                   | Hutchinson           | 541-947-6019            | amyh@lakecountylibrary.org  | 
| Beaverton City Library -Murray Scholls                    | Beaverton City Library          | Murray Scholls                    | Washington | 97007-9702 | Public          | 11200 SW Murray Scholls Place Suite 102 | Beaverton    | Washington     | OR            | 97007-9702       | 503-644-2197 option 6 | (503) 350-3645 | http://www.beavertonlibrary.org        | WCCLS                     | Abigail               | Elder                | (503) 526-3705          | aelder@beavertonoregon.gov  | 
```