<!-- 💖✨ PULL REQUEST CHECKLIST ✨💖 -->

Before setting your PR to "Ready to Review", please make sure everything is set. 📋 

- **Tags/Attributes** (on the right-hand side):
  - 👩‍💻👨‍💻**Reviewers**: Add at least 2 reviewers (or ask us on slack if you're new)
  - 😵‍💫 **Assignees**: Assign the person responsible for finalizing the PR and resolving comments (this is probably you!)
  - 🏷️ **Label**: Add appropriate descriptors
  - ✂️ **Projects**: Select GeoIPS - All Repos and All Functionality, and other Projects as appropriate

 
- **GitHub Actions will check that you have done the following:**:
  - 🧠  **Release note**: Add a release note using [brassy](https://github.com/biosafetylvl5/brassy)
  - 🧪 **Unit tests**: Make sure your PR does not reduce code coverage (add tests if you write new code)
  - 📝 **Write docs**: If you contributed, changed or deprecated a feature, document it!

- **Related Issue**:  
  Ensure the related Issue is properly linked and finalized (follow the instructions below) 🔗

Delete this section when you're done editing and change your PR to **"Ready to Review"**! 🌈🐱

---

## ✨ Summary

Please write a short summary of the changes you made - feel free to copy things from your YAML change log!

---

## ✅ Checklist for Reviewer Reference (filled out by PR Author)

- [ ] **Tests**: All tests and CI pass (e.g., full, base, extra, etc.)
    - [ ] **Full test**: Yes, full test *is passing*.
- [ ] **Integration Tests**: Integration tests added/updated for new/modified functionality *OR* no new functionality
- [ ] **Other Repos**: I have updated other repositories to handle this change *OR* my package doesn't impact other plugin packages.

For more details, please see our [review template](https://github.com/NRLMMD-GEOIPS/.github/blob/main/.github/review-template.md) 💌

---



## 🔗 Related Issues

- **Fixes:** `NRLMMD-GEOIPS/geoips#NNN`  
  <!-- You can point to multiple issues or issues in another repository if needed! -->

---

## 🧪 Testing Instructions

Let us know how to test/verify your changes if you need anything *beyond* running the integration and unit tests.

Keep it simple and clear—like an empty sky! ☀️

---

## 📸 Output 

### 🧪 SDemonstrate new test scripts operate as expected
- Command line outputs or imagery outputs demonstrating passed tests.
- For imagery outputs commited to the repository, include clean imagery using very small test sectors with minimal formatting (no extra YAML metadata, or extra image annotations!).
- If you've added new image products, remember to create tests in:
  - `<repo>/tests/scripts/<testname>.sh`
  - And update `<repo>/tests/integration/integration_tests.py`

### 🖼️ Pretty imagery demonstrating functionality

- You can drop "pretty" imagery outputs directly in this section - these are for reference only, and can be used to share the beauty of your updates with others! Imagery you drop directly in the PR can have any formatting you wish - the prettier the better.

### 🧙🔎 Image difference files

Sometimes matplotlib or numpy will cause very minor differences in image outputs, causing an updated image with no visible change within the github files changed tab
In these cases, it can sometimes be useful to drop the image diff output from the geoips run directly in this section (lives in tests/outputs/[folder]/diff_*)
These image diff outputs are a faded out version of the image, with bright red highlighting where there were changes in the image between the old and new version.

---

💖🌟🌎🌟💖
