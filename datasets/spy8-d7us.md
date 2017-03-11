# Sept 2014 ECY Stations with Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen and pH

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/spy8-d7us/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/sept-2014-ecy-stations-with-exceeded-criteria-for-fecal-bacteria-temperature-oxygen-and-ph-f89c7)
* Id = spy8-d7us
* Name = Sept 2014 ECY Stations with Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen and pH
* Attribution = Washingotn State Department of Ecology
* Attribution Link = http://www.ecy.wa.gov/programs/eap/fw_riv/rv_main.html
* Category = Natural Resources & Environment
* Created = 2014-11-10T17:17:47Z
* Publication Date = 2014-11-10T17:20:29Z
* Rows Updated = 2014-11-10T17:18:03Z

## Description



## Columns

```ls
| Name                     | Field Name               | Data Type     | Render Type   | Schema Type    | Included | 
| ======================== | ======================== | ============= | ============= | ============== | ======== | 
| Station                  | station                  | text          | text          | series tag     | Yes      | 
| Station Name             | station_name             | text          | text          | series tag     | Yes      | 
| WQ Violation Date        | wq_violation_date        | calendar_date | calendar_date | time           | Yes      | 
| Time                     | time                     | calendar_date | calendar_date |                | No       | 
| Variable/Units           | variable_units           | text          | text          | series tag     | Yes      | 
| Sample Result or geo.mn  | sample_result_or_geo_mn  | number        | number        | numeric metric | Yes      | 
| Criterion                | criterion                | number        | number        | numeric metric | Yes      | 
| Percent exceeds standard | percent_exceeds_standard | number        | number        | numeric metric | Yes      | 
```

## Time Field

```ls
Value = wq_violation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = time
Annotation Fields = 
```

## Data Commands

```ls
series e:spy8-d7us d:2014-09-09T00:00:00.000Z t:station_name="Pend Oreille R @ Newport" t:station=62A150 t:variable_units="pH (pH)" m:criterion=8.5 m:percent_exceeds_standard=0.6 m:sample_result_or_geo_mn=8.6

series e:spy8-d7us d:2014-09-09T00:00:00.000Z t:station_name="Pend Oreille R @ Metaline Falls" t:station=62A090 t:variable_units="pH (pH)" m:criterion=8.5 m:percent_exceeds_standard=1.3 m:sample_result_or_geo_mn=8.6

series e:spy8-d7us d:2014-09-08T00:00:00.000Z t:station_name="Columbia R @ Northport" t:station=61A070 t:variable_units="Oxygen (mg/L)" m:criterion=9.5 m:percent_exceeds_standard=7.8 m:sample_result_or_geo_mn=8.8
```

## Meta Commands

```ls
metric m:sample_result_or_geo_mn l:"Sample Result or geo.mn" t:dataTypeName=number

metric m:criterion p:integer l:Criterion t:dataTypeName=number

metric m:percent_exceeds_standard l:"Percent exceeds standard" t:dataTypeName=number

entity e:spy8-d7us l:"Sept 2014 ECY Stations with Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen and pH" t:attribution="Washingotn State Department of Ecology" t:url=https://data.wa.gov/api/views/spy8-d7us

property e:spy8-d7us t:meta.view d:2017-03-03T14:28:35.867Z v:id=spy8-d7us v:category="Natural Resources & Environment" v:attributionLink=http://www.ecy.wa.gov/programs/eap/fw_riv/rv_main.html v:averageRating=0 v:name="Sept 2014 ECY Stations with Exceeded Criteria For Fecal Bacteria, Temperature, Oxygen and pH" v:attribution="Washingotn State Department of Ecology"

property e:spy8-d7us t:meta.view.owner d:2017-03-03T14:28:35.867Z v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:spy8-d7us t:meta.view.tableauthor d:2017-03-03T14:28:35.867Z v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```