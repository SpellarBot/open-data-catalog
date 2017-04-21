# System Reliability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/system-reliability) |
| Metadata | [Link](https://data.austintexas.gov/api/views/ddh8-gyev) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/ddh8-gyev/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/ddh8-gyev/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | ddh8-gyev |
| Name | System Reliability |
| Attribution | Austin energy |
| Category | Utility |
| Tags | system reliability, electric system reliability, energy, electric system, outage, electric outage, austin energy |
| Created | 2016-08-29T14:35:20Z |
| Publication Date | 2016-10-03T17:02:56Z |

## Description

The target numbers for the average duration of power outages or System Average Interruption Duration Index (SAIDI) prior to 2016 and for 2016 to present are 60.00 minutes and 57.22 minutes, respectively. For the System Average Interruption Frequency Index (SAIFI) or the average number of power outages per customer, the target numbers are 0.80  for years prior to 2016, and 0.75 from year 2016 up to the present. The target number for the System Average Transmission Line Performance index (SATLPI) or the 12-month rolling average of the number of transmission line faults per 100 miles is 3.0. View the outages per customer, average length of outages, and system average transmission line performance index per year. Go to austinenergy.com/wps/portal/ae/about/company-profile/electric-system/ and austinenergy.com/go/corporatereports to learn more.

## Columns

```ls
| Included | Schema Type    | Field Name                                                | Name                                                        | Data Type     | Render Type   |
| ======== | ============== | ========================================================= | =========================================================== | ============= | ============= |
| Yes      | time           | fiscal_year_2                                             | Fiscal Year                                                 | calendar_date | calendar_date |
| Yes      | numeric metric | system_average_interruption_frequency_index_saifi         | Outages Per Customer                                        | number        | number        |
| Yes      | numeric metric | system_average_interruption_duration_index_saidi          | Average Length of Outages (Minutes)                         | number        | number        |
| Yes      | numeric metric | system_average_transmission_line_performance_index_satlpi | System Average Transmission Line Performance Index (SATLPI) | number        | number        |
```

## Time Field

```ls
Value = fiscal_year_2
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:ddh8-gyev d:2006-09-01T00:00:00.000Z m:system_average_interruption_duration_index_saidi=84.68 m:system_average_interruption_frequency_index_saifi=1 m:system_average_transmission_line_performance_index_satlpi=3.56

series e:ddh8-gyev d:2007-09-01T00:00:00.000Z m:system_average_interruption_duration_index_saidi=82.13 m:system_average_interruption_frequency_index_saifi=1.03 m:system_average_transmission_line_performance_index_satlpi=3.24

series e:ddh8-gyev d:2008-09-01T00:00:00.000Z m:system_average_interruption_duration_index_saidi=46.48 m:system_average_interruption_frequency_index_saifi=0.63 m:system_average_transmission_line_performance_index_satlpi=1.46
```

## Meta Commands

```ls
metric m:system_average_interruption_frequency_index_saifi p:float l:"Outages Per Customer" t:dataTypeName=number

metric m:system_average_interruption_duration_index_saidi p:float l:"Average Length of Outages (Minutes)" t:dataTypeName=number

metric m:system_average_transmission_line_performance_index_satlpi p:float l:"System Average Transmission Line Performance Index (SATLPI)" t:dataTypeName=number

entity e:ddh8-gyev l:"System Reliability" t:attribution="Austin energy" t:url=https://data.austintexas.gov/api/views/ddh8-gyev

property e:ddh8-gyev t:meta.view v:id=ddh8-gyev v:category=Utility v:averageRating=0 v:name="System Reliability" v:attribution="Austin energy"

property e:ddh8-gyev t:meta.view.license v:name="Public Domain"

property e:ddh8-gyev t:meta.view.owner v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:displayName="Sarah Lambert"

property e:ddh8-gyev t:meta.view.tableauthor v:id=c433-zrb5 v:profileImageUrlMedium=/api/users/c433-zrb5/profile_images/THUMB v:profileImageUrlLarge=/api/users/c433-zrb5/profile_images/LARGE v:screenName="Sarah Lambert" v:profileImageUrlSmall=/api/users/c433-zrb5/profile_images/TINY v:roleName=publisher v:displayName="Sarah Lambert"
```

## Top Records

```ls
| fiscal_year_2       | system_average_interruption_frequency_index_saifi | system_average_interruption_duration_index_saidi | system_average_transmission_line_performance_index_satlpi | 
| =================== | ================================================= | ================================================ | ========================================================= | 
| 2006-09-01T00:00:00 | 1                                                 | 84.68                                            | 3.56                                                      | 
| 2007-09-01T00:00:00 | 1.03                                              | 82.13                                            | 3.24                                                      | 
| 2008-09-01T00:00:00 | 0.63                                              | 46.48                                            | 1.46                                                      | 
| 2009-09-01T00:00:00 | 0.89                                              | 63.41                                            | 2.1                                                       | 
| 2010-09-01T00:00:00 | 0.69                                              | 51.57                                            | 1.94                                                      | 
| 2011-09-01T00:00:00 | 0.77                                              | 54.54                                            | 1.78                                                      | 
| 2012-09-01T00:00:00 | 0.77                                              | 60.74                                            | 2.9                                                       | 
| 2013-09-01T00:00:00 | 0.59                                              | 46.24                                            | 1.44                                                      | 
| 2014-09-01T00:00:00 | 0.56999999999999995                               | 45.25                                            | 4.17                                                      | 
| 2015-09-01T00:00:00 | 0.65                                              | 56.04                                            | 3.36                                                      | 
```