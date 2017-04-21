# Naloxone Prescribing Pharmacists - TO BE DISCONITNUED - Please see description

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/naloxone-prescribing-pharmacists) |
| Metadata | [Link](https://data.ct.gov/api/views/qjtc-pbhi) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/qjtc-pbhi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/qjtc-pbhi/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | qjtc-pbhi |
| Name | Naloxone Prescribing Pharmacists - TO BE DISCONITNUED - Please see description |
| Attribution | Department of Mental Health and Addiction Services |
| Category | Health and Human Services |
| Tags | naloxone, narcan, pharmacy, prescription |
| Created | 2015-12-30T18:41:39Z |
| Publication Date | 2016-05-23T14:55:23Z |

## Description

NEW DATA AVAILABLE HERE: https://data.ct.gov/d/2vby-9bet?category=Public-Safety&view_name=Pharmacies-offering-Narcan-Evzio-and-other-brands-Opens in new window. A listing of Pharmacies and Pharmacists known to prescribe Naloxone. This list will be updated periodically as more pharmacies or pharmacists are identified. This is not a comprehensive list as pharmacists are allowed to opt-in to this list, thus there may be others that have chosen not to be identified.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | pharmacy        | Pharmacy        | text      | text        |
| No       |             | address         | Address         | text      | text        |
| Yes      | series tag  | phone           | Phone           | text      | text        |
| Yes      | series tag  | email_fax_other | Email/Fax/Other | text      | text        |
| Yes      | series tag  | pharmacist      | Pharmacist      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:qjtc-pbhi d:2016-02-26T13:04:59.000Z t:pharmacy=Suburban t:phone=860-236-3564 t:pharmacist="Alan Rosenthal" m:row_number.qjtc-pbhi=1

series e:qjtc-pbhi d:2016-02-26T13:05:21.000Z t:pharmacy="Bunker Hill" t:phone=203-574-7825 t:pharmacist="Kevin Czarzasty; Christopher O'Brien" m:row_number.qjtc-pbhi=2

series e:qjtc-pbhi d:2016-02-26T13:05:21.000Z t:pharmacy="Main Street" t:phone=203-212-3800 t:pharmacist="Jean Jacob" m:row_number.qjtc-pbhi=3
```

## Meta Commands

```ls
metric m:row_number.qjtc-pbhi p:long l:"Row Number"

entity e:qjtc-pbhi l:"Naloxone Prescribing Pharmacists - TO BE DISCONITNUED - Please see description" t:attribution="Department of Mental Health and Addiction Services" t:url=https://data.ct.gov/api/views/qjtc-pbhi

property e:qjtc-pbhi t:meta.view v:id=qjtc-pbhi v:category="Health and Human Services" v:attributionLink=http://www.ct.gov/dmhas v:averageRating=0 v:name="Naloxone Prescribing Pharmacists - TO BE DISCONITNUED - Please see description" v:attribution="Department of Mental Health and Addiction Services"

property e:qjtc-pbhi t:meta.view.license v:name="Public Domain"

property e:qjtc-pbhi t:meta.view.owner v:id=cyms-6imd v:screenName="susan wolfe" v:displayName="susan wolfe"

property e:qjtc-pbhi t:meta.view.tableauthor v:id=cyms-6imd v:screenName="susan wolfe" v:roleName=editor v:displayName="susan wolfe"
```

## Top Records

```ls
| :updated_at | pharmacy    | address                             | phone                                  | email_fax_other                           | pharmacist                                       | 
| =========== | =========== | =================================== | ====================================== | ========================================= | ================================================ | 
| 1456491899  | Suburban    | 344 North Main St West Hartford, CT | 860-236-3564                           |                                           | Alan Rosenthal                                   | 
| 1456491921  | Bunker Hill | 256 Bunker Hill Ave Waterbury, CT   | 203-574-7825                           |                                           | Kevin Czarzasty; Christopher O'Brien             | 
| 1456491921  | Main Street | 2117 Boston Ave Bridgeport, CT      | 203-212-3800                           |                                           | Jean Jacob                                       | 
| 1456491921  | Main Street | 151 Main St, Danbury, CT            | 203-297-6130                           | (f) 203-297-6132                          | Sangwoo Lee                                      | 
| 1456491921  | Circle Care | 618 West Ave Norwalk, CT            | 203-939-1765 or toll free 855-205-7535 | http://circlecarecenter.org/pharmacy.html | Fareed Choudhry; Melissa Hyland; Ranjeeta Mhatre | 
| 1456491921  | Higganum    | 23 Killingworth Rd Higganum, CT     | 860-345-3607                           |                                           | Greg McKenna                                     | 
| 1456491921  | Hancock     | 1 Long Wharf Dr New Haven, CT       | 203-787-9908                           |                                           | Jacqueline Murphy                                | 
| 1456491921  | People's    | 375 Washington Ave, North Haven, CT | 203-287-7375                           |                                           | Suruchi Patel                                    | 
| 1456491921  | Oxford      | 100 Oxford Rd, Oxford, CT           | 203-888-4567                           |                                           | Frank Diaferio                                   | 
| 1456491921  | Beacon      | 609 North Main St Southington, CT   | 860-628-3972                           | www.beaconcompounding.com                 | Annik Chamberlin; Lukasz Jamrozek                | 
```