# Contributing to Bluesky Projects

Each Bluesky repository has designated Maintainers (listed in the repository's
MAINTAINERS.md file). They determine the repository's process for accepting
contributions, articulated in the repository's CONTRIBUTING.md file.

Broadly, repositories should use one of the following workflows:

## Stable

* Every change should go through a Pull Request.
* The person submitting a Pull Request should not merge their own Pull Request.
* Proposed changes with a large impact---including changes that introduce
  new concepts, technologies or depenencies; alter the project's scope; or make
  significant backward-incompatible changes---should be left open for at least
  one week to allow time for comment, and review should be solicited from a
  broad range of Maintainers or Contributors who may have useful input on the
  impact of the change. It is to up a repositiory's Maintainers to judge how much
  review is needed for a given Pull Request.

## Experimental

Bluesky projects are typically public from the very first commit. In this
early stage, the Maintianers have complete discretion about what
if any review is needed. Changes may be pushed directly to the `main`
branch; pull request may be self-merged.


## Non-code repositories

Non-code repositories should select a workflow repository-by-repository basis that matches
the intended usage.

For example, changes to this repository will require approval of the Advisory Committee.  
On the other extreme we push to the default branch of the documentation hosting repository 
via automated tools on CI.

---
Licensed under the [CC-BY 4.0](https://creativecommons.org/licenses/by-sa/4.0/) License.
