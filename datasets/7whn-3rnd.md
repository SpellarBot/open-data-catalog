# Illinois Grants Fake Data 2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/illinois-grants-fake-data-2-faad4) |
| Metadata | [Link](https://data.illinois.gov/api/views/7whn-3rnd) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/7whn-3rnd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/7whn-3rnd/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 7whn-3rnd |
| Name | Illinois Grants Fake Data 2 |
| Created | 2014-01-14T22:24:39Z |
| Publication Date | 2014-01-14T22:25:01Z |

## Columns

```ls
| Included | Schema Type    | Field Name   | Name         | Data Type     | Render Type   |
| ======== | ============== | ============ | ============ | ============= | ============= |
| Yes      | series tag     | agency       | Agency       | text          | text          |
| Yes      | series tag     | name         | Name         | text          | text          |
| Yes      | series tag     | description  | Description  | text          | text          |
| Yes      | numeric metric | grant_amount | Grant Amount | money         | money         |
| Yes      | time           | date         | Date         | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7whn-3rnd d:2012-05-30T00:00:00.000Z t:description="Vestibulum vel nunc et orci viverra faucibus. Nam sodales nisi sit amet metus eleifend imperdiet pulvinar nec mi. Phasellus nec lorem ultrices diam consequat aliquam et id metus." t:name="Grant 21" t:agency="Agency Five" m:grant_amount=5000

series e:7whn-3rnd d:2012-01-01T00:00:00.000Z t:description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent non augue mattis, tincidunt ipsum id, ullamcorper leo. Donec ac magna id leo dapibus ultricies eu ac leo. Sed et augue diam. Nulla nec mi tellus." t:name="Grant 22" t:agency="Agency Five" m:grant_amount=25000

series e:7whn-3rnd d:2013-02-01T00:00:00.000Z t:description="Curabitur enim eros, lacinia quis iaculis ac, pulvinar ut quam. Duis rhoncus elementum velit, a porta libero laoreet pulvinar. Suspendisse consectetur, metus tempus suscipit egestas, tellus enim aliquam est, ac pulvinar mi justo in erat." t:name="Grant 23" t:agency="Agency Five" m:grant_amount=7000
```

## Meta Commands

```ls
metric m:grant_amount p:double l:"Grant Amount" t:dataTypeName=money

entity e:7whn-3rnd l:"Illinois Grants Fake Data 2" t:url=https://data.illinois.gov/api/views/7whn-3rnd

property e:7whn-3rnd t:meta.view v:id=7whn-3rnd v:averageRating=0 v:name="Illinois Grants Fake Data 2"

property e:7whn-3rnd t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:7whn-3rnd t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| agency      | name     | description                                                                                                                                                                                                                                   | grant_amount | date                | 
| =========== | ======== | ============================================================================================================================================================================================================================================= | ============ | =================== | 
| Agency Five | Grant 21 | Vestibulum vel nunc et orci viverra faucibus. Nam sodales nisi sit amet metus eleifend imperdiet pulvinar nec mi. Phasellus nec lorem ultrices diam consequat aliquam et id metus.                                                            | 5000.00      | 2012-05-30T00:00:00 | 
| Agency Five | Grant 22 | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent non augue mattis, tincidunt ipsum id, ullamcorper leo. Donec ac magna id leo dapibus ultricies eu ac leo. Sed et augue diam. Nulla nec mi tellus.                           | 25000.00     | 2012-01-01T00:00:00 | 
| Agency Five | Grant 23 | Curabitur enim eros, lacinia quis iaculis ac, pulvinar ut quam. Duis rhoncus elementum velit, a porta libero laoreet pulvinar. Suspendisse consectetur, metus tempus suscipit egestas, tellus enim aliquam est, ac pulvinar mi justo in erat. | 7000.00      | 2013-02-01T00:00:00 | 
| Agency Five | Grant 24 | Nullam in luctus arcu. Curabitur nec nulla rhoncus, tempus justo vel, ornare risus. Donec ac sollicitudin tellus. Morbi eget leo quis urna aliquet dignissim. Ut pulvinar convallis lectus molestie lobortis. Fusce nec dapibus libero.       | 12000.00     | 2011-12-01T00:00:00 | 
| Agency Five | Grant 25 | In adipiscing nec ante sit amet molestie. Quisque eleifend ligula sed arcu aliquam faucibus. Nam quis orci arcu. Praesent vel scelerisque quam. Nam cursus accumsan arcu, sed laoreet sapien sollicitudin sit amet                            | 40000.00     | 2013-10-01T00:00:00 | 
| Agency Four | Grant 16 | Curabitur enim eros, lacinia quis iaculis ac, pulvinar ut quam. Duis rhoncus elementum velit, a porta libero laoreet pulvinar. Suspendisse consectetur, metus tempus suscipit egestas, tellus enim aliquam est, ac pulvinar mi justo in erat. | 12000.00     | 2013-02-01T00:00:00 | 
| Agency Four | Grant 17 | Nullam in luctus arcu. Curabitur nec nulla rhoncus, tempus justo vel, ornare risus. Donec ac sollicitudin tellus. Morbi eget leo quis urna aliquet dignissim. Ut pulvinar convallis lectus molestie lobortis. Fusce nec dapibus libero.       | 5000.00      | 2011-12-01T00:00:00 | 
| Agency Four | Grant 18 | In adipiscing nec ante sit amet molestie. Quisque eleifend ligula sed arcu aliquam faucibus. Nam quis orci arcu. Praesent vel scelerisque quam. Nam cursus accumsan arcu, sed laoreet sapien sollicitudin sit amet                            | 25000.00     | 2013-10-01T00:00:00 | 
| Agency Four | Grant 19 | Vestibulum vel nunc et orci viverra faucibus. Nam sodales nisi sit amet metus eleifend imperdiet pulvinar nec mi. Phasellus nec lorem ultrices diam consequat aliquam et id metus.                                                            | 40000.00     | 2012-05-30T00:00:00 | 
| Agency Four | Grant 20 | Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent non augue mattis, tincidunt ipsum id, ullamcorper leo. Donec ac magna id leo dapibus ultricies eu ac leo. Sed et augue diam. Nulla nec mi tellus.                           | 7000.00      | 2012-01-01T00:00:00 | 
```