# Beach Lab Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/beach-lab-data) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/2ivx-z93u) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/2ivx-z93u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/2ivx-z93u/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 2ivx-z93u |
| Name | Beach Lab Data |
| Attribution | Chicago Park District |
| Category | Parks & Recreation |
| Tags | beaches, parks, chicago park district, open spaces, parks & recreation, recreation, water |
| Created | 2016-05-04T17:34:00Z |
| Publication Date | 2017-02-16T21:49:40Z |

## Description

The Chicago Park District tests water samples at beaches along Chicago's Lake Michigan lakefront, which it tests for E. coli in order to monitor swimming safety.  Multiple samples may be taken from a beach and samples may be tested by culture, DNA testing, or both.

What do these numbers mean? 

The modeling prediction numbers forecast real-time Escherichia coli (E. coli) bacteria levels present in the water. The Chicago Park District (CPD) in partnership with the US Geological Survey, has developed statistical prediction models by using weather data pulled from CPD buoys (https://data.cityofchicago.org/d/qmqz-2xku) and weather stations (https://data.cityofchicago.org/d/k7hf-8y75). E. coli is an indicator species for the presence of disease-causing bacteria, viruses, and protozoans that may pose health risks to the public.

The culture based testing numbers indicate E. coli levels present in the water. This method requires 18-24 hours of processing to receive results. US Environmental Protection Agency (USEPA) recommends notifying the public when E. coli bacteria levels are above the federal water quality Beach Action Value (BAV), which is 235*CFU. When bacteria levels exceed 235 CFU, a yellow or red flag will be implemented. This standard is used at beaches throughout the Great Lakes region. For more information please refer to the USEPA Recreational Water Quality Criteria.

The rapid testing method (qPCR analysis) is a new method that measures levels of pathogenic DNA in beach water. Unlike the culture based test that requires up to 24 hours of processing, the new rapid testing method requires a few hours for results. The Chicago Park District can use results of the rapid test to notify the public when levels exceed UPEPA recommended levels. US Environmental Protection Agency (USEPA) recommends notifying the public when DNA bacteria levels are above the federal water quality Beach Action Value (BAV), which is 1000*CCE. When DNA bacteria levels exceed 1000 CCE, a yellow or red flag will be implemented. For more information please refer to the USEPA Recreational Water Quality Criteria (http://water.epa.gov/scitech/swguidance/standards/criteria/health/recreation).

* The unit of measurement for Escherichia coli is Colony Forming Units (CFU) per 100 milliliters of water.
*The unit of measuring DNA is Enterococci Calibrator Cell Equivalents (CCE) per 100 milliliters of water.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type     | Render Type   |
| ======== | ============== | ========================== | ========================== | ============= | ============= |
| Yes      | series tag     | culture_test_id            | Culture Test ID            | text          | text          |
| Yes      | time           | culture_sample_1_timestamp | Culture Sample 1 Timestamp | calendar_date | calendar_date |
| Yes      | series tag     | beach                      | Beach                      | text          | text          |
| Yes      | numeric metric | culture_sample_1_reading   | Culture Sample 1 Reading   | number        | number        |
| Yes      | numeric metric | culture_sample_2_reading   | Culture Sample 2 Reading   | number        | number        |
| Yes      | numeric metric | culture_reading_mean       | Culture Reading Mean       | number        | number        |
| Yes      | series tag     | culture_note               | Culture Note               | text          | text          |
| Yes      | numeric metric | culture_sample_interval    | Culture Sample Interval    | number        | number        |
| No       |                | culture_sample_2_timestamp | Culture Sample 2 Timestamp | calendar_date | calendar_date |
| Yes      | series tag     | dna_test_id                | DNA Test ID                | text          | text          |
| No       |                | dna_sample_timestamp       | DNA Sample Timestamp       | calendar_date | calendar_date |
| Yes      | numeric metric | dna_sample_1_reading       | DNA Sample 1 Reading       | number        | number        |
| Yes      | numeric metric | dna_sample_2_reading       | DNA Sample 2 Reading       | number        | number        |
| Yes      | numeric metric | dna_reading_mean           | DNA Reading Mean           | number        | number        |
| No       |                | latitude                   | Latitude                   | number        | number        |
| No       |                | longitude                  | Longitude                  | number        | number        |
```

## Time Field

```ls
Value = culture_sample_1_timestamp
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = culture_sample_2_timestamp,dna_sample_timestamp,latitude,longitude
```

## Data Commands

```ls
series e:2ivx-z93u d:2013-08-15T00:00:00.000Z t:culture_test_id=107973 t:beach=NA m:culture_sample_2_reading=248 m:culture_reading_mean=239.3491174 m:culture_sample_1_reading=231

series e:2ivx-z93u d:2014-08-27T00:00:00.000Z t:culture_test_id=93598 t:beach=NA m:culture_sample_2_reading=4 m:culture_reading_mean=6.92820323 m:culture_sample_1_reading=12

series e:2ivx-z93u d:2012-07-05T00:00:00.000Z t:culture_test_id=108593 t:beach=NA m:culture_sample_2_reading=2 m:culture_reading_mean=2 m:culture_sample_1_reading=2
```

## Meta Commands

```ls
metric m:culture_sample_1_reading p:float l:"Culture Sample 1 Reading" d:"Colony Forming Units (CFU) per 100 ml of water" t:dataTypeName=number

metric m:culture_sample_2_reading p:double l:"Culture Sample 2 Reading" d:"Colony Forming Units (CFU) per 100 ml of water" t:dataTypeName=number

metric m:culture_reading_mean p:double l:"Culture Reading Mean" d:"The geometric mean of Culture Sample 1 Reading and Culture Sample 2 Reading (if any)." t:dataTypeName=number

metric m:culture_sample_interval p:integer l:"Culture Sample Interval" d:"Time in minutes between collection of the two samples for culture testing." t:dataTypeName=number

metric m:dna_sample_1_reading p:integer l:"DNA Sample 1 Reading" d:"Enterococci calibrator cell equivalents (CCE) per 100 ml of water" t:dataTypeName=number

metric m:dna_sample_2_reading p:double l:"DNA Sample 2 Reading" d:"Enterococci calibrator cell equivalents (CCE) per 100 ml of water" t:dataTypeName=number

metric m:dna_reading_mean p:double l:"DNA Reading Mean" d:"The geometric mean of the DNA Sample 1 Reading and the DNA Sample 2 Reading (if any)." t:dataTypeName=number

entity e:2ivx-z93u l:"Beach Lab Data" t:attribution="Chicago Park District" t:url=https://data.cityofchicago.org/api/views/2ivx-z93u

property e:2ivx-z93u t:meta.view v:id=2ivx-z93u v:category="Parks & Recreation" v:attributionLink=http://www.chicagoparkdistrict.com/ v:averageRating=0 v:name="Beach Lab Data" v:attribution="Chicago Park District"

property e:2ivx-z93u t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:2ivx-z93u t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| culture_test_id | culture_sample_1_timestamp | beach | culture_sample_1_reading | culture_sample_2_reading | culture_reading_mean | culture_note | culture_sample_interval | culture_sample_2_timestamp | dna_test_id | dna_sample_timestamp | dna_sample_1_reading | dna_sample_2_reading | dna_reading_mean | latitude | longitude | 
| =============== | ========================== | ===== | ======================== | ======================== | ==================== | ============ | ======================= | ========================== | =========== | ==================== | ==================== | ==================== | ================ | ======== | ========= | 
| 107973          | 2013-08-15T00:00:00        | NA    | 231                      | 248                      | 239.3491174          |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 93598           | 2014-08-27T00:00:00        | NA    | 12                       | 4                        | 6.92820323           |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 108593          | 2012-07-05T00:00:00        | NA    | 2                        | 2                        | 2                    |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 105618          | 2013-07-02T00:00:00        | NA    | 1                        | 1                        | 1                    |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 98229           | 2006-07-18T00:00:00        | NA    | 104.6                    | 86                       | 94.845136934         |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 104762          | 2006-07-03T00:00:00        | NA    | 2                        | 3.1                      | 2.48997992           |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 92980           | 2014-08-14T00:00:00        | NA    | 67                       | 58                       | 62.337789502         |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 106097          | 2013-07-23T00:00:00        | NA    | 6                        | 17                       | 10.099504938         |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 97761           | 2006-07-12T00:00:00        | NA    | 19.9                     | 19.9                     | 19.9                 |              |                         |                            |             |                      |                      |                      |                  |          |           | 
| 96646           | 2011-07-19T00:00:00        | NA    | 81.3                     | 60.5                     | 70.133087769         |              |                         |                            |             |                      |                      |                      |                  |          |           | 
```