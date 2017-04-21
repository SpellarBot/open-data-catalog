# Taxi Trips

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/taxi-trips) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/wrvz-psew) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/wrvz-psew/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/wrvz-psew/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | wrvz-psew |
| Name | Taxi Trips |
| Attribution | City of Chicago |
| Category | Transportation |
| Tags | taxis, transportation |
| Created | 2016-05-27T21:27:48Z |
| Publication Date | 2016-11-14T17:40:03Z |

## Description

Taxi trips reported to the City of Chicago in its role as a regulatory agency.  To protect privacy but allow for aggregate analyses, the Taxi ID is consistent for any given taxi medallion number but does not show the number, Census Tracts are suppressed in some cases, and times are rounded to the nearest 15 minutes.

Due to the data reporting process, not all trips are reported but the City believes that most are.

See http://digital.cityofchicago.org/index.php/chicago-taxi-data-released for more information about this dataset and how it was created.

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                       | Data Type     | Render Type   |
| ======== | ============== | =========================== | ========================== | ============= | ============= |
| Yes      | series tag     | trip_id                     | Trip ID                    | text          | text          |
| Yes      | series tag     | taxi_id                     | Taxi ID                    | text          | text          |
| Yes      | time           | trip_start_timestamp        | Trip Start Timestamp       | calendar_date | calendar_date |
| No       |                | trip_end_timestamp          | Trip End Timestamp         | calendar_date | calendar_date |
| Yes      | numeric metric | trip_seconds                | Trip Seconds               | number        | number        |
| Yes      | numeric metric | trip_miles                  | Trip Miles                 | number        | number        |
| Yes      | series tag     | pickup_census_tract         | Pickup Census Tract        | text          | text          |
| Yes      | series tag     | dropoff_census_tract        | Dropoff Census Tract       | text          | text          |
| Yes      | numeric metric | pickup_community_area       | Pickup Community Area      | number        | number        |
| Yes      | numeric metric | dropoff_community_area      | Dropoff Community Area     | number        | number        |
| Yes      | numeric metric | fare                        | Fare                       | money         | money         |
| Yes      | numeric metric | tips                        | Tips                       | money         | money         |
| Yes      | numeric metric | tolls                       | Tolls                      | money         | money         |
| Yes      | numeric metric | extras                      | Extras                     | money         | money         |
| Yes      | numeric metric | trip_total                  | Trip Total                 | money         | money         |
| Yes      | series tag     | payment_type                | Payment Type               | text          | text          |
| Yes      | series tag     | company                     | Company                    | text          | text          |
| Yes      | numeric metric | pickup_centroid_latitude    | Pickup Centroid Latitude   | number        | number        |
| Yes      | numeric metric | pickup_centroid_longitude   | Pickup Centroid Longitude  | number        | number        |
| Yes      | series tag     | pickup_centroid_location    | Pickup Centroid Location   | point         | point         |
| Yes      | numeric metric | dropoff_centroid_latitude   | Dropoff Centroid Latitude  | number        | number        |
| Yes      | numeric metric | dropoff_centroid_longitude  | Dropoff Centroid Longitude | number        | number        |
| Yes      | series tag     | dropoff_centroid_location   | Dropoff Centroid Location  | point         | point         |
| Yes      | numeric metric | :@computed_region_vrxf_vc4k | Community Areas            | number        | number        |
```

## Time Field

```ls
Value = trip_start_timestamp
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = trip_end_timestamp
```

## Data Commands

```ls
series e:wrvz-psew d:2014-07-04T20:15:00.000Z t:trip_id=6b2c51e58fa7d3ac60f1c72d9fbdbda87f3ccfd9 t:dropoff_centroid_location="POINT (-87.620763 41.898332)" t:pickup_census_tract=17031081600 t:dropoff_census_tract=17031081300 t:pickup_centroid_location="POINT (-87.628874 41.892073)" t:taxi_id=9a2c3954c98603a0faa433c5f816a5da927f9aafad246005113146990b5e0787ca840b45f115f1131903eaf47ee23d20f33a88267951efa19e907131e2de38e5 t:company="5074 - Ahzmi Inc" t:payment_type=Cash m:pickup_community_area=8 m:dropoff_community_area=8 m:pickup_centroid_latitude=41.892072635 m:dropoff_centroid_longitude=-87.620762865 m:trip_miles=0.8 m:dropoff_centroid_latitude=41.898331794 m:trip_total=6.85 m::@computed_region_vrxf_vc4k=37 m:pickup_centroid_longitude=-87.628874157 m:fare=5.85 m:trip_seconds=420 m:tips=0 m:tolls=0 m:extras=1

