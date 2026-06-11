---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

name: 🐞 Bug report
description: Something in MaiD isn't working the way it should
title: "[Bug]: "
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to report a bug! Please
        [search existing issues](https://github.com/Australware/MaiD-Support/issues) first, it may
        already be reported.
  - type: input
    id: macos-version
    attributes:
      label: macOS version
      placeholder: "e.g. macOS 14.5 (Sonoma)"
    validations:
      required: true
  - type: input
    id: maid-version
    attributes:
      label: MaiD version
      description: Find it in **MaiD ▸ About MaiD**.
      placeholder: "e.g. 1.0.1"
    validations:
      required: true
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: What did you do, what did you expect, and what actually happened?
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to reproduce
      placeholder: |
        1. Open …
        2. Click …
        3. See …
    validations:
      required: false
  - type: textarea
    id: extra
    attributes:
      label: Screenshots or a sample file
      description: Drag in a screenshot or a small sample `.md` file if it helps. No private content needed.
    validations:
      required: false
