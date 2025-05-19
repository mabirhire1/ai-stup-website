### GIT BRANCHING AND MERGING

## 1. Initial Repository Setup
![Initial Repository](img/screenshot1-initial-GitHub-repository.png)

## 2. Create Branches for Team members 
![Multiple Branches](img/screenshot2-multple-branches.png)

## 3. Initiate Pull Request for Tom's Branch
![Initiate PR](img/screenshot3-initiate-pull-request.png)

## 4. Create Pull Request for Tom's Branch 
![Create PR](img/screenshot4-creation-of-pr-for-Tom.png)

## 5. Review PR
![PR Review](img/screenshot5-comments-and-review-on-pr.png)

## 6. Make Requested Changes
![Requsted Changes](img/screenshot6-additional-commits-addressing-feedback.png)

## 7. Approve and Merge the PR on GitHub
![Merge Confirmation](img/screenshot8-Tom's-pr-merged.png)

## 8. Update Local Main
![Updated Local Main](img/screenshot9-terminal-showing-updated-main-after-merge.png)

## 9. Conflict Resolution
![Resolve Conflict](img/screenshot10-resolve-conflicts.png)

## 10. Synchronizing Jerry's Branch with Main
![Feedback Addressed](img/screenshot11-commits-addressing-feedbacks.png)

## 11. Create PR for Jerry's Branch on GitHub
![Create PR](img/screenshot12-create-pr.png)

## 12. Add Review Comments
![Review Comments](img/screenshot13-review-comments.png)

## 13. Address PR Feedback in Jerry's Branch
![PR Feedback Commit](img/screenshot14-commits-addressing-feedbacks.png)

## 14. Approve and Merge Jerry's PR
![Merge PR](img/screenshot15-reviewed-pr-merged.png)

## 15. Verify Final State of Main Branch
![Updated Main Branch](img/screenshot16-final-content.png)

## 16. Repository Structure on GitHub Showing Merged Branches
![Project History](img/screenshot17-history-of-merged-branches.png)

---

## Challenges Faced & Resolutions

| Challenge                         | Description                                                       | Resolution                                                        |
|----------------------------------|-------------------------------------------------------------------|-------------------------------------------------------------------|
| Committing to wrong branch       | Accidentally committed to `add-contact-info` instead of `main`    | Used `git checkout main`, ensured changes were in sync, then pushed correctly |

| Divergent branches error         | Got error while pulling: “need to specify how to reconcile”        | Used `git pull --rebase` to rebase instead of merge              |

| No upstream branch tracking      | Push error when branch wasn’t tracking remote                      | Used `git push --set-upstream origin add-contact-info`           |                    |

| Forgetting to switch branches    | Made edits in `main` by mistake                                    | Used `git stash`, switched to correct branch, then applied stash |
