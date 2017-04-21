# DMH Veterans Provider Enrollment

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dmh-veterans-provider-enrollment-71d7a) |
| Metadata | [Link](https://data.mo.gov/api/views/8zvy-7azn) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/8zvy-7azn/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/8zvy-7azn/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 8zvy-7azn |
| Name | DMH Veterans Provider Enrollment |
| Category | Health |
| Created | 2014-03-14T17:39:54Z |
| Publication Date | 2017-04-17T13:14:37Z |

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                           | Data Type | Render Type |
| ======== | =========== | ============================== | ============================== | ========= | =========== |
| No       | time        | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag  | company_name                   | Company Name                   | text      | text        |
| Yes      | series tag  | ban                            | BAN                            | text      | text        |
| Yes      | series tag  | substance_abuse                | Substance Abuse                | text      | text        |
| Yes      | series tag  | lcsw                           | LCSW                           | text      | text        |
| Yes      | series tag  | lpc                            | LPC                            | text      | text        |
| Yes      | series tag  | mft                            | MFT                            | text      | text        |
| Yes      | series tag  | lmsw                           | LMSW                           | text      | text        |
| Yes      | series tag  | plpc                           | PLPC                           | text      | text        |
| Yes      | series tag  | psychiatric_nurse_practitioner | Psychiatric Nurse Practitioner | text      | text        |
| Yes      | series tag  | psychiatrist                   | Psychiatrist                   | text      | text        |
| Yes      | series tag  | psychologist                   | Psychologist                   | text      | text        |
| Yes      | series tag  | alcohol_and_substance_abuse    | Alcohol and Substance Use      | text      | text        |
| Yes      | series tag  | anger_management               | Anger Management               | text      | text        |
| Yes      | series tag  | child_adolescent               | Child/Adolescent               | text      | text        |
| Yes      | series tag  | domestic_violence              | Domestic Violence              | text      | text        |
| Yes      | series tag  | faith_based                    | Faith Based                    | text      | text        |
| Yes      | series tag  | family_marriage                | Family/Marriage                | text      | text        |
| Yes      | series tag  | general_mental_health          | General Mental Health          | text      | text        |
| Yes      | series tag  | post_traumatic_stress          | Post Traumatic Stress          | text      | text        |
| Yes      | series tag  | sexual_assault                 | Sexual Assault                 | text      | text        |
| Yes      | series tag  | suicide_prevention             | Suicide Prevention             | text      | text        |
| Yes      | series tag  | traumatic_brain_injury         | Traumatic Brain Injury         | text      | text        |
| Yes      | series tag  | website                        | Website                        | text      | text        |
| Yes      | series tag  | phone_number                   | Phone Number                   | text      | text        |
| Yes      | series tag  | zip_code                       | Zip Code                       | text      | number      |
| Yes      | series tag  | country                        | Country                        | text      | text        |
| Yes      | series tag  | tricare                        | TRICARE                        | text      | text        |
| Yes      | series tag  | military_culture               | Military Culture               | text      | text        |
| Yes      | series tag  | admin_notes                    | Admin Notes                    | text      | text        |
| Yes      | series tag  | suite_no                       | Suite No.                      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8zvy-7azn d:2015-10-20T07:36:53.000Z t:plpc=No t:post_traumatic_stress=Yes t:general_mental_health=Yes t:phone_number=6608267909 t:zip_code=65301 t:substance_abuse=No t:lcsw=No t:anger_management=Yes t:domestic_violence=Yes t:company_name="Dr. Gary C. Kitto & Associates, LLC" t:tricare=Yes t:psychiatrist=No t:sexual_assault=Yes t:ban=No t:military_culture="Yes, I have training in military culture" t:alcohol_and_substance_abuse=Yes t:suicide_prevention=Yes t:psychologist=No t:faith_based=Yes t:country="United States" t:family_marriage=Yes t:child_adolescent=Yes t:mft=No t:lpc=Yes t:psychiatric_nurse_practitioner=No t:lmsw=No t:traumatic_brain_injury=Yes m:row_number.8zvy-7azn=1

series e:8zvy-7azn d:2015-10-20T07:36:53.000Z t:plpc=No t:post_traumatic_stress=Yes t:general_mental_health=No t:phone_number=8167531866 t:zip_code=64112 t:substance_abuse=No t:lcsw=No t:anger_management=Yes t:domestic_violence=No t:company_name="Vet Center (Kansas City)" t:tricare=Yes t:psychiatrist=No t:sexual_assault=Yes t:ban=No t:military_culture="Yes, I have training in military culture" t:alcohol_and_substance_abuse=No t:suicide_prevention=No t:psychologist=No t:faith_based=No t:country="United States" t:family_marriage=Yes t:child_adolescent=No t:mft=No t:lpc=Yes t:psychiatric_nurse_practitioner=No t:lmsw=No t:traumatic_brain_injury=No m:row_number.8zvy-7azn=2

series e:8zvy-7azn d:2015-10-20T07:36:53.000Z t:plpc=No t:post_traumatic_stress=Yes t:general_mental_health=Yes t:phone_number=6363666543 t:zip_code=65714 t:substance_abuse=No t:lcsw=No t:anger_management=Yes t:domestic_violence=Yes t:company_name="ReignHeart Counseling (In Home Counseling Available)" t:tricare=No t:psychiatrist=No t:sexual_assault=No t:ban=No t:website=http://www.rhaofhope.org t:military_culture="Not yet, but I would like to work with the military community" t:alcohol_and_substance_abuse=Yes t:suicide_prevention=No t:psychologist=No t:faith_based=Yes t:country="United States" t:family_marriage=Yes t:child_adolescent=Yes t:mft=No t:lpc=Yes t:psychiatric_nurse_practitioner=No t:lmsw=No t:traumatic_brain_injury=Yes m:row_number.8zvy-7azn=3
```

## Meta Commands

```ls
metric m:row_number.8zvy-7azn p:long l:"Row Number"

entity e:8zvy-7azn l:"DMH Veterans Provider Enrollment" t:url=https://data.mo.gov/api/views/8zvy-7azn

property e:8zvy-7azn t:meta.view v:id=8zvy-7azn v:category=Health v:averageRating=0 v:name="DMH Veterans Provider Enrollment"

property e:8zvy-7azn t:meta.view.owner v:id=qj3c-3m85 v:screenName="Jon Sabala" v:displayName="Jon Sabala"

property e:8zvy-7azn t:meta.view.tableauthor v:id=qj3c-3m85 v:screenName="Jon Sabala" v:roleName=editor v:displayName="Jon Sabala"
```

## Top Records

```ls
| :updated_at | company_name                                         | ban | substance_abuse | lcsw | lpc | mft | lmsw | plpc | psychiatric_nurse_practitioner | psychiatrist | psychologist | alcohol_and_substance_abuse | anger_management | child_adolescent | domestic_violence | faith_based | family_marriage | general_mental_health | post_traumatic_stress | sexual_assault | suicide_prevention | traumatic_brain_injury | website                     | phone_number | zip_code | country       | tricare | military_culture                                              | admin_notes | suite_no  | 
| =========== | ==================================================== | === | =============== | ==== | === | === | ==== | ==== | ============================== | ============ | ============ | =========================== | ================ | ================ | ================= | =========== | =============== | ===================== | ===================== | ============== | ================== | ====================== | =========================== | ============ | ======== | ============= | ======= | ============================================================= | =========== | ========= | 
| 1445326613  | Dr. Gary C. Kitto & Associates, LLC                  | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | Yes                         | Yes              | Yes              | Yes               | Yes         | Yes             | Yes                   | Yes                   | Yes            | Yes                | Yes                    |                             | 6608267909   | 65301    | United States | Yes     | Yes, I have training in military culture                      |             |           | 
| 1445326613  | Vet Center (Kansas City)                             | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | No                          | Yes              | No               | No                | No          | Yes             | No                    | Yes                   | Yes            | No                 | No                     |                             | 8167531866   | 64112    | United States | Yes     | Yes, I have training in military culture                      |             |           | 
| 1445326613  | ReignHeart Counseling (In Home Counseling Available) | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | Yes                         | Yes              | Yes              | Yes               | Yes         | Yes             | Yes                   | Yes                   | No             | No                 | Yes                    | http://www.rhaofhope.org    | 6363666543   | 65714    | United States | No      | Not yet, but I would like to work with the military community |             |           | 
| 1445326613  | White Oak Counseling                                 | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | Yes                         | Yes              | Yes              | Yes               | Yes         | Yes             | Yes                   | Yes                   | Yes            | Yes                | Yes                    |                             | 5732212111   | 63401    | United States | Yes     | Not yet, but I would like to work with the military community |             |           | 
| 1445326613  | Counseling Associates                                | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | Yes                         | Yes              | Yes              | Yes               | Yes         | Yes             | Yes                   | Yes                   | No             | Yes                | Yes                    |                             | 4176671931   | 64804    | United States | No      | Not yet, but I would like to work with the military community |             |           | 
| 1445326613  | Curtis Counseling, LLC                               | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | No                          | Yes              | Yes              | No                | No          | Yes             | Yes                   | Yes                   | No             | No                 | No                     |                             | 4172521942   | 65793    | United States | Yes     | Not yet, but I would like to work with the military community |             |           | 
| 1445326613  | H.O.U.S.E. Inc.                                      | No  | Yes             | No   | No  | No  | No   | No   | No                             | No           | No           | Yes                         | No               | No               | No                | No          | No              | No                    | No                    | No             | No                 | No                     | http://house-inc.org        | 4176238933   | 64870    | United States | No      | Not yet, but I would like to work with the military community |             |           | 
| 1445326613  | Frances V. Totta, LPC                                | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | No                          | No               | No               | No                | Yes         | Yes             | Yes                   | No                    | No             | No                 | No                     | http://TherapistLocator.net | 8164446750   | 64116    | United States | No      | Not yet, but I would like to work with the military community |             |           | 
| 1445326613  | Tobias Simers, LPC                                   | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | No                          | Yes              | Yes              | Yes               | Yes         | Yes             | Yes                   | Yes                   | No             | No                 | No                     |                             | 6364866250   | 63040    | United States | No      | Not yet, but I would like to work with the military community |             | Suite 212 | 
| 1445326613  | Kathleen Leach-Ross, LPC                             | No  | No              | No   | Yes | No  | No   | No   | No                             | No           | No           | No                          | Yes              | No               | Yes               | No          | No              | Yes                   | Yes                   | Yes            | Yes                | No                     |                             | 3148785570   | 63141    | United States | No      | Not yet, but I would like to work with the military community |             |           | 
```