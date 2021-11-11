---
name: Create new repo
about: 'Use #issueops to create a new repo in this org'
title: Create new repo
labels: issueops
assignees: ''

---

Fill out the form & submit to create a new repo!
---
body:
- type: input
  id: repo_name
  attributes:
    label: Repo name
    description: "Name of the new repo"
    placeholder: "Example: test-#"
  validations:
    required: true
- type: dropdown
  id: visibility
  attributes:
    label: Visibility
    description: What is the repo's visibility?
    multiple: false
    options:
      - label: public
      - label: private
      - label: internal
  validations:
    required: true
- type: checkboxes
  id: 
  attributes:
    label: Code of Conduct
    description: By checking this and creating the issue, you agree not to abuse the test automation available here.
    options:
      - label: I agree to follow this project's Code of Conduct
        required: true
