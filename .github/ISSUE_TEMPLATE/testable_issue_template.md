#### # # Distribution Statement A. Approved for public release. Distribution unlimited.
#### # # 
#### # # Author:
#### # # Naval Research Laboratory, Marine Meteorology Division
#### # # 
#### # # This program is free software:
#### # # you can redistribute it and/or modify it under the terms
#### # # of the NRLMMD License included with this program.
#### # # 
#### # # If you did not receive the license, see
#### # # https://github.com/U-S-NRL-Marine-Meteorology-Division/
#### # # for more information.
#### # # 
#### # # This program is distributed WITHOUT ANY WARRANTY;
#### # # without even the implied warranty of MERCHANTABILITY
#### # # or FITNESS FOR A PARTICULAR PURPOSE.
#### # # See the included license for more details.

---
name: Standard testable issue
about: Required update including template for issue resolution as well as description
title: ''
labels: ''
assignees: ''

---
# Requested Update

### Description
  [ In 2-3 sentences briefly describe the required bug fix or feature with this issue. ]

### Environment
  [ IF APPROPRIATE: Corresponding repository versions ]

### Details
  [ OPTIONAL: Provide additional detailed information ]

### Code to reproduce issue
  [ IF APPROPRIATE: See "Testing Instructions" below for fully reproducible test output - ]
  [      can include steps here to produce the error if appropriate ]

# Resolution
  [ The following information should be included with the issue once all repos are ready for approval/merge ]
  [ There may be more than one related repo - they should all be approved / merged as a group ]
  [ Once all issue requirements are met, update the ticket with the following information ]
  [ Then all associated pull requests can be approved and merged ]

## Details

This functionality is ready for review and approval - all tests successfully returned 0.

  [ Copy and paste output of successful test commands ]

### Associated pull requests that should be merged with this approval are labeled with issue number
Navigate to each associated pull request, review changes, and approve individually.
None will be merged until ALL are approved.

### Summary
  [ 2-3 sentence summary of the overll changes that were made to meet the requirements of the ticket ]

## Testing Instructions
  [ INCLUDE TESTING INSTRUCTIONS IF APPROPRIATE / REQUIRED, can point to exhaustive installation/test if appropriate ]

### Instructions to set up required packages from scratch
* [ https://<url>/repos/<package1>/browse/README.md ]
* [ https://<url>/repos/<package2>/browse/README.md ]
* [ https://<url>/repos/<package3>/browse/README.md ]


### Obtain the correct branch and reinstall all associated repos:
```
$GEOIPS_PACKAGES_DIR/geoips/setup.sh update_source_repo [package1] [BRANCH NAME]
$GEOIPS_PACKAGES_DIR/geoips/setup.sh update_source_repo [package2] [BRANCH NAME]
$GEOIPS_PACKAGES_DIR/geoips/setup.sh update_source_repo [package3] [BRANCH NAME]

$GEOIPS_PACKAGES_DIR/geoips/setup.sh update_test_repo [testrepo1] [BRANCH NAME]
$GEOIPS_PACKAGES_DIR/geoips/setup.sh update_test_repo [testrepo2] [BRANCH NAME]
    
$GEOIPS_BASEDIR/geoips_packages/[package1]/setup.sh install
$GEOIPS_BASEDIR/geoips_packages/[package2]/setup.sh install
```
  
### Obtain correct versions of all dependencies for consistent test outputs
```
$GEOIPS/setup.sh install
$GEOIPS/setup.sh install_cartopy_offlinedata
```
  

### Test the new functionality
```
$GEOIPS_BASEDIR/geoips_packages/[package1]/tests/test_all.sh
$GEOIPS_BASEDIR/geoips_packages/[package2]/tests/scripts/<script>.sh
```
  [ Include output indicating 0 returns ]
