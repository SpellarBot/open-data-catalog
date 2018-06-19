# Office for the Aging Service Expenditures: Beginning Fiscal Year 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-for-the-aging-service-expenditures-beginning-fiscal-year-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/7sw8-sdsd) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7sw8-sdsd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7sw8-sdsd/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7sw8-sdsd |
| Name | Office for the Aging Service Expenditures: Beginning Fiscal Year 2009 |
| Attribution | Local Area Agencies on Aging |
| Category | Human Services |
| Tags | seniors, older new yorkers, expenditures, snap, eisep, cse, csi, title iii |
| Created | 2013-02-17T22:01:04Z |
| Publication Date | 2016-11-04T22:07:45Z |

## Description

Dataset showing expenditures by county, by service for the following State Fiscal Years beginning 2009/10

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type | Render Type |
| ======== | ============== | ====================================== | ====================================== | ========= | =========== |
| Yes      | series tag     | county                                 | County                                 | text      | text        |
| Yes      | series tag     | county_name                            | County Name                            | text      | text        |
| No       |                | date_state_fiscal_year                 | Date - State Fiscal Year               | text      | text        |
| Yes      | numeric metric | pc_level_ii                            | Personal Care Level II                 | money     | money       |
| Yes      | numeric metric | pc_level_i                             | Personal Care Level I                  | money     | money       |
| Yes      | numeric metric | home_health_aide                       | Home Health Aide                       | money     | money       |
| Yes      | numeric metric | home_delivered_meals                   | Home Delivered Meals                   | money     | money       |
| Yes      | numeric metric | adult_day_services                     | Adult Day Services                     | money     | money       |
| Yes      | numeric metric | case_management                        | Case Management                        | money     | money       |
| Yes      | numeric metric | congregate_meals                       | Congregate Meals                       | money     | money       |
| Yes      | numeric metric | nutrition_counseling                   | Nutrition Counseling                   | money     | money       |
| Yes      | numeric metric | assisted_transportation                | Assisted Transportation                | money     | money       |
| Yes      | numeric metric | transportation                         | Transportation                         | money     | money       |
| Yes      | numeric metric | legal_assistance                       | Legal Assistance                       | money     | money       |
| Yes      | numeric metric | nutrition_education                    | Nutrition Education                    | money     | money       |
| Yes      | numeric metric | information_assistance                 | Information & Assistance               | money     | money       |
| Yes      | numeric metric | ourtreach                              | Outreach                               | money     | money       |
| Yes      | numeric metric | in_home_services                       | In-Home Services                       | money     | money       |
| Yes      | numeric metric | senior_center_recreation_and_education | Senior Center Recreation and Education | money     | money       |
| Yes      | numeric metric | health_promotion                       | Health Promotion                       | money     | money       |
| Yes      | numeric metric | personal_emergency_response            | Personal Emergency Response            | money     | money       |
| Yes      | numeric metric | caregiver_services                     | Caregiver Services                     | money     | money       |
| Yes      | numeric metric | long_term_care_ombudsman_program       | Long Term Care Ombudsman Program       | money     | money       |
| Yes      | numeric metric | other                                  | Other                                  | money     | money       |
```

## Time Field

```ls
Value = 2009
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date_state_fiscal_year
```

## Data Commands

```ls
series e:7sw8-sdsd d:2009-01-01T00:00:00.000Z t:county=1 t:county_name=Albany m:information_assistance=22599 m:other=6550 m:nutrition_counseling=0 m:case_management=136978 m:pc_level_ii=1051521 m:nutrition_education=0 m:health_promotion=9450 m:home_health_aide=1488 m:transportation=445047 m:pc_level_i=65908 m:congregate_meals=544903 m:personal_emergency_response=126164 m:senior_center_recreation_and_education=7491 m:long_term_care_ombudsman_program=0 m:assisted_transportation=0 m:home_delivered_meals=731955 m:ourtreach=0 m:in_home_services=44782 m:caregiver_services=14252 m:adult_day_services=222317 m:legal_assistance=39739

