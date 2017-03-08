# Home Health Care - Zip Codes

## Dataset

* [Dataset URL](https://data.medicare.gov/api/views/m5eg-upu5/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/home-health-care-zip-codes-0c0fb)
* [Metadata URL](https://data.medicare.gov/api/views/m5eg-upu5)
* Id = m5eg-upu5
* Name = Home Health Care - Zip Codes
* Category = Home Health Compare
* Tags = [hhc, general information]
* Created = 2012-10-17T19:56:31Z
* Publication Date = 2017-01-26T01:48:47Z
* Rows Updated = 2017-01-05T16:42:03Z

## Description



## Columns

```ls
| Name                            | Field Name      | Data Type | Render Type | Schema Type    | Included | 
| =============================== | =============== | ========= | =========== | ============== | ======== | 
| updated_at                      | :updated_at     | meta_data | meta_data   | time           | No       | 
| State                           | state           | text      | text        | series tag     | Yes      | 
| CMS Certification Number (CCN)* | provider_number | number    | text        | numeric metric | Yes      | 
| ZIP Code                        | zip_code        | text      | text        | series tag     | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:m5eg-upu5 d:2017-01-05T16:16:55.000Z t:zip_code=36104 t:state=AL m:provider_number=17000

series e:m5eg-upu5 d:2017-01-05T16:16:55.000Z t:zip_code=35005 t:state=AL m:provider_number=17008

series e:m5eg-upu5 d:2017-01-05T16:16:55.000Z t:zip_code=35020 t:state=AL m:provider_number=17008
```

## Meta Commands

```ls
metric m:provider_number p:integer l:"CMS Certification Number (CCN)*" d:"formerly Medicare Provider Number" t:dataTypeName=number

entity e:m5eg-upu5 l:"Home Health Care - Zip Codes" t:url=https://data.medicare.gov/api/views/m5eg-upu5

property e:m5eg-upu5 t:meta.view d:2017-03-08T00:01:51.593Z v:id=m5eg-upu5 v:category="Home Health Compare" v:averageRating=0 v:name="Home Health Care - Zip Codes"

property e:m5eg-upu5 t:meta.view.owner d:2017-03-08T00:01:51.593Z v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:m5eg-upu5 t:meta.view.tableauthor d:2017-03-08T00:01:51.593Z v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:m5eg-upu5 t:meta.view.metadata.custom_fields.common_core d:2017-03-08T00:01:51.593Z v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=HomeHealthQualityQuestions@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```