1. Why is 'Squash and Merge' preferable over standard merge commits for small feature branches in team projects?

'Squash and Merge' is preferable because it's cleaner than other options. It can clean up temporary or work in progress commits and with smaller feature branches, it can create a simpler history to review.

2. Describe the difference between 'Add single comment' and 'Start a review' on GitHub. Why is batching important?

Batching is important so as to not overwhelm the person with individual notifications for comments. Add a single comment will notify independently whereas Start a review will allow you to add all comment simultaneously.

3. How do Branch Protection Rules prevent accidental production breakage?

Branch protection rules allow for stop points, so that the rest of the team can review code before it's commited to the main branch. This forces the team to double check code before finally commiting it.

4. When a remote conflict occurs in a PR, why is it better to merge origin/main into your feature branch locally rather than forcing a push?

It's better to merge origin/main into your feature branch so that you can properly review the differences. If you force a push, it might be rejected or create conflicts with existing main branch code.
