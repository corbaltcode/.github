## PR Description
-- Enter your description here --

## PR Checklist
* [ ] **The code passes existing automated tests/coding style checks.**
* [ ] **New automated tests have been written to the extent possible.**

  There is always a trade-off between faster development time and increased automated testing, and not all automated testing is very valuable, so sometimes it is not worth writing a test. But it should always be considered and decided explicitly, not by default.
* [ ] **The code has been checked for structural/syntactic validity.**
	- AMI/application: a build was performed
	- terraform changes: "terraform plan" checked on every affected environment
* [ ] **The general purpose, structure, and flow of the code can be understood from looking at the code, PR description, and any linked design docs.
(If applicable) the code has been manually tested on our infrastructure.**
	- AMI/application: deployed an a test or dev environment
	- terraform changes: applied to test or dev environment
	- script: run against test or dev environment
* [ ] **Likely failure points and new functionality have been identified and tested manually.**
	Examples:
	- Application manually run in a way that triggers any new branches
	- AMI logged into and changes verified from login shell
* [ ] **Pull request description includes a description of all the manual steps performed to accomplish the above.**

  No need to describe automated testing since you can see that elsewhere in the PR.
