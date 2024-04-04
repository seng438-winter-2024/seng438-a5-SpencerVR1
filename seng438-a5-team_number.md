**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:  1    |   |
|-----------------|---|
| Student Names:  | Spencer van Roessel |
|                 | Harris Hasnain |
|                 | Houssem Zaggar |
|                 | Kaylyn Tanton |

# Introduction

This lab report explores two primary methodologies: Reliability Growth Testing in Part 1 and Reliability Assessment using Reliability Demonstration Charts (RDC) in  Part 2. 

Part 1 gave us hands-on experience in assessing the reliability of a hypothetical system given its failure data collected during integration testing. This was done using the reliability growth assessment tool, C-SFRAT. Through this, we better understood reliability growth testing, learned how to measure the failure rate, MTTF, and reliability of the SUT, and became familiar with C-SFRAT. 

Part 2 involved using a Reliability Demonstration Chart (RDC) to check whether or not the target failure rate or MTTF is met. We had to decide upon the adequacy of testing for a given MTTF of the SUT by plotting the test data. This section allowed us to become familiar with the features and usage of an RDCtool.

# 

# Assessment Using Reliability Growth Testing 

## Result of model comparison (selecting top two models)	 

<img width="959" alt="MVF all" src="https://github.com/seng438-winter-2024/seng438-a5-SpencerVR1/assets/113068550/9a6db9ac-5a52-4cdb-a12d-6213a30d8c74">

We overlayed all the models over each other and deselected the worst ones until we were left with the best two. We found that the best models were 'TL' and 'IFRGSB'. The model comparison tab confirmed this, as those two models exhibited the lowest log-likelihood scores which is a metric that indicates its goodness of fit.

<img width="959" alt="MVF 2" src="https://github.com/seng438-winter-2024/seng438-a5-SpencerVR1/assets/113068550/0ad8bfde-7a4b-44dd-a6ab-07b8bd3367b0">

## Result of range analysis (an explanation of which part of data is good for proceeding with the analysis)	

## Plots for failure rate and reliability of the SUT for the test data provided	

MVF Graph of 'IFRGSB' Model
<img width="959" alt="MVF orange" src="https://github.com/seng438-winter-2024/seng438-a5-SpencerVR1/assets/113068550/96232f05-f131-4d2e-9973-42d20b4ecd4f">

MVF Graph of 'TL' Model
<img width="959" alt="MVF grey" src="https://github.com/seng438-winter-2024/seng438-a5-SpencerVR1/assets/113068550/9ddb0d0c-3b61-4fbd-9f97-aa55e2f6f10c">

Intensity Graph of 'IFRGSB' Model
<img width="959" alt="intensity orange" src="https://github.com/seng438-winter-2024/seng438-a5-SpencerVR1/assets/113068550/22453a4d-4ed5-4bcc-ac9e-1cc03588c4c9">

Intensity Graph of 'TL' Model
<img width="959" alt="intensity grey" src="https://github.com/seng438-winter-2024/seng438-a5-SpencerVR1/assets/113068550/9cd016f3-4149-4b01-a91e-0dc000734d37">

## A discussion on decision making given a target failure rate	

## A discussion on the advantages and disadvantages of reliability growth analysis	

Advantages:
- Can be used to predict the system's reliability  over time.
- Can help teams allocate resources better or prioritize more crucial improvements.
- Can help identify weaknesses in the system earlier in the development process, addressing issues promptly and improving overall reliability.
- Promotes continuous improvement by tracking metrics over time.
- Can help predict maintenance needs to prevent failures before they happen.
- Saves cost by reducing downtime.
- Can help determine which tests need to be run and when they need to run.

Disadvantages:
- Actual results may differ from predictions. For example, unexpected failures or changes in the environment or system will affect predictive accuracy.
- Dependent on the data provided. The predictions will be negatively impacted if the data is insufficient, inaccurate, or difficult to obtain.
- Can be resource intensive. Smaller organizations may struggle with time, data collection, and analysis.
- Translating findings into actionable improvements may be challenging. 
- Can be complex and may require technical expertise.

# Assessment Using Reliability Demonstration Chart 

## 3 plots for MTTFmin, twice and half of it for your test data	

## Explain your evaluation and justification of how you decide the MTTFmin	

## A discussion on the advantages and disadvantages of RDC	

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

# How the team work/effort was divided and managed

# 

# Difficulties encountered, challenges overcome, and lessons learned

# Comments/feedback on the lab itself
