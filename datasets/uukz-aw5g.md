# Homeless Services

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/homeless-services-ae63f) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/uukz-aw5g) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/uukz-aw5g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/uukz-aw5g/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | uukz-aw5g |
| Name | Homeless Services |
| Attribution | Mayor's Office of Human Services was |
| Category | Health |
| Tags | homeless services, human services, outreach, shelter |
| Created | 2012-09-25T15:27:36Z |
| Publication Date | 2014-04-03T23:44:48Z |

## Description

Baltimore City Street Outreach Information

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | series tag     | organization      | Organization      | text      | text        |
| Yes      | series tag     | type              | Type              | text      | text        |
| Yes      | series tag     | eligibleclients   | EligibleClients   | text      | text        |
| Yes      | series tag     | phone             | Phone             | text      | text        |
| Yes      | series tag     | hours             | Hours             | text      | text        |
| Yes      | numeric metric | men               | Men               | number    | number      |
| Yes      | numeric metric | women             | Women             | number    | number      |
| Yes      | numeric metric | womenchildren     | WomenChildren     | number    | number      |
| Yes      | numeric metric | youth             | Youth             | number    | number      |
| Yes      | numeric metric | families          | Families          | number    | number      |
| Yes      | numeric metric | showers           | Showers           | number    | number      |
| Yes      | numeric metric | clothing          | Clothing          | number    | number      |
| Yes      | numeric metric | transportation    | Transportation    | number    | number      |
| Yes      | numeric metric | telephones        | Telephones        | number    | number      |
| Yes      | numeric metric | educationtraining | EducationTraining | number    | number      |
| Yes      | numeric metric | drugrehab         | DrugRehab         | number    | number      |
| Yes      | numeric metric | food              | Food              | number    | number      |
| Yes      | numeric metric | casemanagement    | CaseManagement    | number    | number      |
| Yes      | numeric metric | medical           | Medical           | number    | number      |
| Yes      | numeric metric | laundry           | Laundry           | number    | number      |
| Yes      | series tag     | url               | URL               | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:uukz-aw5g d:2012-09-25T08:27:49.000Z t:organization="Paul's Place" t:phone=410-625-0775 t:hours="M-F: 8am-4pm" t:type="Drop-in Center" t:eligibleclients=All t:url=http://www.paulsplaceoutreach.org/ m:showers=1 m:womenchildren=0 m:clothing=1 m:telephones=1 m:youth=0 m:transportation=0 m:families=1 m:educationtraining=0 m:women=1 m:laundry=1 m:medical=0 m:drugrehab=0 m:food=1 m:men=1 m:casemanagement=0

series e:uukz-aw5g d:2012-09-25T08:27:49.000Z t:organization="DSS-HEESU (Homeless Environmental Emergency Services Unit)" t:phone=443-423-6000 t:hours="M-F: 8am-5pm (Application site for public benefits)" t:type="Drop-in Center" t:eligibleclients=All t:url=http://dhr.maryland.gov/county/baltimorecity/services.php m:showers=0 m:womenchildren=0 m:clothing=0 m:telephones=0 m:youth=0 m:transportation=1 m:families=1 m:educationtraining=0 m:women=1 m:laundry=0 m:medical=0 m:drugrehab=0 m:food=0 m:men=1 m:casemanagement=1

series e:uukz-aw5g d:2012-09-25T08:27:49.000Z t:organization="American Rescue Workers" t:phone=410-566-3300 t:hours="Everyday: 6pm-7am" t:type="Emergency Shelter" t:eligibleclients="Adult men" t:url=http://www.americanrescueworkers.org/ m:showers=0 m:womenchildren=0 m:clothing=0 m:telephones=0 m:youth=0 m:transportation=0 m:families=0 m:educationtraining=1 m:women=0 m:laundry=0 m:medical=0 m:drugrehab=1 m:food=0 m:men=1 m:casemanagement=0
```

## Meta Commands

```ls
metric m:men p:integer l:Men t:dataTypeName=number

metric m:women p:integer l:Women t:dataTypeName=number

metric m:womenchildren p:integer l:WomenChildren t:dataTypeName=number

metric m:youth p:integer l:Youth t:dataTypeName=number

metric m:families p:integer l:Families t:dataTypeName=number

metric m:showers p:integer l:Showers t:dataTypeName=number

metric m:clothing p:integer l:Clothing t:dataTypeName=number

metric m:transportation p:integer l:Transportation t:dataTypeName=number

metric m:telephones p:integer l:Telephones t:dataTypeName=number

metric m:educationtraining p:integer l:EducationTraining t:dataTypeName=number

metric m:drugrehab p:integer l:DrugRehab t:dataTypeName=number

metric m:food p:integer l:Food t:dataTypeName=number

metric m:casemanagement p:integer l:CaseManagement t:dataTypeName=number

metric m:medical p:integer l:Medical t:dataTypeName=number

metric m:laundry p:integer l:Laundry t:dataTypeName=number

