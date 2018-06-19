# Attorney General Consumer Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/attorney-general-consumer-complaints) |
| Metadata | [Link](https://data.wa.gov/api/views/gpri-47xz) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/gpri-47xz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/gpri-47xz/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | gpri-47xz |
| Name | Attorney General Consumer Complaints |
| Attribution | Washington State Attorney General's Office Consumer Protection Division |
| Category | Consumer Protection |
| Tags | washington state attorney general, consumer complaints, consumer issues, top consumer issues |
| Created | 2016-04-15T20:27:54Z |
| Publication Date | 2016-08-08T22:17:44Z |

## Description

Complaint data from consumer complaints filed with the Consumer Protection Division. The existence of a complaint is not evidence of wrongdoing.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | openeddate          | OpenedDate          | calendar_date | calendar_date |
| No       |                | openedyear          | OpenedYear          | number        | number        |
| Yes      | series tag     | status              | Status              | text          | text          |
| Yes      | numeric metric | estimatedsavings    | EstimatedSavings    | money         | money         |
| Yes      | numeric metric | actualsavings       | ActualSavings       | money         | money         |
| Yes      | series tag     | businesscategory    | BusinessCategory    | text          | text          |
| Yes      | series tag     | naics               | NAICS               | text          | text          |
| Yes      | series tag     | naicsname           | NAICS Name          | text          | text          |
| Yes      | series tag     | business            | BusinessName        | text          | text          |
| Yes      | series tag     | businessstreetline1 | BusinessStreetLine1 | text          | text          |
| Yes      | series tag     | businessstreetline2 | BusinessStreetLine2 | text          | text          |
| Yes      | series tag     | businesscity        | BusinessCity        | text          | text          |
| Yes      | series tag     | businessstate       | BusinessState       | text          | text          |
| Yes      | series tag     | businesszip         | BusinessZip         | text          | text          |
| Yes      | series tag     | business_id         | BusinessId          | text          | number        |
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
series e:gpri-47xz d:2015-07-01T00:00:00.000Z t:businesszip=98002 t:naics=621200 t:businessstate=WA t:status=Closed t:businesscategory="Health Care" t:business_id=236514 t:business="A Street Dental" t:businesscity=Auburn t:businessstreetline1="902 A St SE Ste A" m:actualsavings=0 m:estimatedsavings=0

series e:gpri-47xz d:2017-02-06T00:00:00.000Z t:naics="990000-Unclassified Establishments" t:status=New t:businesscategory="Unclassified Establishments" t:business_id=207054 t:business=Unknown m:actualsavings=0 m:estimatedsavings=0

series e:gpri-47xz d:2017-04-20T00:00:00.000Z t:businesszip=18706 t:naics="522291-Consumer Lending (includes Payday Lenders)" t:businessstate=PA t:status=New t:businesscategory="Consumer Lending & Transfer Agents" t:business_id=122656 t:business="Navient fka Sallie Mae" t:businesscity=Wilkes-Barre t:businessstreetline1="220 Lasley Ave" m:actualsavings=0 m:estimatedsavings=0
```

## Meta Commands

```ls
metric m:estimatedsavings p:double l:EstimatedSavings t:dataTypeName=money

metric m:actualsavings p:double l:ActualSavings t:dataTypeName=money

entity e:gpri-47xz l:"Attorney General Consumer Complaints" t:attribution="Washington State Attorney General's Office Consumer Protection Division" t:url=https://data.wa.gov/api/views/gpri-47xz

property e:gpri-47xz t:meta.view v:id=gpri-47xz v:category="Consumer Protection" v:averageRating=0 v:name="Attorney General Consumer Complaints" v:attribution="Washington State Attorney General's Office Consumer Protection Division"

property e:gpri-47xz t:meta.view.owner v:id=f8sf-wn9w v:profileImageUrlMedium=/api/users/f8sf-wn9w/profile_images/THUMB v:profileImageUrlLarge=/api/users/f8sf-wn9w/profile_images/LARGE v:screenName="Young, Marvin (ATG)" v:profileImageUrlSmall=/api/users/f8sf-wn9w/profile_images/TINY v:displayName="Young, Marvin (ATG)"

property e:gpri-47xz t:meta.view.tableauthor v:id=f8sf-wn9w v:profileImageUrlMedium=/api/users/f8sf-wn9w/profile_images/THUMB v:profileImageUrlLarge=/api/users/f8sf-wn9w/profile_images/LARGE v:screenName="Young, Marvin (ATG)" v:profileImageUrlSmall=/api/users/f8sf-wn9w/profile_images/TINY v:roleName=designer v:displayName="Young, Marvin (ATG)"
```

## Top Records

```ls
| openeddate          | openedyear | status | estimatedsavings | actualsavings | businesscategory                   | naics                                                     | naicsname | business                            | businessstreetline1 | businessstreetline2 | businesscity | businessstate | businesszip | business_id | id     | 
| =================== | ========== | ====== | ================ | ============= | ================================== | ========================================================= | ========= | =================================== | =================== | =================== | ============ | ============= | =========== | =========== | ====== | 
| 2016-04-12T00:00:00 | 2016       | Open   |                  |               |                                    | 713940-Fitness & Recreational Industries                  |           | Highline Athletic Club              |                     |                     | Burien       | WA            | 98148-1220  | 257432      | 483906 | 
| 2016-04-08T00:00:00 | 2016       | New    |                  |               |                                    | 990000-Unclassified Establishments                        |           | Inquiry                             |                     |                     |              |               |             | 6033        | 483674 | 
| 2016-04-08T00:00:00 | 2016       | New    |                  |               |                                    | 993000-Phishing                                           |           | Unknown - Attorney General's Office |                     |                     |              | WA            |             | 261923      | 483723 | 
| 2016-04-08T00:00:00 | 2016       | New    |                  |               |                                    | 560000-Admin. & support services (office admin., faciliti |           | UST Development/US Telecom          |                     |                     | Ontario      | CA            | 91764       | 236270      | 483692 | 
| 2015-07-01T00:00:00 | 2015       | Closed | 0.00             | 0.00          | Health Care                        | 621200                                                    |           | A Street Dental                     | 902 A St SE Ste A   |                     | Auburn       | WA            | 98002       | 236514      | 468341 | 
| 2017-02-06T00:00:00 | 2017       | New    | 0.00             | 0.00          | Unclassified Establishments        | 990000-Unclassified Establishments                        |           | Unknown                             |                     |                     |              |               |             | 207054      | 499827 | 
| 2017-04-20T00:00:00 | 2017       | New    | 0.00             | 0.00          | Consumer Lending & Transfer Agents | 522291-Consumer Lending (includes Payday Lenders)         |           | Navient fka Sallie Mae              | 220 Lasley Ave      |                     | Wilkes-Barre | PA            | 18706       | 122656      | 503670 | 
| 2017-04-20T00:00:00 | 2017       | New    | 0.00             | 0.00          | Consumer Lending & Transfer Agents | 522291-Consumer Lending (includes Payday Lenders)         |           | Navient fka Sallie Mae              | 220 Lasley Ave      |                     | Wilkes-Barre | PA            | 18706       | 122656      | 503688 | 
| 2017-04-20T00:00:00 | 2017       | New    | 0.00             | 0.00          | Consumer Lending & Transfer Agents | 522291-Consumer Lending (includes Payday Lenders)         |           | Navient fka Sallie Mae              | 220 Lasley Ave      |                     | Wilkes-Barre | PA            | 18706       | 122656      | 503705 | 
| 2017-04-20T00:00:00 | 2017       | New    | 0.00             | 0.00          | Consumer Lending & Transfer Agents | 522291-Consumer Lending (includes Payday Lenders)         |           | Navient fka Sallie Mae              | 220 Lasley Ave      |                     | Wilkes-Barre | PA            | 18706       | 122656      | 503708 | 
```