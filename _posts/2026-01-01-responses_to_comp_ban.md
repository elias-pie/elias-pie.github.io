---
title: Thoughts on the new personal computer ban
date: 2026-01-01 14:38:00 +/-TTTT
categories: [user_responses]
tags: [AI Used, Statistical Data, Survey]     # TAG names should always be lowercase
author: <elias>                     # for single entry
description: Responses to the survey me and Beckett did regarding the computer ban
toc: true
---

## Background
So me and [Beckett](https://www.instagram.com//beckettjensen21) were curious about people's thoughts on the new personal computer ban at TVHS. After consulting eachother for a bit, 
we created a (google form)[https://forms.gle/q3rZJENtHu4xR9w3A] asking aboutpeople's thoughts. As of now (1/1/26, this form has 46 responses. 

## Actual Responses to the questions.

### What year of school are you in?
![Desktop View](https://raw.githubusercontent.com/elias-pie/elias-pie.github.io/refs/heads/main/_post_data/images/responses_to_ban/q1.png)

> This was added after 3 hours of the form's initial creation, so there is less responses to this question.
{: .prompt-info }

### Do you use a Personal Computer at school?
![Desktop View](https://raw.githubusercontent.com/elias-pie/elias-pie.github.io/refs/heads/main/_post_data/images/responses_to_ban/q2.png)

### Will you be effected next year by this new rule?
![Desktop View](https://raw.githubusercontent.com/elias-pie/elias-pie.github.io/refs/heads/main/_post_data/images/responses_to_ban/q3.png)

### If so, how?
> This section was summarized using an ollama model[^ai_data].
{: .prompt-tip }

> Response from ollama:

Students who use their personal devices for educational purposes at school are expressing concerns about the new policy banning personal computers from school premises, citing issues with website accessibility, slow and inefficient school-issued Chromebooks, restrictions on personal freedoms and autonomy, worries about losing productivity and academic performance, frustration over not being able to access necessary resources, difficulty adapting to the school's tracking system, potential waste of personal property investments, and feelings of mistrust towards the school's handling of student data.

### How much money did your computer cost?
> This section was graphed using an ollama model[^ai_data].
{: .prompt-tip }

| Range                                  | Count   |
| -------------------------------------- | ------- |
| $100-$200                              | 2       |
| $200-$300                              | 4       |
| $300-$400                              | 6       |
| $400-$500                              | 5       |
| $500-$600                              | 4       |
| $600-$700                              | 3       |
| $700-$800                              | 2       |
| $800-$900                              | 2       |
| $900-$1000                             | 1       |
| $1000-$1500                            | 7       |
| $1500-$2000                            | 5       |
| Unknown/Other                          | 11      |

## Similarities Between Computers

### What is your computer type
![Desktop View](https://raw.githubusercontent.com/elias-pie/elias-pie.github.io/refs/heads/main/_post_data/images/responses_to_ban/q4.png)

### Are you able to get a return on your computer due to this rule?
![Desktop View](https://raw.githubusercontent.com/elias-pie/elias-pie.github.io/refs/heads/main/_post_data/images/responses_to_ban/q5.png)

### How long have you been using this computer?
> This section was graphed using an ollama model[^ai_data].
{: .prompt-tip }

| Range                   | Count |
| ----------------------- | ----- |
| Less than 1 year        | 22    |
| 1-2 years               | 8     |
| 2-3 years               | 7     |
| 3-4 years               | 5     |
| 4-6 years               | 5     |
| More than 6 years       | 3     |

### Have you gotten a replacement computer for a previously broken computer that was used for school?
![Desktop View](https://raw.githubusercontent.com/elias-pie/elias-pie.github.io/refs/heads/main/_post_data/images/responses_to_ban/q6.png)

### If so, how many?
#### Total Count
24 Computers were replaced for various reasons

#### Reasons for replacement
> This section was ranked using an ollama model[^ai_data].
{: .prompt-tip }

| #   | Reason                                                       |
| --- | ------------------------------------------------------------ |
| 1   | Accidental damage (e.g. dropped, stepped on) - 7 instances   |
| 2   | Mishandling or misuse (e.g. kid broke it) - 5 instances      |
| 3   | Battery and charging issues - 4 instances                    |
| 4   | Old or damaged device from previous use - 3 instances        |

### How much did each replacement cost you, if you know?

| Range                                  | Count   |
| -------------------------------------- | ------- |
| Unknown/Other                          | 7       |
| No Response                            | 3       |
| $0                                     | 1       |
| $75-$100                               | 1       |
| $100-$200                              | 2       |
| $150-$300                              | 1       |
| $200-$400                              | 1       |
| $400-$500                              | 3       |
| $1000-$1500                            | 2       |

## Final Thoughts

### Anything else you would like to add?
> This section was summarized using an ollama model[^ai_data].
{: .prompt-tip }

> Response from Ollama:

The implementation of a policy mandating the use of school-issued Chromebooks instead of personal devices in educational settings is met with significant opposition and disagreement from students, who express concerns about the potential negative consequences on their academic experiences, well-being, and personal freedoms. Some students argue that this policy is an overreaction to perceived problems with students using AI or playing games during class, and that it will disproportionately affect those who rely on their personal devices for schoolwork and productivity. Others feel that the policy is an abuse of power, neglecting more pressing issues such as student well-being, safety, and academic support, and that it prioritizes administrative convenience over student needs. Many students also express frustration with the lack of explanation or rationale provided by administrators for this policy change, which they believe is an unnecessary restriction on their rights to use personal property and pursue educational activities outside of school. Some students share concerns about the potential impact on their mental health, academic performance, and future college applications, as well as the financial burden placed on families who have invested in personal devices for their children's education. Overall, the policy has sparked a heated debate among students, with many calling for changes or reversals to this new rule.

### [^ai_data]: Ai Data
This data was assisted to be presentable by AI, specifically, ollama3.1:8b, which is self hosted. Sure, an 8b model does have low resources and will make mistakes. These mistakes were checked before adding to the website. The PC used has an i7-13th gen intel core processor with an 4060 Nvidia GPU. This AI had zero access to the internet and only summarized what was provided to the model

### Response Prompt for your reference
```
Summarize multiple provided statements into a single, cohesive statement that integrates all key points.
Remain neutral and unbiased, accurately representing differing perspectives and topics in proportion to their presence.
Do not omit major ideas, add new information, or include personal opinions.
The resulting summary may be long but must be written as one unified statement. Output only the summarized statement.
```
