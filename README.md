# CS 3110 NFA Designs
_By Avery King, made with JFLAP._

## Selected Problems
- Problem 6
- Problem 13
- Problem 15
- Problem 18
- Problem 19

## How This Is Laid Out
Each directory will use the following naming template: `nProblem`. For example, if problem 8 is selected, then it would be named `n08`.

In each folder will be the following files:

- `nProblem.jff`: The actual JFLAP file of the NFA design itself.
- `nProblemt.txt`: A text file containing test strings. Accepted strings will come before rejected strings.
- `nProblemr.md`: Essentially each document's README with a screenshot of the NFA itself and its test strings.
- Any pictures: used in `nProblemr.md`. Please ignore.

## Summary of Doing These Problems
I felt like these problems were fairly simple to do, and as I was doing them, I did not encounter many surprises, but I did find one that caught me a little off-guard. Throughout my time in completing these assignments, I did not use AI for anything, but neither did I ask any questions to my professor.

In completing problem 19, my original automaton design allowed for accepting a string of all zeroes. I interpreted the question as requiring at least three 1s and overall accepting any input string that has a number of 1s with a multiple of three. With that in mind, I went to test my original design, and I saw one of the test strings that was supposed to be rejected accepted. When I stepped through the simulation of my design, it was because I was missing a special bad state that would've caused the automaton to accept some perfectly fine strings otherwise.
