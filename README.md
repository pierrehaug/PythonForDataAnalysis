# PythonForDataAnalysis
Project MiniBooNE

L’expérience MiniBooNE (Mini Booster Neutrinos Experiment) a pour but de détecter l’oscillation des neutrino (particule élémentaire). 
C’est un sujet en physique des particules.


Le travail sur le dataset « MinibooNE » est un travail de classification où l’objectif est, à l’origine, d’observer les oscillations des neutrinos. 
Les neutrinos sont des particules élémentaires. Le but ici est de déterminer deux classes pouvant « résumer » notre dataset : les « électrons » neutrinos (signal) et les neutrinos  « muoniques » (background).

La première ligne du dataset est la part de "Signal Event" / "Background Event". Ces valeurs permettent de créer une variable "target" en créant deux groupes "naïf" en fonction de ces proportions.
