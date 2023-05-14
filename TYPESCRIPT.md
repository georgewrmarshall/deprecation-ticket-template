<!--
Select all instances and replace the following with ticket details
- COMPONENT_NAME
-->

# Migrate components to TS: COMPONENT_NAME

### Description

Migrate `COMPONENT_NAME` component in `ui/components/component-library` to TypeScript

### Technical Details

- Convert Objects in `SNAKE_CASE` to enums in `PascalCase` (name and keys. Values should remain as is)
- Ensure enum name is singular not plural e.g. `Size` not `Sizes`
- Update file name from `component-name.contants.js` to `component-name.types.ts` and add types
- Update file name from `component-name.js` to `component-name.tsx` and add types
- Update file name from `component-name.test.js` to `component-name.test.tsx`
- Update file name from `component-name.stories.js` to `component-name.stories.tsx`
- Update all instances of component objects to enums
- Update all documentation

### Acceptance Criteria

- Component has been converted to TypeScript
- Stories, documentation and tests have been updated inside of the `component-name` folder
- Before/After screen cast of component stories in storybook to show no visual regression after migration

If the acceptance criteria is not met, PRs may be closed.

### Difficulty: Intermediate

Good first issue for: External contributors who are familiar with TypeScript and want to contribute to improving the stability of the extension
