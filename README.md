For use with version 0.5.0 only

To use:

Create a .txt file in Mods named "tags"

Seperating by comma, add in this order:

- The tag name you want to apply
- The gene index of the tag to sort by (see below)
- Either "GREATER_THAN" or "LESS_THAN", to check if the bibite's gene is greater or less than the target value
- The target value to sort by

Bibites will be tagged if their gene's value is greater or less than the target value, depending on the sort type

Then, simply run your simulation, click on any bibite, and click the tag button next to the tag name

To tag bibites normally, clear all text from the tags file

Example:

BlueBibite,7,GREATER_THAN,0.5


Gene indices:

0 = layTime

1 = broodTime

2 = hatchTime

3 = sizeRatio

4 = speedRatio

5 = colorR

6 = colorG

7 = colorB

8 = strength

9 = defence

10 = mutationVariance

11 = mutationChance

12 = brainMutationVariance

13 = brainMutationChance

14 = viewAngle.minValue

15 = viewRadius

16 = clkSpeed

17 = pherosense

18 = diet

19 = baseImmuneActivation

20 = herdSeparationWeight

21 = herdAlignmentWeight

22 = herdCohesionWeight

23 = herdVelocityWeight

24 = herdSeparationDistance

25 = growthFactor

26 = growthMaturityFactor

27 = growthMaturityExponent
