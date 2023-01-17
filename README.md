# test_repo
## Here we will describe how we work with our repository

### _GIT pull_

Git pull is a command that allows you to fetch from and integrate with another repository or local branch.

Use GIT pull only when you have complete context about the changes you will be getting from your remote repository and adding to your local copy.
*Git pull is actually a Git fetch followed by an additional action(s)—typically a Git merge*.
 
**Git pull is faster** as you’re performing multiple actions in one. Using the Git pull command you’re probably less worried about introducing conflicts into your local repo and you just want the most up-to-date changes from the remote branch you’re pulling from.


### _GIT fetch_
Git fetch is a command that allows you to download objects from another repository.

If you only want to see all of the current branches and changes in your remote repository, Git fetch can get you all of the information you need without actually making any local changes to your work.

This gives you time to decide on the best course of action for incorporating your changes, such as merging them in or fast-forwarding your local branch.

**Git fetch is a safer alternative** because it pulls in all the commits from your remote but doesn’t make any changes to your local files.

***
**Git pull is a more advanced action** and it’s important to understand that you will be introducing changes and immediately applying them to your currently checked out branch.

Git fetch is a bit different; you can use the Git fetch command to see all of the remote’s changes without applying them. This action can be great if you’re newer to Git, as it provides more visibility about the changes being introduced. On the other hand, fetch might also be preferred by Git veterans who just want more control over what’s happening in their repo.
***
