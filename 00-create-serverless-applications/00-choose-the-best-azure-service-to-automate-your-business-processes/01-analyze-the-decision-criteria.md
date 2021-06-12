# Analyze the decision criteria

We've introduced an array of Azure technology that could be used to help build these processes. Let's try to be more
concrete about how we make the decision for a given process.

## How to choose a service

![Service decision diagram](https://docs.microsoft.com/en-us/learn/modules/choose-azure-service-to-integrate-and-automate-business-processes/media/3-service-choice-flow-diagram.png)

## Mixing Technologies

Remember that there is no requirement for you to use the same technology for different workflows. You can call one
workflow from another.

One reason to mix the technologies used in your business processes would be to give users control over a small section
of a complete workflow. Do this by implementing that section in Microsoft Power Automate, then call that flow from a
Logic App, Web Job, or Function.