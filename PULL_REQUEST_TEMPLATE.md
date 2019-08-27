## PR Description
-- Enter your description here --

## PR Checklist
* [ ] **New automated tests have been written to the extent possible.**
* [ ] **The code has been checked for structural/syntactic validity.**
	- AMI/application: a build was performed
	- terraform changes: "terraform plan" checked on every affected environment
* [ ] **(If applicable) the code has been manually tested on our infrastructure.**
	- AMI/application: deployed an a test or dev environment
	- terraform changes: applied to test or dev environment
	- script: run against test or dev environment
* [ ] **Likely failure points and new functionality have been identified and tested manually.**
	Examples:
	- Application manually run in a way that triggers any new branches
	- AMI logged into and changes verified from login shell
* [ ] **Pull request description includes a description of all the manual steps performed to accomplish the above.**
