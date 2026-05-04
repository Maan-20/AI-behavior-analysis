# Reasoning Consistency Across Prompt Variations

## Prompt
If a bat and ball cost $1.10 total, and the bat costs $1 more than the ball, how much does the ball cost?

## Test Approach
The same logical problem was presented in slightly different phrasings to evaluate consistency in reasoning.

## Observations
- In some cases, the model answers "$0.10" incorrectly  
- In other cases, it correctly answers "$0.05"  
- Accuracy varies depending on wording of the prompt  

## Issues
- Susceptibility to cognitive bias (pattern recognition instead of reasoning)  
- Inconsistent reasoning across semantically identical prompts  

## Why It Matters
- Indicates shallow reasoning despite confident responses  
- Critical flaw in tasks requiring logical precision  

## Conclusion
The model does not consistently apply logical reasoning and appears sensitive to prompt phrasing, suggesting reliance on heuristics rather than structured problem-solving.
