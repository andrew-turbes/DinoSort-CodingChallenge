# DinoSort-CodingChallenge

![alt text](https://images.askmen.com/1080x540/2016/09/26-112751-professional_jet_skier_performs_tricks_in_t_rex_costume.jpg)

The objective of this challenge is determine which dinosaurs are the most imporant of them all. Please read the instructions carefully, as every detail matters.

<b>What You Know</b>
* Navigate to: 10.249.252.159:3000
* Each dinosaur contains a unique id
* Each dinosaur contains a list of friends

<b>Your Objective</b>  
* Use the data to determine which dinosaur is the most important
* A dinosaur is considered the most important by the number of dinosaurs claiming to be their friend (dinos refrencing them in the friend list. The more points a dinosaur has, the more important he/she is.
* In the case of ties, this is the order to determine 
* Once you've determined which dinosaurs are the most important, output the results to a json file called important-dinos.json
* The structure of the json should just be an array of json objects. Each entry/object must contain a genus as the key corresponding to the genus name, and a key named importance, with the "weight" as the value.
* The output should be sorted from most important to least important
* 
