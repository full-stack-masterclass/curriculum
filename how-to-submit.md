# How to submit your weekly projects


## One time setup

1. Create a [fork](https://help.github.com/en/articles/fork-a-repo) of the project repository. the project repository is `https://github.com/full-stack-masterclass/fsm-projects-XYYYY` where X is `W`(Winter) or `S`(Summer) and `Y` the Year (e.g `https://github.com/full-stack-masterclass/fsm-projects-W2024` for 2024 Winter batch that starts from 07.01.2024 and ends 24.05.2024). Use `fork` option on the top right to do this.
2. Navigate to the URL of the cloned repository (it should be in your personal GitHub account, under "repositories").
3. Clone the repository.
4. Navigate to your repository folder.

## Every week

1. `git pull` on your main branch to get the latest version.
2. Create a new branch for each week you have a project assignment (with this format: `YOUR-GITHUB-USERNAME/weekN`). For example, for the assignment of week 2 for my username it will be: `Amzani/week2`
3. Complete your project
4. Create the commit (`git commit`). Make the commit message meaningful
5. Push the branch to your forked repository.
6. On the GitHub page of your forked repository, click on the `create pull request` button. Make sure the `base repository` is the `fsm-projects-XYYYY` repository, on branch `main`.
7. Give the pull request a title in the following format: `Assignment week N <Your name>` (N is week number)
8. Submit the pull request from your forked repository branch into the `main` branch.


# Assignments Review Process
 
## Review process

The mentors will place comments on your pull request. You have to adjust your work accordingly and reply on the feedback.


### Labels 
To help get a clear assignment status, mentors will use some labels on your PR.

| Label | Description |
| --- | --- |
|no label  |not reviewed yet   |
|Needs work   |reviewed, but you need to implement feedback  |
|Approved   |reviewed, and your assignment has been approved   |