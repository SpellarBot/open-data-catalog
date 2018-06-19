# DHHL Revocable Permits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dhhl-revocable-permits-fdad1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/j5dq-nmjy) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/j5dq-nmjy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/j5dq-nmjy/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | j5dq-nmjy |
| Name | DHHL Revocable Permits |
| Attribution | DHHL |
| Category | Economic Development |
| Tags | dhhl, recovable permits, hawaiian home lands |
| Created | 2012-07-11T21:39:12Z |
| Publication Date | 2012-09-05T19:22:01Z |

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type     | Render Type   |
| ======== | ============== | ============== | ============== | ============= | ============= |
| Yes      | series tag     | island         | Island         | text          | text          |
| Yes      | numeric metric | acreage        | Acreage        | number        | text          |
| No       |                | no             | No.            | text          | text          |
| Yes      | series tag     | use_zoning     | Use/Zoning     | text          | text          |
| Yes      | series tag     | permittee      | Permittee      | text          | text          |
| Yes      | series tag     | location       | Location       | text          | text          |
| Yes      | series tag     | tmk_number     | TMK Number     | text          | text          |
| Yes      | time           | date_issued    | Date Issued    | calendar_date | calendar_date |
| Yes      | series tag     | current_annual | Current Annual | text          | text          |
| Yes      | series tag     | comments       | Comments       | text          | text          |
```

## Time Field

```ls
Value = date_issued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = no
```

## Data Commands

```ls
series e:j5dq-nmjy d:1995-05-01T00:00:00.000Z t:permittee="Molokai Homestead Livestock Association" t:tmk_number="(2) 5-2-010:001(P), 5-4-003:003" t:current_annual=$240.00 t:location=Kalamaula t:use_zoning=Pasture t:island=Molokai m:acreage=9370

series e:j5dq-nmjy d:1998-02-09T00:00:00.000Z t:permittee="Gilbert Medeiros, Sr. & Gilbert Medeiros Jr." t:tmk_number="(3) 9-3-001:002 (P)" t:current_annual=$504.00 t:location=Kamaoa-Puueo t:use_zoning=Pasture t:island=Hawaii m:acreage=280

series e:j5dq-nmjy d:2004-10-01T00:00:00.000Z t:permittee="Winifred Pele Hanoa and Pernell E. Hanoa" t:tmk_number="(3) 9-5-019:016" t:current_annual=$1,488.00 t:location=Wailau t:use_zoning=Pasture t:island=Hawaii m:acreage=326.76
```

## Meta Commands

```ls
metric m:acreage p:integer l:Acreage t:dataTypeName=number

entity e:j5dq-nmjy l:"DHHL Revocable Permits" t:attribution=DHHL t:url=https://data.hawaii.gov/api/views/j5dq-nmjy

property e:j5dq-nmjy t:meta.view v:id=j5dq-nmjy v:category="Economic Development" v:averageRating=0 v:name="DHHL Revocable Permits" v:attribution=DHHL

property e:j5dq-nmjy t:meta.view.license v:name="Creative Commons Attribution | Share Alike 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-sa/3.0/legalcode v:logoUrl=images/licenses/cc30bysa.png

property e:j5dq-nmjy t:meta.view.owner v:id=an38-krt2 v:screenName="Linda Inouye" v:displayName="Linda Inouye"

property e:j5dq-nmjy t:meta.view.tableauthor v:id=an38-krt2 v:screenName="Linda Inouye" v:roleName=editor v:displayName="Linda Inouye"
```

## Top Records

```ls
| island  | acreage | no  | use_zoning      | permittee                                    | location     | tmk_number                      | date_issued         | current_annual | comments | 
| ======= | ======= | === | =============== | ============================================ | ============ | =============================== | =================== | ============== | ======== | 
| Hawaii  |         |     | Pending w/KA    | Carbon Division, Inc.                        | Kalaoa       | (3) 7-3-010:040 (P)             |                     | $58,800.00     |          | 
| Molokai | 9370    | 178 | Pasture         | Molokai Homestead Livestock Association      | Kalamaula    | (2) 5-2-010:001(P), 5-4-003:003 | 1995-05-01T00:00:00 | $240.00        |          | 
| Hawaii  | 280     | 212 | Pasture         | Gilbert Medeiros, Sr. & Gilbert Medeiros Jr. | Kamaoa-Puueo | (3) 9-3-001:002 (P)             | 1998-02-09T00:00:00 | $504.00        |          | 
| Hawaii  | 326.76  | 231 | Pasture         | Winifred Pele Hanoa and Pernell E. Hanoa     | Wailau       | (3) 9-5-019:016                 | 2004-10-01T00:00:00 | $1,488.00      |          | 
| Hawaii  | 100     | 241 | Pasture         | George Pua, Sr.                              | Olaa         | (3) 1-8-011:012                 | 2000-08-01T00:00:00 | $660.00        |          | 
| Hawaii  | 0.077   | 243 | Water Tank Site | Hokuloa, Inc.                                | Kawaihae     | (3) 6-1-006:007 (P)             | 2000-09-01T00:00:00 | $240.00        |          | 
| Hawaii  | 450     | 244 | Pasture         | Daryl K. Kalua'u                             | Kau          | (3) 9-3-001:002(P)              | 2000-11-01T00:00:00 | $840.00        |          | 
| Hawaii  | 750     | 253 | Pasture         | Daleico Ranch c/o Francis Hind               | Kau          | (3) 9-3-001:002 (P)             | 2001-06-01T00:00:00 | $1,536.00      |          | 
| Kauai   | 45.023  | 256 | Pasture         | William J., Sr. and Alison Sanchez           | Wailua       | (4) 3-9-002:003                 | 2001-06-15T00:00:00 | $2,136.00      |          | 
| Hawaii  |         | 280 | Parking         | Robert Pacheco                               | Humuula      | (3) 3-8-001:007 (P)             | 2003-03-01T00:00:00 | $0.00          |          | 
```