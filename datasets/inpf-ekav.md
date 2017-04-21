# Cigarette and Other Tobacco Products Licensees

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cigarette-and-other-tobacco-products-licensees) |
| Metadata | [Link](https://data.mo.gov/api/views/inpf-ekav) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/inpf-ekav/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/inpf-ekav/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | inpf-ekav |
| Name | Cigarette and Other Tobacco Products Licensees |
| Attribution | Missouri Department of Revenue |
| Category | Revenue |
| Tags | tobacco, licensees, other tobacco products |
| Created | 2015-09-21T21:23:34Z |
| Publication Date | 2017-04-20T20:21:48Z |

## Description

List of Cigarette and Other Tobacco Products Licensees

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type | Render Type |
| ======== | =========== | ====================== | ====================== | ========= | =========== |
| No       | time        | :updated_at            | updated_at             | meta_data | meta_data   |
| Yes      | series tag  | licensee_name          | Licensee Name          | text      | text        |
| No       |             | mailing_address        | Mailing Address        | text      | text        |
| Yes      | series tag  | cigarette              | Cigarette              | text      | text        |
| Yes      | series tag  | other_tobacco_products | Other Tobacco Products | text      | text        |
| Yes      | series tag  | retailer               | Retailer               | text      | text        |
| Yes      | series tag  | license_number         | License Number         | text      | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = mailing_address
```

## Data Commands

```ls
series e:inpf-ekav d:2015-09-21T14:23:37.000Z t:other_tobacco_products=OTP t:cigarette=CIG t:licensee_name="A. E. WEASE, INCORPORATED  DBA:  WEASE DISTRIBUTING" t:license_number=18 t:retailer=NO m:row_number.inpf-ekav=1

series e:inpf-ekav d:2015-09-21T14:23:37.000Z t:other_tobacco_products=OTP t:licensee_name="AMBICA FOODS" t:license_number=1483 t:retailer=YES m:row_number.inpf-ekav=2

series e:inpf-ekav d:2015-09-21T14:23:37.000Z t:other_tobacco_products=OTP t:cigarette=CIG t:licensee_name="AMCON DISTRIBUTING COMPANY" t:license_number=280 t:retailer=NO m:row_number.inpf-ekav=3
```

## Meta Commands

```ls
metric m:row_number.inpf-ekav p:long l:"Row Number"

entity e:inpf-ekav l:"Cigarette and Other Tobacco Products Licensees" t:attribution="Missouri Department of Revenue" t:url=https://data.mo.gov/api/views/inpf-ekav

property e:inpf-ekav t:meta.view v:id=inpf-ekav v:category=Revenue v:averageRating=0 v:name="Cigarette and Other Tobacco Products Licensees" v:attribution="Missouri Department of Revenue"

property e:inpf-ekav t:meta.view.owner v:id=drqb-jxxn v:screenName="Darin Chilcutt" v:displayName="Darin Chilcutt"

property e:inpf-ekav t:meta.view.tableauthor v:id=drqb-jxxn v:screenName="Darin Chilcutt" v:roleName=editor v:displayName="Darin Chilcutt"
```

## Top Records

```ls
| :updated_at | licensee_name                                     | mailing_address                                 | cigarette | other_tobacco_products | retailer | license_number | 
| =========== | ================================================= | =============================================== | ========= | ====================== | ======== | ============== | 
| 1442845417  | A. E. WEASE, INCORPORATED DBA: WEASE DISTRIBUTING | PO BOX 490, DESOTO, MO 63020                    | CIG       | OTP                    | NO       | 18             | 
| 1442845417  | AMBICA FOODS                                      | 12264 ST. CHARLES ROCK RD. BRIDGETON, MO 63044  |           | OTP                    | YES      | 1483           | 
| 1442845417  | AMCON DISTRIBUTING COMPANY                        | 7405 IRVINGTON ROAD, OMAHA, NE 68122            | CIG       | OTP                    | NO       | 280            | 
| 1442845417  | AMCON DISTRIBUTING COMPANY                        | 821 E. COMMERCIAL SPRINGFIELD, MO 65803         | CIG       | OTP                    | NO       | 348            | 
| 1442845417  | AMCON DISTRIBUTING COMPANY                        | 2517 ELLINGTON ROAD, QUINCY, IL 62305           | CIG       | OTP                    | NO       | 439            | 
| 1442845417  | AMERICAN SNUFF COMPANY, LLC                       | PO BOX 217, MEMPHIS, TN 38101                   |           | OTP                    | NO       | 1358           | 
| 1442845417  | APEX WHOLESALE, INC.                              | 1501 W. 31ST STREET #575 KANSAS CITY, MO 64111  |           | OTP                    | NO       | 1443           | 
| 1442845417  | APPLE WHOLESALE & DISTRIBUTION, LLC               | 2317 INDEPENDENCE AVENUE, KANSAS CITY, MO 64124 | CIG       | OTP                    | NO       | 519            | 
| 1442845417  | ASSOCIATED WHOLESALE GROCERS INC.                 | 5000 KANSAS AVE, KANSAS CITY, KS 66106          | CIG       | OTP                    | NO       | 146            | 
| 1442845417  | ASSOCIATED WHOLESALE GROCERS INC.                 | 5000 KANSAS AVE. KANSAS CITY, KS 66106          | CIG       | OTP                    | NO       | 147            | 
```