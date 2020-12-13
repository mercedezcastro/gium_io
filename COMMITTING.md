When working on an issue, you must follow the following guidelines:

## Creating a branch
Each issue must be worked on in a separate branch from `master`. The format for naming the branch is as follows: `<label>`/`<issue number>`/`<short description>`

The label corresponds to the label that the issue was assigned. The issue number corresponds to the number of the issue. The short description is a short description (separated by hyphens "-", if needed) on what the issue is about. 

## Commit Message
Each commit must have a meaningful commit message that follows these formats:

#### Short Commit Messages
`<type>: <short description>`
#### Long Commit Messages
```
<type>: <short description>
<BLANK LINE>
<body of description>
```

### Allowed \<type\>s
* feat - feature; any change that adds functional code to the project
* fix - bug fix; any change that fixes a bug
* refactor - any change that refactors existing code
* style - any change that is formatting, missing semi colons, etc...
* build - any change that changes the setup of the project (ESLint, new dependencies, etc...)
* chore - any change that does not add any meaningful function to the project

### Multiple Types
Commits can have multiple types (changes). They must be formatted as such:

#### Short Commit Messages
```
<type>: <short description>
<type>: <short description>
...
```

#### Short and Long Commit Messages
```
<type>: <short description> // short commit
<BLANK LINE>
<type>: <short description> // long commit
<BLANK LINE>
<body of description>
<BLANK LINE>
<type>: <short description> // short commit
```
