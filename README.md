# Pelz et al., 2022 Replication

## Experiment Stimuli
Raw stimuli can be found in both the Images and Videos folder. The full JsPsych code can be found under index.html in the main folder. 

## Data

### The Raw Data can be found under the Data folder. The columns are as follows:


#### Official_ID: 
Participant

#### Subject_ID: 
The name of the raw data file for each participant. These files are stored on OSF: https://osf.io/8xa2q/overview.

#### Consent: 
Agree/Disagree to participate in the experiment. 

#### Attention_Check: 
Corresponds to the attention check after the familiarization trial. In this trial, participants see one of two boxes (unknown) being sampled. Once the identity of the samples are revealed, participants must answer which box they came from. Data in this column are either "72White" or "72Black," referring to the relative proportions inside each box. "72White" is the correct answer.

#### Catch_Trial: 
Corresponds to the catch trial, where participants are told to select a particular box if they are paying attention. Data in this column are either "correct" or "incorrect."

#### Trial_Name: 
Corresponds to each individual test trial. Values correspond to each of the 10 distributions, which were randomized in order for participants (e.g., 95_5 is the trial where the balls inside each box are 95 Pink/5 White or 5 Pink/95 White).

#### Samples_Requested: 
Corresponds to the key dependent variable: how many balls did participants request on each test trial (Trial_Name).

#### Strategy: 
Participants were asked to report what strategy the used in the experiment. These data were not included in the analysis.

#### Feedback: 
Participants were encouraged to provide feedback for the experiment. These data were not included in the analysis.

#### The analysis script can be found in the replication report, along with a full writeup of the replication project (located in the Writeup folder). 