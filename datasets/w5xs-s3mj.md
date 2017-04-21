# Individual Navigators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/individual-navigators-4f8ec) |
| Metadata | [Link](https://data.mo.gov/api/views/w5xs-s3mj) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/w5xs-s3mj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/w5xs-s3mj/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | w5xs-s3mj |
| Name | Individual Navigators |
| Attribution | Missouri Department of Insurance, Financial Institutions & Professional (DIFP) |
| Category | Insurance |
| Tags | health, insurance, navigators, navigator, licensed navigators, health insurance, navigator phone, navigators phone |
| Created | 2013-10-07T14:02:05Z |
| Publication Date | 2017-04-19T19:43:09Z |

## Description

Individual Navigators licensed in Missouri.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| No       | time           | :updated_at    | updated_at     | meta_data | meta_data   |
| Yes      | series tag     | last_name      | Last Name      | text      | text        |
| Yes      | series tag     | first_name     | First Name     | text      | text        |
| Yes      | numeric metric | business_phone | Business Phone | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:w5xs-s3mj d:2017-04-19T19:43:03.000Z t:first_name=DONNA t:last_name=ADAMS m:business_phone=3142628291

series e:w5xs-s3mj d:2017-04-19T19:43:03.000Z t:first_name="MAAME ABENA" t:last_name="AGYEMAN PREMPEH" m:business_phone=4178310150

series e:w5xs-s3mj d:2017-04-19T19:43:03.000Z t:first_name=MICHELE t:last_name=AHOLT m:business_phone=5734435823
```

## Meta Commands

```ls
metric m:business_phone p:long l:"Business Phone" t:dataTypeName=number

entity e:w5xs-s3mj l:"Individual Navigators" t:attribution="Missouri Department of Insurance, Financial Institutions & Professional (DIFP)" t:url=https://data.mo.gov/api/views/w5xs-s3mj

property e:w5xs-s3mj t:meta.view v:id=w5xs-s3mj v:category=Insurance v:averageRating=0 v:name="Individual Navigators" v:attribution="Missouri Department of Insurance, Financial Institutions & Professional (DIFP)"

property e:w5xs-s3mj t:meta.view.owner v:id=byu7-dn9b v:screenName=DIFP v:displayName=DIFP

property e:w5xs-s3mj t:meta.view.tableauthor v:id=byu7-dn9b v:screenName=DIFP v:roleName=editor v:displayName=DIFP
```

## Top Records

```ls
| :updated_at | last_name       | first_name  | business_phone | 
| =========== | =============== | =========== | ============== | 
| 1492630983  | ADAMS           | DONNA       | 3142628291     | 
| 1492630983  | AGYEMAN PREMPEH | MAAME ABENA | 4178310150     | 
| 1492630983  | AHMED           | SADIYA      |                | 
| 1492630983  | AHOLT           | MICHELE     | 5734435823     | 
| 1492630983  | ALLEE           | ASH         | 8167535144     | 
| 1492630983  | ALLEN           | JUDY        | 3143644485     | 
| 1492630983  | ALQAISI         | ALAA        | 3147739090     | 
| 1492630983  | ANDERSON        | PAULA       | 4174519450     | 
| 1492630983  | ANDERSON        | ERIKA       | 8168344634     | 
| 1492630983  | ARMENTA         | MARTHA      | 8162769476     | 
```