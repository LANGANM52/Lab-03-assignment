# Lab-03-assignment

Problem 1) Find and show how to compute Big O for the following algorithm: 70%

To find Big O for this following algorithm the main thing to look for is loops. The start of the program is initializing some integer values, these all count for O(1) and O(1) + O(1) = O(1). Then the program has a while loop, this while loop doesn’t contain a loop within it and no predetermined end point so it counts for O(N). The if and return statements following are all constant so they count for O(1). So our final result is O(1) + O(N) which is just equal to O(N).


Problem 2) You have 20 M&Ms bags. 19 bags have 1.0 gram pieces, but one has pieces of weight  1.1 grams. Given a scale that provides an exact measurement, how would you find the heavy bag? You can only use the scale once.  30%

The solution would be to label each bag from 1-20 and then take that respective amount of M&Ms out of each bag. So bag 1 you would take 1 M&Ms, bag 2 you would take 2 M&Ms, ect… Then you want to take all the M&M you’ve taken out and weigh them. Take that weight you measured and subtract it by 210 (the sum of 1+2+3+4+5…..+20) and then multiply that result by 10 and that is the bag number that is heavier than the rest. So if bag number 17 was the heavier one per say, the weight would measure in at 211.7 grams, subtract that by 210 you have 1.7 (the extra amount of weight). Multiply by 10 and you get 17.
