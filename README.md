For use with version 0.5.0 only

To use:

Replace "BibitesAssembly.dll" in the TheBibites_Data/Managed folder with the file by the same name here

Create a .txt file in the Mods folder named "tags"

Seperating by comma, add in this order:

- The tag name you want to apply
- The gene index of the tag to sort by (see below), or the name of the gene (exactly as it appears in the indices list)
- Either "GREATER_THAN" or "LESS_THAN", to check if the bibite's gene is greater or less than the target value
- The target value to sort by
- Optionally, one more GREATER_THAN/LESS_THAN and a second target value that will be sorted by the second conditional (allowing you to tag only a defined range of genes)

Bibites will be tagged if their gene's value is greater or less than the target value, depending on the sort type

Then, simply run your simulation, click on any bibite, and click the tag button next to the tag name

To tag bibites normally, clear all text from the tags file

Example:

BlueBibite,7,GREATER_THAN,0.75

Example 2:

BlueishBibite,7,GREATER_THAN,0.25,LESS_THAN,0.75


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

14 = viewAngle

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
