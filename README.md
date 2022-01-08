# `gh-complete-issue` GitHub CLI extension

## Installation

```
gh extension install clyer/gh-complete-issue
```

## Usage 

```
gh complete-issue {issue} {?comment}
```

Accept two parameters, the first is the issue number, and the second is the optional content to be commented on. It will assign the issue to the creator and add the `ready-for-testing` label. If there is a comment, then add comment the issue.