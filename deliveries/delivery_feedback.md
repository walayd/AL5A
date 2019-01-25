# Software Architecture (2018) - Feedback on Deliverables

## Deliverable list
- Sept 30th: scope
- Oct 10th: component diagram, roadmap, plan.
- Jan 16th: updated architecture document. Based on the new requirement, update the arch. document to describe what you will keep, what you will change, what you will remove, and more importantly why.
- March 1st: video of scenario demo

## Feedback on Delivery of Oct. 10th.
### Group A
Your plan seems viable, the architectural choices taken so far look good, however you need to explain why they've been taken this way.

### Group B
Plan looks good, technical choice look ok but are not justified. You should start coding now.

### Group C
Plan looks good. Architecture needs be refined a bit more, Esp. the diagram need be explained.

### Group D
Plan is not good. You have too many weeks of whiteboarding / thinking and start coding too late. You need to start coding now, and research the right image library in parallel. Technological choices make assumptions that need be justified.

### Group E
Component diagram is ok, and the explanations below it are sufficient to understand it. Technology choices are not justified and debatable. I didn't see a plan.

### Group F
Plan is scenario-oriented, and in this sense, it is good. However it needs be beefed up with a description of the steps you think you will perform. Component diagram needs some explanation alongside it.

### Group G
Comopnent diagram and matching text are good. Plan seem to devote little time to implementation, you should start coding now and build up your MVP more iteratively. Technology choices will have to be explained and beefed up along the way.

### Group H
I'm happy to finally see a team mentioning testing technology, well done guys!
However you will have to justify you technology choices. Component diagram is ok. Plan looks good but leaves no room for the unexpected.

### Group I
Component diagram page 3 (no page numner?) is ok, however diagram on page 4 is mixing various concepts, including the system as a component of itself? Plan should also include tooling and CI environment.


## Feedback on Delivery of Sept. 30th

### Group A
Personas and scenarios map what we have decided. Scenario 2 is not so clearly defined.
Scope is validated, you can proceed with the next step.
Status log is too detailed, the sections on personas and use cases are not needed here.

### Group B
Half of the content is in the status log, half in the deliverable architecture document, why? Your topic is on billing, the two main use cases mention billing just once, and very vaguely. You need to detail this out more.
You should add a mechanism by which when Alice offers her service, the system suggest a number of points she should charge for (she can decide otherwise).
With this addition I would be happy to validate the scope.

### Group C
You listed a series of user stories, not use cases. This is good, but the list is long. You should prioritize them. Moreover, it would be good for you to pick 2 or 3 end-to-end scenarios for the early November demo, and make sure you start putting in place a walking skeleton that can cover those before implementing the others.
Scope validated.

### Group D
Except that the last sentence is cut off, the scenarios description is good and has the right granularity. Prioritize the scenarios, pick 2 or 3 that are fully end to end and start with that.
Scope validated.

### Group E
Please add the following to your scenarios: Céline needs a way to query the types of insurance contracts (with criteria, Eg: theft insurance, replacement value, etc.). Hubert needs a way to categorize its contracts. It should not be a simple list to read from.
With these changes I would be happy to validate the scope.

### Group F
Status is a bit too fuzzy...
Scenarios are good, I understand you plan to cover them all, and with that the scope is validated.

### Group G
I like that you list all the stories, then the end to end demo scenarios, this is good. Prioritize your stories based on those that contribute to the demo scenarios.
Scope is validated.

### Group H
The status document is good. However the main deliverable lacks personaes and scenarios. You have only included a diagram, which can't really be understood without some text to explain it. I have no idea of what I will see at demo day. You need to write the scenarios, and be explicit about your scope, what you will and will not include in the project.
At this point, I can not validate the scope.

### Group I
Missed delivery, please read the instructions, files were not extracted right.
In story 1b, when Bob searches for an offer, he should be able to specify his query by destination and package size, not just get a flat list.
With this addition, the scope is validated.
