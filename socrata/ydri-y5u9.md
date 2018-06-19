# Electrical Business Licenses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/electrical-business-licenses-83a24) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/ydri-y5u9) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/ydri-y5u9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/ydri-y5u9/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | ydri-y5u9 |
| Name | Electrical Business Licenses |
| Category | Licenses/Permits |
| Tags | electrical, license, permit, applications |
| Created | 2013-06-12T01:06:42Z |
| Publication Date | 2014-03-07T00:11:21Z |

## Description

Data for all Electrical Business License Permit applications. Update Frequency: Daily

## Columns

```ls
| Included | Schema Type | Field Name      | Name                      | Data Type     | Render Type   |
| ======== | =========== | =============== | ========================= | ============= | ============= |
| Yes      | series tag  | licensetype     | License Type              | text          | text          |
| Yes      | series tag  | licenseno       | License Number            | text          | text          |
| Yes      | time        | issueddate      | Issue Date                | calendar_date | calendar_date |
| No       |             | expiredate      | License Expiration Date   | calendar_date | calendar_date |
| No       |             | insuranceexpire | Insurance Expiration Date | calendar_date | calendar_date |
| Yes      | series tag  | applicant       | Applicant Name            | text          | text          |
| No       |             | address1        | Address Line 1            | text          | text          |
| No       |             | address2        | Address Line 2            | text          | text          |
| Yes      | series tag  | city            | City                      | text          | text          |
| Yes      | series tag  | state           | State                     | text          | text          |
| Yes      | series tag  | zip             | ZIP Code                  | text          | number        |
```

## Time Field

```ls
Value = issueddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiredate,insuranceexpire,address1,address2
```

## Data Commands

```ls
series e:ydri-y5u9 d:2010-03-10T06:03:00.000Z t:zip=20109 t:state=VA t:applicant="_KWANG LEE CONSTUCTION INC" t:licenseno=EB6031 t:licensetype="ELECTRICAL BUSINESS" t:city=MANASSAS m:row_number.ydri-y5u9=1

series e:ydri-y5u9 d:2004-06-29T08:06:00.000Z t:zip=22180 t:state=VA t:applicant="_ATS ELECTRICAL CONTRACTING INC" t:licenseno=EB4205 t:licensetype="ELECTRICAL BUSINESS" t:city=VIENNA m:row_number.ydri-y5u9=2

series e:ydri-y5u9 d:2012-10-04T02:10:12.000Z t:zip=21236 t:state=MD t:applicant="_HUTSON ELECTRICAL SERVICES LLC" t:licenseno=EB205379 t:licensetype="ELECTRICAL BUSINESS" t:city=BALTIMORE m:row_number.ydri-y5u9=3
```

## Meta Commands

```ls
metric m:row_number.ydri-y5u9 p:long l:"Row Number"

entity e:ydri-y5u9 l:"Electrical Business Licenses" t:url=https://data.montgomerycountymd.gov/api/views/ydri-y5u9

property e:ydri-y5u9 t:meta.view v:id=ydri-y5u9 v:category=Licenses/Permits v:averageRating=0 v:name="Electrical Business Licenses"

property e:ydri-y5u9 t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:ydri-y5u9 t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| licensetype         | licenseno | issueddate          | expiredate          | insuranceexpire     | applicant                             | address1                  | address2 | city           | state | zip   | 
| =================== | ========= | =================== | =================== | =================== | ===================================== | ========================= | ======== | ============== | ===== | ===== | 
| ELECTRICAL BUSINESS | EB6031    | 2010-03-10T06:03:00 | 2018-03-10T12:03:00 | 2017-06-05T12:06:00 | _KWANG LEE CONSTUCTION INC            | 11900 TAC COURT           |          | MANASSAS       | VA    | 20109 | 
| ELECTRICAL BUSINESS | EB4205    | 2004-06-29T08:06:00 | 2018-06-29T12:06:00 | 2016-08-18T12:08:00 | _ATS ELECTRICAL CONTRACTING INC       | 8320 COTTAGE STREET       |          | VIENNA         | VA    | 22180 | 
| ELECTRICAL BUSINESS | EB205379  | 2012-10-04T02:10:12 | 2016-10-04T02:10:12 | 2017-05-10T12:05:00 | _HUTSON ELECTRICAL SERVICES LLC       | 9805 HICKERYHURST DRIVE   |          | BALTIMORE      | MD    | 21236 | 
| ELECTRICAL BUSINESS | EB221342  | 2015-09-21T07:09:47 | 2017-09-21T07:09:47 | 2017-06-12T12:06:00 | _D MOORE & ASSOCIATES ELECTRICAL LLC  | 6409 LAUREL DR            |          | GWYNN OAK      | MD    | 21207 | 
| ELECTRICAL BUSINESS | EB222960  | 2016-06-20T05:06:31 | 2018-06-20T05:06:31 | 2017-03-26T12:03:00 | _PRECISION CONTROLS INSTALLATIONS INC | 7852 BEECHCRAFT AVENUE    |          | GAITHERSBURG   | MD    | 20879 | 
| ELECTRICAL BUSINESS | EB0002    | 2000-02-17T06:02:01 | 1986-06-30T12:06:00 |                     | _HOLY CROSS HOSPITAL                  | 001500 FOREST GLEN RD     |          | SILVER SPRING  | MD    | 20910 | 
| ELECTRICAL BUSINESS | EB0007    | 2000-02-17T06:02:01 | 1992-06-07T12:06:00 |                     | _WOODWARD & LOTHROP                   | 001025 F STNW             |          | WASHINGTON     | DC    | 20001 | 
| ELECTRICAL BUSINESS | EB0008    | 2000-02-17T06:02:01 | 1987-04-15T12:04:00 |                     | _WATKINS JOHNSON CO                   | 000700 QUINCE ORCHARD RD  |          | GAITHERSBURG   | MD    | 20878 | 
| ELECTRICAL BUSINESS | EB0017    | 2000-02-17T06:02:01 | 1990-06-30T12:06:00 |                     | _GROUP HEALTH ASSOCIATION INC         | 002121 PENNSYLVANIA AVENW |          | WASHINGTON     | DC    | 20037 | 
| ELECTRICAL BUSINESS | EB4123    | 2003-12-22T02:12:00 | 2017-12-22T12:12:00 | 2017-11-01T12:11:00 | _CORB ELECTRIC LLC                    | P O BOX 4614              |          | UPPER MARLBORO | MD    | 20775 | 
```