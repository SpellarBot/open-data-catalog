# [alpha] Field Dictionary for Open Data Portal Datasets

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/field-dictionary-for-open-data-portal-datasets) |
| Metadata | [Link](https://data.sfgov.org/api/views/wn8x-uk7i) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wn8x-uk7i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wn8x-uk7i/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wn8x-uk7i |
| Name | [alpha] Field Dictionary for Open Data Portal Datasets |
| Category | City Management and Ethics |
| Tags | data dictionary, field definitions, metadata |
| Created | 2016-09-29T01:04:40Z |
| Publication Date | 2017-01-20T01:09:01Z |

## Description

Note: This dataset is under active development and the schema is subject to change without notice. This represents the current list of fields available within the open data portal organized by dataset. Fields may be documented within through attached documentation or not at all. Over time we will collect and merge all field definitions to this dataset to simplify access to field documentation. It will be updated on a rolling basis.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | columnid                 | columnID                 | text      | text        |
| Yes      | series tag  | datasetid                | datasetID                | text      | text        |
| Yes      | series tag  | inventoryid              | inventoryID              | text      | text        |
| Yes      | series tag  | open_data_portal_url     | Open Data Portal URL     | url       | url         |
| Yes      | series tag  | department               | Department               | text      | text        |
| Yes      | series tag  | dataset_name             | Dataset Name             | text      | text        |
| Yes      | series tag  | field_name               | Field Name               | text      | text        |
| Yes      | series tag  | field_alias              | Field Alias              | text      | text        |
| Yes      | series tag  | field_type               | Field Type               | text      | text        |
| Yes      | series tag  | api_key                  | API Key                  | text      | text        |
| Yes      | series tag  | field_definition         | Field Definition         | text      | text        |
| No       |             | field_type_flag          | Field Type Flag          | text      | text        |
| Yes      | series tag  | data_dictionary_attached | Data Dictionary Attached | checkbox  | checkbox    |
| Yes      | series tag  | field_documented         | Field Documented         | checkbox  | checkbox    |
| Yes      | series tag  | attachment_url           | Attachment URL           | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = field_type_flag
```

## Data Commands

```ls
series e:wn8x-uk7i d:2017-04-21T04:35:50.000Z t:field_name=Title t:field_documented=false t:field_type=text t:data_dictionary_attached=false t:datasetid=yitu-d5am t:api_key=title t:department="Film Commission" t:field_definition="The name of the film or television show that was filmed in San Francisco." t:columnid=yitu-d5am_title t:open_data_portal_url=http://data.sfgov.org/resource/yitu-d5am t:inventoryid=FLM-0001 t:dataset_name="Film Locations in San Francisco" m:row_number.wn8x-uk7i=1

series e:wn8x-uk7i d:2017-04-21T04:35:50.000Z t:field_name="Release Year" t:field_documented=false t:field_type=numeric t:data_dictionary_attached=false t:datasetid=yitu-d5am t:api_key=release_year t:department="Film Commission" t:field_definition="The year the film or television show was released to the public." t:columnid=yitu-d5am_release_year t:open_data_portal_url=http://data.sfgov.org/resource/yitu-d5am t:inventoryid=FLM-0001 t:dataset_name="Film Locations in San Francisco" m:row_number.wn8x-uk7i=2

series e:wn8x-uk7i d:2017-04-21T04:35:50.000Z t:field_name=Locations t:field_documented=false t:field_type=text t:data_dictionary_attached=false t:datasetid=yitu-d5am t:api_key=locations t:department="Film Commission" t:field_definition="The location in San Francisco where part of the film or television show was shot/filmed." t:columnid=yitu-d5am_locations t:open_data_portal_url=http://data.sfgov.org/resource/yitu-d5am t:inventoryid=FLM-0001 t:dataset_name="Film Locations in San Francisco" m:row_number.wn8x-uk7i=3
```

## Meta Commands

```ls
metric m:row_number.wn8x-uk7i p:long l:"Row Number"

entity e:wn8x-uk7i l:"[alpha] Field Dictionary for Open Data Portal Datasets" t:url=https://data.sfgov.org/api/views/wn8x-uk7i

property e:wn8x-uk7i t:meta.view v:id=wn8x-uk7i v:category="City Management and Ethics" v:averageRating=0 v:name="[alpha] Field Dictionary for Open Data Portal Datasets"

property e:wn8x-uk7i t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wn8x-uk7i t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:wn8x-uk7i t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | columnid                     | datasetid | inventoryid | open_data_portal_url                             | department      | dataset_name                    | field_name         | field_alias | field_type | api_key            | field_definition                                                                                   | field_type_flag | data_dictionary_attached | field_documented | attachment_url | 
| =========== | ============================ | ========= | =========== | ================================================ | =============== | =============================== | ================== | =========== | ========== | ================== | ================================================================================================== | =============== | ======================== | ================ | ============== | 
| 1492749350  | yitu-d5am_title              | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Title              |             | text       | title              | The name of the film or television show that was filmed in San Francisco.                          |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_release_year       | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Release Year       |             | numeric    | release_year       | The year the film or television show was released to the public.                                   |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_locations          | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Locations          |             | text       | locations          | The location in San Francisco where part of the film or television show was shot/filmed.           |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_fun_facts          | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Fun Facts          |             | text       | fun_facts          | An interesting fact either about the film/television show or about that location in San Francisco. |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_production_company | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Production Company |             | text       | production_company | The company which produced the film or television show.                                            |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_distributor        | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Distributor        |             | text       | distributor        | The company that released the film or television show to the public.                               |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_director           | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Director           |             | text       | director           | The director of the film or television show.                                                       |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_writer             | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Writer             |             | text       | writer             | The main scriptwriter or writers of the film or television show.                                   |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_actor_1            | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Actor 1            |             | text       | actor_1            | Featured or principle actor in the film or television show.                                        |                 | false                    | false            | [null, null]   | 
| 1492749350  | yitu-d5am_actor_2            | yitu-d5am | FLM-0001    | [http://data.sfgov.org/resource/yitu-d5am, null] | Film Commission | Film Locations in San Francisco | Actor 2            |             | text       | actor_2            | Featured or principle actor in the film or television show.                                        |                 | false                    | false            | [null, null]   | 
```