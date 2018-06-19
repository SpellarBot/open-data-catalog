# Percent of Adult Current Smokers by Sex and Race/Ethnicity, 1995-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-of-adult-current-smokers-by-sex-and-race-ethnicity-1995-2010-4e337) |
| Metadata | [Link](https://data.maryland.gov/api/views/xyrh-5e77) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/xyrh-5e77/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/xyrh-5e77/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | xyrh-5e77 |
| Name | Percent of Adult Current Smokers by Sex and Race/Ethnicity, 1995-2010 |
| Attribution | Behavioral Risk Factor Surveillance System (BRFSS) |
| Category | Health and Human Services |
| Tags | tobacco, smoking, cigarettes, risk behavior, brfss |
| Created | 2012-11-27T23:14:06Z |
| Publication Date | 2012-11-27T23:20:09Z |

## Description

Adults are defined as 18 years of age and older. The CDC defines a "Current Smoker" as an adult who has smoked at least 100 cigarettes (5 packs) in their lifetime and currently smokes either "Every Day" or "Some Days." BRFSS data methodology changed in 2011; therefore, 2011 and after is not comparable to 2010 data and before.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                               | Data Type | Render Type |
| ======== | ============== | ================================= | ================================== | ========= | =========== |
| Yes      | series tag     | calendar_years                    | Calendar Years                     | text      | text        |
| Yes      | numeric metric | male_smokers                      | Male Smokers                       | number    | number      |
| Yes      | numeric metric | female_smokers                    | Female Smokers                     | number    | number      |
| Yes      | numeric metric | white_non_hispanic_smokers        | White, Non-Hispanic Smokers        | number    | number      |
| Yes      | numeric metric | black_non_hispanic_smokers        | Black, Non-Hispanic Smokers        | number    | number      |
| Yes      | numeric metric | hispanic_smokers                  | Hispanic Smokers                   | number    | number      |
| Yes      | numeric metric | male_white_non_hispanic_smokers   | Male, White Non-Hispanic Smokers   | number    | number      |
| Yes      | numeric metric | male_black_non_hispanic_smokers   | Male, Black Non-Hispanic Smokers   | number    | number      |
| Yes      | numeric metric | male_hispanic_smokers             | Male, Hispanic Smokers             | number    | number      |
| Yes      | numeric metric | female_white_non_hispanic_smokers | Female, White Non-Hispanic Smokers | number    | number      |
| Yes      | numeric metric | female_black_non_hispanic_smokers | Female, Black Non-Hispanic Smokers | number    | number      |
| Yes      | numeric metric | female_hispanic_smokers           | Female, Hispanic Smokers           | number    | number      |
```

## Time Field

```ls
Value = 1995
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xyrh-5e77 d:1995-01-01T00:00:00.000Z t:calendar_years=1995-97 m:male_hispanic_smokers=20.4 m:white_non_hispanic_smokers=21.2 m:female_white_non_hispanic_smokers=20.6 m:female_black_non_hispanic_smokers=18.9 m:male_white_non_hispanic_smokers=21.8 m:female_hispanic_smokers=13.1 m:hispanic_smokers=16.6 m:female_smokers=19.6 m:black_non_hispanic_smokers=21.7 m:male_smokers=22.2 m:male_black_non_hispanic_smokers=25.2

series e:xyrh-5e77 d:1995-01-01T00:00:00.000Z t:calendar_years=1996-98 m:male_hispanic_smokers=23.3 m:white_non_hispanic_smokers=21.2 m:female_white_non_hispanic_smokers=20.2 m:female_black_non_hispanic_smokers=19.8 m:male_white_non_hispanic_smokers=22.1 m:female_hispanic_smokers=18 m:hispanic_smokers=20.4 m:female_smokers=19.8 m:black_non_hispanic_smokers=22.2 m:male_smokers=22.8 m:male_black_non_hispanic_smokers=25.1

series e:xyrh-5e77 d:1995-01-01T00:00:00.000Z t:calendar_years=1997-99 m:male_hispanic_smokers=25.9 m:white_non_hispanic_smokers=21 m:female_white_non_hispanic_smokers=19.8 m:female_black_non_hispanic_smokers=19.5 m:male_white_non_hispanic_smokers=22.2 m:female_hispanic_smokers=19.9 m:hispanic_smokers=22.8 m:female_smokers=19.5 m:black_non_hispanic_smokers=21.8 m:male_smokers=22.7 m:male_black_non_hispanic_smokers=24.6
```

## Meta Commands

```ls
metric m:male_smokers p:float l:"Male Smokers" t:dataTypeName=number

metric m:female_smokers p:float l:"Female Smokers" t:dataTypeName=number

metric m:white_non_hispanic_smokers p:float l:"White, Non-Hispanic Smokers" t:dataTypeName=number

metric m:black_non_hispanic_smokers p:float l:"Black, Non-Hispanic Smokers" t:dataTypeName=number

metric m:hispanic_smokers p:float l:"Hispanic Smokers" t:dataTypeName=number

metric m:male_white_non_hispanic_smokers p:float l:"Male, White Non-Hispanic Smokers" t:dataTypeName=number

metric m:male_black_non_hispanic_smokers p:float l:"Male, Black Non-Hispanic Smokers" t:dataTypeName=number

metric m:male_hispanic_smokers p:float l:"Male, Hispanic Smokers" t:dataTypeName=number

metric m:female_white_non_hispanic_smokers p:float l:"Female, White Non-Hispanic Smokers" t:dataTypeName=number

metric m:female_black_non_hispanic_smokers p:float l:"Female, Black Non-Hispanic Smokers" t:dataTypeName=number

metric m:female_hispanic_smokers p:float l:"Female, Hispanic Smokers" t:dataTypeName=number

entity e:xyrh-5e77 l:"Percent of Adult Current Smokers by Sex and Race/Ethnicity, 1995-2010" t:attribution="Behavioral Risk Factor Surveillance System (BRFSS)" t:url=https://data.maryland.gov/api/views/xyrh-5e77

property e:xyrh-5e77 t:meta.view v:id=xyrh-5e77 v:category="Health and Human Services" v:attributionLink=http://marylandbrfss.org v:averageRating=0 v:name="Percent of Adult Current Smokers by Sex and Race/Ethnicity, 1995-2010" v:attribution="Behavioral Risk Factor Surveillance System (BRFSS)"

property e:xyrh-5e77 t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:xyrh-5e77 t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| calendar_years | male_smokers | female_smokers | white_non_hispanic_smokers | black_non_hispanic_smokers | hispanic_smokers | male_white_non_hispanic_smokers | male_black_non_hispanic_smokers | male_hispanic_smokers | female_white_non_hispanic_smokers | female_black_non_hispanic_smokers | female_hispanic_smokers | 
| ============== | ============ | ============== | ========================== | ========================== | ================ | =============================== | =============================== | ===================== | ================================= | ================================= | ======================= | 
| 1995-97        | 22.2         | 19.6           | 21.2                       | 21.7                       | 16.6             | 21.8                            | 25.2                            | 20.4                  | 20.6                              | 18.9                              | 13.1                    | 
| 1996-98        | 22.8         | 19.8           | 21.2                       | 22.2                       | 20.4             | 22.1                            | 25.1                            | 23.3                  | 20.2                              | 19.8                              | 18.0                    | 
| 1997-99        | 22.7         | 19.5           | 21.0                       | 21.8                       | 22.8             | 22.2                            | 24.6                            | 25.9                  | 19.8                              | 19.5                              | 19.9                    | 
| 1998-00        | 22.8         | 19.5           | 20.9                       | 22.2                       | 21.2             | 22.1                            | 25.5                            | 24.5                  | 19.8                              | 19.6                              | 18.5                    | 
| 1999-01        | 22.9         | 18.5           | 20.7                       | 22.4                       | 19.3             | 21.9                            | 27.4                            | 23.1                  | 19.5                              | 18.4                              | 15.9                    | 
| 2000-02        | 24.1         | 18.6           | 21.0                       | 23.2                       | 19.0             | 22.3                            | 30.2                            | 23.1                  | 19.8                              | 17.8                              | 14.8                    | 
| 2001-03        | 24.3         | 18.1           | 20.9                       | 22.8                       | 18.8             | 22.4                            | 30.4                            | 24.4                  | 19.5                              | 17.0                              | 13.0                    | 
| 2002-04        | 23.7         | 17.7           | 20.6                       | 21.4                       | 17.2             | 22.0                            | 28.0                            | 24.1                  | 19.3                              | 16.1                              | 10.4                    | 
| 2003-05        | 21.7         | 17.6           | 19.2                       | 21.4                       | 17.8             | 20.1                            | 26.5                            | 21.8                  | 18.5                              | 17.1                              | 14.2                    | 
| 2004-06        | 20.4         | 17.2           | 18.4                       | 21.1                       | 15.6             | 18.8                            | 25.9                            | 16.1                  | 17.9                              | 17.2                              | 15.1                    | 
```