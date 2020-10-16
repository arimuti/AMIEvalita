# AMIEvalita
This is the code used to create the model for our participation to the Evalita 2020 shared task on  Automatic Misogyny Identification. 

We focus on subtask A ---Misogyny and  Aggressive Behaviour Identification--- which aims at detecting whether a tweet  in Italian is misogynous and, if so, whether it is aggressive. Rather than  building two different models, one for misogyny and one for aggressiveness identification, we handle the problem as one single multi-label classification 
task, considering three classes: non-misogynous, non-aggressive misogynous and  aggressive misogynous. Our official submission obtained an F1-measure of  0.6343, which comes from 0.7263 for the misogyny and 0.5423 for the  aggressiveness task, suggesting that our single classifier gets confused by non-misogynist aggressive instances.
