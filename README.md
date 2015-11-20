# gitlab-ci-bot
A GitLab bot enforcing code review of each Merge (Pull) Request.

Any change to the code in the MR resets the LGTM counter.

Particularly useful if you disable pushing to `master` and use [gitlab-nazi-git](https://github.com/michalrus/gitlab-nazi-git).

![Screenshot](/screenshot.png)
