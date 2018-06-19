# Veterinarian Hospitals Licensed for 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/veterinarian-hospitals-licensed-for-2014-62689) |
| Metadata | [Link](https://data.maryland.gov/api/views/cnpw-2a6b) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/cnpw-2a6b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/cnpw-2a6b/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | cnpw-2a6b |
| Name | Veterinarian Hospitals Licensed for 2014 |
| Attribution | MD Department of Agriculture |
| Category | Agriculture |
| Tags | animal, dog, cat, veterinarian hospital |
| Created | 2013-08-12T14:48:40Z |
| Publication Date | 2013-08-12T15:22:52Z |

## Description

Licensed veterinarian hospitals in Maryland

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type | Render Type |
| ======== | =========== | ============== | ============== | ========= | =========== |
| Yes      | series tag  | county         | COUNTY         | text      | text        |
| Yes      | series tag  | license_no     | LICENSE NO     | text      | text        |
| Yes      | series tag  | hospital_name  | HOSPITAL NAME  | text      | text        |
| Yes      | series tag  | hospital_owner | HOSPITAL OWNER | text      | text        |
| Yes      | series tag  | phone_number   | PHONE NUMBER   | phone     | phone       |
| Yes      | series tag  | fax_number     | FAX NUMBER     | phone     | phone       |
| No       |             | er             | ER             | text      | text        |
| Yes      | series tag  | after_hours    | AFTER HOURS    | text      | text        |
| Yes      | series tag  | hours          | HOURS          | text      | text        |
| Yes      | series tag  | mobile         | MOBILE         | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = er
```

## Data Commands

```ls
series e:cnpw-2a6b d:2014-01-01T00:00:00.000Z t:hospital_owner="DRS. THOMAS L. LOMAX & ELLEN CIANELLI" t:hospital_name="FESTIVAL BEL AIR VETERINARY CLINIC" t:license_no=12-017 t:phone_number=4105159738 t:county=HARFORD t:hours="8-8- m - f  8-1- sat" m:row_number.cnpw-2a6b=1

series e:cnpw-2a6b d:2014-01-01T00:00:00.000Z t:hospital_owner="ELLEN M. COLEWELL, DVM" t:hospital_name="THE SYKESVILLE VETERINARY CLINIC" t:license_no=06-023 t:phone_number=4105490314 t:county=CARROLL t:hours="MON. TUES., THURS., FRI. 7:30 A.M. - 6:30 P.M.
WED. 7:30 A.M. - 4:00 P.M.
SAT. 7:30 - 12:30" m:row_number.cnpw-2a6b=2

series e:cnpw-2a6b d:2014-01-01T00:00:00.000Z t:hospital_owner="VET COR OF CHESAPEAKE, LLC" t:hospital_name="CHESAPEAKE ANIMAL CLINIC (DBA)" t:license_no=04-003 t:phone_number=3018553181 t:county=CALVERT t:hours="MON. - FRI. 8:00 A.M. - 8:00 P.M.
SAT. 8:00 A.M. - 2:00 P.M." m:row_number.cnpw-2a6b=3
```

## Meta Commands

```ls
metric m:row_number.cnpw-2a6b p:long l:"Row Number"

entity e:cnpw-2a6b l:"Veterinarian Hospitals Licensed for 2014" t:attribution="MD Department of Agriculture" t:url=https://data.maryland.gov/api/views/cnpw-2a6b

property e:cnpw-2a6b t:meta.view v:id=cnpw-2a6b v:category=Agriculture v:attributionLink=http://www.mda.maryland.gov v:averageRating=0 v:name="Veterinarian Hospitals Licensed for 2014" v:attribution="MD Department of Agriculture"

property e:cnpw-2a6b t:meta.view.owner v:id=tpc4-inqc v:screenName="Lisa Stollof" v:displayName="Lisa Stollof"

property e:cnpw-2a6b t:meta.view.tableauthor v:id=tpc4-inqc v:screenName="Lisa Stollof" v:roleName=editor v:displayName="Lisa Stollof"
```

## Top Records

```ls
| county        | license_no | hospital_name                       | hospital_owner                        | phone_number       | fax_number         | er | after_hours | hours                                                                                          | mobile | 
| ============= | ========== | =================================== | ===================================== | ================== | ================== | == | =========== | ============================================================================================== | ====== | 
| HARFORD       | 12-017     | FESTIVAL BEL AIR VETERINARY CLINIC  | DRS. THOMAS L. LOMAX & ELLEN CIANELLI | [4105697387, null] | [4105159738, null] |    |             | 8-8- m - f 8-1- sat                                                                            |        | 
| CARROLL       | 06-023     | THE SYKESVILLE VETERINARY CLINIC    | ELLEN M. COLEWELL, DVM                | [4105497798, null] | [4105490314, null] |    |             | MON. TUES., THURS., FRI. 7:30 A.M. - 6:30 P.M. WED. 7:30 A.M. - 4:00 P.M. SAT. 7:30 - 12:30    |        | 
| CALVERT       | 04-003     | CHESAPEAKE ANIMAL CLINIC (DBA)      | VET COR OF CHESAPEAKE, LLC            | [3018555166, null] | [3018553181, null] |    |             | MON. - FRI. 8:00 A.M. - 8:00 P.M. SAT. 8:00 A.M. - 2:00 P.M.                                   |        | 
| MONTGOMERY    | 15-075     | FOUR COUNTY ANIMAL HOSPITAL         | DAVID I. GOODMAN, D.V.M.              | [3012536144, null] | [3012532690, null] |    |             | MON. - THURS. 8:00 A.M. - 7:00 P.M. FRI. 8:00 A.M. - 6:00 P.M. SAT. 8:00 A.M. - 11:00 A.M.     |        | 
| CARROLL       | 06-026     | NORTH CARROLL VETERINARY SERVICE    | KAY I. WAGNER, DVM                    | [4102393713, null] | [4103740657, null] |    | Y           | MON. - FRI. 8A.M. TO 6P.M. SAT. 8-12                                                           |        | 
| HARFORD       | 12-030     | SWAN CREEK VETERINARY CLINIC        | DANIEL HOPKINS, DVM                   | [4109399500, null] | [4109399554, null] |    |             | MON. - THURS. 7:30 A.M. - 6:00 P.M. FRI. 7:30 A.M. - 5:00 P.M. SAT. 8:00 A.M. - NOON           |        | 
| MONTGOMERY    | 15-070     | GERMANTOWN VETERINARY CLINIC, LLC   | LUCY C. TIDD, D.V.M.                  | [3019729730, null] | [3015404816, null] |    | Y           | MONDAY-THURSDAY 8AM-7PM FRIDAY 8AM-6PM, SATURDAY 8AM-2PM                                       |        | 
| HARFORD       | 12-006     | CHURCHVILLE VETERINARY CLINIC, INC. | PAULA WINTERS-BUECHLER, DVM           | [4108380085, null] | [4108386587, null] |    |             | MON. - THURS. 7:30 A.M. - 6:00 P.M. FRI. 8:00 A.M. - 5:00 P.M. SAT. 8:00 A.M. - NOON           |        | 
| BALTIMORE CO. | 03-046     | LUTHERVILLE ANIMAL HOSPITAL         | KENNETH W. VOLK, JR., VMD             | [4102967387, null] | [4102961931, null] |    |             | MON., TUES., WED. 8:00 A.M. - 8:00 .M. THURS., FRI. 8:00 A.M. - 7:00 .M. SAT. 8:00 - 2:00 P.M. |        | 
| BALTIMORE CO. | 03-085     | CATONSVILLE ANIMAL HOSPITAL         | LAWRENCE BLANKEN, D.V.M.              | [4107192445, null] | [4107198937, null] |    |             | MON. - FRI. 8:30 A.M. - 6:30 P.M. SAT. 9:00 A.M. - 12:00 A.M.                                  |        | 
```