# Hospitals in Hawaii

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospitals-in-hawaii-51a75) |
| Metadata | [Link](https://data.hawaii.gov/api/views/rwns-g4bn) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/rwns-g4bn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/rwns-g4bn/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | rwns-g4bn |
| Name | Hospitals in Hawaii |
| Attribution | Department of Health |
| Category | Health |
| Tags | hospital |
| Created | 2012-08-26T21:07:30Z |
| Publication Date | 2012-08-28T00:51:32Z |

## Description

Department of Health Hospitals listing

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | services    | Services   | text      | text        |
| Yes      | series tag  | house       | House      | text      | text        |
| Yes      | series tag  | zip_code    | Zip code   | text      | text        |
| Yes      | series tag  | island      | Island     | text      | text        |
| Yes      | series tag  | phone       | PHONE      | text      | text        |
| Yes      | series tag  | map_icon    | Map icon   | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:rwns-g4bn d:2012-08-27T17:29:05.000Z t:phone=263-5500 t:services="Licensed Beds & Psychiatric Beds" t:zip_code=96734 t:name="CASTLE MEDICAL CENTER" t:house=640 t:map_icon=OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw t:island=Oahu m:row_number.rwns-g4bn=1

series e:rwns-g4bn d:2012-08-27T17:41:03.000Z t:phone=247-2191 t:services="Psychiatric Beds" t:zip_code=96744 t:name="HAWAII STATE HOSPITAL" t:house=45-710 t:map_icon=OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw t:island=Oahu m:row_number.rwns-g4bn=2

series e:rwns-g4bn d:2012-08-27T17:39:54.000Z t:phone=775-7211 t:services="Licensed Beds" t:zip_code=96727 t:name="HALE HO'OLA HAMAKUA" t:house=45-547 t:map_icon=OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw t:island=Hawaii m:row_number.rwns-g4bn=3
```

## Meta Commands

```ls
metric m:row_number.rwns-g4bn p:long l:"Row Number"

entity e:rwns-g4bn l:"Hospitals in Hawaii" t:attribution="Department of Health" t:url=https://data.hawaii.gov/api/views/rwns-g4bn

property e:rwns-g4bn t:meta.view v:id=rwns-g4bn v:category=Health v:attributionLink=http://hawaii.gov/health v:averageRating=0 v:name="Hospitals in Hawaii" v:attribution="Department of Health"

property e:rwns-g4bn t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:rwns-g4bn t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:rwns-g4bn t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | name                                            | services                         | house   | zip_code | island | phone    | map_icon                                    | 
| =========== | =============================================== | ================================ | ======= | ======== | ====== | ======== | =========================================== | 
| 1346088545  | CASTLE MEDICAL CENTER                           | Licensed Beds & Psychiatric Beds | 640     | 96734    | Oahu   | 263-5500 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089263  | HAWAII STATE HOSPITAL                           | Psychiatric Beds                 | 45-710  | 96744    | Oahu   | 247-2191 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089194  | HALE HO'OLA HAMAKUA                             | Licensed Beds                    | 45-547  | 96727    | Hawaii | 775-7211 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089417  | KAHI MOHALA                                     | Psychiatric Beds                 | 91-2301 | 96706    | Oahu   | 671-8511 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089446  | KAHUKU MEDICAL CENTER                           | Licensed Beds                    | 56-117  | 96731    | Oahu   | 293-9221 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089475  | KAISER FOUNDATION HOSPITAL                      | Licensed Beds                    | 3288    | 96819    | Oahu   | 432-0000 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089493  | KAPIOLANI MEDICAL CENTER for WOMEN and CHILDREN | Licensed Beds                    | 1319    | 96826    | Oahu   | 983-6000 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089518  | KAU HOSPITAL                                    | Licensed Beds                    | 1       | 96777    | Hawaii | 928-2050 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089566  | KOHALA HOSPITAL                                 | Licensed Beds                    | 54-383  | 96755    | Hawaii | 889-6211 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
| 1346089590  | KONA COMMUNITY HOSPITAL                         | Licensed Beds                    | 79-1019 | 96750    | Hawaii | 322-9311 | OrTuFnwJTBz2hv0ooCNGiWjrlvLjp5ks4zudY_z3xbw | 
```