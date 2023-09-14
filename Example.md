# Hypothetical Example: Usability Testing Using Heuristics

## Introduction

Usability testing often employs heuristics to evaluate a software application's user interface and overall experience. In this hypothetical example, we use six heuristics from Nielsen's Ten Usability Heuristics to evaluate a web application.

## Selected Heuristics and Their Scores

We select six heuristics for this example and fix a "usability score":

1. **Visibility of System Status**: Score - 65
2. **Match Between System and Real World**: Score - 70
3. **User Control and Freedom**: Score - 75
4. **Consistency and Standards**: Score - 80
5. **Error Prevention**: Score - 82
6. **Recognition Rather than Recall**: Score - 85

## Calculation of Average Usability (Overall Mean)

Firstly, to get an overall usability mean, we sum the individual heuristic scores and divide them by the number of heuristics.

$$
\text{Overall Mean} = \frac{65 + 70 + 75 + 80 + 82 + 85}{6} = \frac{457}{6} \approx 76.17
$$

## Relevance of the Last Three Heuristics Over the First Three

Note that the scores of the last three heuristics are generally higher than those of the first three. These values could imply that aspects like "Consistency and Standards," "Error Prevention," and "Recognition Rather than Recall" are more effectively implemented in the application than aspects like "Visibility of System Status," "Match Between System and the Real World," and "User Control and Freedom." Nevertheless, the low values could not imply low usability; instead, the software could focus more on guaranteeing the Visibility of System Status," "Match Between System and the Real World," and "User Control and Freedom." as pivotal characteristics. Thus, the score must not be computed equally because the values with low scores are less relevant than the others, and an overall average could dispassionate the reality of the practical usability of the software. 

### Heightened Average Using AHP

One could use the Analytic Hierarchy Process (AHP) to provide a more accurate representation of usability to weigh these heuristics based on their relative importance. For example, if "Error Prevention" and "Recognition Rather than Recall" are crucial for this specific application, they should be assigned higher weights. The challenge is to assign weights to the heuristics to generate a better approximation and interpretation. 

#### Using AHP to Set Coefficients
With the help of the Analytic Hierarchy Process and the function in **Weighted Heuristics using AHP.ipynb**, we could compare usability heuristics and obtain a weighted value of 79.123 (**Example solution.ipynb**)- significantly higher than the unweighted value of 76.17. This finding is crucial for two reasons. Firstly, it enables us to accurately reflect a system's true usability (the value could increase or decrease depending on the prior characteristics developed). Secondly, it empowers us to prioritize our efforts and optimize a system's critical characteristics, especially with constrained resources such as time, budget, and human resources. 
