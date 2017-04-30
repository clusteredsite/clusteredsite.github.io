![Build Status](https://gitlab.com/clustered/clustered.gitlab.io/badges/master/build.svg)

---

This is the static website for Clustered Site, which is built using `jekyll`.

We build this automatically using CI pipelines, and host it with the following providers:

* GitHub Pages
* GitLab Pages

This is load balanced in round-robin via CloudFlare.

When updating the site, commits should be pushed to GitHub, then mirrored manually to GitLab via the `Sync Now` button here:

https://gitlab.com/clustered/clustered.gitlab.io/settings/repository

This will trigger a pipeline to build the updated pages.
