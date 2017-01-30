# Git Definitions

**Instructions:** *Define each of the following Git concepts.*

* What is version control?  Why is it useful?
  * **Version control** is a method of tracking the history of a collection of documents (often documents consisting of machine code in particular) that change over time. The collection and its history together are called a **repository**.
  * The repository allows multiple users to see how the collection has changed over time, revert the collection to a prior state, and eases the process of reconciling multiple simultaneous changes to the same documents.
* What is a branch and why would you use one?
  * A **branch** is a part of your repository where you can work on one particular feature of your project. Changes required to create or modify the feature of interest can be collected and tracked in the branch, even if they become quite numerous, without much risk that bad changes will end up in the project itself - the master branch.
* What is a commit? What makes a good commit message?
  * A **commit** is like a snapshot of one branch of your repository. It's one of the states that you can easily restore your branch to, in case something goes wrong. 
  * A good commit message describes succinctly what changed between the previous commit and this one. If it can't be described succinctly, you probably aren't committing often enough.
* What is a merge conflict?
  * When a source branch is **merged** to an object branch, changes to the documents in the source branch are isolated, copied, and added to the object branch in the same locations. This is normally done automatically by the version control software. 
  * But sometimes the same location in the object branch doesn't exist. Sometimes the object branch also includes recent changes in the same locations. In both of these cases, the branches are in **conflict**, and human intervention is needed to determine which change will produce the best results (or possibly write a new one). This is usually done in a peer review process.
  