series e:7sw8-sdsd d:2009-01-01T00:00:00.000Z t:county=2 t:county_name=Allegany m:information_assistance=320198 m:other=139924 m:nutrition_counseling=759 m:case_management=81747 m:pc_level_ii=56560 m:nutrition_education=22045 m:health_promotion=6702 m:home_health_aide=0 m:transportation=15986 m:pc_level_i=109838 m:congregate_meals=191711 m:personal_emergency_response=28612 m:senior_center_recreation_and_education=1789 m:long_term_care_ombudsman_program=10071 m:assisted_transportation=0 m:home_delivered_meals=602238 m:ourtreach=160 m:in_home_services=10675 m:caregiver_services=15044 m:adult_day_services=0 m:legal_assistance=7935

series e:7sw8-sdsd d:2009-01-01T00:00:00.000Z t:county=3 t:county_name=Broome m:information_assistance=536274 m:other=422011 m:nutrition_counseling=6518 m:case_management=478707 m:pc_level_ii=226398 m:nutrition_education=7671 m:health_promotion=83483 m:home_health_aide=0 m:transportation=196037 m:pc_level_i=128909 m:congregate_meals=727408 m:personal_emergency_response=23547 m:senior_center_recreation_and_education=81079 m:long_term_care_ombudsman_program=0 m:assisted_transportation=0 m:home_delivered_meals=889670 m:ourtreach=563 m:in_home_services=29597 m:caregiver_services=39099 m:adult_day_services=282973 m:legal_assistance=34791
```

## Meta Commands

```ls
metric m:pc_level_ii p:double l:"Personal Care Level II" d:"A service that includes some or total assistance with the personal tasks on behalf of or to assist a person commensurate with the person's limitations" t:dataTypeName=money

metric m:pc_level_i p:double l:"Personal Care Level I" d:"A service that includes some or total assistance with the household tasks on behalf of or to assist a person commensurate with the person's limitations" t:dataTypeName=money

metric m:home_health_aide p:double l:"Home Health Aide" d:"The provision of health care tasks, personal hygiene services, housekeeping tasks and other specialized related support services essential to the client's health, such as assistance with medical needs." t:dataTypeName=money

metric m:home_delivered_meals p:double l:"Home Delivered Meals" d:"A hot or other appropriate meal which meets nutritional requirements and is provided to an eligible person for home consumption." t:dataTypeName=money

metric m:adult_day_services p:double l:"Adult Day Services" d:"There are two types of adult day services (ADS)?social adult day services (SADS), and adult day health care (ADH), which includes a medical component and is regulated by the NYS Department of Health." t:dataTypeName=money

metric m:case_management p:double l:"Case Management" d:"The definition now notes that contact must be made with Case Management clients funded by both state and federal sources at least every two months." t:dataTypeName=money

metric m:congregate_meals p:double l:"Congregate Meals" d:"A hot or other appropriate meal which meets nutritional requirements and is served to an eligible participant in a group setting." t:dataTypeName=money

metric m:nutrition_counseling p:double l:"Nutrition Counseling" d:"Individualized guidance to individuals who are at nutritional risk because of their health or nutrition history, dietary intake, chronic illnesses, or medications use." t:dataTypeName=money

metric m:assisted_transportation p:double l:"Assisted Transportation" d:"A ssistance and transportation, including escort, to a person who has difficulties (physical or cognitive) using regular vehicular transportation." t:dataTypeName=money

metric m:transportation p:double l:Transportation d:"Transportation is an optional component under SADS and therefore is to be reported separately (units, expenditure s and clients) rather than included in the reporting under adult day services." t:dataTypeName=money

metric m:legal_assistance p:double l:"Legal Assistance" d:"Provision of legal advice, counseling and representation by an attorney or other person acting under the supervision of an attorney." t:dataTypeName=money

