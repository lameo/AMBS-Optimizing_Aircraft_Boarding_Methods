# Optimizing Aircraft Boarding Methods
*Under Professor Cheng Shih-Fen, School of Information Systems, Singapore Management University*

#### Abstract
One major area airlines can improve on to cut costs is through optimization of aircraft boarding methods. Through robust examination of existing methods and comparison with new strategies, this paper attempts to identify the relatively best strategy, using Agent-based Modelling and Simulation. As we strive to make the model as realistic as possible, characteristics of our autonomous agents such as their willingness to follow boarding instructions (compliance) have been simulated. We also try to understand if the number of bags each passenger carry will have a significant impact on total boarding time. Our findings suggest that the Luggage First method is most successful in reducing total boarding time, with relatively high performance and low overhead costs. 

## 1 Introduction
#### 1.1	Background and Importance of Optimizing Aircraft Boarding Strategies

In the airline industry, the phrase “time is money” rings true. Airlines generate revenue only when their planes are utilized and flying passengers. Thus, the longer a plane takes to takeoff means fewer routes it can fly. (Iyigunlu, Fookes, & Yarlagadda, 2014)

But a most common problem – and one of the most challenging ones – plaguing these airline companies is passenger boarding delays. Slow boarding time translates to minutes lost for each plane to depart and thus opportunities to generate profits lost. They cost the US economy on average $32.9 billion a year, and most of it are borne by both passengers and airline companies. 
Thus, there needs to be a more efficient way to minimize the time taken for passengers to board than what was traditionally used. In this project, we attempt to introduce 3 new boarding methods and compare it with an existing and relatively efficient method, the Random Method. 
Since a major reason for passenger boarding delays is the time spent waiting for each passenger in front (of the queue) to put their luggage and sit so that the queue can move forward, our goal will be to minimize this waiting time. 
Through this comparison, we will be able to draw conclusions on the most efficient method, and possibly benefit the airlines industry by proposing a method that is optimized and capable of reducing passenger boarding delays. 
1.2	Agent-based Modelling and Simulation

In order to test the efficacy of our proposed strategies, we will be utilizing Agent-based Modelling and Simulation (ABMS), in an attempt to create a more realistic simulation. The main feature of ABMS is the modeling of individuals as autonomous agents capable of making decisions. (Iyigunlu, Fookes, & Yarlagadda, 2014)

This is most apt for this project as passengers are modelled as agents with the capacity to: 
•	Non-comply with the boarding strategies
•	Have carry-on or choose to go without
•	Have different walking and storing luggage speeds which will affect total boarding time

In summary, plane boarding is not static and there can be no assumption that each person will behave like a robot, executing the same actions as everyone else. There must be a way to introduce the individual characteristics of each person and analyze how such “randomness” will affect the whole boarding time, to better reflect reality.

## 2	Literature Review
#### 2.1 Existing Strategies
There are many research studies on the topic of aircraft boarding methods, but none that are realistically easy to implement and feature low overheads. In fact, the conventional method airlines are still using today, the Back-to-Front method, is actually the worst performing strategy based on research. However, airlines still use them because of its ease of implementation compared to other methods. 
To have a good comparison, we looked at 4 existing strategies (Iyigunlu, Fookes, & Yarlagadda, 2014), mainly: 
1.	Back-to-Front (the Standard Method): Passengers seated at back rows enter first followed by those seated at the middle and the front. 
a.	Pros: Easy to implement. 
b.	Cons: Slow boarding time due to long waiting along the aisle for passengers in front to put their luggage

2.	WILMA: Also known as “Window, Middle, Aisle”, this strategy involves letting passengers seated at the window seat to board first, followed by middle and aisle seat passengers. 
a.	Pros: Easy to implement.
b.	Cons: Unrealistic and results in customer dissatisfaction. For instance, for passengers travelling as a group or family, they may be unwilling to allow their children to board first without them

3.	Random: Passengers are randomly assigned seat numbers and board randomly. 
a.	Pros: Easy to implement and relatively quick boarding time. 
b.	Cons: Easily causes customer dissatisfaction due to inability to choose seats. 

4.	Steffen: Passengers are seated two rows apart in equivalent seats. (E.g. 1A, 3A, 5A)
a.	Pros: Very fast boarding time, probably the most efficient method
b.	Cons: Hard to implement. Especially on a big airplane with 800 over passengers, it may not be realistic to ask passengers to board one-by-one according to seat number. Again, causes separation of groups.

#### 2.2 Proposed Strategies
Although there are quite a few existing strategies, their efficacy still remain uncertain. Hence, this paper will attempt to modify the existing methods and come up with new strategies that are more realistic and easier to implement. 
The three strategies are mainly: 
1. Modified Steffen Method (Mix Random): 
•	Divide passengers into 5 groups 
•	Instead of a single passenger seated 2 rows apart, this method will instead allow a group to board at the same time, in a random pattern. 
2. Modified Steffen Method (Modifications from Existing methods): 
•	Alternating rows of passengers of the left aisle will board first, followed by those from the right aisle. This is to minimize the amount of time each passenger waits for the one in front to finish putting his/her luggage.
> Reference: https://www.youtube.com/watch?v=oAHbLRjF0vo#action=share
Note: This is a proposed method by the YouTube channel CGP Grey. To the best of our knowledge, no study has yet been done on this method.

3. Luggage First Method:
•	Passengers with 2 luggage will board first, followed by 1 and 0 carry-on. The sequence of boarding is random, and this is to ensure those that will take a long time to store their luggage do not result in a long waiting time for those without.
•	To the best of our knowledge, no study has yet been done on these proposed strategies and this paper believes that through the attempt in finding the optimized strategy for aircraft boarding, it will also be able to suggest a more realistic method that is an extension from the original. 
In order to have a fair comparison and a benchmark, we will be comparing the total boarding time taken for our proposed methods against the Random method, which is a relatively efficient and realistic method compared with the rest.

## 3 Hypotheses
Please refer to the attached word doc for the rest of the document...

