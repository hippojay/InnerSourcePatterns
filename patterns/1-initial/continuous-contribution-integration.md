## Title

Continuous contribution integration

## Patlet

The impact of large pull requests on host teams can introduce overheads and delays. For guest teams it can cause long feedback times and frustration at delayed merges. Reducing contributions pull request sizes can help guests get the feedback they need quickly and reduce the load on host teams.

## Problem

Teams contributing code or features may often wait until that feature is complete submitting a pull request.  The lag between starting and finishing a feature can be many days or weeks, resulting in complex merge issues, lengthy code review cycles and difficult knowledge sharing/understanding sessions.  This slows down contribution merges and increases reluctance for Guests and Hosts to engage with InnerSource initiatives.

## Context

* Guest teams are new to InnerSource and wish to perfect features before submitting for review.
* Host teams are new to InnerSource, maintain exclusive team code ownership and work with long lived feature branches.
* There may be many silos in the company; team practices are not widely shared.
* Company culture may expect a high degree of perfection for delivered features, rather than quick feedback and continual learning.
* Large features are being created, spanning multiple day/weeks/sprints.  Infrequent deployments.

## Forces

* Evolving DevOps practices are pointing towards long lived feature branches as poor practices, with a move towards Trunk Based Development.
* The rise of continuous integration (CI) capabilities is allowing for rapid automated assessment of change, reducing overheads of smaller merges.
* The demand of organisations to move faster is enabling continuous delivery (CD), moving away from single large releases to progressive deployments to production

## Solutions

Break down large features into smaller multiple pull requests, enabling continuous contribution integration. Size of the pull request would depend on the feature context, the target being towards daily merge cadences.  The following are suggested solutions to help achieve this:

* Adoption of short lived feature branches with smaller commits and pull requests ; See **[Github Flow](https://githubflow.github.io/)** or **[Trunk Based Development](https://trunkbaseddevelopment.com/short-lived-feature-branches/)**.
* Staged delivery of code in multiple pull requests from guest teams through agreed cadence.
* Embedded guests within host teams to engage directly in team workflows, working with short lived branches.
* Feature flagging of features to allow for progressive deployment of change without exposing to users until complete.

## Resulting Context

* Guest teams enjoy quicker feedback on contributions ensuring that features maintain their value focus.
* Complex merge issues are reduced as smaller pull requests are being validated and reviewed on a more regular basis.
* Host teams have a greater understanding of the scope and impact of code contributions.
* Teams are encouraged to adopt good engineering practices in CI and CD, improving teams overall quality and workflow.

## Known Instances

TBD

## Status

Initial

## Author

* David Hawes-Johnson
* Plus assistance from those within InnerSource Commons Slack channel (see references)

## References

* Initial Slack discussion: https://innersourcecommons.slack.com/archives/C04PXKRN4/p1649322081852339
