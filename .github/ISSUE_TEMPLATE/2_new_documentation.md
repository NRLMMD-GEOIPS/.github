---
name: New Documentation
about: Describe documentation to be created as we complete our documentation
labels: 'documentation'

---

# New Documentation (change this title)

### Documentation Task
* [ In a few words or a sentence, describe the documentation task. ]

### Files to be edited
* [ A list of the file/files that will be edited. ]

### Resources to be created
* [ List any resources you will need to create for this task including images, flow charts, etc. ]

### Related Documentation

### Scope of Documentation
* Does NOT include
     - How to act on Github
     - How to use ``git``
* Does include
     - How to check if a feature is being worked on already
     - Who to contact with questions
     - Here is an example page: `Kubernets <https://kubernetes.io/docs/contribute/>`_

### Checklist for Completion
* [ ] Work done on a feature branch, eg. documentation-adding-functionality
* [ ] Write the required documentation in RST.
* [ ] Add any required resource files to a sub-folder
* [ ] Run `./docs/build_docs.sh html_only` to ensure the documentation builds correctly, inspect the result, and edit as required to achive a well formatted document.
* [ ] Update the relevant release notes.
* [ ] Readable and followable writing, please use a grammar checker + spell checker
* [ ] Passes doc8 checks, see the [sphinx RST Primer](https://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html#restructuredtext-primer>) and checkout this black-like tool @biosafetylvl5 wrote for auto-formatting RST files: [pink](https://github.com/biosafetylvl5/pinkrst/tree/main>)
* [ ] A PR from your feature branch to `main` 😊 with @biosafetylvl5 as a reviewer

