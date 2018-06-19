# Missouri Alcohol Temporary License Expirations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-alcohol-temporary-license-expirations-274a3) |
| Metadata | [Link](https://data.mo.gov/api/views/n3tx-eq5q) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/n3tx-eq5q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/n3tx-eq5q/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | n3tx-eq5q |
| Name | Missouri Alcohol Temporary License Expirations |
| Attribution | Missouri Division of Alcohol and Tobacco Control |
| Category | Regulatory |
| Tags | missouri, alcohol, liquor, license, temporary, expire |
| Created | 2012-07-12T15:05:02Z |
| Publication Date | 2017-04-20T12:50:25Z |

## Description

List of temporary alcohol license expiration dates

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | license_number         | License Number         | text          | number        |
| Yes      | series tag  | licensee_name          | Licensee Name          | text          | text          |
| Yes      | series tag  | dba_name               | DBA Name               | text          | text          |
| Yes      | series tag  | business_type          | Business Type          | text          | text          |
| Yes      | series tag  | license_type           | License Type           | text          | text          |
| Yes      | series tag  | license_current_status | License Current Status | text          | text          |
| Yes      | time        | expiration_date        | Expiration Date        | calendar_date | calendar_date |
| Yes      | series tag  | district               | District               | text          | text          |
| Yes      | series tag  | sub_district           | Sub District           | text          | text          |
| Yes      | series tag  | county                 | County                 | text          | text          |
| Yes      | series tag  | street_number          | Street Number          | text          | number        |
| Yes      | series tag  | street_name            | Street Name            | text          | text          |
| Yes      | series tag  | city                   | City                   | text          | text          |
| Yes      | series tag  | state                  | State                  | text          | text          |
| Yes      | series tag  | zip_code               | Zip Code               | text          | number        |
| No       |             | mailing_address        | Mailing Address        | text          | text          |
| No       |             | mailing_address_line_2 | Mailing Address Line 2 | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mailing_address,mailing_address_line_2
```

## Data Commands

```ls
series e:n3tx-eq5q d:2017-04-04T00:00:00.000Z t:sub_district=00 t:license_type=RBDT t:zip_code=64804 t:license_number=243046 t:street_name=BROADLAWN t:state=MO t:dba_name="REDINGS MILL INN" t:license_current_status=EXP t:city="REDINGS MILL" t:licensee_name="RMI LLC" t:county=073 t:street_number=102 t:business_type=L t:district=5 m:row_number.n3tx-eq5q=1

series e:n3tx-eq5q d:2017-04-16T00:00:00.000Z t:sub_district=00 t:license_type=RBDT t:zip_code=65337 t:license_number=243136 t:street_name="EAST PINE" t:state=MO t:dba_name="EL AUSENTE" t:license_current_status=EXP t:city="LA MONTE" t:licensee_name="AGUILER, RUPERTO" t:county=080 t:street_number=100 t:business_type=O t:district=1 m:row_number.n3tx-eq5q=2

series e:n3tx-eq5q d:2017-05-03T00:00:00.000Z t:sub_district=00 t:license_type=RBDT t:zip_code=65355 t:license_number=243370 t:street_name="E. MAIN ST." t:state=MO t:dba_name="NORTHTOWN RESTAURANT AND LOUNGE" t:license_current_status=ACT t:city=WARSAW t:licensee_name="NORTHTOWN RESTAURANT AND LOUNGE LLC" t:county=008 t:street_number=1895 t:business_type=L t:district=5 m:row_number.n3tx-eq5q=3
```

## Meta Commands

```ls
metric m:row_number.n3tx-eq5q p:long l:"Row Number"

entity e:n3tx-eq5q l:"Missouri Alcohol Temporary License Expirations" t:attribution="Missouri Division of Alcohol and Tobacco Control" t:url=https://data.mo.gov/api/views/n3tx-eq5q

property e:n3tx-eq5q t:meta.view v:id=n3tx-eq5q v:category=Regulatory v:attributionLink=http://www.atc.dps.mo.gov v:averageRating=0 v:name="Missouri Alcohol Temporary License Expirations" v:attribution="Missouri Division of Alcohol and Tobacco Control"

property e:n3tx-eq5q t:meta.view.owner v:id=gytm-8bsj v:screenName="Rob Gourley" v:displayName="Rob Gourley"

property e:n3tx-eq5q t:meta.view.tableauthor v:id=gytm-8bsj v:screenName="Rob Gourley" v:roleName=editor v:displayName="Rob Gourley"
```

## Top Records

```ls
| license_number | licensee_name                          | dba_name                        | business_type | license_type | license_current_status | expiration_date     | district | sub_district | county | street_number | street_name       | city         | state | zip_code | mailing_address             | mailing_address_line_2   | 
| ============== | ====================================== | =============================== | ============= | ============ | ====================== | =================== | ======== | ============ | ====== | ============= | ================= | ============ | ===== | ======== | =========================== | ======================== | 
| 243046         | RMI LLC                                | REDINGS MILL INN                | L             | RBDT         | EXP                    | 2017-04-04T00:00:00 | 5        | 00           | 073    | 102           | BROADLAWN         | REDINGS MILL | MO    | 64804    | 7186 HIGHWAY NN             | JOPLIN MO 64804          | 
| 243136         | AGUILER, RUPERTO                       | EL AUSENTE                      | O             | RBDT         | EXP                    | 2017-04-16T00:00:00 | 1        | 00           | 080    | 100           | EAST PINE         | LA MONTE     | MO    | 65337    | 403 E. MASON ST.            | LA MONTE, MO 65337       | 
| 243370         | NORTHTOWN RESTAURANT AND LOUNGE LLC    | NORTHTOWN RESTAURANT AND LOUNGE | L             | RBDT         | ACT                    | 2017-05-03T00:00:00 | 5        | 00           | 008    | 1895          | E. MAIN ST.       | WARSAW       | MO    | 65355    | PO BOX 1182                 | WARSAW MO 65355          | 
| 243384         | CHIPOTLE MEXICAN GRILL OF COLORADO LLC | CHIPOTLE MEXICAN GRILL          | L             | RBDT         | ACT                    | 2017-05-15T00:00:00 | 1        | 00           | 051    | 728           | N. MAGUIRE STREET | WARRENSBURG  | MO    | 64093    | PO BOX 456                  | JEFFERSON CITY MO 65102  | 
| 243403         | CLUB 67 LLC                            | CLUB 67                         | L             | RBDT         | ACT                    | 2017-05-06T00:00:00 | 4        | 00           | 012    | 21500         | HWY 67 SOUTH      | NEELYVILLE   | MO    | 63954    | PO BOX 4178                 | POPLAR BLUFF MO 63902    | 
| 243723         | POUR HOUSE LLC, THE                    | POUR HOUSE, THE                 | L             | RBDT         | ACT                    | 2017-05-21T00:00:00 | 2        | 00           | 103    | 108           | SOUTH CENTER      | CLARENCE     | MO    | 63437    | 108 SOUTH CENTER            | CLARENCE, MO 63437       | 
| 243811         | GET UR SHINEBOX LLC                    | BARREL 131                      | L             | RBDT         | ACT                    | 2017-05-24T00:00:00 | 4        | 00           | 016    | 131           | S. HIGH STREET    | JACKSON      | MO    | 63755    | PO BOX 758                  | JACKSON MO 63755         | 
| 243912         | REDHEAD MANAGEMENT LLC                 | MOBY DICK'S EATERY AND PUB      | L             | RBDT         | ACT                    | 2017-05-30T00:00:00 | 5        | 00           | 105    | 46            | MYRTLE LANE       | INDIAN POINT | MO    | 65616    | 165 KEEL LN #4              | KIMBERLING CITY MO 65686 | 
| 243938         | ARGUS ENTERPRISES LLC                  | AUGIE'S PUB AND GRUB            | L             | RBDT         | ACT                    | 2017-05-31T00:00:00 | 2        | 00           | 071    | 31331         | CUP TREE RD.      | GRAVOIS MILL | MO    | 65037    | 31331 CUP TREE RD.          | GRAVOIS MILL, MO 65037   | 
| 243999         | LAS BRISAS #6 INC.                     | LAS BRISAS #6                   | C             | RBDT         | ACT                    | 2017-06-03T00:00:00 | 4        | 00           | 016    | 5841          | US HIGHWAY 61     | JACKSON      | MO    | 63755    | 613 POTOMAC PLACE, STE. 201 | SMYRNA TN 37167          | 
```