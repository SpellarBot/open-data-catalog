# Code Enforcement All Violations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/code-enforcement-all-violations) |
| Metadata | [Link](https://data.nola.gov/api/views/3ehi-je3s) |
| Data: JSON | [100 Rows](https://data.nola.gov/api/views/3ehi-je3s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.nola.gov/api/views/3ehi-je3s/rows.csv?max_rows=100) |
| Host | data.nola.gov |
| Id | 3ehi-je3s |
| Name | Code Enforcement All Violations |
| Category | Housing, Land Use, and Blight |
| Tags | blightstatus, violation |
| Created | 2014-02-05T17:09:08Z |
| Publication Date | 2014-02-19T03:35:00Z |

## Description

Code Enforcement All Violations. Connected to http://blightstatus.nola.gov/.

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type     | Render Type   |
| ======== | =========== | ============= | ============= | ============= | ============= |
| Yes      | series tag  | caseid        | CaseID        | text          | number        |
| Yes      | series tag  | violationid   | ViolationID   | text          | number        |
| Yes      | series tag  | caseno        | CaseNo        | text          | text          |
| Yes      | series tag  | location      | Location      | text          | text          |
| Yes      | time        | violationdate | ViolationDate | calendar_date | calendar_date |
| Yes      | series tag  | codesection   | CodeSection   | text          | text          |
| Yes      | series tag  | violation     | Violation     | text          | text          |
| Yes      | series tag  | description   | Description   | text          | text          |
| No       |             | lastupload    | LastUpload    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = violationdate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = lastupload
```

## Data Commands

```ls
series e:3ehi-je3s d:2013-03-06T10:52:44.000Z t:location="6218-6220 Wainwright Dr" t:description="Structural members shall be maintained structurally sound, free from deterioration, and must be capable of supporting the imposed dead and live loads." t:violation="28-11 Structure" t:codesection=28-11 t:caseno=09-002855 t:violationid=547584 t:caseid=171833 m:row_number.3ehi-je3s=1

series e:3ehi-je3s d:2013-03-06T10:53:03.000Z t:location="6218-6220 Wainwright Dr" t:description="Structural members including floor joists must be maintained structurally sound." t:violation="28-11 Floor Joists" t:codesection=28-11 t:caseno=09-002855 t:violationid=547585 t:caseid=171833 m:row_number.3ehi-je3s=2

series e:3ehi-je3s d:2013-03-06T10:53:55.000Z t:location="6218-6220 Wainwright Dr" t:description="Structural members including studs must be maintained structurally sound." t:violation="28-11 Studs" t:codesection=28-11 t:caseno=09-002855 t:violationid=547590 t:caseid=171833 m:row_number.3ehi-je3s=3
```

## Meta Commands

```ls
metric m:row_number.3ehi-je3s p:long l:"Row Number"

entity e:3ehi-je3s l:"Code Enforcement All Violations" t:url=https://data.nola.gov/api/views/3ehi-je3s

property e:3ehi-je3s t:meta.view v:id=3ehi-je3s v:category="Housing, Land Use, and Blight" v:averageRating=0 v:name="Code Enforcement All Violations"

property e:3ehi-je3s t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:3ehi-je3s t:meta.view.owner v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:displayName="Socrata Service Account"

property e:3ehi-je3s t:meta.view.tableauthor v:id=ubzy-vsh3 v:screenName="Socrata Service Account" v:roleName=editor v:displayName="Socrata Service Account"

property e:3ehi-je3s t:meta.view.metadata.custom_fields.common_core v:Contact_Email=data@nola.gov
```

## Top Records

```ls
| caseid | violationid | caseno    | location                | violationdate       | codesection | violation                 | description                                                                                                                                                                                               | lastupload          | 
| ====== | =========== | ========= | ======================= | =================== | =========== | ========================= | ========================================================================================================================================================================================================= | =================== | 
| 171833 | 547584      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:52:44 | 28-11       | 28-11 Structure           | Structural members shall be maintained structurally sound, free from deterioration, and must be capable of supporting the imposed dead and live loads.                                                    | 2014-02-18T22:43:37 | 
| 171833 | 547585      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:53:03 | 28-11       | 28-11 Floor Joists        | Structural members including floor joists must be maintained structurally sound.                                                                                                                          | 2014-02-18T22:43:37 | 
| 171833 | 547590      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:53:55 | 28-11       | 28-11 Studs               | Structural members including studs must be maintained structurally sound.                                                                                                                                 | 2014-02-18T22:43:37 | 
| 171833 | 547592      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:54:20 | 28-11       | 28-11 Rafters             | Structural members including rafters must be maintained structurally sound.                                                                                                                               | 2014-02-18T22:43:37 | 
| 171833 | 547586      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:53:15 | 28-13       | 28-13 Weatherboards       | Exterior walls and weatherboards must be free from holes, breaks, and loose or rotting materials, and must be maintained weatherproof and properly surface coated where required.                         | 2014-02-18T22:43:37 | 
| 171833 | 547587      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:53:24 | 28-13       | 28-13 Siding              | Exterior walls and siding must be free from holes, breaks, and loose or rotting materials, and must be maintained weatherproof and properly surface coated where required.                                | 2014-02-18T22:43:37 | 
| 171833 | 547591      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:54:07 | 28-13       | 28-13 Parapet Wall        | Exterior walls must be free from holes, breaks, and loose or rotting materials, and must be maintained weatherproof and properly surface coated where required.                                           | 2014-02-18T22:43:37 | 
| 171833 | 547593      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:54:27 | 28-14       | 28-14 Roof                | The roof and flashing must be sound, tight, and without defects; must prevent dampness or deterioration in walls and interior of structure; and must be maintained in good repair free from obstructions. | 2014-02-18T22:43:37 | 
| 171833 | 547600      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:57:50 | 28-15       | 28-15 Boarded and Secured | Unoccupied structures must be boarded and secured to prevent entry of unauthorized persons.                                                                                                               | 2014-02-18T22:43:37 | 
| 171833 | 547595      | 09-002855 | 6218-6220 Wainwright Dr | 2013-03-06T10:55:28 | 28-20       | 28-20 Rodent Harborage    | All structures and exterior property must be kept free from rodent harborage and infestation. When found, rodents must be promptly exterminated by approved processes.                                    | 2014-02-18T22:43:37 | 
```