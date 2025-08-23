# Contributing to *The Veil of Aether*

Thank you for your interest in contributing to the Veil of Aether! Please read the guidelines if you aren't yet familiar with them.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
  - [Reporting Problems](#reporting-problems)
  - [Suggesting Plot Elements](#suggesting-plot-elements)
  - [Submitting Changes](#submitting-changes)
- [Style Guide](#style-guide)
- [License](#license)

---

### Code of Conduct

We’re committed to creating a welcoming and respectful environment for everyone. All contributors are expected to:

- Be kind and constructive in all communications.

- Respect differing opinions and experiences.

- Avoid personal attacks, harassment, and discriminatory language.

see [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for more details. By participating in this project, you agree to uphold these standards.

---

### How to Contribute

#### Reporting Problems

If you encounter a problem or inconsistency, please check the [issues](https://gitlab.com/veil-of-asether/worldbuilding/-/issues) to see if it has already been reported. If not, you can report it by opening a new issue.

- Provide a **clear description** of the issue.
- If applicable, explain how you would recommend it be fixed

#### Suggesting Plot Elements

We welcome suggestions for new plot points, sidequests, dialogues, characters and more! If you have an idea, feel free to open a new issue with the label "Plot Addition Request".

- Explain in detail what this plot element is
- Describe how the plot element would add to the story
- Keep the plot element aligned with the vision and theme of *The Veil of Aether*.

#### Submitting Changes

We are happy to accept direct contributions! Here's how to get started:

Please note that this guide targets people less familiar with Git/GitLab and the command line

If you have any questions or problems, feel free to contact a maintainer.

1. **Fork** the repository
  - Click the button labeled "Fork" at the top right of the repository
  - Be sure to choose your username in the dropdown under "Project URL"
  - Don't change anything else here unless you know what you're doing
  - Click on "Fork project" at the bottom left
2. **Create a new branch** for your document or edit:
  - In your fork, click on "+" in the top right
  - Click "New branch"
  - Choose a name that describes your contribution (e.g. "improveCharacters")
3. **Make your changes**, following the style guide below.
  - Adding a new file
    - Click "+" in the top right, then "New file"
  - Editing an existing file
    - Navigate to the file you wish to edit, then click on it
    - Click "Edit" on the top right, then "Edit single file"
  - Use the web editor to make your changes
4. **Commit** your changes with a clear, descriptive message:
  - Once you're done editing, click "Commit changes"
  - Create a commit message that describes what you did
5. **Create a merge request** to the main repository. Be sure to explain what your changes do and why they are necessary.
  - Back in the main repository, click "Merge requests" in the sidebar
  - Click "New merge request"
  - Under "Source branch":
    - Change the field that says "veil-of-aether/worldbuilding" to your fork
    - Now make sure the second field has the name of the branch you created
  - Click "Compare branches and continue"
  - Create a title and description for your merge request
  - Click "Create merge request" at the bottom of the page

A maintainer will review your merge request

---

### Style Guide

To maintain consistency across the repository, please follow these style guidelines:

- **Documents**: We use Markdown for documents in this repository. If you don't know what that is, you can use [this guide](https://www.markdownguide.org/).
- **File Organization**: Please put files into appropriate directories (e.g. Characters or Battles)
- **Naming Files**: File names should be in all-lowercase [kebab-case](https://developer.mozilla.org/en-US/docs/Glossary/Kebab_case). The name should be the name of what it discusses, followed by the `.md` extension (e.g sword-of-elements.md).
- **File Structure**: Each file should start with a header 1 title (e.g. \# Elymion), followed if necessary by a title in quotes with header 2 (e.g. \#\# "Radiant Wisdom"), and the function, purpose, or occupation using header 3 (e.g. \#\#\# Elder of the Light Dragons), then a longer description of what it is/does.
- **Commit Messages**: Use clear, descriptive commit messages. Start with a short summary of the change, followed by a detailed explanation if necessary.
  
Example:
```bash
Expanded Evron's description

Gave Evron additional personality traits and quirks
```

### License

By contributing to ***The Veil of Aether*'s worldbuilding repository**, you agree that your contributions will be licensed under the [Creative Commons Attribution ShareAlike License 4.0](LICENSE).
