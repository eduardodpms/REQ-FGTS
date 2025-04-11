---
name: Documentation Issue
about: Report errors, suggest improvements in the documentation or new additions in
  documentations
title: "[Docs] <short summary of the issue>"
labels: documentation
assignees: ''

---

body:
  - type: markdown
    attributes:
      value: |
        Thank you for helping improve the documentation! Please provide as much detail as possible.

  - type: input
    id: location
    attributes:
      label: 📍 Location of the Issue
      description: |
        Where is the documentation problem? (File name, section, or URL if hosted online)
      placeholder: e.g., README.md, docs/setup.md, https://yourproject.github.io/docs/page
    validations:
      required: true

  - type: textarea
    id: description
    attributes:
      label: 📝 Description of the Problem
      description: |
        Describe the issue. Is it a typo, outdated info, unclear explanation, or missing content?
      placeholder: Describe the documentation problem here...
    validations:
      required: true

  - type: textarea
    id: suggestion
    attributes:
      label: 💡 Suggested Fix or Improvement
      description: |
        If you have suggestions or can contribute a fix, please add them here.
      placeholder: I suggest updating the section to include...
    validations:
      required: false

  - type: dropdown
    id: urgency
    attributes:
      label: ⏱️ Urgency
      description: How urgent or critical is this documentation issue?
      options:
        - Low
        - Medium
        - High
    validations:
      required: true

  - type: checkboxes
    id: contribution
    attributes:
      label: 🙋‍♂️ Would you like to work on this issue?
      description: Let us know if you're interested in fixing it.
      options:
        - label: I’d like to open a PR to fix this
