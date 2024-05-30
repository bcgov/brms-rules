# BRMS Rules
This repository functions as a version management tool for the SDPR Business Rules Engine (BRE) and Business Rules Engine Management System (BRMS) Rules.

## How to Contribute

Please note that this project is released with a [Contributor Code of Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

Thank you for your interest in contributing to our repository! Follow the steps below to get started:

### 1. Sign Up for a GitHub Account

If you don't already have a GitHub account, you must [sign up for one](https://github.com/join).

### 2. Request Team Access

Request that a team member add you to the ISD-BRE team on GitHub. You can also [request approval through github directly](https://github.com/orgs/bcgov/teams/isd-bre). Once approved, you will be able to submit edits.

### 3. Switch to Desired Working Branch

Switch to the branch on which you would like to submit a change.

![Select working branch](./assets/gifs/switch-to-dev.gif)

### 4. Navigate to the Desired Folder

Navigate through the repository to the desired folder for the item you wish to modify: - Click on the `rules` folder. - Select the folder where the rule you would like to modify is currently located, or where would like to create a new rule. - Click on the `Add file` button located in the upper right of the screen, and proceed to the next step to upload the desired files.

![Navigate to folder for upload](./assets/gifs/navigate-upload.gif)

### 5. Upload Your File

Drag the changed or new file into the window, or select it using the file explorer.

![Drag file to upload](./assets/gifs/upload-file.gif)

### 6. Add a Commit Message

Add a short summary of the change as the header/title. This line should explain the commit in one line, using the imperative mood (e.g., "Add", "Fix", "Update", "Change", "Remove"), and should be less than 50 characters in length.

#### Examples:

- Add user authentication feature
- Fix typo in monthly benefit rule
- Remove deprecated benefit language

Add an additional extended description detailing the changes you have made.

![Add commit message](./assets/gifs/enter-commit-message.gif)

### 7. Create a Pull Request

1. Select `create a new branch for this commit and start a pull request`.
2. Title the pull request with your username, the category of the branch, and the name of the update in the format: `author-category-name`

#### Categories

| Category     | Meaning                                                                 |
| ------------ | ----------------------------------------------------------------------- |
| hotfix       | quick fixes to critical issues                                          |
| bugfix       | bugs fixes                                                              |
| policyupdate | adding, removing, or modifying a rule in alignment with a policy update |
| test         | experimenting with something                                            |
| wip          | a work in progress                                                      |

#### Example:

brysonjbest-policyupdate-test-text-insertion

3. Click the `Propose changes` button.

![Create new branch and pull request](./assets/gifs/create-branch-pull.gif)

### 8. Submit Pull Request

You will be presented with a final screen that shows the details of your request.

1. Confirm that the base branch selected (your desired working branch) is correct.
2. Confirm the title and description are correct.
3. Click the 'Create pull request' button to submit your request.

![Create new branch and pull request](./assets/images/submit-pull-request.png)

### 9. Notify a Maintainer

After making sure that your change request has been pushed through, send a message to one of the repository maintainers to get it double-checked, and if everything looks good, they will update the repository with your proposed changes.

Thank you for your contributions!


## License

```
Copyright 2024 Province of British Columbia

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