series e:wrvz-psew d:2013-03-31T16:15:00.000Z t:trip_id=6b2c51e829c8045e1cd22f720aa191cddc368093 t:taxi_id=a3c8065ab5ffa7d0ff73ea972ea84cca15d327fe32472a22cdb4256453281e875aacceba26b8f5c7841ce82993be9fc23c40b9ffdaa5325d4e95bce6f26b7844 t:company="Taxi Affiliation Services" t:payment_type=Cash m:trip_miles=0 m:trip_total=3.25 m:fare=3.25 m:trip_seconds=0 m:tips=0 m:tolls=0 m:extras=0

series e:wrvz-psew d:2014-07-02T05:15:00.000Z t:trip_id=6b2c52741bd07c22f336521e2b17503b08c5ce81 t:dropoff_centroid_location="POINT (-87.771167 41.97883)" t:pickup_centroid_location="POINT (-87.655998 41.944227)" t:taxi_id=c6d134b4154f45bc6ba23522e7a43d30845751164754dc6fab67f5a73926bdaf506c4adf3b8d9d004bb1ec97818ac000a330bb0f1a6e2ad730f2a82d733fb67e t:company="Dispatch Taxi Affiliation" t:payment_type=Cash m:pickup_community_area=6 m:dropoff_community_area=11 m:pickup_centroid_latitude=41.944226601 m:dropoff_centroid_longitude=-87.771166703 m:trip_miles=8.8 m:dropoff_centroid_latitude=41.978829526 m:trip_total=21.65 m::@computed_region_vrxf_vc4k=57 m:pickup_centroid_longitude=-87.655998182 m:fare=21.65 m:trip_seconds=1440 m:tips=0 m:tolls=0 m:extras=0
```

## Meta Commands

```ls
metric m:trip_seconds p:long l:"Trip Seconds" d:"Time of the trip in seconds." t:dataTypeName=number

metric m:trip_miles p:long l:"Trip Miles" d:"Distance of the trip in miles." t:dataTypeName=number

metric m:pickup_community_area p:long l:"Pickup Community Area" d:"The Community Area where the trip began." t:dataTypeName=number

metric m:dropoff_community_area p:long l:"Dropoff Community Area" d:"The Community Area where the trip ended." t:dataTypeName=number

metric m:fare p:double l:Fare d:"The fare for the trip." t:dataTypeName=money

metric m:tips p:double l:Tips d:"The tip for the trip. Cash tips generally will not be recorded." t:dataTypeName=money

metric m:tolls p:double l:Tolls d:"The tolls for the trip." t:dataTypeName=money

metric m:extras p:double l:Extras d:"Extra charges for the trip." t:dataTypeName=money

metric m:trip_total p:double l:"Trip Total" d:"Total cost of the trip, the total of the previous columns." t:dataTypeName=money

metric m:pickup_centroid_latitude p:long l:"Pickup Centroid Latitude" d:"The latitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy." t:dataTypeName=number

metric m:pickup_centroid_longitude p:long l:"Pickup Centroid Longitude" d:"The longitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy." t:dataTypeName=number

metric m:dropoff_centroid_latitude p:long l:"Dropoff Centroid Latitude" d:"The latitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy." t:dataTypeName=number

metric m:dropoff_centroid_longitude p:long l:"Dropoff Centroid Longitude" d:"The longitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy." t:dataTypeName=number

metric m::@computed_region_vrxf_vc4k p:long l:"Community Areas" t:dataTypeName=number

