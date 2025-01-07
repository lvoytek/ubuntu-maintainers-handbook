# Documentation triage

Documentation is hosted in [github](https://github.com/canonical/ubuntu-server-documentation)
and from there rendered to PDF and the online view at [Ubuntu Server docs](https://documentation.ubuntu.com/server).
This kind of structure gave us better interaction rates and contributions than
on Discourse, but to make them worthwhile we need to ensure we pick up and act
on what we get there

## Lists

For the daily triage rotation you only have to look at those issues or pull
requests created or updated in the time your duty covers.

- [Pull requests](https://github.com/canonical/ubuntu-server-documentation/pulls?q=is%3Apr+is%3Aopen+sort%3Aupdated-desc)
- [Issues](https://github.com/canonical/ubuntu-server-documentation/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc)

Check what the interaction is about and help them to progress and land or resolve.

## Tag usage in Doc triage

Right now we have a few tags defined that help us to quickly see in what state
an issue/PR was last time as well as later on allowing volunteers to better find
how they could help us.

* `tech-review` used by volunteer triagers, flagging that to go forward this needs a technical or even subject matter expert reviewer.
* `Open Documentation Academy`: used by triagers to declare a case as a good candidate to be resolved by volunteers of the Open Documentation Academy.
* `server:need-info`: to represent that this isn't actionable without further into being provided. This matches an incomplete state in [Bug triage](BudTriage.md).
* Classifiations like `code:*`, `content:*`, `dia:*` can be helpful to allow volunteers to more easily pick cases they can help with, adding them is optional
  * The use of those only makes sense once a case is actionable and ok for a volunteer to contibute
