# Licensed Public Adjusters

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/licensed-public-adjusters) |
| Metadata | [Link](https://data.iowa.gov/api/views/rw5w-dmcr) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/rw5w-dmcr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/rw5w-dmcr/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | rw5w-dmcr |
| Name | Licensed Public Adjusters |
| Attribution | Iowa Insurance Division |
| Category | Economy |
| Tags | public adjusters, insurance |
| Created | 2015-07-02T18:50:52Z |
| Publication Date | 2016-12-23T15:40:44Z |

## Description

This dataset contains a listing of licensed resident and non-resident public adjusters.

## Columns

```ls
| Included | Schema Type | Field Name        | Name                            | Data Type     | Render Type   |
| ======== | =========== | ================= | =============================== | ============= | ============= |
| Yes      | series tag  | npn               | NATIONAL PRODUCER NUMBER        | text          | number        |
| Yes      | series tag  | last_name         | LAST NAME                       | text          | text          |
| Yes      | series tag  | first_name        | FIRST NAME                      | text          | text          |
| No       |             | address_line_1    | MAILING ADDRESS1                | text          | text          |
| No       |             | address_line_2    | MAILING ADDRESS2                | text          | text          |
| No       |             | address_line_3    | MAILING ADDRESS3                | text          | text          |
| Yes      | series tag  | city              | MAILING CITY                    | text          | text          |
| Yes      | series tag  | state             | MAILING STATE                   | text          | text          |
| Yes      | series tag  | zip               | MAILING ZIP                     | text          | text          |
| Yes      | time        | first_active_date | DATE IOWA LICENSE FIRST ACTIVE  | calendar_date | calendar_date |
| No       |             | expiry_date       | IOWA LICENSE EXPIRATION DATE    | calendar_date | calendar_date |
| Yes      | series tag  | business_phone    | BUSINESS PHONE                  | phone         | phone         |
| Yes      | series tag  | email             | BUSINESS EMAIL                  | email         | email         |
| Yes      | series tag  | ce_compliance     | CONTINUING EDUCATION COMPLIANCE | text          | text          |
```

## Time Field

```ls
Value = first_active_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2,address_line_3,expiry_date
```

## Data Commands

```ls
series e:rw5w-dmcr d:2008-03-11T00:00:00.000Z t:first_name=KELLY t:zip=92138 t:last_name=BARBIERI t:state="SAN DIEGO" t:ce_compliance=Y t:npn=7680652 m:row_number.rw5w-dmcr=1

series e:rw5w-dmcr d:2013-10-25T00:00:00.000Z t:first_name=JESSICA t:zip=21208 t:email=jbivens@gggco.com t:last_name=BIVENS t:state=BALTIMORE t:ce_compliance=Y t:npn=3594377 t:city="3903 NAYLORS LN" m:row_number.rw5w-dmcr=2

series e:rw5w-dmcr d:2008-07-28T00:00:00.000Z t:first_name=MADELINE t:zip=92138 t:phone_number=6194508600 t:email=licensing@qualityclaims.com t:last_name=BUSTRIA t:state="SAN DIEGO" t:ce_compliance=Y t:npn=8425418 m:row_number.rw5w-dmcr=3
```

## Meta Commands

```ls
metric m:row_number.rw5w-dmcr p:long l:"Row Number"

entity e:rw5w-dmcr l:"Licensed Public Adjusters" t:attribution="Iowa Insurance Division" t:url=https://data.iowa.gov/api/views/rw5w-dmcr

property e:rw5w-dmcr t:meta.view v:id=rw5w-dmcr v:category=Economy v:averageRating=0 v:name="Licensed Public Adjusters" v:attribution="Iowa Insurance Division"

property e:rw5w-dmcr t:meta.view.license v:name="Public Domain"

property e:rw5w-dmcr t:meta.view.owner v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:displayName="Iowa Insurance Division (Commerce)"

property e:rw5w-dmcr t:meta.view.tableauthor v:id=ym8t-nug5 v:profileImageUrlMedium=/api/users/ym8t-nug5/profile_images/THUMB v:profileImageUrlLarge=/api/users/ym8t-nug5/profile_images/LARGE v:screenName="Iowa Insurance Division (Commerce)" v:profileImageUrlSmall=/api/users/ym8t-nug5/profile_images/TINY v:roleName=publisher v:displayName="Iowa Insurance Division (Commerce)"
```

## Top Records

```ls
| npn      | last_name | first_name | address_line_1                    | address_line_2            | address_line_3 | city                      | state       | zip   | first_active_date   | expiry_date         | business_phone     | email                             | ce_compliance | 
| ======== | ========= | ========== | ================================= | ========================= | ============== | ========================= | =========== | ===== | =================== | =================== | ================== | ================================= | ============= | 
| 7680652  | BARBIERI  | KELLY      | PO BOX 87611                      |                           |                |                           | SAN DIEGO   | 92138 | 2008-03-11T00:00:00 | 2017-11-30T00:00:00 | [null, null]       |                                   | Y             | 
| 3594377  | BIVENS    | JESSICA    | C/O ADJUSTERS INTERNATIONAL       | 3903 NAYLORS LN           |                | 3903 NAYLORS LN           | BALTIMORE   | 21208 | 2013-10-25T00:00:00 | 2018-01-31T00:00:00 | [null, null]       | jbivens@gggco.com                 | Y             | 
| 8425418  | BUSTRIA   | MADELINE   | PO BOX 87611                      |                           |                |                           | SAN DIEGO   | 92138 | 2008-07-28T00:00:00 | 2018-02-28T00:00:00 | [6194508600, null] | licensing@qualityclaims.com       | Y             | 
| 12084673 | CANIO     | LENIN      | PO BOX 87611                      |                           |                |                           | SAN DIEGO   | 92138 | 2008-12-17T00:00:00 | 2018-11-30T00:00:00 | [null, null]       | licensing@qualityclaims.com       | Y             | 
| 3684428  | CHARRIER  | JOSEPH     | NATIONAL FIRE ADJUSTMENT CO. INC. | 1 NFA PARK                |                | 1 NFA PARK                | AMHERST     | 14228 | 2016-10-04T00:00:00 | 2018-11-30T00:00:00 | [null, null]       | jcharrier@nfa.com                 | Y             | 
| 12813641 | COX       | LEASA      | C/O MORTGAGE & AUTO SOLUTIONS INC | 827 W GROVE AVE           |                | 827 W GROVE AVE           | MESA        | 85210 | 2010-12-14T00:00:00 | 2017-03-31T00:00:00 | [null, null]       | leasa.cox@masiadvantage.com       | Y             | 
| 5032562  | COX       | WILLIAM    | INSURANCE ADJUSTERS GROUP LLC     | PO BOX 672                |                |                           | FULTON      | 65251 | 2015-11-23T00:00:00 | 2017-10-31T00:00:00 | [null, null]       | w.cox@insuranceadjustersgroup.com | Y             | 
| 406897   | D AMICO   | ANTHONY    | ADJUSTERS INTERNATIONAL           | 275 MADISON AVENUE        | SUITE 2218     | 275 MADISON AVENUE        | NEW YORK    | 10016 | 2008-06-24T00:00:00 | 2018-10-31T00:00:00 | [null, null]       | tdamico@gggco.com                 | Y             | 
| 577861   | DELUISE   | ROGER      | MATRIX BUSINESS CONSULTING        | 340 E 1ST AVE STE 300     |                | 340 E 1ST AVE STE 300     | BROOMFIELD  | 80020 | 2008-08-25T00:00:00 | 2018-05-31T00:00:00 | [3032981711, null] | scott@matrix-bc.com               | Y             | 
| 3745943  | DOORLEY   | DANIEL     | C/O ALEX N. SILL CO               | 6000 LOMBARDO CTR STE 600 |                | 6000 LOMBARDO CTR STE 600 | SEVEN HILLS | 44131 | 2016-03-30T00:00:00 | 2017-12-31T00:00:00 | [null, null]       | ddoorley@sill.com                 | Y             | 
```