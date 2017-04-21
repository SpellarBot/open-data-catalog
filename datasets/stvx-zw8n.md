# Plumbing Continuing Education Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/plumbing-continuing-education-listing-58753) |
| Metadata | [Link](https://data.illinois.gov/api/views/stvx-zw8n) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/stvx-zw8n/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/stvx-zw8n/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | stvx-zw8n |
| Name | Plumbing Continuing Education Listing |
| Attribution | Illinois Department of Public Health - Plumbing Program |
| Category | Public Health |
| Tags | plumbing, plumbers, continuing education |
| Created | 2014-10-31T20:38:16Z |
| Publication Date | 2017-04-12T13:46:47Z |

## Description

The dataset provides information on upcoming plumbing continuing education courses that licensees may attend to fulfill the requirements of the Illinois Plumbing Code. Last Updated April 2017.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | ============== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag     | training_type             | Training Type             | text          | text          |
| Yes      | time           | date                      | Date                      | calendar_date | calendar_date |
| Yes      | series tag     | time                      | Time                      | text          | text          |
| Yes      | series tag     | location                  | Location                  | text          | text          |
| No       |                | location_address          | Location Address          | text          | text          |
| Yes      | series tag     | location_city             | Location City             | text          | text          |
| Yes      | series tag     | location_state            | Location State            | text          | text          |
| Yes      | series tag     | location_zip_code         | Location Zip Code         | text          | number        |
| Yes      | series tag     | contact_name              | Contact Name              | text          | text          |
| Yes      | series tag     | contact_phone             | Contact Phone             | text          | text          |
| Yes      | series tag     | contact_email             | Contact Email             | text          | text          |
| Yes      | series tag     | contact_website           | Contact Website           | text          | text          |
| Yes      | series tag     | maximum_seating           | Maximum Seating           | text          | text          |
| Yes      | numeric metric | fee                       | Fee                       | money         | money         |
| Yes      | numeric metric | credit_hours              | Credit Hours              | number        | number        |
| Yes      | series tag     | state_sponsored           | State Sponsored?          | text          | text          |
| Yes      | series tag     | comments_special_criteria | Comments/Special Criteria | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = location_address
```

## Data Commands

```ls
series e:stvx-zw8n d:2017-08-26T00:00:00.000Z t:location_state=IL t:time="10:00-2:00 p.m." t:contact_email=fosterbruce@sbcglobal.net t:location="NIU Hoffman Estate Conference Center" t:contact_name="Bruce Foster" t:training_type="Plumber Continuing Education" t:contact_phone=847-845-6883 t:state_sponsored=No t:contact_website=www.plumbing.name t:maximum_seating=Unlimited t:location_zip_code=60192 t:location_city="Hoffman Estates" m:fee=100 m:credit_hours=4

series e:stvx-zw8n d:2017-04-21T00:00:00.000Z t:contact_email=shelly@ilphcc.com t:location="Heartland College Bloomington/Normal" t:comments_special_criteria="Main Campus-Challenger Learning Center" t:contact_phone=217-522-7219 t:training_type="Plumber Continuing Education" t:maximum_seating=100 t:location_city=Normal t:location_state=IL t:time="1:00-5:00 p.m." t:contact_name="Shelly Lot" t:state_sponsored=Yes t:contact_website=www.ilphcc.com t:location_zip_code=61761 m:fee=75 m:credit_hours=4

series e:stvx-zw8n d:2017-08-23T00:00:00.000Z t:location_state=IL t:time="4:00-8:00 p.m." t:contact_email=plumbingclass@yahoo.com t:location="Victoria Restaurant" t:contact_name="George Swietczak" t:training_type="Plumber Continuing Education" t:contact_phone=312-969-6902 t:state_sponsored=No t:contact_website=www.illinoisplumbingclass.com t:maximum_seating=25 t:location_zip_code=60164 t:location_city="Melrose Park" m:fee=80 m:credit_hours=4
```

## Meta Commands

```ls
metric m:fee p:integer l:Fee t:dataTypeName=money

metric m:credit_hours p:integer l:"Credit Hours" t:dataTypeName=number

entity e:stvx-zw8n l:"Plumbing Continuing Education Listing" t:attribution="Illinois Department of Public Health - Plumbing Program" t:url=https://data.illinois.gov/api/views/stvx-zw8n

property e:stvx-zw8n t:meta.view v:id=stvx-zw8n v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/plumbing v:averageRating=0 v:name="Plumbing Continuing Education Listing" v:attribution="Illinois Department of Public Health - Plumbing Program"

property e:stvx-zw8n t:meta.view.license v:name="Public Domain"

property e:stvx-zw8n t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:stvx-zw8n t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| training_type                   | date                | time              | location                             | location_address                | location_city   | location_state | location_zip_code | contact_name               | contact_phone | contact_email             | contact_website                                                      | maximum_seating | fee | credit_hours | state_sponsored | comments_special_criteria              | 
| =============================== | =================== | ================= | ==================================== | =============================== | =============== | ============== | ================= | ========================== | ============= | ========================= | ==================================================================== | =============== | === | ============ | =============== | ====================================== | 
| Plumber Continuing Education    | 2017-08-26T00:00:00 | 10:00-2:00 p.m.   | NIU Hoffman Estate Conference Center | 5555 Trillium Blvd.             | Hoffman Estates | IL             | 60192             | Bruce Foster               | 847-845-6883  | fosterbruce@sbcglobal.net | www.plumbing.name                                                    | Unlimited       | 100 | 4            | No              |                                        | 
| Plumber Continuing Education    | 2017-04-21T00:00:00 | 1:00-5:00 p.m.    | Heartland College Bloomington/Normal | 1500 West Raab Road             | Normal          | IL             | 61761             | Shelly Lot                 | 217-522-7219  | shelly@ilphcc.com         | www.ilphcc.com                                                       | 100             | 75  | 4            | Yes             | Main Campus-Challenger Learning Center | 
| Plumber Continuing Education    | 2017-08-23T00:00:00 | 4:00-8:00 p.m.    | Victoria Restaurant                  | 2080 N. Mannheim Road           | Melrose Park    | IL             | 60164             | George Swietczak           | 312-969-6902  | plumbingclass@yahoo.com   | www.illinoisplumbingclass.com                                        | 25              | 80  | 4            | No              |                                        | 
| Plumber Continuing Education    | 2017-04-25T00:00:00 | 5:00-9:00 p.m.    |                                      | 2587 Millennium Dr., Unit K2    | Elgin           | IL             | 60124             | Rick Marvel                | 847-836-8690  | info@testgauge.net        |                                                                      | 25              | 85  | 4            | No              |                                        | 
| Irrigation Continuing Education | 2017-05-10T00:00:00 | 8:00 - 12:00 p.m. | Swanhills Golf                       | 2600 Gustafson Road             | Belvidere       | IL             | 61008             | Corinee Butler             | 703-536-7080  | www.irrigation.org        | http://store.irrigation.org/events/registration.aspx?event=EILBMAY17 |                 | 165 | 4            | No              | 4 hour Irrigation refresher course     | 
| Plumber Continuing Education    | 2017-10-12T00:00:00 | 10:00-2:00 p.m.   | NIU Hoffman Estate Conference Center | 5555 Trillium Blvd.             | Hoffman Estates | IL             | 60192             | Bruce Foster               | 847-845-6883  | fosterbruce@sbcglobal.net | www.plumbing.name                                                    | Unlimited       | 100 | 4            | No              |                                        | 
| Plumber Continuing Education    | 2017-04-22T00:00:00 | 9:00-1:00 p.m.    | The Children's Center of Lake Forest | 28457 N. Ballard Drive, Unit A2 | Lake Forest     | IL             | 60045             | Mirna Magana               | 847-361-7193  | codeplumbinged@yahoo.com  |                                                                      | 50              | 50  | 4            | No              |                                        | 
| Plumber Continuing Education    | 2017-11-01T00:00:00 | 9:00-3:00 p.m.    | Double Tree Hotel-Veterans Pkwy      | 10 Brickyard Drive              | Bloomington     | IL             | 61701             | Kim Bateman or Marcia Webb | 618-650-2030  |                           |                                                                      | 250             | 115 | 5            | Yes             | Backflow Symposium                     | 
| Plumber Continuing Education    | 2017-04-15T00:00:00 | 10:00-2:00 p.m.   | NIU Hoffman Estate Conference Center | 5555 Trillium Blvd.             | Hoffman Estates | IL             | 60192             | Bruce Foster               | 847-845-6883  | fosterbruce@sbcglobal.net | www.plumbing.name                                                    | Unlimited       | 100 | 4            | No              |                                        | 
| Plumber Continuing Education    | 2017-05-11T00:00:00 | 10:00-2:00 p.m.   | NIU Hoffman Estate Conference Center | 5555 Trillium Blvd.             | Hoffman Estates | IL             | 60192             | Bruce Foster               | 847-845-6883  | fosterbruce@sbcglobal.net | www.plumbing.name                                                    | Unlimited       | 100 | 4            | No              |                                        | 
```