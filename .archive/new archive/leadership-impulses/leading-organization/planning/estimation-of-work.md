# Estimation of Work

Estimation and Story Points Are Related to Effort, Not Hours
Instead of estimating how long a product backlog item will take to complete, the developers discuss the effort. 
Using story points or estimates that are not related to time provides a shared understanding and agreement of the effort of the work regardless of which members of the team contribute to its completion.
When a team says something like “one hour is equal to three story points,” the equivalency assumes that all members of the team will perform the same work in the same amount of time. That’s often not the case. While a senior team member may take an hour on a product backlog item (PBI), it may take a junior team member three times as long; however, they’ll be undertaking the same effort. Discussing effort instead of hours supports a common understanding of the scope of the work.
Pointing a story in terms of time alone is mostly an estimation of how long a PBI will take a particular individual. At that point, it’s not a holistic and universal estimation of scope.
How to Estimate Effort
Estimation, a form of understanding the size of the work, is a collaborative process in which the developers discuss the effort of completing an item from the product backlog. The question is, “If we were to implement this product backlog item fully, what is the work involved, and what is the effort of that work?”
 As part of a discussion of the effort involved, the developers may factor in the following:
The complexity of the work
The amount of work
Risk and uncertainty
How to Do Story Point Estimation
First, it’s important to understand that the value of story points is that they are relative. The actual numerical value is meaningless. Whether you choose a scale of 1, 3, 5, or 200, 300, 400, the ratio is what matters — how the effort of a 3 compares to a 1; how the effort of 400 compares to 300. 
It’s the relativity that allows developers to compare the scope of one item to other items.
Common Story Point Estimation Techniques
T-shirt sizes (XS, S, M, L, XL, etc.)
Fibonacci Numbers (1, 2, 3, 5, 8, 13, 21, 34, etc.)
Our Approach - A Blend of T-Shirt Sizes and the Fibonacci Numbers

T-Shirt Size
XS
S
M
L
XL
Story Points	1-2	3-5	8-13	21-34	55+
Guidelines	
Small modifications to existing functionality
Architecturally insignificant
Only involves one team
Similar work done in the past
No new technologies involved
Small modifications to functionality
Architecturally insignificant
Minimal dependencies between teams
Similar work done in the past
No new technologies involved
More significant modifications to new or existing functionality
Minor architectural changes
Few dependencies between multiple teams
Precedents exist for the work but team is inexperienced doing it
May involve new technologies or tools
No existing functionality to leverage
Major architectural changes required
Multiple dependencies across multiple teams
No precedents for the work or no experience doing it
Involves new technologies or tools
No existing functionality to leverage
Major architectural changes required
Multiple dependencies across multiple teams
No precedents for the work or no experience doing it
Involves new technologies or tools
Should be decomposed further
Agreeing to an Estimate or Size
Sizing conversations happen among the developers on the scrum team. Story points or another estimation device make it possible for everyone on the team to agree on effort through conversation. 
Insights from this conversation can be incredibly valuable. Especially when the size estimates differ widely. For example, when one developer sizes a PBI at eight and another assigns a three, a conversation ensues about why each developer chose the size. 
The ultimate outcome may be that the full scope of the work wasn’t understood by everyone. Perhaps there is some risk or complexity that only one developer recognized. Now they can align on the scope.
On the other hand, the developer who assigned a three may have recognized an opportunity. Perhaps a new tool or pivot in processes can eliminate a wasteful part of the work. The developer can explain this opportunity to the rest of the developers so they can understand it and align on the size of three.
Planning Poker and Other Methods
The whole idea is for story point estimation to be a quick, lightweight process. Determining the size to assign to a PBI shouldn’t be a laborious, painstaking task requiring hours of collaboration. 
The reason? Agile teams emphasize their interaction and collaboration over processes and tools. Don’t let this tool hamper your ability to collaborate and deliver value.
There are a few common ways scrum teams engage in a light process to estimate PBIs:
Planning poker. Someone reads the PBI and the developers use cards with the points written on them to vote on the size of the PBI. You can hold up a card for all to see or use an anonymous version. Discrepancies are then discussed and resolved, which not only leads to a point assignment but also creates an opportunity for the team to discuss the work and get a better idea of the scope.
Have a discussion. The developers can simply take a few moments to discuss the PBI and agree on a point or size. Some teams don’t need anything more than a brief conversation.
Vote, then discuss discrepancies. Take a quick vote on the size of the PBI and then hold a brief discussion to resolve any major discrepancies.
What this means in Jira?
As a team, enter the story point estimate using a fibonacci number in one of three ways (keep in mind that only stories and tasks have story points, discovery items, features and bugs do not):
When creating new issues - use the story points field just like you would the epic, sprint or etc. field.
When editing an existing issue - same as above
From the side view menu - enter fibonacci number in the Estimate field
