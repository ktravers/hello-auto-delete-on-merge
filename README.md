# hello-auto-delete-on-merge

In this repo, we auto-delete head branches on merge, even if the head branch is protected (because our branch protection rule allows deletion).

But if the branch protection rule doesn't allow deletion, then we respect the branch protection rules and do not auto-delete a protected branch on merge.

