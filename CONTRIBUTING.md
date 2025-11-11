# Contributing to my various projects

Thanks for your interest in contributing to my projects, it means a lot to me!  
If you have questions about anything, feel free to ask in my community spaces or message me directly.
The links are all on [my website][website].

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Reporting Bugs](#reporting-bugs) - tell me what went wrong and how to reproduce it
- [Suggesting Improvements](#suggesting-improvements) - share ideas that would make the project better
- [Submitting Changes](#submitting-changes) - add new features, fix bugs, clean things up, or just improve the documentation
- [Style Guides](#style-guides) for issues, commit messages, and source code.

## Code of Conduct

By participating, you are expected to uphold the [code of conduct][coc].
Please report unacceptable behaviour directly to me via a method linked on [my website][website].

## Reporting Bugs

### Before Submitting a Bug Report

- Make sure you are using the latest version
- Make sure your bug is really a bug and not an error on your side, e.g. a wider system issue
- Check if other people already reported this bug in the [project's issues][issues]
- Collect as much information about the bug as you can
  - Error messages, stack trace, etc.
  - Versions of the project, its dependencies, your operating system, etc. depending on what seems relevant (e.g. "Version 1.0, Windows 11 25H2")
  - Your inputs and the expected and actual outputs
  - Is it reproducible in other versions or on other platforms?

### Submitting a Bug Report

> [!CAUTION]
> Never report security related issues in public spaces.
> Instead please message me directly via a method linked on [my website][website].

- Open a [new issue](../../issues/new) using one of the templates
- Provide as much context as you can
- Describe how to reproduce the issue, if possible using a minimal example

Please keep the issue short and concise while providing as much detail as possible.

## Suggesting Improvements

### Before Suggesting Something New

- Make sure you are using the latest version
- Read the documentation to find out if your suggestion already exists somewhere
- Check the project's [issues][issues] if someone already suggested it
  - If yes, add a comment to the existing issue
- Decide whether your suggestion fits the scope of the project

### Submitting a Suggestion

The best way to suggest new features is in my community spaces or by messaging me directly.
You can find all the necessary links on [my website][website].

[Github issues][issues] are an alternative or optional addition, and in some projects I'll create them once a feature is confirmed.

- Use a clear and descriptive title
- Provide as many details as possible
- Explain why the suggestion would be useful

## Submitting Changes

> ### Legal Notice
>
> When contributing to one of my projects, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the [project license](../../LICENSE).

### Before You Start

- Check for [open issues][issues] first
- Discuss your planned changes with me or other maintainers
- Be kind and constructive - we’re all here to learn and build together

### Working with Source Code

1. [Fork](../../fork) the repository and then clone it
1. To keep your fork updated, add the current project as an upstream remote

   ```sh
   # Add upstream remote
   git remote add upstream <project-link>

   # Update your fork
   git fetch upstream
   ```

1. Create a new branch following the project's branching strategy as outlined in the [README][readme]
1. Make your changes
1. Add tests for your changes if applicable
1. Update the documentation if applicable

### Creating a Pull Request

1. Synchronize your fork with upstream
   ```sh
   git fetch upstream HEAD
   git rebase FETCH_HEAD
   ```
1. Fix any merge conflicts and test your changes thoroughly
1. [Open a pull request](../../compare) with a clear title and description

## Style Guides

### Code Style

Follow the style and formatting of the existing code as outlined in the project's [README][readme].
The configuration for the formatter should be included in the repository and enabling `Format on Save` is recommended.

### Commit Messages

Commit messages should describe what your changes would do when merged, preferably using the format described in this section.

The first line should be `[Module]: [Verb] [Change]`, preferably 50 characters or less.
If you're unsure about what to put as the module, feel free to ask.
Examples:

```
UI: Fix button alignment in context menu
Gameplay: Increase input latency
Settings: Add feature to disable settings
```

Leave the second line empty to separate the "subject line" from the "body".  
Add any details and additional information starting on line 3.

[coc]: ../../?tab=coc-ov-file
[readme]: ../../?tab=readme-ov-file
[issues]: ../../issues
[website]: https://kigurusen.github.com
