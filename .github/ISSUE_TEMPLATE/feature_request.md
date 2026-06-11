---
name: Feature request
about: Suggest an idea for this project
title: ''
labels: ''
assignees: ''

---

name: 💡 Feature request
description: Suggest an idea or improvement for MaiD
title: "[Feature]: "
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for the idea! Please
        [search existing requests](https://github.com/Australware/MaiD-Support/issues) first — if it's
        already there, a 👍 helps us prioritize.
  - type: textarea
    id: problem
    attributes:
      label: What problem would this solve?
      description: What are you trying to do that's hard or impossible in MaiD today?
    validations:
      required: true
  - type: textarea
    id: proposal
    attributes:
      label: What would you like to see?
      description: Describe the feature or change you have in mind.
    validations:
      required: true
  - type: textarea
    id: alternatives
    attributes:
      label: Alternatives or workarounds
      description: Anything you've tried, or other ways this could work.
    validations:
      required: false