entity e:uukz-aw5g l:"Homeless Services" t:attribution="Mayor's Office of Human Services was" t:url=https://data.baltimorecity.gov/api/views/uukz-aw5g

property e:uukz-aw5g t:meta.view v:id=uukz-aw5g v:category=Health v:attributionLink=http://humanservices.baltimorecity.gov/ v:averageRating=0 v:name="Homeless Services" v:attribution="Mayor's Office of Human Services was"

property e:uukz-aw5g t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:uukz-aw5g t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:uukz-aw5g t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | organization                                               | type              | eligibleclients          | phone        | hours                                               | men | women | womenchildren | youth | families | showers | clothing | transportation | telephones | educationtraining | drugrehab | food | casemanagement | medical | laundry | url                                                                                            | 
| =========== | ========================================================== | ================= | ======================== | ============ | =================================================== | === | ===== | ============= | ===== | ======== | ======= | ======== | ============== | ========== | ================= | ========= | ==== | ============== | ======= | ======= | ============================================================================================== | 
| 1348561669  | Paul's Place                                               | Drop-in Center    | All                      | 410-625-0775 | M-F: 8am-4pm                                        | 1   | 1     | 0             | 0     | 1        | 1       | 1        | 0              | 1          | 0                 | 0         | 1    | 0              | 0       | 1       | [http://www.paulsplaceoutreach.org/, null]                                                     | 
| 1348561669  | DSS-HEESU (Homeless Environmental Emergency Services Unit) | Drop-in Center    | All                      | 443-423-6000 | M-F: 8am-5pm (Application site for public benefits) | 1   | 1     | 0             | 0     | 1        | 0       | 0        | 1              | 0          | 0                 | 0         | 0    | 1              | 0       | 0       | [http://dhr.maryland.gov/county/baltimorecity/services.php, null]                              | 
| 1348561669  | American Rescue Workers                                    | Emergency Shelter | Adult men                | 410-566-3300 | Everyday: 6pm-7am                                   | 1   | 0     | 0             | 0     | 0        | 0       | 0        | 0              | 0          | 1                 | 1         | 0    | 0              | 0       | 0       | [http://www.americanrescueworkers.org/, null]                                                  | 
| 1348561669  | AIRS City Steps                                            | Drop-in Center    | Homeless Youth           | 410-528-0267 | M-F: 9am-5pm                                        | 0   | 0     | 0             | 1     | 0        | 0       | 0        | 0              | 0          | 0                 | 0         | 0    | 1              | 0       | 0       | [http://www.airshome.org/index.cfm?page=citysteps, null]                                       | 
| 1348561669  | Bon Secours Women's Resource Center                        | Drop-in Center    | Adult women and children | 410-362-3547 | M,T,Th,F: 9am-4:30pm                                | 0   | 1     | 1             | 0     | 0        | 1       | 1        | 0              | 1          | 0                 | 0         | 1    | 1              | 0       | 1       | [http://bonsecoursvocations.org/what-we-do/human-services/womens-resource-center/, null]       | 
| 1348561669  | Our Daily Bread Employment Center                          | Drop-in Center    | All                      | 443-986-9000 | M-F: 6am-4pm                                        | 1   | 1     | 1             | 0     | 0        | 0       | 0        | 1              | 1          | 0                 | 0         | 1    | 1              | 1       | 0       | [http://www.catholiccharities-md.org/our-daily-bread/, null]                                   | 
| 1348561669  | Weinberg Housing & Resource Center                         | Emergency Shelter | Adult men and women      | 443-478-3777 | Everyday: 24 hrs                                    | 1   | 1     | 0             | 0     | 0        | 1       | 0        | 0              | 1          | 0                 | 0         | 1    | 1              | 0       | 1       | [http://jhrbaltimore.org/shelter.htm, null]                                                    | 
| 1348562180  | HealthCare Access Maryland                                 | Drop-in Center    | All                      | 410-649-0501 | M-F: 8am-4:30pm                                     | 1   | 1     | 1             | 0     | 1        | 0       | 0        | 0              | 0          | 0                 | 0         | 0    | 1              | 0       | 0       | [http://www.healthcareaccessmaryland.org/, null]                                               | 
| 1348562199  | Sarah's Hope Mount Street Shelter                          | Emergency Shelter | Adult women and children | 410-396-2204 | Everyday: 24 hrs, Intake 9am-6pm                    | 0   | 0     | 1             | 0     | 0        | 0       | 0        | 0              | 1          | 0                 | 0         | 1    | 1              | 0       | 0       | [http://www.vincentbaltimore.org/programs_sarahs_hope_mountst_st_vincent_baltimore.html, null] | 
| 1348561669  | Health Care for the Homeless                               | Health Care       | All homeless             | 410-837-5533 | Walk-in M-F arrive by 6am, Sat arrive by 7am        | 1   | 1     | 0             | 0     | 1        | 0       | 0        | 0              | 0          | 0                 | 1         | 0    | 1              | 1       | 0       | [http://hchmd.org/, null]                                                                      | 
```