metric m:nutrition_education p:double l:"Nutrition Education" d:"Each participant of a group or individual session receives one unit of service. In addition, each distribution of handouts to congregate and/or homebound participants (not counted if handouts are part of a presentation or are left on display to be picked" t:dataTypeName=money

metric m:information_assistance p:double l:"Information & Assistance" d:"Provides individuals with information on services available through the AAA and within the communities or assists individuals by linking them to services that are available within the communities." t:dataTypeName=money

metric m:ourtreach p:double l:Outreach d:"The unit of service definition for Outreach has been expanded to allow the AAA or its subcontractors to count as contacts meetings held at a table at a health event with an individual. For example, providers might conduct face-to-face identification of is" t:dataTypeName=money

metric m:in_home_services p:double l:"In-Home Services" d:"A service that provides assistance with the tasks that are the same or similar to those included in the definitions of Personal Care Level I and Personal Care Level II, and which is managed by the consumer, or a representative selected by the consumer." t:dataTypeName=money

metric m:senior_center_recreation_and_education p:double l:"Senior Center Recreation and Education" d:"Activities organized and scheduled through the AAA or its subcontractors which involve older persons in courses, workshops, other learning activities and satisfying use of free time." t:dataTypeName=money

metric m:health_promotion p:double l:"Health Promotion" d:"Each participant or attendee of a group session, class or event receives one unit of service and each distribution of a health related topic in a newsletter, newspaper, radio or TV show is one unit." t:dataTypeName=money

metric m:personal_emergency_response p:double l:"Personal Emergency Response" d:"A service which utilizes an electronic device to alert appropriate people of the need for immediate assistance in the event of an emergency situation in an older person's home." t:dataTypeName=money

metric m:caregiver_services p:double l:"Caregiver Services" d:"Services included are support groups for caregivers, caregiver counseling on issues to help caregivers in making decisions and solving problems related to their care giving roles and training workshops for caregivers." t:dataTypeName=money

metric m:long_term_care_ombudsman_program p:double l:"Long Term Care Ombudsman Program" d:"Services provided by duly authorized patient advoca tes on behalf of people residing in long term care facilities and their families." t:dataTypeName=money

metric m:other p:double l:Other d:"Other services provided that may include services and activities designed to provide support to older people who are isolated because of physical and/or cognitive limitations. These services are not defined separately elsewhere" t:dataTypeName=money

entity e:7sw8-sdsd l:"Office for the Aging Service Expenditures: Beginning Fiscal Year 2009" t:attribution="Local Area Agencies on Aging" t:url=https://data.ny.gov/api/views/7sw8-sdsd

property e:7sw8-sdsd t:meta.view v:id=7sw8-sdsd v:category="Human Services" v:averageRating=0 v:name="Office for the Aging Service Expenditures: Beginning Fiscal Year 2009" v:attribution="Local Area Agencies on Aging"

