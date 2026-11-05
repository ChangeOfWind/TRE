# TRE

Final Project for the Building AI course

## Summary

Transformer for Requirements Enablement - Given a system landscape, functions based on user defined requirements and a growing repository of project documentation, a trained chatbot is supposed to guide users of a system through the process of defining further projects starting with the requirements, to add needed functionality.

## Background

I spent a lot of time in my professional life, 
- defining requirements,
- cross checking,
- investigating legal implications, other requirements, efforts versus benefits and of course mostly
- guiding users and other stakeholders to define and phrase things in an appropriate manner.

So the idea is to train a chatbot (later maybe a more sophisticated system) and give it access to a defined system in order to support all eligible stakeholders to state there requests.
This could cover the typical skills of requirements engineering (how to phrase, what to think of, what to avoid, how to make developers, testers and others able to understand what the intention is).
Furthermore, it could, with the correct access to current projects/programs and enough documentation, check if
- this function already exists,
- it violates restrictions,
- it counterfeits other functions or ongoing or planned projects.

Providing enough information it might also setup project ideas, milestone plans and even effort estimations and benefits to rate the requirement for later prioritization.
This way more users could provide more ideas and see the weak points, if there are any.

## Data and AI techniques

Most likely for the pure Requirements phrasing part a well trained LLM would do the job.
The more proprietary information about the context of a system landscape and the system itself the Chatbot has, the more precise the phrasing can become.
Latest for the check with other requirements and efforts this part will be needed.
in order to work out parts of the project and change management access to a project database will be needed.

## How is it used

the Chatbot should provide a common interface as known from other LLMs and chat programs to appear familiar for users of this application.
Another output could the the development, team the project management team, the security team.

## Challenges

- How to define, which user can define requirements and for which systems?
- How to find enough training data for the more context specific tasks?
- Is it save to share that data?

## What next

Make it part of common project management suites.
