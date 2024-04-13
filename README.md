# FightingSystem
 
I designed a fighting system which you can find better explained in the pdf in this repository. The Unity project is  simulator for this fighting system.

The Unity project allows you to use use 5 diffrenet attacks on dummy type enemies. It also uses an energy system which would prevent you from spamming attacks. 
The present attacks in this project are: punching, sword, magic projectile, magic explosive and triple arrow. 

## Intstructions

To change between abilities use numbers from 1 to 5 and to attack click. You can also press escape to choose your character again.

## Software architecture

Each attack is created with an abstract class and they have a scriptable object attached to them that holds its stats. I am also using scribtable objects for the characters in this game (player and enemies). Additionaly, I am using an event bus.
