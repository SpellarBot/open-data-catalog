# FOIA Requests (FY 2007-2015)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-requests-fy-2007-2015) |
| Metadata | [Link](https://data.imls.gov/api/views/9dh4-qcur) |
| Data: JSON | [100 Rows](https://data.imls.gov/api/views/9dh4-qcur/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.imls.gov/api/views/9dh4-qcur/rows.csv?max_rows=100) |
| Host | data.imls.gov |
| Id | 9dh4-qcur |
| Name | FOIA Requests (FY 2007-2015) |
| Attribution | IMLS |
| Category | Administrative Data |
| Tags | foia, freedom of information act, administrative, transparency |
| Created | 2015-02-09T16:15:46Z |
| Publication Date | 2016-06-15T12:43:10Z |

## Description

Review summary data on IMLS' annual reports on Freedom of Information Act (FOIA) requests from FY 2007 to FY 2015. 

Full reports are available at https://www.imls.gov/about-us/agency-reports/freedom-information-act-foia.

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                          | Data Type | Render Type |
| ======== | ============== | ============================================================= | ============================================================= | ========= | =========== |
| Yes      | time           | fiscal_year                                                   | Fiscal Year                                                   | number    | text        |
| Yes      | numeric metric | total_number_of_requests_processed_in_fiscal_year             | Total Number of Requests Processed in Fiscal Year             | number    | number      |
| Yes      | numeric metric | number_of_full_grants                                         | Number of Full Grants                                         | number    | number      |
| Yes      | numeric metric | number_of_partial_grants_partial_denials                      | Number of Partial Grants/ Partial Denials                     | number    | number      |
| Yes      | numeric metric | number_of_full_denials_based_on_exemptions                    | Number of Full Denials Based on Exemptions                    | number    | number      |
| Yes      | numeric metric | number_of_full_denials_based_on_reasons_other_than_exemptions | Number of Full Denials Based on Reasons Other than Exemptions | number    | number      |
| Yes      | numeric metric | denial_no_records                                             | Denial - No Records                                           | number    | number      |
| Yes      | numeric metric | denial_all_records_referred_to_another_component_or_agency    | Denial - All Records Referred to Another Component or Agency  | number    | number      |
| Yes      | numeric metric | denial_request_withdrawn                                      | Denial - Request Withdrawn                                    | number    | number      |
| Yes      | numeric metric | denial_fee_related_reason                                     | Denial - Fee-Related Reason                                   | number    | number      |
| Yes      | numeric metric | denial_records_not_reasonably_described                       | Denial - Records not Reasonably Described                     | number    | number      |
| Yes      | numeric metric | denial_improper_foia_request_for_other_reason                 | Denial - Improper FOIA Request for Other Reason               | number    | number      |
| Yes      | numeric metric | denial_not_agency_record                                      | Denial - Not Agency Record                                    | number    | number      |
| Yes      | numeric metric | denial_duplicate_request                                      | Denial - Duplicate Request                                    | number    | number      |
| Yes      | numeric metric | denial_other_explain_in_chart_below                           | Denial - Other                                                | number    | number      |
| Yes      | numeric metric | simple_median_number_of_days                                  | Simple - Median Number of Days                                | number    | number      |
| Yes      | numeric metric | simple_average_number_of_days                                 | Simple - Average Number of Days                               | number    | number      |
| Yes      | numeric metric | simple_lowest_number_of_days                                  | Simple - Lowest Number of Days                                | number    | number      |
| Yes      | numeric metric | simple_highest_number_of_days                                 | Simple - Highest Number of Days                               | number    | number      |
| Yes      | numeric metric | complex_median_number_of_days                                 | Complex - Median Number of Days                               | number    | number      |
| Yes      | numeric metric | complex_average_number_of_days                                | Complex - Average Number of Days                              | number    | number      |
| Yes      | numeric metric | complex_lowest_number_of_days                                 | Complex - Lowest Number of Days                               | number    | number      |
| Yes      | numeric metric | complex_highest_number_of_days                                | Complex - Highest Number of Days                              | number    | number      |
| Yes      | numeric metric | expedited_processing_median_number_of_days                    | Expedited Processing - Median Number of Days                  | number    | number      |
| Yes      | numeric metric | expedited_processing_average_number_of_days                   | Expedited Processing - Average Number of Days                 | number    | number      |
| Yes      | numeric metric | expedited_processing_lowest_number_of_days                    | Expedited Processing - Lowest Number of Days                  | number    | number      |
| Yes      | numeric metric | expedited_processing_highest_number_of_days                   | Expedited Processing - Highest Number of Days                 | number    | number      |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9dh4-qcur d:2007-01-01T00:00:00.000Z m:denial_improper_foia_request_for_other_reason=2 m:denial_not_agency_record=4 m:denial_no_records=4 m:denial_fee_related_reason=0 m:complex_average_number_of_days=38 m:denial_other_explain_in_chart_below=0 m:number_of_full_denials_based_on_reasons_other_than_exemptions=11 m:denial_duplicate_request=0 m:total_number_of_requests_processed_in_fiscal_year=58 m:number_of_partial_grants_partial_denials=27 m:denial_all_records_referred_to_another_component_or_agency=0 m:denial_records_not_reasonably_described=0 m:denial_request_withdrawn=1 m:number_of_full_grants=17 m:number_of_full_denials_based_on_exemptions=1 m:simple_average_number_of_days=11

series e:9dh4-qcur d:2008-01-01T00:00:00.000Z m:expedited_processing_median_number_of_days=1 m:denial_improper_foia_request_for_other_reason=1 m:denial_not_agency_record=0 m:denial_no_records=10 m:simple_highest_number_of_days=25 m:simple_lowest_number_of_days=1 m:denial_fee_related_reason=0 m:denial_other_explain_in_chart_below=0 m:number_of_full_denials_based_on_reasons_other_than_exemptions=11 m:total_number_of_requests_processed_in_fiscal_year=44 m:denial_duplicate_request=0 m:expedited_processing_average_number_of_days=1 m:number_of_partial_grants_partial_denials=18 m:simple_median_number_of_days=9 m:denial_all_records_referred_to_another_component_or_agency=0 m:denial_records_not_reasonably_described=0 m:expedited_processing_lowest_number_of_days=1 m:denial_request_withdrawn=0 m:expedited_processing_highest_number_of_days=1 m:number_of_full_grants=15 m:number_of_full_denials_based_on_exemptions=0 m:simple_average_number_of_days=11

series e:9dh4-qcur d:2009-01-01T00:00:00.000Z m:expedited_processing_median_number_of_days=0 m:denial_improper_foia_request_for_other_reason=0 m:simple_highest_number_of_days=38 m:denial_fee_related_reason=0 m:complex_average_number_of_days=64.5 m:denial_other_explain_in_chart_below=0 m:denial_duplicate_request=0 m:denial_all_records_referred_to_another_component_or_agency=0 m:expedited_processing_lowest_number_of_days=0 m:number_of_full_grants=12 m:number_of_full_denials_based_on_exemptions=0 m:complex_lowest_number_of_days=44 m:simple_average_number_of_days=12.7 m:denial_not_agency_record=5 m:complex_highest_number_of_days=85 m:denial_no_records=3 m:simple_lowest_number_of_days=1 m:total_number_of_requests_processed_in_fiscal_year=39 m:number_of_full_denials_based_on_reasons_other_than_exemptions=10 m:expedited_processing_average_number_of_days=0 m:number_of_partial_grants_partial_denials=17 m:simple_median_number_of_days=11 m:denial_records_not_reasonably_described=0 m:denial_request_withdrawn=2 m:complex_median_number_of_days=65 m:expedited_processing_highest_number_of_days=0
```

## Meta Commands

```ls
metric m:total_number_of_requests_processed_in_fiscal_year p:integer l:"Total Number of Requests Processed in Fiscal Year" t:dataTypeName=number

metric m:number_of_full_grants p:integer l:"Number of Full Grants" t:dataTypeName=number

metric m:number_of_partial_grants_partial_denials p:integer l:"Number of Partial Grants/ Partial Denials" t:dataTypeName=number

metric m:number_of_full_denials_based_on_exemptions p:integer l:"Number of Full Denials Based on Exemptions" t:dataTypeName=number

metric m:number_of_full_denials_based_on_reasons_other_than_exemptions p:integer l:"Number of Full Denials Based on Reasons Other than Exemptions" t:dataTypeName=number

metric m:denial_no_records p:integer l:"Denial - No Records" t:dataTypeName=number

metric m:denial_all_records_referred_to_another_component_or_agency p:integer l:"Denial - All Records Referred to Another Component or Agency" t:dataTypeName=number

metric m:denial_request_withdrawn p:integer l:"Denial - Request Withdrawn" t:dataTypeName=number

metric m:denial_fee_related_reason p:integer l:"Denial - Fee-Related Reason" t:dataTypeName=number

metric m:denial_records_not_reasonably_described p:integer l:"Denial - Records not Reasonably Described" t:dataTypeName=number

metric m:denial_improper_foia_request_for_other_reason p:integer l:"Denial - Improper FOIA Request for Other Reason" t:dataTypeName=number

metric m:denial_not_agency_record p:integer l:"Denial - Not Agency Record" t:dataTypeName=number

metric m:denial_duplicate_request p:integer l:"Denial - Duplicate Request" t:dataTypeName=number

metric m:denial_other_explain_in_chart_below p:integer l:"Denial - Other" t:dataTypeName=number

metric m:simple_median_number_of_days p:double l:"Simple - Median Number of Days" t:dataTypeName=number

metric m:simple_average_number_of_days p:float l:"Simple - Average Number of Days" t:dataTypeName=number

metric m:simple_lowest_number_of_days p:integer l:"Simple - Lowest Number of Days" t:dataTypeName=number

metric m:simple_highest_number_of_days p:integer l:"Simple - Highest Number of Days" t:dataTypeName=number

metric m:complex_median_number_of_days p:double l:"Complex - Median Number of Days" t:dataTypeName=number

metric m:complex_average_number_of_days p:float l:"Complex - Average Number of Days" t:dataTypeName=number

metric m:complex_lowest_number_of_days p:integer l:"Complex - Lowest Number of Days" t:dataTypeName=number

metric m:complex_highest_number_of_days p:integer l:"Complex - Highest Number of Days" t:dataTypeName=number

metric m:expedited_processing_median_number_of_days p:float l:"Expedited Processing - Median Number of Days" t:dataTypeName=number

metric m:expedited_processing_average_number_of_days p:float l:"Expedited Processing - Average Number of Days" t:dataTypeName=number

metric m:expedited_processing_lowest_number_of_days p:integer l:"Expedited Processing - Lowest Number of Days" t:dataTypeName=number

metric m:expedited_processing_highest_number_of_days p:integer l:"Expedited Processing - Highest Number of Days" t:dataTypeName=number

entity e:9dh4-qcur l:"FOIA Requests (FY 2007-2015)" t:attribution=IMLS t:url=https://data.imls.gov/api/views/9dh4-qcur

property e:9dh4-qcur t:meta.view v:id=9dh4-qcur v:category="Administrative Data" v:attributionLink=https://www.imls.gov/about-us/agency-reports/freedom-information-act-foia v:averageRating=0 v:name="FOIA Requests (FY 2007-2015)" v:attribution=IMLS

property e:9dh4-qcur t:meta.view.license v:name="Public Domain U.S. Government" v:termsLink=https://www.usa.gov/government-works

property e:9dh4-qcur t:meta.view.owner v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:9dh4-qcur t:meta.view.tableauthor v:id=b4ig-itd5 v:screenName=Ammie v:displayName=Ammie

property e:9dh4-qcur t:meta.view.metadata.custom_fields.common_core v:Contact_Email=imlsinfo@imls.gov v:Contact_Name="Office of Digital and Information Strategy" v:Bureau_Code=474:00 v:Program_Code=000:000
```

## Top Records

```ls
| fiscal_year | total_number_of_requests_processed_in_fiscal_year | number_of_full_grants | number_of_partial_grants_partial_denials | number_of_full_denials_based_on_exemptions | number_of_full_denials_based_on_reasons_other_than_exemptions | denial_no_records | denial_all_records_referred_to_another_component_or_agency | denial_request_withdrawn | denial_fee_related_reason | denial_records_not_reasonably_described | denial_improper_foia_request_for_other_reason | denial_not_agency_record | denial_duplicate_request | denial_other_explain_in_chart_below | simple_median_number_of_days | simple_average_number_of_days | simple_lowest_number_of_days | simple_highest_number_of_days | complex_median_number_of_days | complex_average_number_of_days | complex_lowest_number_of_days | complex_highest_number_of_days | expedited_processing_median_number_of_days | expedited_processing_average_number_of_days | expedited_processing_lowest_number_of_days | expedited_processing_highest_number_of_days | 
| =========== | ================================================= | ===================== | ======================================== | ========================================== | ============================================================= | ================= | ========================================================== | ======================== | ========================= | ======================================= | ============================================= | ======================== | ======================== | =================================== | ============================ | ============================= | ============================ | ============================= | ============================= | ============================== | ============================= | ============================== | ========================================== | =========================================== | ========================================== | =========================================== | 
| 2007        | 58                                                | 17                    | 27                                       | 1                                          | 11                                                            | 4                 | 0                                                          | 1                        | 0                         | 0                                       | 2                                             | 4                        | 0                        | 0                                   |                              | 11                            |                              |                               |                               | 38                             |                               |                                |                                            |                                             |                                            |                                             | 
| 2008        | 44                                                | 15                    | 18                                       | 0                                          | 11                                                            | 10                | 0                                                          | 0                        | 0                         | 0                                       | 1                                             | 0                        | 0                        | 0                                   | 9                            | 11                            | 1                            | 25                            |                               |                                |                               |                                | 1                                          | 1                                           | 1                                          | 1                                           | 
| 2009        | 39                                                | 12                    | 17                                       | 0                                          | 10                                                            | 3                 | 0                                                          | 2                        | 0                         | 0                                       | 0                                             | 5                        | 0                        | 0                                   | 11                           | 12.7                          | 1                            | 38                            | 65                            | 64.5                           | 44                            | 85                             | 0                                          | 0                                           | 0                                          | 0                                           | 
| 2010        | 51                                                | 12                    | 27                                       | 0                                          | 12                                                            | 7                 | 0                                                          | 0                        | 0                         | 0                                       | 0                                             | 3                        | 1                        | 1                                   | 9                            | 9.6                           | 1                            | 26                            | 55.5                          | 55.3                           | 36                            | 74                             | 0                                          | 0                                           | 0                                          | 0                                           | 
| 2011        | 36                                                | 11                    | 16                                       | 3                                          | 6                                                             | 2                 | 0                                                          | 1                        | 0                         | 0                                       | 0                                             | 1                        | 1                        | 1                                   | 9.5                          | 9.3                           | 1                            | 22                            | 77                            | 58.5                           | 40                            | 77                             | 3.5                                        | 3.5                                         | 3                                          | 4                                           | 
| 2012        | 35                                                | 8                     | 18                                       | 0                                          | 9                                                             | 4                 | 0                                                          | 1                        | 0                         | 0                                       | 0                                             | 0                        | 0                        | 4                                   | 9                            | 8.9                           | 1                            | 19                            | 24                            | 28.7                           | 23                            | 39                             | 0                                          | 0                                           | 0                                          | 0                                           | 
| 2013        | 41                                                | 10                    | 18                                       | 0                                          | 13                                                            | 7                 | 0                                                          | 0                        | 0                         | 1                                       | 0                                             | 2                        | 0                        | 3                                   | 9                            | 8.9                           | 1                            | 18                            | 24.5                          | 24.8                           | 21                            | 30                             | 0                                          | 0                                           | 0                                          | 0                                           | 
| 2014        | 51                                                | 24                    | 13                                       | 0                                          | 14                                                            | 10                | 0                                                          | 2                        | 0                         | 0                                       | 0                                             | 0                        | 0                        | 2                                   | 7                            | 7.9                           | 1                            | 20                            | 24.5                          | 33.4                           | 22                            | 56                             |                                            |                                             |                                            |                                             | 
| 2015        | 33                                                | 13                    | 9                                        | 2                                          | 0                                                             | 7                 | 0                                                          | 0                        | 0                         | 0                                       | 1                                             | 1                        | 0                        | 0                                   | 5                            | 5.92                          | 1                            | 17                            | 26                            | 31.1                           | 20                            | 67                             | 0                                          | 0                                           | 0                                          | 0                                           | 
```