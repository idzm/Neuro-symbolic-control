# Pull Request Template

## Title

Please provide a descriptive and succinct title for the pull request. It should summarize the primary change being introduced.

#### Example:
- **Good Title:** "Fix issue with user authentication"
- **Bad Title:** "Bug fix"

> [!TIP]
> A good title helps maintainers and other contributors quickly understand the purpose of the pull request. It should be specific enough to convey the change but also concise. Avoid using vague terms like "fix", "update", or "change" without context.

## Description

Please include a summary of the changes and the related issue. Include relevant motivation and context. List any dependencies that are required for this change.

#### Example:
> **Fixes #42: User Authentication Issue.**
> 
> **Description**: This pull request fixes issue #42, which was causing users to be unable to log in under certain conditions. The problem was traced to a missing validation check in the authentication logic. This fix adds the necessary validation and includes tests to verify the solution.
> 
> **Motivation and Context**: Users were unable to access their accounts, which affected their ability to use the application. This fix ensures that the authentication process works correctly, improving the overall user experience.
> 
> **Dependencies**: This change does not introduce any new dependencies.


> [!TIP]
> For example, if your pull request addresses issue number 42, you should write `Fixes #42`. This line is used to automatically close the referenced issue when the pull request is merged. This helps in managing issues and ensuring that resolved issues are properly closed.

## Type of change

Please delete options that are not relevant.

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update

## How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce. Please also list any relevant details for your test configuration.

- [ ] Test A
- [ ] Test B

**Test Configuration**:
* OS version:
* Hardware:
* TeX Engine:
* TeX/LaTeX distribution:

##  Checklist:

- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published in downstream modules
