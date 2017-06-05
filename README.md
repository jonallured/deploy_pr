# deploy\_pr

A simple script to automate the Artsy release branch based deployment workflow.
The script will find all the merged PRs that will be included in the deployment
and spit out their links. It then pauses to let you review those PRs and asks
you for a title. Finally, it will use [hub][hub] to create the deploy PR and
gives you a link to it.

## Install

The easiest way to install is via homebrew:

```
$ brew tap artsy/formulas
$ brew install deploy_pr
```

But as a simple script, it's also easy to just grab it and add to your PATH as
you see fit.
