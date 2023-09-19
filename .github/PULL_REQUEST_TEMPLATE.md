## Summary of Changes
(Please provide a brief description of the changes in this pull request.)

## How to QA the Update
(Please provide links to the preview pages. If certain situations need to be reproduced, give detailed instructions on how to do so.)

## Additional Information
(Provide any other relevant information about this PR.)

### Pre-review Checklist
Ensure you've covered the following items before requesting a review:

- [ ] The UI matches the design mockup across **all viewports**.
- [ ] New feature or style works well on **all pages and websites** where the new code is implemented.
- [ ] All development **leftovers** like `console.log` have been removed.
- [ ] The website's **performance** has been considered. Ensure you've done a Pagespeed insights test if necessary.
- [ ] All TypeScript code has **adequately defined types**, avoiding `any` type that might be confusing.
- [ ] If the code is complex or not straightforward, it's **properly commented, or test cases are written** for clarity.
- [ ] Any necessary **documentation** and **tests** updates have been made.
- [ ] Your changes don't introduce any new warnings or errors.
- [ ] **Existing legacy code has been refactored** if any updates were made.
    - [ ] Unnecessary types have been deleted.
    - [ ] Redundant queries have been removed.
    - [ ] Superfluous CSS has been deleted.
    - [ ] Legacy buttons have been replaced with the new ones, if applicable.
