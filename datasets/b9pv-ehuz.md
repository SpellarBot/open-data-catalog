# Soil Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/soil-data) |
| Metadata | [Link](https://data.oregon.gov/api/views/b9pv-ehuz) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/b9pv-ehuz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/b9pv-ehuz/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | b9pv-ehuz |
| Name | Soil Data |
| Attribution | DEQ |
| Category | Public Safety |
| Tags | soil, portland metals emissions |
| Created | 2016-03-08T21:50:36Z |
| Publication Date | 2016-04-20T17:36:57Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                                            | Name                                                                    | Data Type     | Render Type   |
| ======== | ============== | ===================================================================== | ======================================================================= | ============= | ============= |
| No       |                | today_s_date                                                          | Today's Date                                                            | calendar_date | calendar_date |
| Yes      | series tag     | name                                                                  | Name                                                                    | text          | text          |
| Yes      | series tag     | phone                                                                 | Phone                                                                   | phone         | phone         |
| Yes      | series tag     | email                                                                 | Email                                                                   | email         | email         |
| Yes      | time           | date_sampled                                                          | Date Sampled                                                            | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_samples_analyzed                                            | Number of samples analyzed:                                             | number        | number        |
| Yes      | series tag     | description_of_location_of_sampling_on_property_and_depth_of_sampling | Description of location of sampling on property, and depth of sampling: | html          | html          |
| Yes      | series tag     | name_of_certified_lab_used_to_analyze                                 | Name of Certified Lab used to analyze:                                  | text          | text          |
| Yes      | series tag     | results                                                               | List of metals tested for, and results                                  | html          | html          |
| Yes      | series tag     | you_can_include_pdf_of_lab_report                                     | You can include PDF of lab report                                       | document      | document      |
| Yes      | series tag     | responded_to                                                          | Responded to                                                            | checkbox      | checkbox      |
| No       |                | date                                                                  | Date                                                                    | calendar_date | calendar_date |
| Yes      | series tag     | deq_comments                                                          | DEQ Comments                                                            | text          | text          |
```

## Time Field

```ls
Value = date_sampled
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = today_s_date,date
```

## Data Commands

```ls
series e:b9pv-ehuz d:2016-02-21T13:00:00.000Z t:you_can_include_pdf_of_lab_report.file_id=67cf3a54-e990-499f-aca9-341be8114174 t:phone_number=5127058686 t:phone_type=Cell t:you_can_include_pdf_of_lab_report.filename="99999soil16-054-100 Arsenic  Chromium Cadmium (1).pdf" t:deq_comments="duplicate submittal, email sent on 3.21.2016" t:name_of_certified_lab_used_to_analyze="A&L Western Agricultural Labs" t:you_can_include_pdf_of_lab_report.size=55283 t:results="Arsenic 2.22ppm
Chromium 21.8ppm
Cadmium 0.66ppm" t:responded_to=true t:email=toddhoppe1@gmail.com t:name="Todd Hoppe" t:description_of_location_of_sampling_on_property_and_depth_of_sampling="10 samples from fron and backyard. 3-6 inches deep." t:you_can_include_pdf_of_lab_report.content_type=application/pdf m:number_of_samples_analyzed=1

series e:b9pv-ehuz d:2016-03-03T00:00:00.000Z t:you_can_include_pdf_of_lab_report.file_id=b4b22c1e-c1be-4e7e-8913-ec40b8a1b041 t:phone_number=503-310-5766 t:responded_to=true t:results="Cadmium, Arsenic. Results attached in PDF." t:email=matt@cullyneighborhoodfarm.com t:name="Matt Hoffman (for Matt Gordon)" t:you_can_include_pdf_of_lab_report.filename="5620 NE Alberta St, F&BI 603048.pdf" t:description_of_location_of_sampling_on_property_and_depth_of_sampling="PDF attached" t:you_can_include_pdf_of_lab_report.content_type=application/pdf t:deq_comments="email response, 2 soil samples from Cully Garden" t:name_of_certified_lab_used_to_analyze="PDF attached" t:you_can_include_pdf_of_lab_report.size=63196 m:number_of_samples_analyzed=2

series e:b9pv-ehuz d:2016-02-23T09:00:00.000Z t:phone_number=5037743241 t:responded_to=true t:results="Arsenic,Cadmium,Chromium,Copper,Lead,Mercury. Nickel,Zinc" t:email=claytyler@mtscottfuel.com t:name="Clay Tyler" t:deq_comments="email response. Mt Scott commercial topsoil evaluation" t:description_of_location_of_sampling_on_property_and_depth_of_sampling="This is topsoil that I sell. I am know there are two types of Chromium and i am not sure which one they test for or the result are for." t:name_of_certified_lab_used_to_analyze="A&L Western Ag labs" m:number_of_samples_analyzed=1
```

## Meta Commands

```ls
metric m:number_of_samples_analyzed p:integer l:"Number of samples analyzed:" t:dataTypeName=number

entity e:b9pv-ehuz l:"Soil Data" t:attribution=DEQ t:url=https://data.oregon.gov/api/views/b9pv-ehuz

property e:b9pv-ehuz t:meta.view v:id=b9pv-ehuz v:category="Public Safety" v:attributionLink=http://airsafety.oregon.gov/Pages/index.aspx v:averageRating=0 v:name="Soil Data" v:attribution=DEQ

property e:b9pv-ehuz t:meta.view.owner v:id=kms4-i2k5 v:screenName="Lia Boyarshinova" v:displayName="Lia Boyarshinova"

property e:b9pv-ehuz t:meta.view.tableauthor v:id=kms4-i2k5 v:screenName="Lia Boyarshinova" v:roleName=editor v:displayName="Lia Boyarshinova"
```

## Top Records

```ls
| today_s_date        | name                           | phone                | email                          | date_sampled        | number_of_samples_analyzed | description_of_location_of_sampling_on_property_and_depth_of_sampling                                                                   | name_of_certified_lab_used_to_analyze         | results                                                      | you_can_include_pdf_of_lab_report                                                                                    | responded_to | date                | deq_comments                                           | 
| =================== | ============================== | ==================== | ============================== | =================== | ========================== | ======================================================================================================================================= | ============================================= | ============================================================ | ==================================================================================================================== | ============ | =================== | ====================================================== | 
|                     | Todd Hoppe                     | [5127058686, Cell]   | toddhoppe1@gmail.com           | 2016-02-21T13:00:00 | 1                          | 10 samples from fron and backyard. 3-6 inches deep.                                                                                     | A&L Western Agricultural Labs                 | Arsenic 2.22ppm Chromium 21.8ppm Cadmium 0.66ppm             | [application/pdf, 67cf3a54-e990-499f-aca9-341be8114174, 99999soil16-054-100 Arsenic Chromium Cadmium (1).pdf, 55283] | true         | 2016-03-21T00:00:00 | duplicate submittal, email sent on 3.21.2016           | 
|                     | Matt Hoffman (for Matt Gordon) | [503-310-5766, null] | matt@cullyneighborhoodfarm.com | 2016-03-03T00:00:00 | 2                          | PDF attached                                                                                                                            | PDF attached                                  | Cadmium, Arsenic. Results attached in PDF.                   | [application/pdf, b4b22c1e-c1be-4e7e-8913-ec40b8a1b041, 5620 NE Alberta St, F&BI 603048.pdf, 63196]                  | true         | 2016-03-21T00:00:00 | email response, 2 soil samples from Cully Garden       | 
|                     | Clay Tyler                     | [5037743241, null]   | claytyler@mtscottfuel.com      | 2016-02-23T09:00:00 | 1                          | This is topsoil that I sell. I am know there are two types of Chromium and i am not sure which one they test for or the result are for. | A&L Western Ag labs                           | Arsenic,Cadmium,Chromium,Copper,Lead,Mercury. Nickel,Zinc    | [null, null, null, null]                                                                                             | true         | 2016-03-22T00:00:00 | email response. Mt Scott commercial topsoil evaluation | 
|                     | Megan Jones Clegg              | [5038061272, null]   | megjonesi@gmail.com            | 2016-02-29T00:00:00 | 1                          | Backyard - raised garden bed. Took samle from top 6 inches of soil.                                                                     | A & L Western Agricultural Laboratories, Inc. | Arsenic 3.17 ppm, chromium 18.6 ppm, cadmium 0.43 ppm        | [application/pdf, ff91c298-6975-4c43-a488-eb7e9c4d1b93, Clegg Soil Sample.pdf, 51559]                                | true         | 2016-03-21T00:00:00 | email response                                         | 
|                     | Kyle Goulard                   | [5037560320, Cell]   | kgoulard@gmail.com             | 2016-02-25T09:00:00 | 2                          | Raised garden beds, top 6 inches of soil                                                                                                | A & L WESTERN AGRICULTURAL LABORATORIES, INC. | Arsenic and Cadmium                                          | [application/pdf, 495cc270-c30f-4b79-9f6b-1b6667143fd4, 99999soil16-056-130 Cadmium Arsenic.pdf, 50604]              | true         | 2016-03-21T00:00:00 | email response                                         | 
| 2016-05-12T16:40:00 | Bette Briggs                   | [503-949-8876, Cell] | bettebriggs@gmail.com          | 2016-03-23T08:00:00 | 1                          | Errol Heights Community Garden, Plot 17J, southeast corner Sample consisting of leaves from Kale plant that wintered over 2015-2016     | A & L WESTERN AGRICULTURAL LABORATORIES, INC. | EPA 503 METALS PLAN ANALYSIS, see attached PDF of lab report | [application/pdf, 8bf5a179-b84e-440f-a21a-89638950eda8, 16083077 BETTE BRIGGS PLANT EPA 503 Metals.pdf, 89593]       |              |                     |                                                        | 
| 2016-05-12T16:40:00 | Bette Briggs                   | [503-949-8876, Cell] | bettebriggs@gmail.com          | 2016-03-23T08:00:00 | 1                          | Errol Heights Community Garden, Plot 17J, southeast corner Sample consisting of leaves from Kale plant that wintered over 2015-2016     | A & L WESTERN AGRICULTURAL LABORATORIES, INC. | EPA 503 METALS PLAN ANALYSIS, see attached PDF of lab report | [application/pdf, e152bf8e-99b3-43a1-baab-c7eec99e1641, 16083077 BETTE BRIGGS PLANT EPA 503 Metals.pdf, 89593]       |              |                     |                                                        | 
| 2016-05-12T16:40:00 | Bette Briggs                   | [503-949-8876, Cell] | bettebriggs@gmail.com          | 2016-03-23T08:00:00 | 1                          | Errol Heights Community Garden, Plot 17J, southeast corner Sample consisting of leaves from Kale plant that wintered over 2015-2016     | A & L WESTERN AGRICULTURAL LABORATORIES, INC. | EPA 503 METALS PLAN ANALYSIS, see attached PDF of lab report | [application/pdf, addfb315-af76-4835-9de6-e8132599f7be, 16083077 BETTE BRIGGS PLANT EPA 503 Metals.pdf, 89593]       |              |                     |                                                        | 
| 2016-05-12T16:40:00 | Bette Briggs                   | [503-949-8876, Cell] | bettebriggs@gmail.com          | 2016-03-23T08:00:00 | 1                          | Errol Heights Community Garden, Plot 17J, southeast corner Sample consisting of leaves from Kale plant that wintered over 2015-2016     | A & L WESTERN AGRICULTURAL LABORATORIES, INC. | EPA 503 METALS PLAN ANALYSIS, see attached PDF of lab report | [application/pdf, 24808cd1-d514-429c-bee2-5732cbb92336, 16083077 BETTE BRIGGS PLANT EPA 503 Metals.pdf, 89593]       |              |                     |                                                        | 
| 2016-05-26T09:28:00 | Ray Test #9                    | [503 333-2222, null] | o@gmail.com                    | 2016-01-09T08:00:00 | 20                         | Vegetables                                                                                                                              | APEX                                          | Mercury Test                                                 | [null, null, null, null]                                                                                             |              |                     |                                                        | 
```