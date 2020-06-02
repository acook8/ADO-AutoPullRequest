# ADO-AutoPullRequest
An Azure Function that will create pull requests when a sprint ends

Every two weeks a sprint ends and we need to merge code from the Dev branch into the staging branch so last minute testing and development for the next sprint can happen at the same time. This Azure function will use Azure DevOps APIs to create the pull request
