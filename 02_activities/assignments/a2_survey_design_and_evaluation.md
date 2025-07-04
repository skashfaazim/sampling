# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
The purpose of this survey is to identify the key factors driving high employee turnover within entry- and lower-level positions at a large tech company. The results will inform Human Resources about workplace issues that negatively impact employee satisfaction, with the aim of guiding targeted interventions and improving retention.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
- **Target Population:** Current and former employees (within the last 12 months) who held entry- or lower-level positions across departments in the company.
- **Sampling Frame:** An internal HR database that contains contact information and employment details of all current and recently exited employees.
- **Sampling Units:** Individual employees (both current and former).
- **Observational Units:** Responses from individual employees about their experiences and perceptions regarding the workplace.
- **Sampling Strategy:** Stratified random sampling, ensuring proportional representation across departments and employment status (current vs. former employees), to capture diverse perspectives and reduce sampling bias.
```

Your 5-10 question survey:
```
1. How long did you work (or have you been working) at the company?
   - Less than 6 months
   - 6–12 months
   - 1–2 years
   - More than 2 years

2. What department did/do you work in?
   - Engineering/Development
   - Sales/Marketing
   - Customer Support
   - HR/Admin
   - Other: _________

3. What were the main reasons for your departure (or considerations to leave)? (Select all that apply)
   - Lack of growth opportunities
   - Inadequate compensation or benefits
   - Poor management
   - High workload/stress
   - Lack of recognition or support
   - Better opportunity elsewhere
   - Other: ____________

4. How satisfied were/are you with the following aspects of your role?  
   *(Rate each from 1 = Very Dissatisfied to 5 = Very Satisfied)*  
   - Compensation and benefits  
   - Opportunities for career advancement  
   - Managerial support  
   - Work-life balance  
   - Workplace culture  

5. Have you communicated your concerns to a supervisor or HR before leaving (or considering leaving)?
   - Yes
   - No
   - Not applicable

6. What improvements would most increase your job satisfaction? (Select up to 3)
   - Better pay
   - Career development programs
   - More supportive leadership
   - Better workload management
   - Flexible work hours
   - Team-building and inclusive culture

7. Would you recommend this company to a friend looking for similar work?
   - Yes
   - No
   - Maybe

8. Are there any other comments or suggestions you would like to share?
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
## 1. Sample type
Probability sample with stratified design. Simple random sampling without replacement was used within each stratum. A *rejective sampling* method was applied to reduce over-sampling of non-volunteers.

## 2. Sample size
- Final sample size (after removing rejected respondents): **16,149**
- Initial target sample size: **20,000**
- Usable responses (including rejected): **19,857**

## 3. Target population
All persons aged 15 years or older living in the 10 Canadian provinces, excluding residents of the territories and full-time residents of institutions.

## 4. Sampling frame
The frame was constructed from:
- Lists of landline and mobile telephone numbers available to Statistics Canada
- The Address Register (AR) of all dwellings in the 10 provinces  
86% of telephone numbers were linked to AR.

## 5. Survey mode(s)
- Self-completed electronic questionnaire (rEQ)  
- Computer-Assisted Telephone Interviewing (iEQ)

## 6. Timeline
Data were collected from **September 4 to December 28, 2018**.

## 7. Response rate
The overall response rate was **41.9%**.

## 8. Weights
A person-level weight (**WGHT_PER**) is included in the PUMF to make estimates representative.  
- Weights were adjusted for:
  - Probability of selection
  - Non-response
  - Rejective sampling
  - Population benchmarks by geography, age, sex, and income using raking methods  
- Bootstrap weights are also available for variance estimation.

## 9. Data processing
- Responses entered electronically by respondents (rEQ) or interviewers (iEQ)  
- Coding of open responses into standard classification systems (e.g., NAICS, ICNPO)  
- Derivation of composite and recoded variables  
- Some donor data were perturbed for confidentiality

## 10. Cleaning, imputation, etc.
- **Deterministic edits** and **flow edits** were applied  
- **Hot-deck and donor imputation** used to fill item non-response or errors  
- Out-of-scope cases and duplicate records were removed  
- Valid skips (code 6) and non-response (code 9) were used consistently

## 11. Sources of error
- **Sampling errors** due to complex design and stratification  
- **Non-sampling errors** including:
  - Interviewer/respondent misunderstandings  
  - Data entry and coding errors  
  - Item and unit non-response  
  - Mode effects (online vs. telephone)

## 12. Limitations, known biases, etc.
- **Under-coverage** of households without telephones  
- **Lower response rate** among younger males and cell-phone-only households  
- Comparisons with past GVP/CSGVP iterations may be **inappropriate** due to major design changes  
- Self-reported data may be influenced by **social desirability and recall bias**

## 13. Link to documentation and any additional sources used
- [GSS GVP 2018 Survey Page](https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=4526)  
- [Public Use Microdata File (PUMF) User Guide – PDF](https://www150.statcan.gc.ca/n1/en/catalogue/89M0033X)  
- Internal reference: *2018_GSS33GVP_PUMFGuide.pdf*

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 29/06/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
