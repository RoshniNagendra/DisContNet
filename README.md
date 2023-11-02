# DisContNet
A transformer based contradiction detector. It detects contradictions in sentence pairs using NLP and Deep learning.

This current project is under review to be published, hence the code is unavailable.

We created a custom dataset to feed to our model. A novel concept that we bring to this project is that it can identify degree of contradiction and clissify the type of contradition it falls to.

Label Name Example
0 Non-contradictory :
I am studying.
I am a student.
1 Contradiction due to negation :
Bengaluru weather is the best.
The weather Bengaluru experiences is definitely
not the best.
2 Numeric contradiction :
Over 2000 people voted for Shreya to be president.
A 100 people voted for Shreya to be president.
3 General contradiction :
The turtle followed the fish.
The fish followed the turtle.
