# Complaint By Practice

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/complaint-by-practice) |
| Metadata | [Link](https://data.wa.gov/api/views/fvrz-yz45) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/fvrz-yz45/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/fvrz-yz45/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | fvrz-yz45 |
| Name | Complaint By Practice |
| Attribution | Washington State Attorney General's Office |
| Category | Consumer Protection |
| Tags | consumer protection data consumer complaints |
| Created | 2016-04-28T14:51:30Z |
| Publication Date | 2016-08-08T22:21:08Z |

## Description

This dataset contains codes which attempts to summarize the issues described in the complaints.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | openeddate          | OpenedDate          | calendar_date | calendar_date |
| No       |                | openedyear          | OpenedYear          | number        | number        |
| Yes      | series tag     | status              | Status              | text          | text          |
| Yes      | series tag     | practicecode        | PracticeCode        | text          | text          |
| Yes      | series tag     | practicename        | PracticeName        | text          | text          |
| Yes      | series tag     | businesscategory    | BusinessCategory    | text          | text          |
| Yes      | series tag     | naics               | NAICS               | text          | text          |
| Yes      | series tag     | naicsname           | NAICS Name          | text          | text          |
| Yes      | series tag     | businessname        | BusinessName        | text          | text          |
| Yes      | series tag     | businessstreetline1 | BusinessStreetLine1 | text          | text          |
| Yes      | series tag     | businessstreetline2 | BusinessStreetLine2 | text          | text          |
| Yes      | series tag     | businesscity        | BusinessCity        | text          | text          |
| Yes      | series tag     | businessstate       | BusinessState       | text          | text          |
| Yes      | series tag     | businesszip         | BusinessZip         | text          | text          |
| Yes      | numeric metric | estimatedsavings    | EstimatedSavings    | money         | money         |
| Yes      | series tag     | practiceid          | PracticeId          | text          | number        |
| Yes      | numeric metric | actualsavings       | ActualSavings       | money         | money         |
| Yes      | series tag     | complaintid         | ComplaintId         | text          | number        |
| Yes      | series tag     | businessid          | BusinessId          | text          | number        |
| No       |                | id                  | id                  | text          | number        |
```

## Time Field

```ls
Value = openeddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = id,openedyear
```

## Data Commands

```ls
series e:fvrz-yz45 d:2017-04-18T00:00:00.000Z t:businessname="Unknown - Technical Support" t:businessid=265006 t:practiceid=194 t:complaintid=503593 t:naics=993000-Phishing t:status=Closed t:businesscategory=Phishing t:practicename="Imposter scam" t:practicecode=017 m:actualsavings=0 m:estimatedsavings=0

series e:fvrz-yz45 d:2017-04-14T00:00:00.000Z t:businessname="Unknown - Technical Support" t:businessid=265006 t:practiceid=194 t:complaintid=503418 t:naics=993000-Phishing t:status=Closed t:businesscategory=Phishing t:practicename="Imposter scam" t:practicecode=017 m:actualsavings=0 m:estimatedsavings=0

series e:fvrz-yz45 d:2017-04-07T00:00:00.000Z t:businessname="Washington Healthcare Exchange/Washington Healthplan Finder/Washington Health Benefit Exchange" t:businesszip=98501 t:businessstate=WA t:status=Closed t:practicename="Imposter scam" t:businessstreetline1="810 Jefferson St SE" t:practiceid=194 t:businessid=249482 t:naics="524000-Insurance Carriers & Related Activities" t:complaintid=503020 t:businesscategory=Insurance t:practicecode=017 t:businesscity=Olympia m:actualsavings=0 m:estimatedsavings=0
```

## Meta Commands

```ls
metric m:estimatedsavings p:double l:EstimatedSavings t:dataTypeName=money

metric m:actualsavings p:double l:ActualSavings t:dataTypeName=money

entity e:fvrz-yz45 l:"Complaint By Practice" t:attribution="Washington State Attorney General's Office" t:url=https://data.wa.gov/api/views/fvrz-yz45

property e:fvrz-yz45 t:meta.view v:id=fvrz-yz45 v:category="Consumer Protection" v:averageRating=0 v:name="Complaint By Practice" v:attribution="Washington State Attorney General's Office"

property e:fvrz-yz45 t:meta.view.owner v:id=f8sf-wn9w v:profileImageUrlMedium=/api/users/f8sf-wn9w/profile_images/THUMB v:profileImageUrlLarge=/api/users/f8sf-wn9w/profile_images/LARGE v:screenName="Young, Marvin (ATG)" v:profileImageUrlSmall=/api/users/f8sf-wn9w/profile_images/TINY v:displayName="Young, Marvin (ATG)"

property e:fvrz-yz45 t:meta.view.tableauthor v:id=f8sf-wn9w v:profileImageUrlMedium=/api/users/f8sf-wn9w/profile_images/THUMB v:profileImageUrlLarge=/api/users/f8sf-wn9w/profile_images/LARGE v:screenName="Young, Marvin (ATG)" v:profileImageUrlSmall=/api/users/f8sf-wn9w/profile_images/TINY v:roleName=designer v:displayName="Young, Marvin (ATG)"
```

## Top Records

```ls
| openeddate          | openedyear | status | practicecode | practicename  | businesscategory            | naics                                          | naicsname | businessname                                                                                   | businessstreetline1   | businessstreetline2 | businesscity | businessstate | businesszip | estimatedsavings | practiceid | actualsavings | complaintid | businessid | id           | 
| =================== | ========== | ====== | ============ | ============= | =========================== | ============================================== | ========= | ============================================================================================== | ===================== | =================== | ============ | ============= | =========== | ================ | ========== | ============= | =========== | ========== | ============ | 
| 2017-04-18T00:00:00 | 2017       | Closed | 017          | Imposter scam | Phishing                    | 993000-Phishing                                |           | Unknown - Technical Support                                                                    |                       |                     |              |               |             | 0.00             | 194        | 0.00          | 503593      | 265006     | 194000503593 | 
| 2017-04-14T00:00:00 | 2017       | Closed | 017          | Imposter scam | Phishing                    | 993000-Phishing                                |           | Unknown - Technical Support                                                                    |                       |                     |              |               |             | 0.00             | 194        | 0.00          | 503418      | 265006     | 194000503418 | 
| 2017-04-07T00:00:00 | 2017       | Closed | 017          | Imposter scam | Insurance                   | 524000-Insurance Carriers & Related Activities |           | Washington Healthcare Exchange/Washington Healthplan Finder/Washington Health Benefit Exchange | 810 Jefferson St SE   |                     | Olympia      | WA            | 98501       | 0.00             | 194        | 0.00          | 503020      | 249482     | 194000503020 | 
| 2017-03-29T00:00:00 | 2017       | Closed | 017          | Imposter scam | Unclassified Establishments | 990000-Unclassified Establishments             |           | Unknown                                                                                        |                       |                     |              |               |             | 0.00             | 194        | 0.00          | 502550      | 207054     | 194000502550 | 
| 2017-03-29T00:00:00 | 2017       | Closed | 017          | Imposter scam | Unclassified Establishments | 990000-Unclassified Establishments             |           | Unknown                                                                                        |                       |                     |              |               |             | 0.00             | 194        | 0.00          | 502539      | 207054     | 194000502539 | 
| 2017-03-29T00:00:00 | 2017       | Closed | 017          | Imposter scam | Phishing                    | 993000-Phishing                                |           | Unknown - IRS Phishing                                                                         | This is the ALL Major |                     |              |               |             | 0.00             | 194        | 0.00          | 502413      | 227165     | 194000502413 | 
| 2017-03-23T00:00:00 | 2017       | Closed | 017          | Imposter scam | Phishing                    | 993000-Phishing                                |           | Unknown                                                                                        |                       |                     |              |               |             | 0.00             | 194        | 0.00          | 502214      | 207054     | 194000502214 | 
| 2017-03-23T00:00:00 | 2017       | Closed | 017          | Imposter scam | Phishing                    | 993000-Phishing                                |           | Unknown - IRS Phishing                                                                         | This is the ALL Major |                     |              |               |             | 0.00             | 194        | 0.00          | 502188      | 227165     | 194000502188 | 
| 2017-03-22T00:00:00 | 2017       | Closed | 017          | Imposter scam | Phishing                    | 993000-Phishing                                |           | Unknown                                                                                        |                       |                     |              |               |             | 0.00             | 194        | 0.00          | 502158      | 207054     | 194000502158 | 
| 2017-03-22T00:00:00 | 2017       | Closed | 017          | Imposter scam | Phishing                    | 993000-Phishing                                |           | Unknown                                                                                        |                       |                     |              |               |             | 0.00             | 194        | 0.00          | 502146      | 207054     | 194000502146 | 
```