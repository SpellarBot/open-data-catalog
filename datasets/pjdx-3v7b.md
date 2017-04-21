# Informal Comment Form for the Draft Dangerous Waste Regulations - Chapter 173-303 WAC

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/informal-comment-form-for-the-draft-dangerous-waste-regulations-chapter-173-303-wac) |
| Metadata | [Link](https://data.wa.gov/api/views/pjdx-3v7b) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/pjdx-3v7b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/pjdx-3v7b/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | pjdx-3v7b |
| Name | Informal Comment Form for the Draft Dangerous Waste Regulations - Chapter 173-303 WAC |
| Tags | dangerous waste, regulations, rulemaking, public comments, amendments |
| Created | 2016-05-19T15:34:50Z |
| Publication Date | 2016-09-19T18:00:09Z |

## Description

Form for collecting public comments.

## Columns

```ls
| Included | Schema Type | Field Name                              | Name                                      | Data Type      | Render Type    |
| ======== | =========== | ======================================= | ========================================= | ============== | ============== |
| No       | time        | :updated_at                             | updated_at                                | meta_data      | meta_data      |
| Yes      | series tag  | first_name                              | First Name:                               | text           | text           |
| Yes      | series tag  | last_name                               | Last Name:                                | text           | text           |
| Yes      | series tag  | organization                            | Organization                              | text           | text           |
| No       |             | address_line_1                          | Address Line 1:                           | text           | text           |
| No       |             | address_line_2                          | Address Line 2:                           | text           | text           |
| Yes      | series tag  | city                                    | City:                                     | text           | text           |
| Yes      | series tag  | state                                   | State                                     | text           | text           |
| Yes      | series tag  | zip_code                                | Zip Code:                                 | text           | text           |
| Yes      | series tag  | email                                   | Email:                                    | email          | email          |
| Yes      | series tag  | phone                                   | Phone:                                    | text           | text           |
| Yes      | series tag  | select_the_rule_you_are_commenting_on   | Select the rule you are commenting on:    | drop_down_list | drop_down_list |
| Yes      | series tag  | your_comment_question_or_recommendation | Your Comment, Question, or Recommendation | text           | text           |
| Yes      | series tag  | provide_rule_language_optional          | Provide Rule Language (Optional)          | text           | text           |
| Yes      | series tag  | attach_file                             | Attach File:                              | document       | document       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address_line_1,address_line_2
```

## Data Commands

```ls
series e:pjdx-3v7b d:2016-09-26T15:11:04.000Z t:first_name=Rob t:organization=Ecology t:select_the_rule_you_are_commenting_on=yzke-438g t:your_comment_question_or_recommendation=Test t:last_name=Rieck m:row_number.pjdx-3v7b=1

series e:pjdx-3v7b d:2016-11-02T23:17:21.000Z t:first_name=Joy t:organization="Whitworth University" t:phone=5097774339 t:zip_code=99251 t:email=jdiaz02@whitworth.edu t:select_the_rule_you_are_commenting_on=pf2k-rjze t:your_comment_question_or_recommendation="Please consider if and how to include businesses and institutes of higher education in the definition of healthcare facilities when they own and operate health clinic and animal care facilities. Many such dual entities exist and the larger organization is likely already a dangerous waste generator. How do we then merge compliance?" t:last_name=Diaz t:state=Washington t:city=Spokane m:row_number.pjdx-3v7b=2

series e:pjdx-3v7b d:2016-12-15T23:22:27.000Z t:phone=425-261-3535 t:zip_code=98201 t:your_comment_question_or_recommendation="see attached" t:state=Wa t:attach_file.filename="Interim Pharmaceutical Waste Policy Clarification.docx" t:city=Everett t:attach_file.size=42595 t:first_name=Joyce t:organization="Providence Regional Medical Center Everett" t:attach_file.file_id=a21f1528-3e72-4e8a-834b-d0567e7cb56b t:provide_rule_language_optional="see attachment" t:email=joyce.lindell@providence.org t:select_the_rule_you_are_commenting_on=pf2k-rjze t:last_name=Lindell t:attach_file.content_type=application/vnd.openxmlformats-officedocument.wordprocessingml.document m:row_number.pjdx-3v7b=3
```

## Meta Commands

```ls
metric m:row_number.pjdx-3v7b p:long l:"Row Number"

entity e:pjdx-3v7b l:"Informal Comment Form for the Draft Dangerous Waste Regulations - Chapter 173-303 WAC" t:url=https://data.wa.gov/api/views/pjdx-3v7b

property e:pjdx-3v7b t:meta.view v:id=pjdx-3v7b v:attributionLink=http://www.ecy.wa.gov/programs/hwtr/laws_rules/DWRegs/1603pubcom.html v:averageRating=0 v:name="Informal Comment Form for the Draft Dangerous Waste Regulations - Chapter 173-303 WAC"

property e:pjdx-3v7b t:meta.view.owner v:id=8p74-8ut4 v:profileImageUrlMedium=/api/users/8p74-8ut4/profile_images/THUMB v:profileImageUrlLarge=/api/users/8p74-8ut4/profile_images/LARGE v:screenName="Cathy Bouge" v:profileImageUrlSmall=/api/users/8p74-8ut4/profile_images/TINY v:displayName="Cathy Bouge"

property e:pjdx-3v7b t:meta.view.tableauthor v:id=8p74-8ut4 v:profileImageUrlMedium=/api/users/8p74-8ut4/profile_images/THUMB v:profileImageUrlLarge=/api/users/8p74-8ut4/profile_images/LARGE v:screenName="Cathy Bouge" v:profileImageUrlSmall=/api/users/8p74-8ut4/profile_images/TINY v:roleName=publisher v:displayName="Cathy Bouge"
```

## Top Records

```ls
| :updated_at | first_name | last_name | organization                               | address_line_1       | address_line_2     | city       | state      | zip_code | email                        | phone        | select_the_rule_you_are_commenting_on | your_comment_question_or_recommendation                                                                                                                                                                                                                                                                                                      | provide_rule_language_optional | attach_file                                                                                                                                                                                                                                                                           | 
| =========== | ========== | ========= | ========================================== | ==================== | ================== | ========== | ========== | ======== | ============================ | ============ | ===================================== | ============================================================================================================================================================================================================================================================================================================================================ | ============================== | ===================================================================================================================================================================================================================================================================================== | 
| 1474902664  | Rob        | Rieck     | Ecology                                    |                      |                    |            |            |          |                              |              | yzke-438g                             | Test                                                                                                                                                                                                                                                                                                                                         |                                | [null, null, null, null]                                                                                                                                                                                                                                                              | 
| 1478128641  | Joy        | Diaz      | Whitworth University                       | 300 W. Hawthorne Rd. |                    | Spokane    | Washington | 99251    | jdiaz02@whitworth.edu        | 5097774339   | pf2k-rjze                             | Please consider if and how to include businesses and institutes of higher education in the definition of healthcare facilities when they own and operate health clinic and animal care facilities. Many such dual entities exist and the larger organization is likely already a dangerous waste generator. How do we then merge compliance? |                                | [null, null, null, null]                                                                                                                                                                                                                                                              | 
| 1481844147  | Joyce      | Lindell   | Providence Regional Medical Center Everett | Pharmacy             | 1321 Colby Ave     | Everett    | Wa         | 98201    | joyce.lindell@providence.org | 425-261-3535 | pf2k-rjze                             | see attached                                                                                                                                                                                                                                                                                                                                 | see attachment                 | [application/vnd.openxmlformats-officedocument.wordprocessingml.document, a21f1528-3e72-4e8a-834b-d0567e7cb56b, Interim Pharmaceutical Waste Policy Clarification.docx, 42595]                                                                                                        | 
| 1482163009  | Lis        | Houchen   | National Association of Chain Drug Stores  | 1776 Wilson Blvd     | Suite 200          | Arlington  | VA         | 22209    | lhouchen@nacds.org           | 360.480.6990 | pf2k-rjze                             | While we appreciate that the state???s draft rule mostly mirrors the proposed federal rule, we ask the Department to wait for any final EPA rules to ensure consistency between a federal rule and the state amendments.                                                                                                                     |                                | [application/vnd.openxmlformats-officedocument.wordprocessingml.document, 5358bf66-eb0e-4129-b011-ca9c222a87c9, G:\GOVT AFFAIRS AND PUBLIC POLICY\State\Individual States\Washington\Regulations\Washington State Hazardous Waste Pharmaceuticals Comment Letter 12-2016.docx, 70999] | 
| 1482167027  | Selin      | Hoboy     | Stericycle, Inc.                           | 12460 Crabapple Road | Suite 202, Box 227 | Alpharetta | GA         | 30004    | shoboy@stericycle.com        | 847-943-6685 | pf2k-rjze                             | Comment                                                                                                                                                                                                                                                                                                                                      | Please See Attached            | [application/pdf, 3fd109ee-8e4e-434c-91bc-10c464275fc6, C:\Users\shoboy\Documents\1-selinlive\Lobbying\State Issues\WA - Ecology\New Dangerous Waste Proposal 9-2016\Stericycle Comments WAC Pharma proposal - 12192016 - Final.pdf, 578216]                                          | 
```