property e:7sw8-sdsd t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7sw8-sdsd t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:7sw8-sdsd t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| county | county_name | date_state_fiscal_year | pc_level_ii | pc_level_i | home_health_aide | home_delivered_meals | adult_day_services | case_management | congregate_meals | nutrition_counseling | assisted_transportation | transportation | legal_assistance | nutrition_education | information_assistance | ourtreach | in_home_services | senior_center_recreation_and_education | health_promotion | personal_emergency_response | caregiver_services | long_term_care_ombudsman_program | other      | 
| ====== | =========== | ====================== | =========== | ========== | ================ | ==================== | ================== | =============== | ================ | ==================== | ======================= | ============== | ================ | =================== | ====================== | ========= | ================ | ====================================== | ================ | =========================== | ================== | ================================ | ========== | 
| 1      | Albany      | 2015-2016              | 1051521.00  | 65908.00   | 1488.00          | 731955.00            | 222317.00          | 136978.00       | 544903.00        | 0.00                 | 0.00                    | 445047.00      | 39739.00         | 0.00                | 22599.00               | 0.00      | 44782.00         | 7491.00                                | 9450.00          | 126164.00                   | 14252.00           | 0.00                             | 6550.00    | 
| 2      | Allegany    | 2015-2016              | 56560.00    | 109838.00  | 0.00             | 602238.00            | 0.00               | 81747.00        | 191711.00        | 759.00               | 0.00                    | 15986.00       | 7935.00          | 22045.00            | 320198.00              | 160.00    | 10675.00         | 1789.00                                | 6702.00          | 28612.00                    | 15044.00           | 10071.00                         | 139924.00  | 
| 3      | Broome      | 2015-2016              | 226398.00   | 128909.00  | 0.00             | 889670.00            | 282973.00          | 478707.00       | 727408.00        | 6518.00              | 0.00                    | 196037.00      | 34791.00         | 7671.00             | 536274.00              | 563.00    | 29597.00         | 81079.00                               | 83483.00         | 23547.00                    | 39099.00           | 0.00                             | 422011.00  | 
| 4      | Cattaraugus | 2015-2016              | 147161.00   | 21086.00   | 0.00             | 848751.00            | 54352.00           | 313952.00       | 460939.00        | 989.00               | 0.00                    | 16191.00       | 42688.00         | 15904.00            | 160739.00              | 2180.00   | 0.00             | 4432.00                                | 11947.00         | 7350.00                     | 13708.00           | 0.00                             | 1751751.00 | 
| 5      | Cayuga      | 2015-2016              | 56143.00    | 150365.00  | 0.00             | 474480.00            | 8321.00            | 102694.00       | 119563.00        | 595.00               | 0.00                    | 68131.00       | 1731.00          | 2815.00             | 330572.00              | 825.00    | 0.00             | 3786.00                                | 9422.00          | 0.00                        | 28360.00           | 0.00                             | 6343.00    | 
| 6      | Chautauqua  | 2015-2016              | 300912.00   | 257985.00  | 0.00             | 873459.00            | 179860.00          | 286924.00       | 357579.00        | 1240.00              | 0.00                    | 96319.00       | 19253.00         | 13237.00            | 421595.00              | 18572.00  | 23953.00         | 0.00                                   | 127542.00        | 134697.00                   | 7916.00            | 18096.00                         | 222479.00  | 
| 7      | Chemung     | 2015-2016              | 157772.00   | 173692.00  | 0.00             | 267541.00            | 80.00              | 166324.00       | 211969.00        | 5100.00              | 0.00                    | 40570.00       | 12330.00         | 14928.00            | 466775.00              | 8916.00   | 3655.00          | 0.00                                   | 26540.00         | 5586.00                     | 10822.00           | 0.00                             | 650112.00  | 
| 8      | Chenango    | 2015-2016              | 67760.00    | 77751.00   | 0.00             | 464157.00            | 0.00               | 180566.00       | 123228.00        | 1805.00              | 0.00                    | 5599.00        | 24870.00         | 14826.00            | 194701.00              | 8829.00   | 0.00             | 8175.00                                | 5739.00          | 25865.00                    | 8387.00            | 0.00                             | 12258.00   | 
| 9      | Clinton     | 2015-2016              | 279149.00   | 0.00       | 0.00             | 991104.00            | 0.00               | 249488.00       | 261099.00        | 11264.00             | 0.00                    | 57614.00       | 13808.00         | 15527.00            | 443583.00              | 11302.00  | 71551.00         | 82969.00                               | 42587.00         | 134445.00                   | 55304.00           | 0.00                             | 327383.00  | 
| 10     | Columbia    | 2015-2016              | 101713.00   | 89236.00   | 0.00             | 486636.00            | 0.00               | 140274.00       | 209928.00        | 12336.00             | 5000.00                 | 32000.00       | 23669.00         | 12336.00            | 249051.00              | 1175.00   | 685.00           | 19600.00                               | 1097.00          | 861.00                      | 0.00               | 0.00                             | 28783.00   | 
```