# Automatic Sense Making and Explanation using ML Models
The objective of this project is to directly test whether a system can differentiate natural
language statements that make sense from those that do not make sense. Three subtasks were
designed by SemEval 2020.
https://competitions.codalab.org/competitions/21080#learn_the_details-overview

## Part 1
The first task is to choose from two natural language statements with similar wordings which
one makes sense and which one does not make sense;

Example Task A: Validation

Which statement of the two is against common sense?

Statement 1: He put a turkey into the fridge. (correct)

Statement 2: He put an elephant into the fridge.

## Part 2
The second task is to find the key reason from three options why a given statement does not
make sense;

Example Task B: Explanation (Multi-Choice)

Select the most corresponding reason why this statement is against common sense.

Statement: He put an elephant into the fridge.

Reasons:

A: An elephant is much bigger than a fridge. (correct)

B: Elephants are usually white while fridges are usually white.

C: An elephant cannot eat a fridge.

## Part 3
The third task asks machine to generate the reasons and we use BLEU to evaluate them.

Example Task C: Explanation (Generation)

Generate the reason why this statement is against common sense and we will use BELU to
evaluate it.

Statement: He put an elephant into the fridge.

Referential Reasons:

i. An elephant is much bigger than a fridge.

ii. A fridge is much smaller than an elephant.

iii. Most of the fridges aren’t large enough to contain an elephant.
