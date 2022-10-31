# CONTRIBUTING.md

## Table of Contents
- [Making Changes](#Making-Changes)

# Claiming an Issue [Back to Top](#Table-of-Contents)
Here are the steps to claiming an issue:

### 1. Check for an Existing Issue/Create One!

Before you make changes. Look to see if there has already been an issue on this change. The maintainers may have already considered your change and opted against it or someone may already be working on a fix (in which you can offer to help them).

If you don't see an issue for this change, then create one. 

The issue text should do 2-4 things:

1. Explain the problem and it's impact
2. Gives steps to recreate the problem. This includes system settings if applicable
3. (Optional) Suggested Solution
4. (Optional) Are you interested in solving this issue? 

Here is an example for an issue suggesting that we implement Black to format code.
```
## Problem: Black suggests using double-qoutes. This also creates a style-guide standard of the strings should be in the `f"string {value['attr']}"` format.

Using Black to format will reduce the amount of work done solely on formatting code

### To Recreate the Problem
This is  addition so no recreated needed

### Suggested Solution
Implement Black in either CI/CD or in pre-commit

here is the code for black in pre-commit
\```
  - repo: https://github.com/psf/black
    rev: 22.10.0
    hooks:
      - id: black
        name: Format Python
        language_version: python3.10
\```

## Would you like to work on this change?
Yes 😄 
```
This makes it so that more than one person does not work on the same project at the same time (only one pull request will be accepted). 

### 2. Wait to be assigned to the Issue
There will like need to be some conversation about the issue and its solution. Wait until one of the maintainers have assigned the issue to you. This prevents people from working on the same projects without others knowing. If the project is already assigned and you want to work on it, then notify the assigned individual.

### step 3 fork the code [^Back to Top](#Table-of-Contents)
after one of the organizers has assigned you the issue for the code so that you may freely work on it within your own repository. 

Fork the code using the "Fork" button in the top-right corner.

### step 4 Make Changes on all Required and Test your Changes Locally [^Back to Top](#Table-of-Contents)

Don't just make the changes and hope things work. Add tests as necessary so that you know the changes will work as expected. There may be code coverage requirements.

### step 4 Submit a Pull Request [^Back to Top](#Table-of-Contents)
After the changes have been made (and tested) you may then submit a Pull Request (PR). This allows the orginizers to look over the changes either accept them or suggest new ones.  

[^Back to Top](#Table-of-Contents)

