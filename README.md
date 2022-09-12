# Check git status

`git status`

# Git-branch-and-naming-conventions

### Branch Naming

Branches created should be named using the following format:
{story type}-{2-3 word summary}-{pivotal tracker id}
story-type - Indicates the context of the branch and should be one of:

- ft == Feature
- bg == Bug
- ch == Chore
- rf == Refactor
  story-summary - Short 2-3 words summary about what the branch contains
  Example
  ft-resources-rest-endpoints-111504508

### PR Naming

The PR title should be named using the following format: #[STORY_ID] Story description
Example
#111504508 Build out REST Endpoints for Resources (CRUD)

PR Description Template (Markdown)
The description of the PR should contain the following headings and corresponding content in Markdown format.

- What does this PR do?
- Description of Task to be completed?
- How should this be manually tested?
- Any background context you want to provide?
- What are the relevant pivotal tracker stories?
- Screenshots (if appropriate)

Example
![alt text](https://bloomm-profile-image-test-upload.s3.eu-west-2.amazonaws.com/637985747136718226-Screenshot%202022-09-12%20at%2011.17.12%20AM.png)

Any line cannot be longer than 100 characters, meaning be concise.

` <type>(<scope>): <subject>``- <body> - <footer> `

`<type>` should be:

- feature
- bug
- chore
- release
- refactor
- documentation
- style
- test

`<scope>` should be something specific to the commit change. For example:

- flight
- fighting-style
- fan-base
- logo and so on.

`<subject>` text should:

- use present tense: "save" not "saved" or "saving"
- not capitalize first letter i.e no "Carry to safety"
- not end with a dot (.)

### Message body (optional) 

If a body is to be written, it should:

- written in present tense.
- include the reason for change and difference in the previous behaviour

### Message Footer 

This should be used for referencing the issues using the following keywords: Start, Delivers, Fixes and Finishes. it should be inside a square bracket.
Example:

```
[Start #345]
```

or in a case of multiple issues:

```
[Finishes #5438233, #5891837, #4988398]
```
