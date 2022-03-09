name: New Idea
description: Request to implement new capability on Core Engineering GKE Platform (will be prioritised
  at planning)
labels: [new-idea]
body:
  - type: textarea
    id: motivation
    attributes:
      label: Motivation
      description: Describe benefits of implementing this platform capability
      placeholder: Describe benefits of implementing this platform capability
    validations:
      required: true
  - type: textarea
    id: scope
    attributes:
      label: Scope
      description: Define scope of the new capability
      placeholder: Define scope of the new capability
    validations:
      required: false
  - type: textarea
    id: requirements
    attributes:
      label: Requirements
      description: List down success criteria to implement the capability
      placeholder: List down success criteria to implement the capability
    validations:
      required: true
  - type: textarea
    id: assumptions
    attributes:
      label: Assumptions (Optional)
      description: Describe any assumptions made for the delivery of the capability
      placeholder: Describe any assumptions made for the delivery of the capability
    validations:
      required: false
  - type: textarea
    id: dependency
    attributes:
      label: Dependencies (Optional)
      description: List of deliverables this issue depends on
      placeholder: List of deliverables this issue depends on
    validations:
      required: false
