-----------------
Contributing Code
-----------------

Code contributions are welcome! Distributed Ledger is Apache 2.0 licensed and
accepts contributions via GitHub pull requests. When contributing code
please do the following:

* Fork the repository and make your changes in a feature branch. Please add a
  prefix to the branch name (XXXX-) where XXX is the Github bug or issue number.
* Please include unit and integration test changes.
* Please ensure the unit and integration tests run successfully. Both are run
  with `nose2`, but integration tests are run if the environment variable
  ENABLE_INTEGRATION_TESTS is set.

**Commit Guidelines**

Commits should have logical groupings. A bug fix should be a single commit.
A newfeature should be a single commit.

Commit messages should be clear on what is being fixed or added to the code
base. If a commit is addressing an open issue, please start the commit message
with "Fix: #XXX" or "Feature: #XXX".
This will help make the generated changelog for each release easy to read.

Also make sure that you run LINT prior to your commit.

**Pull Request Guidelines**

Pull requests can contain a single commit or multiple commits.
The most important part is that a single commit maps to a single fix.

Here are a few scenarios:

* If a pull request adds a feature but also fixes two bugs, then the pull
  request should have three commits, one commit each for the feature and two
  bug fixes
* If a PR is opened with 5 commits that was work involved to fix a single issue,
  it should be rebased to a single commit
* If a PR is opened with 5 commits, with the first three to fix one issue and
  the second two to fix a separate issue, then it should be rebased to two
  commits, one for each issue

Your pull request should be rebased against the current master branch. Please do
not merge the current master branch in with your topic branch, nor use the
Update Branch button provided by GitHub on the pull request page.

**Please Note** that if your contribution includes significant code, we may
require that you complete and sign a **Developer Certificate of Origin**
from the Linux Foundation. An example can be found here:
http://developercertificate.org/

**Merge Approval**

The maintainers of the repo utilize a "Looks Good To Me" (LGTM) message in the
pull request. After one or more maintainer states LGTM, we will merge your code.
If you have questions or comments on your code, feel free to correct these in
your branch through new commits.