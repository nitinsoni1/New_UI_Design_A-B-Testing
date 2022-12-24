# New UI Design AB Testing
The goal of this project is to test whether New UI Design can brings significantly higher CTR and DAU or not.

## Experiment 1: User Activity Level

### Define Experiment
1) What is the name of the experiment?
AB Test New Design for Landing Page Design
2) Define Hypothesis
- H0 : New design won't increase DAU (Daily Active User)
- H1 : New design will increase DAU (Daily Active User)

3) Who is the participant?
The user that visit landing page

4) What variables will be tested?
Existing Design & New Design

### Define Metrics
Metric : Daily Active Users

### Define Sample Size
When we calculate sample size for daily active user, our sample becomes a number of days rather than number of user needed *note : (continuous sample = metric take value on a scale). We need at least 6 days obvservation for each group. This is just for the sake of the exercise and we keep use all the days given (because the available datasets are intended for a/b testing purposes, so when we use all of these datasets, it will not interfere with other users who are not tested)

### Define Duration
- Experimental Design Date Started :  2021-11-01 00:00:00
- Experimental Design Date Finished :  2021-11-30 00:00:00
- The Number of Days Experimental Design Running :  30
- We will run this experiment for 30 days


### Test Experiment
- Mean Daily Active User for Control Group During Experiment : 15782.0
- Mean Daily Active User for Test Group During Experiment : 29302.433333333334

### Result
- pvalue :  0.0000000000000000000000000000000000000000000000000000000000000000000000000000000000065906035841072442
- Sufficient Reject H0 <br>
Then we will decide that the average difference between daily active user new design and daily active user existing design is very significant. Which means that the average daily active user new design is higher than the existing design.

## Experiment 2: Click Trough Rate

### Define Experiment
1) What is the name of the experiment?
AB Test New Design for Landing Page Design

2) Define Hypothesis
- H0 : New design won't increase CTR (Click Trough Rate)
- H1 : New design will increase CTR (Click Trough Rate)

3) Who is the participant?
The user that visit landing page

4) What variables will be tested?
Existing Design & New Design

### Define Metrics
Metrics : Click Trough Rate

### Define Sample Size
Num of samples (at least) needed : 8796 <br>
We need at least 8796 user samples obvservation for each group. This is just for the sake of the exercise and we keep use all the users given (because the available datasets are intended for a/b testing purposes, so when we use all of these datasets, it will not interfere with other users who are not tested)

### Define Duration
- Experimental Design Date Started :  2021-11-01 00:00:00
- Experimental Design Date Finished :  2021-11-30 00:00:00
- The Number of Days Experimental Design Running :  30
- We will run this experiment for 30 days


### Test Experiment
- Mean Click Trough Rate for Control Group During Experiment : 32.996977569382835
- Mean Click Trough Rate for Test Group During Experiment : 37.99695912626142

### Result
- pvalue :  0.0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
- Sufficient Reject H0 <br>
Then we will decide that the average difference between ctr in new design and ctr in existing design is very significant. Which means that the ctr in new design is significantly higher than the existing design.

