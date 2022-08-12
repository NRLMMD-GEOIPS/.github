# Related Issue
fixes NRLMMD-GEOIPS/geoips#[XXX]

# Testing Instructions
* [ Link to ticket with testing instructions ]
* [ OR ]
* [ note that no exhaustive testing is required (if you have sufficient output below to demonstrate success, and it will be fully tested with next release) ]
* [ OR ]
* [ include testing instructions directly here if appropriate ]

# Summary
* [ COPY AND PASTE your CHANGELOG update here as summary bullet points ]
* [ NOTE Pull request WILL NOT be approved without appropriate updates added to the CHANGELOG ]
   * [ CHANGELOG updates should come before the most recent version header ]
   * [     a new version header will be added during the next version release cycle ]
   * [ Please see https://github.com/NRLMMD-GEOIPS/geoips/blob/dev/CHANGELOG_TEMPLATE.md ]
   * [     for appropriate CHANGELOG update formatting ]

# Output
* [ Optional output demonstrating functionality - command line or imagery output ]
* [ If there is any additional command line output you can copy/paste here to indicate the changes you made work as expected, please include ]
* [ Imagery output is EXPECTED for new or changed image products ]
* [ Related Testing is EXPECTED for new image products ]
    * [ Create <repo>/tests/scripts/<testname>.sh ]
    * [ Update <repo>/tests/test_all.sh ]
    
# Reviewer Checklist

### Ensure you are logged into GitHub

### Confirm all requirements are met for pull request
* Ensure appropriate / sufficient content
    * **Title format**: \<Short description>
    * **Included Issue**: Link to related Issue included at the beginning of pull request
    * **CHANGELOG updated**: Functionality included in pull request is ALSO referenced in CHANGELOG.md
    * **Demonstrated Testing**: Proper testing / output was demonstrated for functionality updates
    * **Included Outputs**: Imagery is included in "Output" section for new or changed product outputs (for reports!)
    * **Test Scripts/Outputs for New Functionality**: If new functionality is included in PR,
        ensure related test scripts and test outputs were included.
* Ensure all appropriate tags / attributes added along right-hand side of pull request
    * **Label**: Added appropriate descriptors
    * **Projects**: GeoIPS - All Repos and All Functionality
        * Other projects allowed as appropriate
* Ensure Related Issue is finalized appropriately (follow link above)
    
### Once all items in checklist have been confirmed:
* **Approve pull request**
    * Click "Files changed" tab
    * Click green "Review changes" button
    * Select "Approve" option
    * Add message if desired
    * Click green "Submit review" button
    * Project status will automatically be updated in Project "GeoIPS - All Repos and All Functionality" when pull request is approved.
