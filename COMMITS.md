# TNG Commit Message Styleguide
This is a streamlined and modified version of [Angular's guide](%22https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit-message-header%22).

## Commit Message Header
\<type\>(\<scope\>):\ <short summary\>
  │       │             │
  │       │             └─⫸ Summary in present imperative. Not capitalized. No period at the end.
  │       │
  │       └─⫸ Commit Scope: Optional, lower-case name of the feature or functionality. 
  │				E.g. puzzle|caching|memory-match. (this differs from Angular)
  └─⫸ Commit Type: build|ci|docs|feat|fix|perf|refactor|test

Note that the summary line in the header should use the imperative. So use 'add component' not 'added component' or 'adds component'.

The logic behind this is that the header summary tells one the effect of applying the commit. If you pull this commit, it will add component to your repo.

## Commit Message Body
Optional. If necessary, add additional context to explain why the change is being made. Note that the focus should not be on 'how' the change was made. One can look at your code to see that. Use proper punctuation. Be as concise as possible.

## Commit Message Footer
If you would like to reference an issue in GitHub or a ticket number in from project management software, do so
in the footer. E.g.
```
Fixes #\<issue number\>
```

## Example Commit Message
```
feat(memory-match): Add dynamically generated menu

Replace previous hard-wired, fixed size menu and get data from API instead of locally.
```