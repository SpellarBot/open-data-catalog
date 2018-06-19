# Permit Consultant Registration and Quarterly Disclosure Reports

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/permit-consultant-registration-and-quarterly-disclosure-reports-d7546) |
| Metadata | [Link](https://data.sfgov.org/api/views/py46-sknn) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/py46-sknn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/py46-sknn/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | py46-sknn |
| Name | Permit Consultant Registration and Quarterly Disclosure Reports |
| Attribution | San Francisco Ethics Commission |
| Category | City Management and Ethics |
| Tags | permit consultant, registration, quarterly, disclosure |
| Created | 2015-01-08T22:36:50Z |
| Publication Date | 2016-05-04T20:44:09Z |

## Description

Effective January 1, 2015, an individual who qualifies as a permit consultant under San Francisco law must register and file quarterly reports with the Ethics Commission.A permit consultant is an individual who receives or is promised compensation to provide permit consulting services on a ???major project?? or a ???minor project,?? including any employee who receives compensation for time spent on permit consulting services. ???Permit consulting services?? means any contact with the Department of Building Inspection, the Entertainment Commission, the Planning Department, or the Department of Public Works to help a permit applicant obtain a permit.  ???Permit consulting services?? do not include simple requests for information which do not otherwise include attempts to help obtain a permit.A ???major project?? is a real estate development project located in the City and County of San Francisco with estimated construction costs exceeding $1,000,000 and which requires a permit issued by the Department of Building Inspection or the Planning Department.   Estimated constructions costs are to be calculated in the same manner used to determine building permit fees under the Building Code. A ???minor project?? is a project located in the City and County of San Francisco which requires a permit issued by the Entertainment Commission.The following individuals are not permit consultants and thus are not required to register or report:-a licensed architect or engineer of record for construction activity allowed or contemplated by the permit, or an employee of that architect or engineer;-a contractor who will be responsible for all construction activity associated with the requested permit, or an employee of that contractor; or-an employee or agent of an organization with tax exempt status under 26 United States Code Section 501(c)(3) communicating on behalf of that organization regarding the development of a project for that organization. Each permit consultant must register with the Ethics Commission no later than five business days after providing permit consulting services.  Quarterly disclosure reports must subsequently be filed with the Ethics Commission.

## Columns

```ls
| Included | Schema Type | Field Name                   | Name                         | Data Type      | Render Type    |
| ======== | =========== | ============================ | ============================ | ============== | ============== |
| Yes      | series tag  | permit_consultant_last_name  | Permit Consultant Last Name  | text           | text           |
| Yes      | series tag  | permit_consultant_first_name | Permit Consultant First Name | text           | text           |
| Yes      | series tag  | employer                     | Employer                     | text           | text           |
| Yes      | time        | date_filed                   | Date Filed                   | calendar_date  | calendar_date  |
| Yes      | series tag  | report_type                  | Report Type                  | drop_down_list | drop_down_list |
| Yes      | series tag  | report                       | Report                       | document       | document       |
| No       |             | period_start_date            | Period Start Date            | calendar_date  | calendar_date  |
| No       |             | period_end_date              | Period End Date              | calendar_date  | calendar_date  |
| Yes      | series tag  | amendment_filing             | Amendment Filing             | checkbox       | checkbox       |
| No       |             | amendment_to_report_filed    | Amendment to Report Filed    | calendar_date  | calendar_date  |
| Yes      | series tag  | activity                     | Activity                     | checkbox       | checkbox       |
| Yes      | series tag  | termination                  | Termination                  | checkbox       | checkbox       |
```

## Time Field

```ls
Value = date_filed
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = period_start_date,period_end_date,amendment_to_report_filed
```

## Data Commands

```ls
series e:py46-sknn d:2015-04-16T00:00:00.000Z t:report.content_type=application/pdf t:report.filename=YYYYMMDD_20150416_3410A_Beattie_Linda_Redacted.pdf t:permit_consultant_last_name=Beattie t:employer="B & B Contractors Services LLC" t:report_type=u6d4-g9iu t:report.file_id=ShzHQFfIsjVo276qMHS8CWqOds24vLyPDwJuL2GH6qw t:report.size=341994 t:permit_consultant_first_name=Linda m:row_number.py46-sknn=1

series e:py46-sknn d:2015-04-15T00:00:00.000Z t:report.content_type=application/pdf t:report.filename=YYYYMMDD_20150415_3410A_Larizadeh_Ahmad_Redacted.pdf t:permit_consultant_last_name=Larizadeh t:employer="Bana Consulting Inc." t:report_type=u6d4-g9iu t:report.file_id=Q0hB2vPZZnpsy0C0sAwFDeHJk_mJDDbYzU1xTTe6_4A t:report.size=130805 t:permit_consultant_first_name=Ahmad m:row_number.py46-sknn=2

series e:py46-sknn d:2015-04-15T00:00:00.000Z t:report.content_type=application/pdf t:report.filename=YYYYMMDD_20150415_3410A_Larizadeh_Ahmad_Redacted.pdf t:permit_consultant_last_name=Larizadeh t:employer="Bana Consulting Inc." t:report_type=u6d4-g9iu t:report.file_id=Q0hB2vPZZnpsy0C0sAwFDeHJk_mJDDbYzU1xTTe6_4A t:report.size=130805 t:permit_consultant_first_name=Mahmoud m:row_number.py46-sknn=3
```

## Meta Commands

```ls
metric m:row_number.py46-sknn p:long l:"Row Number"

entity e:py46-sknn l:"Permit Consultant Registration and Quarterly Disclosure Reports" t:attribution="San Francisco Ethics Commission" t:url=https://data.sfgov.org/api/views/py46-sknn

property e:py46-sknn t:meta.view v:id=py46-sknn v:category="City Management and Ethics" v:attributionLink=http://www.sfethics.org v:averageRating=0 v:name="Permit Consultant Registration and Quarterly Disclosure Reports" v:attribution="San Francisco Ethics Commission"

property e:py46-sknn t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:py46-sknn t:meta.view.owner v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:displayName="Steven Massey"

property e:py46-sknn t:meta.view.tableauthor v:id=vm9c-ykir v:profileImageUrlMedium=/api/users/vm9c-ykir/profile_images/THUMB v:profileImageUrlLarge=/api/users/vm9c-ykir/profile_images/LARGE v:screenName="Steven Massey" v:profileImageUrlSmall=/api/users/vm9c-ykir/profile_images/TINY v:roleName=publisher v:displayName="Steven Massey"
```

## Top Records

```ls
| permit_consultant_last_name | permit_consultant_first_name | employer                       | date_filed          | report_type | report                                                                                                                                       | period_start_date   | period_end_date     | amendment_filing | amendment_to_report_filed | activity | termination | 
| =========================== | ============================ | ============================== | =================== | =========== | ============================================================================================================================================ | =================== | =================== | ================ | ========================= | ======== | =========== | 
| Beattie                     | Linda                        | B & B Contractors Services LLC | 2015-04-16T00:00:00 | u6d4-g9iu   | [application/pdf, ShzHQFfIsjVo276qMHS8CWqOds24vLyPDwJuL2GH6qw, YYYYMMDD_20150416_3410A_Beattie_Linda_Redacted.pdf, 341994]                   | 2015-04-16T00:00:00 | 2015-04-16T00:00:00 |                  | 2015-08-25T16:11:07       |          |             | 
| Larizadeh                   | Ahmad                        | Bana Consulting Inc.           | 2015-04-15T00:00:00 | u6d4-g9iu   | [application/pdf, Q0hB2vPZZnpsy0C0sAwFDeHJk_mJDDbYzU1xTTe6_4A, YYYYMMDD_20150415_3410A_Larizadeh_Ahmad_Redacted.pdf, 130805]                 | 2015-04-15T00:00:00 | 2015-04-15T00:00:00 |                  | 2015-08-25T16:16:56       |          |             | 
| Larizadeh                   | Mahmoud                      | Bana Consulting Inc.           | 2015-04-15T00:00:00 | u6d4-g9iu   | [application/pdf, Q0hB2vPZZnpsy0C0sAwFDeHJk_mJDDbYzU1xTTe6_4A, YYYYMMDD_20150415_3410A_Larizadeh_Ahmad_Redacted.pdf, 130805]                 | 2015-04-15T00:00:00 | 2015-04-15T00:00:00 |                  | 2015-08-25T16:18:09       |          |             | 
| Tan                         | Christopher                  | Bana Consulting Inc.           | 2015-04-15T00:00:00 | u6d4-g9iu   | [application/pdf, Q0hB2vPZZnpsy0C0sAwFDeHJk_mJDDbYzU1xTTe6_4A, YYYYMMDD_20150415_3410A_Larizadeh_Ahmad_Redacted.pdf, 130805]                 | 2015-04-15T00:00:00 | 2015-04-15T00:00:00 |                  | 2015-08-25T16:19:18       |          |             | 
| Tan                         | Desmond                      | Bana Consulting Inc.           | 2015-04-15T00:00:00 | u6d4-g9iu   | [application/pdf, Q0hB2vPZZnpsy0C0sAwFDeHJk_mJDDbYzU1xTTe6_4A, YYYYMMDD_20150415_3410A_Larizadeh_Ahmad_Redacted.pdf, 130805]                 | 2015-04-15T00:00:00 | 2015-04-15T00:00:00 |                  | 2015-08-25T16:20:48       |          |             | 
| Baumann                     | Bruce                        | Bruce D Baumann & Associates   | 2015-04-10T00:00:00 | frr7-727g   | [application/pdf, _6S0Kz6TKNfv5O0PERc0alxIURZFLd7mFXndhTTqTYY, 20150331_20150410_3410B_Baumann_Bruce_Redacted.pdf, 1538436]                  | 2015-01-01T00:00:00 | 2015-03-31T00:00:00 |                  | 2015-08-25T16:32:17       | true     |             | 
| Baumann                     | Bruce                        | Bruce D Baumann & Associates   | 2015-07-13T00:00:00 | frr7-727g   | [application/pdf, mGjpWtDI7SWRgir7l1eOjTl71f3OgTNpOOKa8IgjDJM, 20150630_20150713_3410B_Baumann_Bruce_Redacted.pdf, 1862227]                  | 2015-04-01T00:00:00 | 2015-06-30T00:00:00 |                  | 2015-08-25T16:44:05       | true     |             | 
| Tan                         | Brandon                      | Bana Consulting Inc.           | 2015-04-15T00:00:00 | u6d4-g9iu   | [application/pdf; charset=binary, Q0hB2vPZZnpsy0C0sAwFDeHJk_mJDDbYzU1xTTe6_4A, YYYYMMDD_20150415_3410A_Larizadeh_Ahmad_Redacted.pdf, 130805] | 2015-04-15T00:00:00 | 2015-04-15T00:00:00 |                  | 2015-08-25T16:22:07       |          |             | 
| Badiner                     | Lawrence                     | Badiner Urban Planning, Inc.   | 2015-04-09T00:00:00 | frr7-727g   | [application/pdf, -avhjVoiqFCnq7XF8k129djhrmTttbVYAqLCwXFTpEc, 20150331_20150409_3410B_Badiner_Lawrence_Redacted.pdf, 529714]                | 2015-01-01T00:00:00 | 2015-03-31T00:00:00 |                  | 2015-08-25T16:13:19       | true     |             | 
| Dick                        | Ilene                        | Farella Braun + Martel LLP     | 2015-04-15T00:00:00 | frr7-727g   | [application/pdf, Rq4SSr9kF6mumiItWYWnxNRkDjpXxelUEUnmVGy_toM, 20150331_20150415_3410B_Dick_Ilene_Redacted.pdf, 804078]                      | 2015-01-01T00:00:00 | 2015-03-31T00:00:00 |                  | 2015-08-25T16:51:13       | true     |             | 
```