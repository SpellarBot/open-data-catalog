# Stable Open Data 11122014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/stable-open-data-11122014-4004c) |
| Metadata | [Link](https://data.maryland.gov/api/views/ehcz-9ryw) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/ehcz-9ryw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/ehcz-9ryw/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | ehcz-9ryw |
| Name | Stable Open Data 11122014 |
| Attribution | MDA |
| Category | Agriculture |
| Tags | horse riding, stables |
| Created | 2014-11-13T16:36:32Z |
| Publication Date | 2014-11-13T16:44:15Z |

## Description

This dataset shows all horse stables in Maryland which are licensed by the Maryland Department of Agriculture for FY 2015 (July 1, 2014 through June 30, 2015).

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | =========== | ======================== | ======================== | ============= | ============= |
| Yes      | time        | license_date             | LICENSE DATE             | calendar_date | calendar_date |
| Yes      | series tag  | license_number           | LICENSE NUMBER           | text          | number        |
| No       |             | expiration_year          | EXPIRATION YEAR          | number        | text          |
| Yes      | series tag  | stable_contact           | STABLE CONTACT           | text          | text          |
| Yes      | series tag  | stable_name              | STABLE NAME              | text          | text          |
| Yes      | series tag  | county                   | COUNTY                   | text          | text          |
| Yes      | series tag  | location                 | LOCATION                 | text          | text          |
| No       |             | mailing_address          | MAILING ADDRESS          | text          | text          |
| Yes      | series tag  | stable_phone             | STABLE PHONE             | text          | text          |
| Yes      | series tag  | day_phone                | DAY PHONE                | text          | text          |
| Yes      | series tag  | evening_phone            | EVENING PHONE            | text          | text          |
| Yes      | series tag  | boarding                 | BOARDING                 | text          | text          |
| Yes      | series tag  | sales                    | SALES                    | text          | text          |
| Yes      | series tag  | rental                   | RENTAL                   | text          | text          |
| Yes      | series tag  | instruction              | INSTRUCTION              | text          | text          |
| Yes      | series tag  | rescue                   | RESCUE                   | text          | text          |
| Yes      | series tag  | nutrient_management_plan | NUTRIENT MANAGEMENT PLAN | text          | text          |
| Yes      | series tag  | website                  | WEBSITE                  | text          | text          |
| Yes      | series tag  | email                    | EMAIL                    | text          | text          |
| Yes      | series tag  | manager                  | MANAGER                  | text          | text          |
| Yes      | series tag  | manager_phone            | MANAGER PHONE            | text          | text          |
| Yes      | series tag  | summer_camps             | SUMMER CAMPS             | text          | text          |
| Yes      | series tag  | therapeutic              | THERAPEUTIC              | text          | text          |
| Yes      | series tag  | multi_purpose            | MULTI PURPOSE            | text          | text          |
| Yes      | series tag  | beginners                | BEGINNERS                | text          | text          |
| Yes      | series tag  | horse_share              | HORSE SHARE              | text          | text          |
| Yes      | series tag  | western                  | WESTERN                  | text          | text          |
```

## Time Field

```ls
Value = license_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = mailing_address,expiration_year
```

## Data Commands

```ls
series e:ehcz-9ryw d:2014-06-23T00:00:00.000Z t:evening_phone=410-913-6872 t:county=BALTIMORE t:email=jsjs2424@gmail.com t:location="825 STUMPFS ROAD,BALTIMORE MD 21220" t:stable_name="HUNTER HILLS FARM" t:stable_contact="JOSHUA SINES" t:license_number=309 t:boarding=Y t:stable_phone=410-913-6872 t:day_phone=410-913-6872 m:row_number.ehcz-9ryw=1

series e:ehcz-9ryw d:2014-05-09T00:00:00.000Z t:county="ANNE ARUNDEL" t:email=baywoodfarms@gmail.com t:website=www.baywoodfarms.com t:location="195 WESTON FARM ROAD,HARWOOD MD 20776" t:nutrient_management_plan=Y t:stable_name="BAYWOOD FARMS, LLC" t:stable_contact="SARAH SUCHOSKI" t:license_number=136 t:boarding=Y t:instruction=Y t:stable_phone=410-867-7923 t:day_phone=410-867-7923 m:row_number.ehcz-9ryw=2

series e:ehcz-9ryw d:2014-07-16T00:00:00.000Z t:nutrient_management_plan=Y t:location="1575 UNDERWOOD ROAD,GAMBRILLS MD 21054" t:website=www.beechgrovefarm.biz t:license_number=455 t:stable_contact="ANITA BAASE" t:stable_name="BEECH GROVE FARM" t:boarding=Y t:rental=Y t:stable_phone=410-320-3330 t:county="ANNE ARUNDEL" t:email=abatbqf@verizon.net t:instruction=Y t:day_phone=410-320-3330 m:row_number.ehcz-9ryw=3
```

## Meta Commands

```ls
metric m:row_number.ehcz-9ryw p:long l:"Row Number"

entity e:ehcz-9ryw l:"Stable Open Data 11122014" t:attribution=MDA t:url=https://data.maryland.gov/api/views/ehcz-9ryw

property e:ehcz-9ryw t:meta.view v:id=ehcz-9ryw v:category=Agriculture v:averageRating=0 v:name="Stable Open Data 11122014" v:attribution=MDA

property e:ehcz-9ryw t:meta.view.owner v:id=5i5x-vf5f v:screenName=teachoaa v:displayName=teachoaa

property e:ehcz-9ryw t:meta.view.tableauthor v:id=5i5x-vf5f v:screenName=teachoaa v:roleName=editor v:displayName=teachoaa
```

## Top Records

```ls
| license_date        | license_number | expiration_year | stable_contact           | stable_name                | county       | location                                  | mailing_address                  | stable_phone | day_phone    | evening_phone | boarding | sales | rental | instruction | rescue | nutrient_management_plan | website                | email                         | manager | manager_phone | summer_camps | therapeutic | multi_purpose | beginners | horse_share | western | 
| =================== | ============== | =============== | ======================== | ========================== | ============ | ========================================= | ================================ | ============ | ============ | ============= | ======== | ===== | ====== | =========== | ====== | ======================== | ====================== | ============================= | ======= | ============= | ============ | =========== | ============= | ========= | =========== | ======= | 
| 2014-06-23T00:00:00 | 309            | 2015            | JOSHUA SINES             | HUNTER HILLS FARM          | BALTIMORE    | 825 STUMPFS ROAD,BALTIMORE MD 21220       |                                  | 410-913-6872 | 410-913-6872 | 410-913-6872  | Y        |       |        |             |        |                          |                        | jsjs2424@gmail.com            |         |               |              |             |               |           |             |         | 
| 2014-05-09T00:00:00 | 136            | 2015            | SARAH SUCHOSKI           | BAYWOOD FARMS, LLC         | ANNE ARUNDEL | 195 WESTON FARM ROAD,HARWOOD MD 20776     |                                  | 410-867-7923 | 410-867-7923 |               | Y        |       |        | Y           |        | Y                        | www.baywoodfarms.com   | baywoodfarms@gmail.com        |         |               |              |             |               |           |             |         | 
| 2014-07-16T00:00:00 | 455            | 2015            | ANITA BAASE              | BEECH GROVE FARM           | ANNE ARUNDEL | 1575 UNDERWOOD ROAD,GAMBRILLS MD 21054    |                                  | 410-320-3330 | 410-320-3330 |               | Y        |       | Y      | Y           |        | Y                        | www.beechgrovefarm.biz | abatbqf@verizon.net           |         |               |              |             |               |           |             |         | 
| 2014-06-20T00:00:00 | 297            | 2015            | LUCY WILSON              | BLUEBIRD FARM              | ANNE ARUNDEL | 132 SANSBURY ROAD,FRIENDSHIP MD 20758     |                                  | 301-855-7844 | 301-855-7844 |               | Y        | Y     |        | Y           |        | Y                        |                        | lucyjwilson@aol.com           |         |               |              |             |               |           |             |         | 
| 2014-06-04T00:00:00 | 148            | 2015            | CAROL JAHNIGEN           | BURRAGES END STABLES, LLC. | ANNE ARUNDEL | 5635 OLD RIDGE PATH LANE,LOTHIAN MD 20711 |                                  | 410-271-3100 | 410-271-3100 | 410-271-3100  | Y        |       |        | Y           |        | Y                        |                        | info@burragesandstables.com   |         |               |              |             |               |           |             |         | 
| 2014-07-09T00:00:00 | 348            | 2015            | KERRY WINTER             | C & C STABLES, INC.        | ANNE ARUNDEL | 1650 ROSSBACK ROAD,DAVIDSONVILLE MD 21035 |                                  | 410-721-9561 | 410-721-9561 | 443-995-1680  | Y        | Y     |        | Y           |        | Y                        |                        |                               |         |               |              |             |               |           |             |         | 
| 2014-08-18T00:00:00 | 417            | 2015            | YMCA OF METRO WASHINGTON | CAMP LETTS STABLE          | ANNE ARUNDEL | 4003 CAMP LETTS ROAD,EDGEWATER MD 21037   | P.O. BOX 208, EDGEWATER MD 21037 | 410-798-5768 | 410-798-5768 |               | Y        | Y     | Y      | Y           |        | Y                        | www.campletts.org      | kmccarley@ymcadc.org          |         |               |              |             |               |           |             |         | 
| 2014-05-07T00:00:00 | 253            | 2015            | STEWART PITTMAN          | DODON FARM                 | ANNE ARUNDEL | 440 DODON ROAD,DAVIDSONVILLE MD 21035     |                                  | 410-507-3351 | 410-507-3351 |               | Y        | Y     |        | Y           |        | Y                        | www.dodonfarm.com      | DUDONFARM@VERISON.NET         |         |               |              |             |               |           |             |         | 
| 2014-05-07T00:00:00 | 6              | 2015            | WILLIAM G. CARTER, JR.   | DOVE HILL FARM             | ANNE ARUNDEL | 205 MILL SWAMP RD.,EDGEWATER MD 21037     | PO BOX 449, EDGEWATER MD 21037   |              | 410-798-9574 | 410-798-9574  | Y        |       |        |             |        | Y                        |                        | BILL.DOVEHILLFARM@VERIZON.NET |         |               |              |             |               |           |             |         | 
| 2014-06-23T00:00:00 | 114            | 2015            | CYNTHIA HOLT             | DUN-PIKIN FARM             | ANNE ARUNDEL | 4808 MOUNTAIN ROAD,PASADENA MD 21122      |                                  | 410-255-3918 | 410-255-3918 | 410-255-7254  | Y        |       |        | Y           |        | Y                        | dun-pikin.com          | dunpkincindy@gmail.com        |         |               |              |             |               |           |             |         | 
```