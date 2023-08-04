<!--
Select all instances and replace the following with ticket details
- OLD_COMPONENT
- OLD_COMPONENT_FILE_PATH
- NEW_COMPONENT
- NEW_COMPONENT_FILE_PATH
- NEW_COMPONENT_README_LINK
- REPLACE_OLD_COMPONENT_GITHUB_ISSUE_LINK
-->

# Deprecate OLD_COMPONENT in favor of NEW_COMPONENT

### Description

To prevent further tech debt and inconsistencies `OLD_COMPONENT` can be deprecated in favor of `NEW_COMPONENT`

`OLD_COMPONENT` (old): `OLD_COMPONENT_FILE_PATH`
`NEW_COMPONENT` (new): `NEW_COMPONENT_FILE_PATH`

Add the deprecation JSDoc format below to the deprecated code

```
/**
 * @deprecated The `<OLD_COMPONENT />` component has been deprecated in favor of the new `<NEW_COMPONENT>` component from the component-library.
 * Please update your code to use the new `<NEW_COMPONENT>` component instead, which can be found at NEW_COMPONENT_FILE_PATH.
 * You can find documentation for the new `NEW_COMPONENT` component in the MetaMask Storybook:
 * {@link NEW_COMPONENT_STORYBOOK_DOC_LINK}
 * If you would like to help with the replacement of the old `OLD_COMPONENT` component, please submit a pull request against this GitHub issue:
 * {@link REPLACE_OLD_COMPONENT_GITHUB_ISSUE_LINK}
 */
```

### Technical Details

- Add deprecation message above old component function or class
- Create good first issue to replace all old components with new [Replace old OLD_COMPONENT component with new NEW_COMPONENT component](./REPLACE_MOBILE.md)

### Acceptance Criteria

- Old component has been deprecated (deprecation indicator shows up in VS Code)
- Good first issue has been created for the community to contribute to reducing tech debt and improving the UI consistency of MetaMask

If the acceptance criteria is not met, PRs may be closed.

### Difficulty: Intermediate

Good first issue for: External contributors who are able to run the extension locally, familiar with React Native, component props and proficient at searching a codebase