entity e:wrvz-psew l:"Taxi Trips" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/wrvz-psew

property e:wrvz-psew t:meta.view v:id=wrvz-psew v:category=Transportation v:attributionLink=https://www.cityofchicago.org v:averageRating=0 v:name="Taxi Trips" v:attribution="City of Chicago"

property e:wrvz-psew t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:wrvz-psew t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| trip_id                                  | taxi_id                                                                                                                          | trip_start_timestamp | trip_end_timestamp  | trip_seconds | trip_miles | pickup_census_tract | dropoff_census_tract | pickup_community_area | dropoff_community_area | fare  | tips | tolls | extras | trip_total | payment_type | company                   | pickup_centroid_latitude | pickup_centroid_longitude | pickup_centroid_location     | dropoff_centroid_latitude | dropoff_centroid_longitude | dropoff_centroid_location    | :@computed_region_vrxf_vc4k | 
| ======================================== | ================================================================================================================================ | ==================== | =================== | ============ | ========== | =================== | ==================== | ===================== | ====================== | ===== | ==== | ===== | ====== | ========== | ============ | ========================= | ======================== | ========================= | ============================ | ========================= | ========================== | ============================ | =========================== | 
| 6b2c51e58fa7d3ac60f1c72d9fbdbda87f3ccfd9 | 9a2c3954c98603a0faa433c5f816a5da927f9aafad246005113146990b5e0787ca840b45f115f1131903eaf47ee23d20f33a88267951efa19e907131e2de38e5 | 2014-07-04T20:15:00  | 2014-07-04T20:30:00 | 420          | 0.8        | 17031081600         | 17031081300          | 8                     | 8                      | 5.85  | 0    | 0     | 1      | 6.85       | Cash         | 5074 - Ahzmi Inc          | 41.892072635             | -87.628874157             | POINT (-87.628874 41.892073) | 41.898331794              | -87.620762865              | POINT (-87.620763 41.898332) | 37                          | 
| 6b2c51e829c8045e1cd22f720aa191cddc368093 | a3c8065ab5ffa7d0ff73ea972ea84cca15d327fe32472a22cdb4256453281e875aacceba26b8f5c7841ce82993be9fc23c40b9ffdaa5325d4e95bce6f26b7844 | 2013-03-31T16:15:00  | 2013-03-31T16:15:00 | 0            | 0          |                     |                      |                       |                        | 3.25  | 0    | 0     | 0      | 3.25       | Cash         | Taxi Affiliation Services |                          |                           |                              |                           |                            |                              |                             | 
| 6b2c52741bd07c22f336521e2b17503b08c5ce81 | c6d134b4154f45bc6ba23522e7a43d30845751164754dc6fab67f5a73926bdaf506c4adf3b8d9d004bb1ec97818ac000a330bb0f1a6e2ad730f2a82d733fb67e | 2014-07-02T05:15:00  | 2014-07-02T05:45:00 | 1440         | 8.8        |                     |                      | 6                     | 11                     | 21.65 | 0    | 0     | 0      | 21.65      | Cash         | Dispatch Taxi Affiliation | 41.944226601             | -87.655998182             | POINT (-87.655998 41.944227) | 41.978829526              | -87.771166703              | POINT (-87.771167 41.97883)  | 57                          | 
| 6b2c52cc7be3e53a833d85b40d623ecc93a71a24 | d23eb5fbba65c15fb2b8b3f51e635c943718b9ddb5c42300c4dc10f717934a1d5f1edd65c80ee86697a20686e9bb93438dc4d6dcd1ecaeb23b478e9776664ca2 | 2014-02-23T02:45:00  | 2014-02-23T02:45:00 | 300          | 2.8        |                     |                      | 24                    | 8                      | 8.05  | 0    | 0     | 0      | 8.05       | Cash         | Choice Taxi Association   | 41.901206994             | -87.676355989             | POINT (-87.676356 41.901207) | 41.899602111              | -87.633308037              | POINT (-87.633308 41.899602) | 25                          | 
| 6b2c52dbd0e799da5114abaad21d3b6b28d45228 | 6858949bea066169d802063484d033723c17ceb0a1a560ba53992093813632cd600ad1b69a2c33f5b8244de872b6bc72348fdbe3255b2575164692743504693c | 2015-03-24T12:45:00  | 2015-03-24T12:45:00 | 420          | 1.2        | 17031839100         | 17031081800          | 32                    | 8                      | 6.25  | 2    | 0     | 0      | 8.25       | Credit Card  | Taxi Affiliation Services | 41.880994471             | -87.632746489             | POINT (-87.632746 41.880994) | 41.89321636               | -87.63784421               | POINT (-87.637844 41.893216) | 38                          | 
| 6b2c52f3cd01d3bd2ea37cd0ec1d3ad6e2814305 | 9aff6a31657cc79088572077ee7fb021545aa04997c8fc4f276e7e7d0afffbacc6e65722740d518b3d6667a6a194d2f1022a67b3979c8f22fb260943e3c904cf | 2013-07-20T14:00:00  | 2013-07-20T14:15:00 | 600          | 0          | 17031841900         | 17031330100          | 28                    | 33                     | 7.45  | 0    | 0     | 0      | 7.45       | Cash         | Taxi Affiliation Services | 41.867902418             | -87.642958665             | POINT (-87.642959 41.867902) | 41.859349715              | -87.617358006              | POINT (-87.617358 41.85935)  | 29                          | 
| 6b2c533d099ac58f528823e7bbca18a4335877a1 | a565fa0a2e21feff33d1de1a29c01d6c86cbd57a6e83b0fc630f4b37ba67bcae53f448fcb795bbaf3a3c282b4a813dea3e9a15ab6eeefcc3c3e3fa770214bbf6 | 2013-06-13T21:45:00  | 2013-06-13T22:00:00 | 1080         | 0          |                     |                      |                       |                        | 18.25 | 5    | 0     | 0      | 23.25      | Credit Card  | Chicago Elite Cab Corp.   |                          |                           |                              |                           |                            |                              |                             | 
| 6b2c536f233e559123e2868bff5b5a7378199600 | 1acbc55c0db794a73f1b5e612654b60ff74bfb69ef53bb3445c93c0d1d7d8897a2f7ab9c525b3c87b846c618008efa8ffbc1b744213d488459dee9510a1a18fe | 2013-08-28T10:45:00  | 2013-08-28T10:45:00 | 0            | 0          | 17031280100         | 17031833000          | 28                    | 28                     | 3.25  | 0    | 0     | 0      | 3.25       | Cash         |                           | 41.885300022             | -87.642808466             | POINT (-87.642808 41.8853)   | 41.88528132               | -87.6572332                | POINT (-87.657233 41.885281) | 29                          | 
| 6b2fa384ad9e05114dfeb9a742967465f26b7218 | 4985ff73a0a31882be89c04cbe252165cc8633fb00cb1e2285677a75d1f098c2585d02bb0e66a63617bde79e748b44040c7393b120236ca472b4931e18ec45a0 | 2013-04-19T13:00:00  | 2013-04-19T13:00:00 | 0            | 0          |                     |                      |                       |                        | 8.15  | 1.63 | 0     | 0      | 9.78       | Credit Card  | Chicago Elite Cab Corp.   |                          |                           |                              |                           |                            |                              |                             | 
| 6b2c53da2908717452bbf38619218af93dbe08ba | 52c3ffa685a3b5ced3d16461deec5a0326086bee3d8f6a3699460f1c2c1dae0b239fbbb9b9cece5401785fcf9b4a378ff9675f32598bb94fb26898c1cc2289bc | 2013-03-12T08:15:00  | 2013-03-12T08:45:00 | 1860         | 14.63      |                     |                      | 35                    | 16                     | 30.25 | 0    | 0     | 0      | 30.25      | Cash         |                           | 41.835117986             | -87.618677767             | POINT (-87.618678 41.835118) | 41.953582125              | -87.72345239               | POINT (-87.723452 41.953582) | 1                           | 
```