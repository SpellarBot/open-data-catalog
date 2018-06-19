# Real Property Taxes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-taxes-1adc3) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/27w9-urtv) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/27w9-urtv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/27w9-urtv/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 27w9-urtv |
| Name | Real Property Taxes |
| Attribution | Department of Finance |
| Category | Financial |
| Tags | taxes, property |
| Created | 2011-01-22T16:27:41Z |
| Publication Date | 2016-03-30T19:28:36Z |

## Description

Current Real Property Tax in Baltimore. For more detailed information, visit SDAT at http://sdat.resiusa.org/RealProperty/Pages/default.aspx

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | propertyid      | PropertyID      | text          | text          |
| Yes      | series tag     | block           | Block           | text          | text          |
| Yes      | series tag     | lot             | Lot             | text          | text          |
| Yes      | series tag     | ward            | Ward            | text          | text          |
| Yes      | series tag     | sect            | Sect            | text          | text          |
| No       |                | propertyaddress | PropertyAddress | text          | text          |
| Yes      | series tag     | lotsize         | LotSize         | text          | text          |
| Yes      | numeric metric | citytax         | CityTax         | money         | money         |
| Yes      | numeric metric | statetax        | StateTax        | money         | money         |
| Yes      | series tag     | rescode         | ResCode         | text          | text          |
| Yes      | numeric metric | amountdue       | AmountDue       | money         | money         |
| Yes      | time           | asofdate        | AsOfDate        | calendar_date | calendar_date |
| Yes      | series tag     | neighborhood    | Neighborhood    | text          | text          |
| Yes      | series tag     | policedistrict  | PoliceDistrict  | text          | text          |
| Yes      | series tag     | councildistrict | CouncilDistrict | text          | number        |
```

## Time Field

```ls
Value = asofdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = propertyaddress
```

## Data Commands

```ls
series e:27w9-urtv d:2017-03-02T00:00:00.000Z t:ward=08 t:sect=150 t:councildistrict=13 t:neighborhood="BROADWAY EAST" t:lot=065 t:block=1520 t:rescode="NOT A PRINCIPAL RESIDENCE" t:policedistrict=EASTERN t:propertyid="1520 065" t:lotsize=13-2X70 m:citytax=337.2 m:amountdue=6.91 m:statetax=16.8

series e:27w9-urtv d:2016-06-01T00:00:00.000Z t:ward=12 t:sect=110 t:councildistrict=12 t:neighborhood="GREENMOUNT WEST" t:lot=031 t:block=1103 t:rescode="PRINCIPAL RESIDENCE" t:policedistrict=EASTERN t:propertyid="1103 031" t:lotsize=17X88 m:citytax=1463.45 m:statetax=72.91

series e:27w9-urtv d:2016-08-03T00:00:00.000Z t:ward=13 t:sect=030 t:councildistrict=7 t:neighborhood=HAMPDEN t:lot=010 t:block=3542B t:rescode="PRINCIPAL RESIDENCE" t:policedistrict=NORTHERN t:propertyid=3542B010 t:lotsize=14X103-3 m:citytax=2861.7 m:statetax=142.58
```

## Meta Commands

```ls
metric m:citytax p:double l:CityTax t:dataTypeName=money

metric m:statetax p:double l:StateTax t:dataTypeName=money

metric m:amountdue p:double l:AmountDue t:dataTypeName=money

entity e:27w9-urtv l:"Real Property Taxes" t:attribution="Department of Finance" t:url=https://data.baltimorecity.gov/api/views/27w9-urtv

property e:27w9-urtv t:meta.view v:id=27w9-urtv v:category=Financial v:attributionLink=http://www.baltimorecity.gov/Government/AgenciesDepartments/Finance.aspx v:averageRating=0 v:name="Real Property Taxes" v:attribution="Department of Finance"

property e:27w9-urtv t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:27w9-urtv t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:27w9-urtv t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| propertyid | block | lot | ward | sect | propertyaddress     | lotsize     | citytax   | statetax | rescode                   | amountdue | asofdate            | neighborhood        | policedistrict | councildistrict | 
| ========== | ===== | === | ==== | ==== | =================== | =========== | ========= | ======== | ========================= | ========= | =================== | =================== | ============== | =============== | 
| 1369 037   | 1369  | 037 | 03   | 010  | 11 S BETHEL ST      | 0.020 ACRES |           |          | NOT A PRINCIPAL RESIDENCE |           | 2016-07-06T00:00:00 |                     |                |                 | 
| 1369 038   | 1369  | 038 | 03   | 010  | 13 S BETHEL ST      | 0.020 ACRES |           |          | NOT A PRINCIPAL RESIDENCE |           | 2016-07-06T00:00:00 |                     |                |                 | 
| 1520 065   | 1520  | 065 | 08   | 150  | 1305 N MONTFORD AVE | 13-2X70     | 337.2000  | 16.8000  | NOT A PRINCIPAL RESIDENCE | 6.9100    | 2017-03-02T00:00:00 | BROADWAY EAST       | EASTERN        | 13              | 
| 1103 031   | 1103  | 031 | 12   | 110  | 327 E LAFAYETTE AVE | 17X88       | 1463.4500 | 72.9100  | PRINCIPAL RESIDENCE       |           | 2016-06-01T00:00:00 | GREENMOUNT WEST     | EASTERN        | 12              | 
| 3542B010   | 3542B | 010 | 13   | 030  | 1229 UNION AVE      | 14X103-3    | 2861.7000 | 142.5800 | PRINCIPAL RESIDENCE       |           | 2016-08-03T00:00:00 | HAMPDEN             | NORTHERN       | 7               | 
| 0080 013   | 0080  | 013 | 16   | 150  | 915 N ARLINGTON AVE | 18X90       | 884.2100  | 44.0500  | NOT A PRINCIPAL RESIDENCE | 923.8400  | 2016-07-02T00:00:00 | SANDTOWN-WINCHESTER | WESTERN        | 9               | 
| 4178 027   | 4178  | 027 | 08   | 260  | 3139 RAVENWOOD AVE  | 16X74       | 1652.2800 | 82.3200  | NOT A PRINCIPAL RESIDENCE | 113.9500  | 2017-03-02T00:00:00 | FOUR BY FOUR        | NORTHEASTERN   | 13              | 
| 0017 002   | 0017  | 002 | 15   | 140  | 1602 N CALHOUN ST   | 12X50       | 1011.6000 | 50.4000  | PRINCIPAL RESIDENCE       | 338.4600  | 2016-10-04T00:00:00 | SANDTOWN-WINCHESTER | WESTERN        | 7               | 
| 7202 032   | 7202  | 032 | 25   | 080  | 1615 ELMTREE ST     | 20X100      | 1202.6800 | 59.9200  | NOT A PRINCIPAL RESIDENCE | 1336.5500 | 2016-12-05T00:00:00 | CURTIS BAY          | SOUTHERN       | 10              | 
| 5482D039   | 5482D | 039 | 27   | 350  | 2821 INGLEWOOD AVE  | 50X125      | 2778.5300 | 138.4300 | PRINCIPAL RESIDENCE       | 56.0600   | 2017-03-02T00:00:00 | NORTH HARFORD ROAD  | NORTHEASTERN   | 3               | 
```