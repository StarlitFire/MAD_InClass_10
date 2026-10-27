# Critical Thinking Questions:


## Trace the local tip feature from button tap to displayed text. Which widget/state changes during the simulated loading state, and how does the user recover from the local error case?



## Why must the app keep form validation local even when it can ask an AI for a tip? Give one example of a bad decision if AI were allowed to approve signup.

The app must keep the form validation local because it forces a strict set of rules that must be followed in order for validation to be accepted. If AI were allowed to approve signup, it may add new rules without informing the user, which would lead to frustration from the user not knowing what they are doing wrong with signing up. The AI could also just remove a rule it does not think is necessary, which would lead to the database being more unsafe as junk data might be added without the developers knowledge due to the lack of strict rules.

## Which fixed local category selects the tip, and what form information does the feature deliberately ignore? Why?



## Which local test case changed what you implemented? Describe what you observed.




# Github Repository Link

https://github.com/StarlitFire/MAD_InClass_10