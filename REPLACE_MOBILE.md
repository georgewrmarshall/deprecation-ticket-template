<!--
Select all instances and replace the following with ticket details
- OLD_COMPONENT
- OLD_COMPONENT_FILE_PATH
- NEW_COMPONENT
- NEW_COMPONENT_FILE_PATH
-->

# Replace deprecated OLD_COMPONENT component with NEW_COMPONENT from the component-library

### Description

Currently, mobile is using an outdated `OLD_COMPONENT` component, which needs to be replaced with the new `NEW_COMPONENT` component.

This is a massive undertaking by itself and assigning to a single contributor and creating a single PR would be too large. Smaller PRs can be submitted against this issue from multiple contributors to ensure easier review and gradual improvements.

### Technical Details

- Replace instances of `OLD_COMPONENT` component (`OLD_COMPONENT_FILE_PATH`) with `NEW_COMPONENT` component (`NEW_COMPONENT_FILE_PATH`)
- Component APIs are slightly different so ensure all props have been migrated appropriately

### Acceptance Criteria

- Instances of `OLD_COMPONENT` component are completely replaced with the new `NEW_COMPONENT` component
- The component APIs are updated to reflect the changes in the new `OLD_COMPONENT`` component and there is no functional changes or visual regression
- Each Pull Request (PR) should include **no more than 3 files**
- PR descriptions must adhere to the designated template, ensuring that all relevant sections are completed including before and after screenshots of UI.
- The code changes should pass Jest tests, e2e tests, linting, and Storybook without any errors.

If the acceptance criteria is not met, PRs may be closed.

### Difficulty: Intermediate

Good first issue for: External contributors who are familiar with running mobile locally, have knowledge of React Native, component props, Jest tests, linting, and Storybook, and want to contribute to improving the cohesiveness of UI in mobile
