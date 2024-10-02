# Fuzzy-Control

## Fuzzy logic
Fuzzy logic is an inference method similar to human thinking. In traditional logic, only yes (1) or no (0) can be selected. 
However, fuzzy logic is a continuous interval between 0 and 1, with a fuzzy zone added in the middle area, which fully explains the uncertain nature of fuzzy.

## Fuzzy architecture
### Knowledge base:
We need to define relevant fuzzy sets for each input feature variable. 
For example, the temperature set includes cold and hot, and the motor speed includes low, medium, high, etc.

### Rule base:
We can use domain experts to design a set of rules for us to make inferences and decisions. 
For example, if our goal is to control the product quality of a certain machine, we ca use the process parameters as input features for inference. 
For example: IF the temperature is low AND the humidity is high THEN the product quality is unqualified.

### Fuzzification:
This step will convert the unambiguous input values ​​into the corresponding fuzzy sets through fuzzification. 
And it is combined with the previously established knowledge base and rule base to complete the fuzzification mechanism.

### Inference:
The degree of fuzzy matching is calculated through fuzzy input and fuzzy sets. 
The rules to be triggered are determined based on the input and the corresponding fuzzy set.

### Defuzzification:
Fuzzy operations are performed through the rules set by experts, and all matching rules are aggregated and output.

## Fuzzy set
Fuzzy sets use the size of the membership function as the main decision-making mechanism. 
A fuzzy set is a combination of things with common characteristics. 
It is specially used to summarize a group of things with the same characteristics. 
Sets are also a way to express the concept of things. 
For example, "all machine temperatures", "color of a certain product", etc. can be called sets. 
The things or objects that make up a set are called elements of the set. 
For example: all machine temperatures = {15, 16,…,50}, each temperature is an element of the set.

## Membership Function
Belonging function is the most basic concept in fuzzy theory, and we can use belonging function to represent fuzzy sets. 
It is represented by the attribution function μA(x). 
Through μA(x), it takes a value in the [0, 1] interval, so each attribution value is between 0 and 1. 
The size of the belonging function reflects the degree of belonging of element x to fuzzy set A. 
Therefore, the closer the value of μA(x) is to 1, the higher the degree to which element x belongs to μA. 
On the contrary, if the value of μA is closer to 0, it means that the degree of x belonging to μA is lower.

