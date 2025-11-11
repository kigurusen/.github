# Contributing to Project Name

Thanks for your interest in contributing to my projects, it means a lot to me!  
If you have questions about anything, feel free to ask in my community spaces or message me directly.
The links are all on [my website][website].

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Reporting Bugs](#reporting-bugs) - tell me what went wrong and how to reproduce it
- [Suggesting Improvements](#suggesting-improvements) - share ideas that would make this project better
- [Submitting Changes](#submitting-changes) - add new features, fix bugs, clean things up, or just improve the documentation
- [Style Guides](#style-guides) for source code and commit messages

## Code of Conduct

By participating, you are expected to uphold the [code of conduct][coc].
Please report unacceptable behaviour directly to me via a method linked on [my website][website].

## Reporting Bugs

> ### Security Notice
>
> Never report security related issues in public spaces.
> Instead please message me directly and privately via a method linked on [my website][website].

### Before Submitting a Bug Report

- Make sure you are using the latest version
- Make sure your bug is really a bug and not an error on your side like a wider system issue
- Check if other people already reported this bug in the [project's issues][issues]
- Collect as much information about the bug as you can
  - Error messages, stack trace, and other error information
  - Version info, dependencies, your operating system, and other information that might be relevant (like "Version 1.0, Windows 11 25H2")
  - Your inputs and the expected and actual outputs
  - Is it reproducible in other versions or on other platforms?

### Submitting a Bug Report

1. Open a [new issue][newissue] using a fitting template
2. Use a clear and descriptive title
3. Provide as much context as you can
4. Describe how to reproduce the issue, if possible using a minimal example

Please keep the issue short and concise while providing as much detail as possible.

## Suggesting Improvements

### Before Suggesting Something New

- Make sure you are using the latest version
- Read the documentation to find out if your suggestion already exists somewhere
- Check the project's [issues][issues] if someone already suggested it
  - If yes, simply add a comment to the existing issue so we know people are interested in it
- Decide whether your suggestion fits the scope of the project

### Submitting a Suggestion

0. The best way to suggest something new is in my community spaces or by messaging me directly, consider doing that instead.
   You can find all the necessary links on [my website][website].
1. Open a [new issue][newissue] using a fitting template
2. Use a clear and descriptive title
3. Provide as many details as possible
4. Explain why the suggestion would be useful

## Submitting Changes

> ### Legal Notice
>
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the [project license][license].

### Before You Start

- Check for [open issues][issues] first
- Discuss your planned changes with me or other maintainers
- Be kind and constructive - we’re all here to learn and build together

### Working with Source Code

1. [Fork][fork] this repository and then clone it
2. To keep your fork updated, add this repository as an upstream remote

   ```sh
   # Add upstream remote
   git remote add upstream <project-link>

   # Update your fork
   git fetch upstream
   ```

3. Create a new branch using `git switch -c <new-branch-name> upstream/dev` | Follow the project's branching strategy as outlined in the [README][readme]
4. Make your changes
5. Add tests for your changes if applicable
6. Update the documentation if applicable

### Creating a Pull Request

1. Synchronize your fork with upstream
   ```sh
   git fetch upstream dev
   git rebase FETCH_HEAD
   ```
2. Fix any merge conflicts and test your changes thoroughly
3. [Open a pull request][pr] with a clear title and description
4. Make sure to [include any issues](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) your contribution resolves in the description

## Style Guides

### Code Style

Follow the style and formatting of the existing code as outlined in the project's [README][readme].
The configuration for the formatter is included in the repository and enabling `Format on Save` is recommended.

### Commit Messages

Commit messages should describe what your changes would do when merged, preferably using the format described in this section.

- The first line should be `[Module]: [Verb] [Change]`, preferably 50 characters or less.
  ```
  UI: Fix button alignment in context menu
  Gameplay: Increase input latency
  Settings: Add feature to disable settings
  ```
- Leave the second line empty to separate the "subject line" from the "body".
- Add any details and additional information starting on line 3.

[coc]: /CODE_OF_CONDUCT.md
[license]: /LICENSE
[readme]: /README.md
[issues]: ../../issues
[newissue]: ../../issues/new
[fork]: ../../fork
[pr]: ../../compare
[website]: https://kigurusen.github.com
