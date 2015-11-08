# Using-Git

##This tutorial will Cover
  * [Setting Up a Repository](#setup)
  * [Add + Commit](#adding)
  * [Pushing](#pushing)
  * [Pulling](#pulling)
  * [Branching](#branching)

<a name="setup"></a>
##Setting Up a Repository
####Initializing

####Cloning


<a name="adding"></a>
##Adding and Committing 

<a name="pushing"></a>
##Pushing

<a name="pulling"></a>
##Pulling

<a name="branching"></a>
##Branching
 (Remote and Local)

####Merging
  * To merge two branches, type the following (Assuming master is behind both branches on commits)
  * <pre> git checkout master </pre>
  * Once on the master branch, pull from repository 1, where branch1_name is the name of one of the branches you wish to merge.
  * <pre> git pull origin branch1_name </pre>
  * A merge message should show, type a comment to note your actions.
  * Now pull from the second branch, where branch2_name is the name of the second branch you wish to merge
  * <pre> git pull origin branch2_name </pre>
  * Done! Your master now contains a merge of both branches. To update eith of your branches with the new merge
  * <pre> git checkout branch_name </pre>
  * <pre> git pull origin master </pre>
 
####Rollbacks

