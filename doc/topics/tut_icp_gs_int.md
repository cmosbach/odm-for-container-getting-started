# Tutorial scenario and prerequisites

This tutorial introduces you to key features in ODM for Developers. Prepare for the tutorial by reviewing its objectives and prerequisites.

You start by working in the Decision Center Business console to update a decision service that a loan company uses to determine whether borrowers are eligible for loans. The fictitious company makes changes to its loan policies, and you must reflect the changes in the decision service. When you finish updating the decision service, you deploy a rule application, or RuleApp, to the Decision Server console and test a ruleset. 

The tutorial uses a simple decision service that has only one project. The rules are grouped into two folders in the project:

|Folder|Description|
|------|-----------|
|eligibility|These rules determine whether the loan can be approved.|
|validation|These rules make preliminary checks to determine whether data is rejected immediately.|

As you go through the tutorial, you log in as two different users to get a feel for the collaboration that takes place in the Business console. The two users log in with different user names:

-   odmAdmin: A manager who initiates, reviews, and deploys changes.
-   rtsUser1: A rule author who implements the change.

## Prerequisites

Do the following tasks before you start the tutorial:

-   Install [ODM for Developers](https://hub.docker.com/r/ibmcom/odm/), and note the URLs of your instances of the Decision Center Business console and the Decision Server console.
-   Download [MiniLoan Service.zip](../../Miniloan%20Service.zip?raw=1)
-   Download [miniloan-test.xlsx](../../miniloan-test.xlsx?raw=1)
-   Download [execution-payload.json](../../execution-payload.json?raw=1). As it is a text file, you need to right-click on the link and click on `Save link as`.

## Best practices

This tutorial includes the following best practices:

-   Use the Business console to follow changes to rules, especially when you assign work to other people.
-   Create a snapshot of a branch before modifying it. You can use the snapshot for comparisons or to rollback the branch to a previous state.
-   Post comments for other users. The comments can direct work and serve as part of the history of changes.
-   Use the search feature to find rule artifacts.
-   Test a rule set for REST execution in the Decision Server console.
-   Delete projects from the databases when you no longer use them. 

[**Next** ![Next icon](../images/next.jpg)](../topics/tut_icp_gs_evaluate_changes_lsn.md)

[![](../images/home.jpg) **Back to table of contents**](../../README.md)
