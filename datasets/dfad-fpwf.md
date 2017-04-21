# HRA Special Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hra-special-services-c6fcb) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/dfad-fpwf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/dfad-fpwf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/dfad-fpwf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | dfad-fpwf |
| Name | HRA Special Services |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | hra special services, jobs and economic mobility |
| Created | 2013-03-26T16:56:47Z |
| Publication Date | 2013-03-26T17:58:27Z |

## Description

Listing of special services offered by HRA along with their descriptions.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | services    | Services    | text      | text        |
| Yes      | series tag  | description | Description | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dfad-fpwf d:2013-03-26T09:56:48.000Z t:services="Legal Services" t:description="Sanctuary for Families - Bronx Queens Legal Services - Queens STEPS to End Family Violence - Manhattan/SI Urban Justice Center - Brooklyn, Queens" m:row_number.dfad-fpwf=1

series e:dfad-fpwf d:2013-03-26T09:56:48.000Z t:services="New York Asian Women's Center" t:description="24-hour Hotline; Children's Services. Languages: Mandarin, Cantonese, Taiwanese, Korean, Vietnamese, Japanese, Hindi, Bengali, Urdu, Marathi, Fouzhounese, Shanghainese, Laotian and Thai" m:row_number.dfad-fpwf=2

series e:dfad-fpwf d:2013-03-26T09:56:48.000Z t:services="FEGS Center for Women & Families" t:description="Legal advocacy, community training and technical assistance on DV, trauma, and immigration. Languages: Spanish, French, Portugese, Italian" m:row_number.dfad-fpwf=3
```

## Meta Commands

```ls
metric m:row_number.dfad-fpwf p:long l:"Row Number"

entity e:dfad-fpwf l:"HRA Special Services" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/dfad-fpwf

property e:dfad-fpwf t:meta.view v:id=dfad-fpwf v:category="Social Services" v:averageRating=0 v:name="HRA Special Services" v:attribution="Human Resources Administration (HRA)"

property e:dfad-fpwf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:dfad-fpwf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | services                                | description                                                                                                                                                                               | 
| =========== | ======================================= | ========================================================================================================================================================================================= | 
| 1364291808  | Legal Services                          | Sanctuary for Families - Bronx Queens Legal Services - Queens STEPS to End Family Violence - Manhattan/SI Urban Justice Center - Brooklyn, Queens                                         | 
| 1364291808  | New York Asian Women's Center           | 24-hour Hotline; Children's Services. Languages: Mandarin, Cantonese, Taiwanese, Korean, Vietnamese, Japanese, Hindi, Bengali, Urdu, Marathi, Fouzhounese, Shanghainese, Laotian and Thai | 
| 1364291808  | FEGS Center for Women & Families        | Legal advocacy, community training and technical assistance on DV, trauma, and immigration. Languages: Spanish, French, Portugese, Italian                                                | 
| 1364291808  | Sanctuary for Families                  | Children's Services. Languages: Spanish, French, Japanese, Korean, Bengali, Gujarati, and Twi.                                                                                            | 
| 1364291808  | Barrier Free Living                     | Services for individuals with physical and mental disabilities and their children.                                                                                                        | 
| 1364291808  | STEPS to End Family Violence            | Children's Therapy, teens, disabled population, substance abuse, immigration services. Languages: Spanish, Portuguese, Arabic, French, Italian.                                           | 
| 1364291808  | Violence Intervention Program           | Children's Services; 24-hour Hotline; Spanish                                                                                                                                             | 
| 1364291808  | Queens Legal Services                   | Languages: Hindi, Urdu, Punjabi, Spanish, Mandarin, Romanian, French.                                                                                                                     | 
| 1364291808  | NYC Gay & Lesbian Anti-Violence Program | Training and technical assistance on LGBTQ DV issues, court monitoring, precinct accompaniment.                                                                                           | 
| 1364291808  | JBFCS DV Program                        | Languages: Spanish and Russian                                                                                                                                                            | 
```