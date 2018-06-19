# OIE-FAVN TEST RESULTS BY MICROCHIP - under construction with test data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/oie-favn-test-results-by-microchip-under-construction-with-test-data-bd37a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/fhan-ym2j) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/fhan-ym2j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/fhan-ym2j/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | fhan-ym2j |
| Name | OIE-FAVN TEST RESULTS BY MICROCHIP - under construction with test data |
| Category | Health |
| Created | 2012-07-12T00:53:30Z |
| Publication Date | 2012-11-09T01:53:07Z |

## Description

For details on the data provided in this dataset, please go the AQS microchip webpage at: http://hawaii.gov/hdoa/ai/aqs/copy_of_microchip

## Columns

```ls
| Included | Schema Type | Field Name     | Name                 | Data Type | Render Type |
| ======== | =========== | ============== | ==================== | ========= | =========== |
| No       | time        | :updated_at    | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | chip_number    | Microchip Number     | text      | text        |
| Yes      | series tag  | oie_favn       | FAVN Sample Received | text      | text        |
| Yes      | series tag  | passed         | Result               | text      | text        |
| Yes      | series tag  | th_day         | 120th FAVN           | text      | text        |
| Yes      | series tag  | test           | Test Expiration      | text      | text        |
| Yes      | series tag  | st_vaccination | 90th Vacc            | text      | text        |
| Yes      | series tag  | vaccination    | Vacc Expiration      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:fhan-ym2j d:2012-11-08T17:51:42.000Z t:th_day=05/08/2010 t:passed=T t:oie_favn=01/08/2010 t:test=01/07/2013 t:chip_number=000000249992 m:row_number.fhan-ym2j=1

series e:fhan-ym2j d:2012-11-08T17:51:42.000Z t:th_day=05/06/2010 t:passed=T t:oie_favn=01/06/2010 t:test=01/05/2013 t:chip_number=000000933596 m:row_number.fhan-ym2j=2

series e:fhan-ym2j d:2012-11-08T17:51:42.000Z t:th_day=05/19/2010 t:passed=T t:oie_favn=01/19/2010 t:test=01/18/2013 t:chip_number=000008029335 m:row_number.fhan-ym2j=3
```

## Meta Commands

```ls
metric m:row_number.fhan-ym2j p:long l:"Row Number"

entity e:fhan-ym2j l:"OIE-FAVN TEST RESULTS BY MICROCHIP - under construction with test data" t:url=https://data.hawaii.gov/api/views/fhan-ym2j

property e:fhan-ym2j t:meta.view v:id=fhan-ym2j v:category=Health v:averageRating=0 v:name="OIE-FAVN TEST RESULTS BY MICROCHIP - under construction with test data"

property e:fhan-ym2j t:meta.view.owner v:id=t6a8-bm3j v:screenName="DOA Open Data Coordinator" v:displayName="DOA Open Data Coordinator"

property e:fhan-ym2j t:meta.view.tableauthor v:id=t6a8-bm3j v:screenName="DOA Open Data Coordinator" v:roleName=publisher v:displayName="DOA Open Data Coordinator"
```

## Top Records

```ls
| :updated_at | chip_number  | oie_favn   | passed | th_day     | test       | st_vaccination | vaccination | 
| =========== | ============ | ========== | ====== | ========== | ========== | ============== | =========== | 
| 1352397102  | 000000249992 | 01/08/2010 | T      | 05/08/2010 | 01/07/2013 |                |             | 
| 1352397102  | 000000933596 | 01/06/2010 | T      | 05/06/2010 | 01/05/2013 |                |             | 
| 1352397102  | 000008029335 | 01/19/2010 | T      | 05/19/2010 | 01/18/2013 |                |             | 
| 1352397102  | 000017061E   | 03/24/2010 | T      | 07/22/2010 | 03/23/2013 |                |             | 
| 1352397102  | 00002696BD   | 12/29/2010 | T      | 04/28/2011 | 12/28/2013 | 02/26/2011     | 11/28/2013  | 
| 1352397102  | 00006AD3BB   | 07/14/2010 | T      | 11/11/2010 | 07/13/2013 |                |             | 
| 1352397102  | 000121919755 | 01/12/2010 | T      | 05/12/2010 | 01/11/2013 |                |             | 
| 1352397102  | 000123153696 | 03/15/2011 | T      | 07/13/2011 | 03/14/2014 | 12/10/2010     | 09/11/2011  | 
| 1352397102  | 000123182647 | 01/12/2010 | T      | 05/12/2010 | 01/11/2013 |                |             | 
| 1352397102  | 000141E718   | 07/13/2011 | T      | 11/10/2011 | 07/12/2014 | 09/15/2011     | 06/17/2014  | 
```