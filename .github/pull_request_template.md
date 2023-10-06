<!-- PULL REQUEST REQUIREMENTS FOR APPROVAL
* **Title format**: <Short description>
    * Default title based on Issue title can be sufficient if the Issue was named succinctly and appropriately
* Appropriate tags / attributes added along right-hand side of pull request
    * **Reviewers**: Add at least 2 reviewers
    * **Assignees**: Assign person who is responsible for finalizing the PR and resolving comments
    * **Label**: Add appropriate descriptors
    * **Projects**: GeoIPS - All Repos and All Functionality
        * Other projects allowed as appropriate
* Ensure Related Issue is finalized appropriately (follow link below)
--->

# Reviewer Checklist

PR author: Please ensure you meet all of the below requirements, and check boxes appropriately.

Reviewers: Please confirm all required testing/documentation has been completed prior to approving.

**Remove lines that are not applicable, explain if you select NOT REQUIRED**

* [ ] Required ***existing tests*** pass (ie full_test.sh, others as appropriate)
* [ ] ***existing tests*** NOT REQUIRED (explain why not required)
* [ ] Required ***unit tests*** added and pass for new/modified functionality
* [ ] ***unit tests*** NOT REQUIRED (explain why not required)
* [ ] Required ***integration tests*** added and pass for new/modified functionality
* [ ] ***integration tests*** NOT REQUIRED (explain why not required)
* [ ] Required ***documentation*** added for new/modified functionality
* [ ] ***documentation*** NOT REQUIRED (explain why not required)
* [ ] Required ***release notes*** added for new/modified functionality
* [ ] ***release notes*** NOT REQUIRED (explain why not required)
* [ ] Required ***updates to other repos*** complete
* [ ] ***updates to other repos*** NOT REQUIRED (explain why not required)

https://github.com/NRLMMD-GEOIPS/.github/blob/main/.github/review-template.md

# Related Issues
fixes NRLMMD-GEOIPS/geoips#NNN
<!--- This can point to an issue in another repository if appropriate --->

# Testing Instructions
<!---
* Link to ticket with testing instructions
OR
* Note that no exhaustive testing is required (if you have sufficient output below to demonstrate success, and it will be fully tested with next release)
OR
* include testing instructions directly here if appropriate
--->

# Summary
<!---
* COPY AND PASTE your CHANGELOG update here as summary bullet points
* NOTE Pull request WILL NOT be approved without appropriate updates added to the
  CHANGELOG

  * Please see
    https://raw.githubusercontent.com/NRLMMD-GEOIPS/geoips/main/CHANGELOG_TEMPLATE.rst
    for appropriate CHANGELOG update formatting
--->

# Output
<!---
* Optional output demonstrating functionality - command line or imagery output
* If there is any additional command line output you can copy/paste here to indicate the changes you made work as expected, please include
* Imagery output is EXPECTED for new or changed image products
    * Ideally include the least amount of formatting possible in test outputs
    * Clean imagery, no YAML metadata outputs, small representative sector
    * We want to minimize the dependencies that could cause test outputs to change
* Related Testing is EXPECTED for new image products
    * Create <repo>/tests/scripts/<testname>.sh
    * Update <repo>/tests/test_all.sh
--->
