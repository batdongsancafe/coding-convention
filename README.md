# coding-convention

This based on the consensus between devs.

## Requirements:

- 2 books require Finso devs must read it before.
    + *[Clean code by Robert C. Martin] (https://www.investigatii.md/uploads/resurse/Clean_Code.pdf)*
    + *[Effective Engineer: How to Leverage Your Efforts In Software Engineering to Make a Disproportionate and Meaningful Impact by Edmond Lau]*

- Please setup CI/CD before starting a new project.
- *[SOLID principles] (https://itnext.io/solid-principles-explanation-and-examples-715b975dcad4)*

## Common:

- Use gitflow to manage code. 
    + Basically, there are 2 branches: `master` and `develop`. `master` is used for production and `develop` for staging environment.
    + All your features must be created from the `develop` branch.
    + Once it's done, please create a pull request from your feature to the `develop` branch. The CI will run automatically. 
    + Assign a reviewer for your pull request.
- The code must be tested. 
- Remove redundant code.
- Remove duplication code.
- Remove rem code.
- Meaning function or method name.

## Office 365:


## Golang:
- https://github.com/uber-go/guide/blob/master/style.md
