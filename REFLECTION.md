1. There was no previous merge information when we first merged update-message-a to the main branch. When we merged update-message-b there was already merge information from update-message-a.
2. The section under HEAD represents the changes made by the first merge of update-message-a with main. The section under the branch name represents the new information being merged.
3. git merge --abort would abort a merge in progress and attempt to recreate the previous merge state, though it can sometimes fail to recreate uncommitted changes prior to the current merge in progres.
4. The primary difference between the git log --graph shape from Part C is the offshoot off "Label sum output 'Sum'" that addresses the merge conflict and the change when merging the branches to main.
