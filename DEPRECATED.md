<!--
Select all instances and replace the following with ticket details
- OLD_COMPONENT
- OLD_COMPONENT_FILE_PATH
- NEW_COMPONENT
- NEW_COMPONENT_FILE_PATH
-->

# Deprecate OLD_COMPONENT in favour of NEW_COMPONENT

### Description

To prevent further tech debt and inconsistencies `OLD_COMPONENT` can be deprecated in favour of `NEW_COMPONENT`

`OLD_COMPONENT` (old): `OLD_COMPONENT_FILE_PATH`
`NEW_COMPONENT` (new): `NEW_COMPONENT_FILE_PATH`

### Technical Details

- Add deprecation notice to storybook
- Add deprecation message above old component function or class
- Create good first issue to replace all old components with new [LINK TO TEMPLATE TBC]()

### Acceptance Criteria

- Old component has been deprecated (deprecation indicator shows up in VS Code)
- Good first issue has been created for the community to contribute to reducing tech debt and improving the UI consistency of MetaMask

If the acceptance criteria is not met, PRs may be closed.

### Difficulty: Intermediate

Good first issue for: External contributors who are able to run the extension locally, familiar with React, component props and proficient at searching a codebase
