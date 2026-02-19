# Japanese Household Chore Preference Dataset

## Overview

The dataset consists of responses from 2,000 individuals categorized by parental status, gender, and age range in Japan. 

Participants answered questions about 33 different household chores, including their preferences, time required to complete each task, and frequency.
`data.csv` is the main data file.

## Column Descriptions in `data.csv`

| Variable | Description | Question (English Translation) | Original Question (Japanese) |
|----------|-------------|----------|----------|
| **group** | Demographic group | Group? | グループ |
| **sc1** | Gender (1=Male, 2=Female) | Please let us know your gender. | あなたの性別をお知らせください。 |
| **sc2_1** | Age | What is your age? | あなたの年齢をお知らせください。／歳 |
| **sc4** | Marital status (1=Single, 2=Married (including separated or widowed)) | Are you married? | あなたは結婚していらっしゃいますか。 |
| **sc5** | Parental status (1=Living with children, parenting is part of housework, 2=Living with children, but they are old enough that parenting is not considered part of housework, 3=Have children but not living together, 4=No children) | Do you have children? Is child-rearing included as part of your household chores? | あなたにはお子さまがいらっしゃいますか。家事の一部に子育ての仕事は含まれますか？ |
| **q1_1** | Number of people participating in household chores | Please indicate the number of people, including yourself, who participate in household chores among those you live with (family, roommates, partner). / people | 同居人（家族、ルームメイト、パートナー）の中で、ご自身も含めた家事に参加する人数をお知らせください。／人 |
| **q2_1** | Respondent's share of household chores (%) | Please indicate what percentage of the household chores you personally handle among those you live with (family, roommates, partner). / % | 同居人（家族、ルームメイト、パートナー）の中で、ご自身の家事の負担割合をお知らせください。／％ |
| **q4_1** | Time available for household chores per day (hours) | How much time can you spend on household chores in a day? / hours | 一日のうち家事にどれくらいの時間を費やすことが可能ですか？／時間 |
| **q5_x** | Preference levels for chore categories (1=Like, 2=Somewhat like, 3=Neutral, 4=Somewhat dislike, 5=Dislike) | How would you rate your preference for different categories of household chores? {Cleaning/Cooking/Laundry/Taking care of children or pets}| 以下の項目についてそれぞれそれくらい好きか教えてください。{／掃除／料理／洗濯／子供やペットの世話}|
| **q6_x** | Time required for 33 household tasks | Please tell us how long it takes you to do the household chore. If you do not do the task yourself, please give your best estimate. / {Chore} | 家事にかかる時間を教えてください。ご対応していない場合は、ご想像でご回答ください。／{家事} |
| **q7_x** | Preferences for 33 household tasks (1=Like, 2=Neutral, 3=Dislike) | Please tell us about your preference in the household chore. / {Chore} | 家事の好みを教えてください。／{家事} |
| **q8_x** | Frequency of 33 household tasks | Please tell us how frequently you perform household chores. / {Chore} | 家事の頻度を教えてください。／{家事} |


### Demographic Distribution
Each demographic category (combination of parental status, gender, and age range) contains 100 respondents, for a total of 2,000 participants.
| Parental Status | Gender | Age | Count |
|---|---|---|---|
| Living with Children | Male | 20-29 | 100 |
| | | 30-39 | 100 |
| | | 40-49 | 100 |
| | | 50-59 | 100 |
| | | 60-69 | 100 |
| | Female | 20-29 | 100 |
| | | 30-39 | 100 |
| | | 40-49 | 100 |
| | | 50-59 | 100 |
| | | 60-69 | 100 |
| No Co-resident Children or No Children | Male | 20-29 | 100 |
| | | 30-39 | 100 |
| | | 40-49 | 100 |
| | | 50-59 | 100 |
| | | 60-69 | 100 |
| | Female | 20-29 | 100 |
| | | 30-39 | 100 |
| | | 40-49 | 100 |
| | | 50-59 | 100 |
| | | 60-69 | 100 |
| | | **Total** | **2,000** |



