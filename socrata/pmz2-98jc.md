# Licensed Vetrinarians Statewide

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-vetrinarians-statewide-77887) |
| Metadata | [Link](https://data.maryland.gov/api/views/pmz2-98jc) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/pmz2-98jc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/pmz2-98jc/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | pmz2-98jc |
| Name | Licensed Vetrinarians Statewide |
| Category | Agriculture |
| Tags | veterinarians |
| Created | 2014-11-07T15:57:19Z |
| Publication Date | 2014-11-07T16:08:05Z |

## Description

The data set shows all licensed veterinarians in maryland for FY 2015 as of 11/07/2014. Data are provided by MDA.

## Columns

```ls
| Included | Schema Type | Field Name                | Name            | Data Type | Render Type |
| ======== | =========== | ========================= | =============== | ========= | =========== |
| Yes      | series tag  | county                    | BUSINESS COUNTY | text      | text        |
| Yes      | series tag  | contact_fname_contact_lna | CONTACT NAME    | text      | text        |
| Yes      | time        | lic_date                  | LICENSE DATE    | date      | date        |
| Yes      | series tag  | lic_no                    | LICENSE NUMBER  | text      | text        |
| Yes      | series tag  | contact_bus_addr1_contact | LOCATION        | text      | text        |
| Yes      | series tag  | bus_phone                 | BUSINESS PHONE  | phone     | phone       |
```

## Time Field

```ls
Value = lic_date
Format & Zone = seconds
```

## Data Commands

```ls
series e:pmz2-98jc d:2002-07-18T07:00:00.000Z t:contact_fname_contact_lna="EARL ANNABLE" t:county=WORCESTER t:lic_no=5488 m:row_number.pmz2-98jc=1

series e:pmz2-98jc d:2012-05-31T07:00:00.000Z t:contact_fname_contact_lna="SAMANTHA SWISHER" t:county="OUT OF STATE" t:contact_bus_addr1_contact="RALEIGH  NC 27606" t:lic_no=6935 m:row_number.pmz2-98jc=2

series e:pmz2-98jc d:1963-06-04T07:00:00.000Z t:contact_fname_contact_lna="NEIL CORSELIUS" t:county=FREDERICK t:contact_bus_addr1_contact="2420 MONOCACY BLVD.   FREDERICK  MD 21701" t:lic_no=1112 m:row_number.pmz2-98jc=3
```

## Meta Commands

```ls
metric m:row_number.pmz2-98jc p:long l:"Row Number"

entity e:pmz2-98jc l:"Licensed Vetrinarians Statewide" t:url=https://data.maryland.gov/api/views/pmz2-98jc

property e:pmz2-98jc t:meta.view v:id=pmz2-98jc v:category=Agriculture v:averageRating=0 v:name="Licensed Vetrinarians Statewide"

property e:pmz2-98jc t:meta.view.owner v:id=5i5x-vf5f v:screenName=teachoaa v:displayName=teachoaa

property e:pmz2-98jc t:meta.view.tableauthor v:id=5i5x-vf5f v:screenName=teachoaa v:roleName=editor v:displayName=teachoaa
```

## Top Records

```ls
| county       | contact_fname_contact_lna | lic_date   | lic_no | contact_bus_addr1_contact              | bus_phone          | 
| ============ | ========================= | ========== | ====== | ====================================== | ================== | 
| WORCESTER    | EARL ANNABLE              | 1026975600 | 5488   |                                        | [null, null]       | 
| OUT OF STATE | SAMANTHA SWISHER          | 1338447600 | 6935   | RALEIGH NC 27606                       | [null, null]       | 
| FREDERICK    | NEIL CORSELIUS            | -207594000 | 1112   | 2420 MONOCACY BLVD. FREDERICK MD 21701 | [null, null]       | 
| OUT OF STATE | ALICE DOHERTY             | 686905200  | 3993   | 8189 GREAT COVE ROAD NEEDMORE PA 17238 | [7175734569, null] | 
| MONTGOMERY   | CYNTHIA MYERS             | 802422000  | 4469   |                                        | [null, null]       | 
| FREDERICK    | MARY BROWN                | 110012400  | 1732   |                                        | [null, null]       | 
| MONTGOMERY   | CHERYL FERENDO            | 461228400  | 2750   |                                        | [null, null]       | 
| MONTGOMERY   | JOHN MOHLER               | -457203600 | 808    |                                        | [null, null]       | 
| OUT OF STATE | STACY REEDER              | 802940400  | 4501   | 1009 W MAIN STREET WAYNESBORO VA 22980 | [null, null]       | 
| CARROLL      | HARLAN WILLIAMS           | 513244800  | 3015   |                                        | [4102392323, null] | 
```