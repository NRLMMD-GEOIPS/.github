    # # # Distribution Statement A. Approved for public release. Distribution unlimited.
    # # #
    # # # Author:
    # # # Naval Research Laboratory, Marine Meteorology Division
    # # #
    # # # This program is free software: you can redistribute it and/or modify it under
    # # # the terms of the NRLMMD License included with this program. This program is
    # # # distributed WITHOUT ANY WARRANTY; without even the implied warranty of
    # # # MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the included license
    # # # for more details. If you did not receive the license, for more information see:
    # # # https://github.com/U-S-NRL-Marine-Meteorology-Division/


# v1.6.0: 2022-11-28, open source release
## GEOIPS#119: 2022-11-28, open source release
* Update VERSION to 1.6.0


# v1.5.2: 2022-09-15, clean up ISSUE_TEMPLATEs

## GEOIPS#75: 2022-09-15, clean up ISSUE_TEMPLATEs
### Documentation Updates
#### **.github/ISSUE_TEMPLATE/standard_issue_template.md**
* Update checklist to actually use valid checkboxes in the template
#### **.github/RELEASE_TEMPLATES**
* Moved all release templates here for the time being.
* May eventually make them more easily accessible.
* Crowds the Issue Templates prompt if we have all 5 different version release templates included:
    * **.github/RELEASE_TEMPLATES/developmental_update.md**
    * **.github/RELEASE_TEMPLATES/internal_release.md**
    * **.github/RELEASE_TEMPLATES/open_source_delivery.md**
    * **.github/RELEASE_TEMPLATES/open_source_incoming.md**
    * **.github/RELEASE_TEMPLATES/version_release_template.md**

        

# v1.5.2.dev2: 2022-09-05, simplify PR template

## No PR: 2022-09-05, minor updates
### Documentation Updates
* MODIFIED: **.github/review-template.md**
    * Update to include bullet for reviewing "Files changed"
    * Update to allow one or more Issue(s) linked in PR
* MODIFIED: **.github/pull_request_template.md**
    * Update from Added to Add in PR instructions
* NEW: **.github/ISSUE_TEMPLATE/dev_update.md**
    * Add "dev_update.md" Issue template for github.com Developmental Updates

## GEOIPS#7: 2022-09-05, remove unused template
### Documentation Updates
* REMOVED: **testable_issue_template.md**: Remove from issue templates


# v1.5.2.dev1: 2022-08-16, simplify git workflow

## NRLMMD-GEOIPS/geoips#17: 2022-08-12, simplify PR template
### Documentation Updates
* **pull_request_template.md**
    * Move "Reviewer Checklist" to bottom of PR template
    * Remove <issue_id> and <reponame> from PR titles
        * Since PR contents are used directly in squashed commit messages, shorten PR title
    * Remove large instruction blocks
    * Remove example formats from Reviewer Checklist (title and issue)

## NRLMMD-GEOIPS/geoips#17: 2022-08-01, remove manual linking from github workflow
### Documentation Updates
* **pull_request_template.md**
    * Remove all "labeling" requirements on pull requests (rely on automatic linking when creating branches)
    * Update GEOIPS to NRLMMD-GEOIPS organization
    * Add test script / test output requirement to PR review approval


# v1.5.1: 2022-07-15, update prefix for distro statements on \*.md files to spaces

### Documentation Updates
* Update \*.md Distro statement headers to use 4 spaces prefix rather than ### (formatting improvement)


# v1.5.0: 2022-06-16, add requirements for open source release

### Documentation Updates
* Add VERSION file
* Add CHANGELOG.md

