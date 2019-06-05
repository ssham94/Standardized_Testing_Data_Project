SAT/ACT Data Project
-------------

### Problem Statement:
Between SAT and ACT testing, collegeboard, the organization that created the SAT wishes to increase the participation rate of the test throughout the nation. The data that will be given will be the national averages for each section of the test (no data available for 2018 ACT scores aside from composite) as well as the participation rate for each test based on the state. 

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|states|Object|ACT/SAT|Name of the states listed in both datasets| 
|sat_participation|Int|SAT|The participation rate for each state (units are presented in %)
|act_participation|Int|ACT|The participation rate for each state (units are presented in %)
|sat_reading_and_writing|Int|SAT|The average scores per state for the SAT reading and writing section (represents average scores)
|sat_math|Int|SAT|The average scores per state for the SAT math section (represents average scores)
|sat_totals|Int|SAT|The average total scores per state for the SAT (represents average scores)
|act_english|float|ACT|The average scores per state for the ACT english section (represents average scores)
|act_math|float|ACT|The average scores per state for the ACT math section (represents average scores)
|act_reading|float|ACT|The average scores per state for the ACT reading section (represents average scores)
|act_science|float|ACT|The average scores per state for the ACT science section (represents average scores)
|act_composite|float|ACT|The average composite scores per state for the ACT (represents average scores)

### Executive Summary
During the analysis of the data, the first step was to look at the general statistics of the data that was given. It was clear that ACT had the higher participation rate in both years. Next was a quick look at the score data. The averages as well as the min and max scores for each test were calculated to see if there was any correlation between the tests in terms of difficulty. If we were to use a conversion chart, we can see that the averages as well as the actual scores match each other once the conversion is applied. This shows that the difficulty between the tests would be about the same, and would not be the prime reason for participation rates. 

Once realizing that the scores did not have much effect on the participation rate, other data was needed to determine the why the participation rate for the ACT was higher than the SATs. Outside research showed that the reason for higher or lower participation rates in certain states boiled down to a few factors:
1. Access to test (number of testing centers in state)
2. State/school funding for particular tests
3. Contracts created between testing organization and state

A good example of these factors would be Colorado. In 2017, the state only had a participation rate of 11% while in 2018, the participation rate increased to 100%. This was due to the fact that the state had actually came out with a plan to fund all test takes who wanted to take the SAT in 2018. Thus the sudden increase in SAT testing in just one year. 

### SFinal Conclusion
If the SAT or ACT were to increase participation rates, they should increase funding or support for their test in a state. This means that they should encourage schools to prepare their students for the test in question, as well as increase the amount of testing centers as well as other testing resources for their respective test. 