### Group Categories
| Group ID | Description |
|----------|-------------|
| 1 | Living with Children / Male / 20-29 years |
| 2 | Living with Children / Male / 30-39 years |
| 3 | Living with Children / Male / 40-49 years |
| 4 | Living with Children / Male / 50-59 years |
| 5 | Living with Children / Male / 60-69 years |
| 6 | Living with Children / Female / 20-29 years |
| 7 | Living with Children / Female / 30-39 years |
| 8 | Living with Children / Female / 40-49 years |
| 9 | Living with Children / Female / 50-59 years |
| 10 | Living with Children / Female / 60-69 years |
| 11 | No Co-resident Children or No Children / Male / 20-29 years |
| 12 | No Co-resident Children or No Children / Male / 30-39 years |
| 13 | No Co-resident Children or No Children / Male / 40-49 years |
| 14 | No Co-resident Children or No Children / Male / 50-59 years |
| 15 | No Co-resident Children or No Children / Male / 60-69 years |
| 16 | No Co-resident Children or No Children / Female / 20-29 years |
| 17 | No Co-resident Children or No Children / Female / 30-39 years |
| 18 | No Co-resident Children or No Children / Female / 40-49 years |
| 19 | No Co-resident Children or No Children / Female / 50-59 years |
| 20 | No Co-resident Children or No Children / Female / 60-69 years |



## List of Household Chores

| ID | Household Chore | ID | Household Chore | ID | Household Chore |
|----|-----------------|----|-----------------|----|-----------------|
| 1 | Plan meals | 12 | Cook lunch | 23 | Flatten and dispose of cardboard boxes |
| 2 | Buy groceries | 13 | Refill or replace detergent and fabric softener | 24 | Clean the bathtub |
| 3 | Restock condiments and oil | 14 | Clean the washing machine drum | 25 | Remove clogged hairs in the bathroom drain |
| 4 | Wipe the table | 15 | Clean the washing machine filter | 26 | Clean the toilet |
| 5 | Clean up after meals | 16 | Wash and change bedding | 27 | Set up new garbage bags |
| 6 | Clean the sink drain | 17 | Hang out the laundry | 28 | Wash dishes |
| 7 | Refill dish-washing detergent | 18 | Bring in the laundry | 29 | Dry dishes |
| 8 | Wash the cutting board | 19 | Fold the laundry | 30 | Put away dishes |
| 9 | Wash dishcloths | 20 | Iron clothes | 31 | Take care of pets |
| 10 | Organize the refrigerator | 21 | Collect and sort garbage | 32 | Collect mail |
| 11 | Cook dinner | 22 | Take out the trash | 33 | Water plants |


### Time Required for Each Task
| ID | Duration | ID | Duration |
|----|----------|----|----------|
| 1 | 1 minute or less | 8 | 60 minutes or less |
| 2 | 5 minutes or less | 9 | 70 minutes or less |
| 3 | 10 minutes or less | 10 | 80 minutes or less |
| 4 | 20 minutes or less | 11 | 90 minutes or less |
| 5 | 30 minutes or less | 12 | 2 hours or less |
| 6 | 40 minutes or less | 13 | 3 hours or less |
| 7 | 50 minutes or less | 14 | More than 3 hours |


### Task Frequency
| ID | Frequency | ID | Frequency |
|----|------------|----|------------|
| 1 | Once a month or less | 9 | 8 times a week |
| 2 | Once a week or less | 10 | 9 times a week |
| 3 | Twice a week | 11 | 10 times a week |
| 4 | 3 times a week | 12 | 11 times a week |
| 5 | 4 times a week | 13 | 12 times a week |
| 6 | 5 times a week | 14 | 13 times a week or more |
| 7 | 6 times a week | 15 | Never do |
| 8 | 7 times a week | | |

## References
This dataset is collected from Kajibuntan.

```
Igarashi, A. and Yokoyama, T. (2023). Kajibuntan: A house chore division app. In Proceedings of the 37th AAAI Conference on Artificial Intelligence, pages 16449–16451.
```

