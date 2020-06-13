## Build the demo
```
$ laravel new demo-laravel-actions
$ cd demo-laravel-actions
$ phpunit
```

## Initialize the repo
```
$ git init
$ git add .
$ git commit -m'install framework'
$ git remote add origin git@github.com:<user>/demo-laravel-actions.git
$ git push -u origin master
```

## In GitHub
* Click `Actions`
* Click `Set up this workflow` on the `Laravel` workflow
* Click `Start commit` in the upper right green box.
* In the `Commit new file` popup, select `Create a new branch for this commit and start a pull request`
* Click `Propose new file`

This will `Open a pull request` to include the `Laravel` workflow.

* Click `Create pull request`

Tests will start running. After a few moments they should complete with `This branch has no conflicts with the base branch`

* Click `Merge pull request`
* Click `Confirm merge`

Congratulations! You have added a workflow for `Laravel` in a new branch and successfully merged the new branch into master. This created a new commit to add the workflow and another commit to merge into master. The workflow will run `phpunit` tests on all pull requests and on push to master.
