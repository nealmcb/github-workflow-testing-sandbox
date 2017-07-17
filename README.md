# github-workflow-testing-sandbox
Explore the user interface and integration of github, pull requests, reviews, projects, etc.

## Code review via Pull requests and Comments on Commits

When trying to recover from a premature pull request, just changing a few lines of code in the file and reviewing those only allows commenting on 3 neighboring lines of code.

One workaround involves creating an "empty" branch and then creating a pull request to merge the desired branch into the empty branch:

* .py in the sky
 http://astrofrog.github.io/blog/2013/04/10/how-to-conduct-a-full-code-review-on-github/

That and other options and proposals for github enhancements are discusseed in these pages

* Provide line by line commenting, review, conversation tools in file (blob) view · Issue #211 · isaacs/github
 https://github.com/isaacs/github/issues/211

* Allow commenting on non-pull-request code · Issue #284 · isaacs/github
 https://github.com/isaacs/github/issues/284

Re:
> I don't see how this can be implemented: how to maintain the comment location after a file is modified across commits?

See google approach in one of those links.


## Related sandbox repos of possible interest
* [openmicroscopy/snoopys-sandbox: Test repository for the snoopycrimecop/snoopycrimecop code.](https://github.com/openmicroscopy/snoopys-sandbox)
* [openstack-dev/ci-sandbox: Sandbox for 3rd party CI systems](https://github.com/openstack-dev/ci-sandbox)
