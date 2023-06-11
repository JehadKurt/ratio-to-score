# ratio-to-score
Conversion of ratio  value with ideal and threshold to score 
Ratio to Score Approximation							
							
Ratio	Relationship	Threshold/Ideal (T/I)	T/I Value	T/I Score	Ratio for score of 0	Ratio for score of 100	Description
COGS	Lower ratio -> higher score	Threshold	0.5	30	0.65	0.1	Score decreases quicker as it approaches threshold.
Salaries		Ideal	0.3	100	"0.1, 0.5"	0.3	If ratio is too low score should be low. Score increases quicker as it approaches ideal. Score decreases slower as it approaches max value.
Rent	Lower ratio -> higher score	Threshold	0.04	30	0.1	0	Score decreases quicker as it approaches threshold.
Advertising		Ideal	0.2	100	"0,0.5"	0.2	If ratio is too low score should be low. Score increases slower as it approaches ideal. Score decreases quicker as it approaches max value.
Op Expenses	Lower ratio -> higher score	Threshold	0.64	30	0.8	0.2	Score decreases quicker as it approaches threshold.
Office Expenses	Lower ratio -> higher score	Threshold	0.018	30	0.05	0	Score decreases quicker as it approaches threshold.
GP	Higher ratio -> higher score	Threshold	0.188	70	0.075	0.4	Score increases quicker as it approaches threshold.

#1
Cogs Score
Score decreases quicker as it approaches threshold.
if ratio Low score will be  high
Threshold ratio = 0.5 Threshold Score = 30 
Score = 0 if ratio => 0.65
Score = 100 if ratio< =  0.1 
Score range from 0 to 100
score increase as ratio  decreases from 0.5 to 0.1 
Score Decreases as ratio increase form 0.1 to 0.65 

#2
Salaries Score
If ratio is too low score should be low. 
Score increases quicker as it approaches ideal. Score decreases slower as it approaches max value.
Ideal ratio = 0.3 Ideal Score = 100
Score = 0 if ratio =< 0.1
Score = 0 if ratio =>0.5
Score range from 0 to 100 

#3
Rent Score 
Score decreases quicker as it approaches threshold.
for Lower ratio  score will be  higher
threshold ratio = 0.04 threshold Score = 30
Score = 0 if ratio >= 0.1
Score = 100 if ratio =< 0
ratio range 0 to 0.04 score will be from 100 to 30
ration range from 0.04 to 0.1 score will be from 30 to 0 
Score range from 0 to 100 
# 4
Advertising Score
Ideal= 	0.2 the Score = 100
if ratio = 0 then Score  = 0
if ratio = 0.5 then Score  = 0
when ratio= 0.2 then score = 100
If ratio is too low score should be low. 
Score increases slower as it approaches ideal. Score decreases quicker(exponentionally) as it approaches max value.
Score range from 0 to 100 
 # 5 
Op Expenses Score
for Lower ratio   score higher
Threshold ratio=0.64 Threshold Score = 30	
if ratio = 0.8 score = 0
if ratio = 0.2 then score = 100
Score decreases quicker as it approaches threshold.
score range from 0 to 100



