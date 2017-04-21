# Structural Pest Control Seminar Schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/structural-pest-control-seminar-schedule-e1bf6) |
| Metadata | [Link](https://data.illinois.gov/api/views/vyrk-5hk7) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vyrk-5hk7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vyrk-5hk7/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vyrk-5hk7 |
| Name | Structural Pest Control Seminar Schedule |
| Attribution | Illinois Department of Public, Division of Environmental Health |
| Category | Public Health |
| Tags | pest control, continuing education |
| Created | 2014-07-16T13:09:24Z |
| Publication Date | 2017-03-29T15:02:25Z |

## Description

This schedule provide the dates, location and hours of continuing education opportunities for Pest Control professionals Updated March 29 2017

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type     | Render Type   |
| ======== | ============== | ======================== | ======================== | ============= | ============= |
| Yes      | time           | seminar_date             | Seminar Date             | calendar_date | calendar_date |
| No       |                | seminar_time             | Seminar Time             | text          | text          |
| Yes      | series tag     | seminar_title            | Seminar title            | text          | text          |
| Yes      | series tag     | contact_person           | Contact Person           | text          | text          |
| Yes      | series tag     | phone_number             | Phone Number             | text          | text          |
| Yes      | series tag     | email_address_of_contact | Email address of Contact | text          | text          |
| Yes      | series tag     | seminar_location         | Seminar location         | text          | text          |
| No       |                | seminar_location_address | Seminar location address | text          | text          |
| Yes      | series tag     | seminar_location_city    | Seminar location city    | text          | text          |
| Yes      | series tag     | seminar_location_state   | Seminar location state   | text          | text          |
| Yes      | series tag     | seminar_sponsor          | Seminar Sponsor          | text          | text          |
| Yes      | numeric metric | contact_hours            | Contact Hours            | number        | text          |
| Yes      | series tag     | note                     | Note:                    | text          | text          |
```

## Time Field

```ls
Value = seminar_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = seminar_time,seminar_location_address
```

## Data Commands

```ls
series e:vyrk-5hk7 d:2017-01-05T00:00:00.000Z t:seminar_location="Illinois Conference Center" t:phone_number=800-644-2123 t:note="Training for IDA General Standards (GS) Exam -- Cannot be repeated" t:seminar_title="Dept. of Ag - Training Clinic" t:seminar_location_city=Champaign t:seminar_sponsor="IDA and Univ. of Illinois Extension" t:seminar_location_state=Illinois m:contact_hours=3

series e:vyrk-5hk7 d:2017-01-09T00:00:00.000Z t:seminar_location="Giovanni's Convention Center" t:phone_number=800-644-2123 t:note="Training for IDA General Standards (GS) Exam -- Cannot be repeated" t:seminar_title="Dept. of Ag - Training Clinic" t:seminar_location_city=Rockford t:seminar_sponsor="IDA and Univ. of Illinois Extension" t:seminar_location_state=Illinois m:contact_hours=3

series e:vyrk-5hk7 d:2017-01-09T00:00:00.000Z t:seminar_location="Stewart Center" t:phone_number="(765) 494-5856" t:email_address_of_contact=htimmons@purdue.edu t:contact_person="Holly Fletcher-Timmons" t:note="Note: Credits not awarded for mosquito presentations" t:seminar_title="Purdue Pest Management Conf." t:seminar_location_city="West Lafayette" t:seminar_sponsor="Center for Urban & Industrial Pest Mgt." t:seminar_location_state=Indiana m:contact_hours=3
```

## Meta Commands

```ls
metric m:contact_hours p:integer l:"Contact Hours" t:dataTypeName=number

entity e:vyrk-5hk7 l:"Structural Pest Control Seminar Schedule" t:attribution="Illinois Department of Public, Division of Environmental Health" t:url=https://data.illinois.gov/api/views/vyrk-5hk7

property e:vyrk-5hk7 t:meta.view v:id=vyrk-5hk7 v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/structural-pest-control v:averageRating=0 v:name="Structural Pest Control Seminar Schedule" v:attribution="Illinois Department of Public, Division of Environmental Health"

property e:vyrk-5hk7 t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:vyrk-5hk7 t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| seminar_date        | seminar_time       | seminar_title                   | contact_person         | phone_number     | email_address_of_contact   | seminar_location                       | seminar_location_address          | seminar_location_city | seminar_location_state | seminar_sponsor                         | contact_hours | note                                                                                | 
| =================== | ================== | =============================== | ====================== | ================ | ========================== | ====================================== | ================================= | ===================== | ====================== | ======================================= | ============= | =================================================================================== | 
| 2017-01-05T00:00:00 | 8:00 am - 11:30 am | Dept. of Ag - Training Clinic   |                        | 800-644-2123     |                            | Illinois Conference Center             | 1900 S First St                   | Champaign             | Illinois               | IDA and Univ. of Illinois Extension     | 3             | Training for IDA General Standards (GS) Exam -- Cannot be repeated                  | 
| 2017-01-09T00:00:00 | 8:00 am - 11:30 am | Dept. of Ag - Training Clinic   |                        | 800-644-2123     |                            | Giovanni's Convention Center           | 610 N Bell School Rd              | Rockford              | Illinois               | IDA and Univ. of Illinois Extension     | 3             | Training for IDA General Standards (GS) Exam -- Cannot be repeated                  | 
| 2017-01-09T00:00:00 | 11:30 am-9:00 pm   | Purdue Pest Management Conf.    | Holly Fletcher-Timmons | (765) 494-5856   | htimmons@purdue.edu        | Stewart Center                         | Purdue University                 | West Lafayette        | Indiana                | Center for Urban & Industrial Pest Mgt. | 3             | Note: Credits not awarded for mosquito presentations                                | 
| 2017-01-10T00:00:00 | 8:00 am - 9:00 pm  | Purdue Pest Management Conf.    | Holly Fletcher-Timmons | (765) 494-5856   | htimmons@purdue.edu        | Stewart Center                         | Purdue University                 | West Lafayette        | Indiana                | Center for Urban & Industrial Pest Mgt. | 8             | Note: Credits not awarded for feral swine presentation                              | 
| 2017-01-11T00:00:00 | 8:00 am - 3:00 pm  | Purdue Pest Management Conf.    | Holly Fletcher-Timmons | (765) 494-5856   | htimmons@purdue.edu        | Stewart Center                         | Purdue University                 | West Lafayette        | Indiana                | Center for Urban & Industrial Pest Mgt. | 5             |                                                                                     | 
| 2017-01-12T00:00:00 | 8:00 am - 11:30 am | Dept. of Ag - Training Clinic   |                        | 800-644-2123     |                            | Holiday Inn                            | 222 Potomac Blvd (I-57 at Rt. 15) | Mt. Vernon            | Illinois               | IDA and Univ. of Illinois Extension     | 3             | Training for IDA General Standards (GS) Exam -- Cannot be repeated                  | 
| 2017-01-13T00:00:00 | 7:45 am - 4:00 pm  | MPMA Winter School              | Sandra Boeckman        | 800-848-6722     |                            | Stoney Creek Hotel & Conference Center | 2601 S Providence Rd              | Columbia              | Missouri               | Missouri Pest Management Association    | 7             | THIS SEMINAR HAS BEEN CANCELLED                                                     | 
| 2017-01-14T00:00:00 | 8:00 am - 5:00 pm  | Fumigation Recertification      | Deborah Murphy         | 913-782-6399     | dmurphy@fisaconsulting.com | Four Points Hotel                      | 5115 Hopyard Rd                   | Pleasanton            | California             | Food Industry Sanitation Auditors       | 6             | No credit for attending same seminar in Charlotte, Chicago, Kansas City or Denton   | 
| 2017-01-18T00:00:00 | 8:00 am - 5:00 pm  | UM Recertification & Retraining | Kim Foley              | 573-882-9558     |                            | Stoney Creek Hotel & Conference Center | 2601 S Providence Rd              | Colombia              | Missouri               | University of Missouri                  | 6             | No credit for attending same seminar in Columbia, Cape Girardeau or St. Charles, MO | 
| 2017-01-19T00:00:00 | 8:00 am - 5:00 pm  | UM Recertification & Retraining | Kim Foley              | 573-882-9558     |                            | Stoney Creek Hotel & Conference Center | 2601 S Providence Rd              | Colombia              | Missouri               | University of Missouri                  | 6             | No credit for attending same seminar in Columbia, Cape Girardeau or St. Charles, MO | 
```