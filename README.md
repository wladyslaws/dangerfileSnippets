# dangerfileSnippets
This repository contains Dangerfile snippets with both straightforward and not-straightforward rules implemented in separate files.
## contributions are very welcome!
Just stick to simple rules below:) or if you want to change them, make a PR on readme:)
### naming
Name your snippet following this convention:
`whatRuleAchieves.rb`
### content
each file should contain only one separate rule with all the code necessary to perform it, use abstract names for variables. Code should be followed by detailed description of the rule and an empty line. Exempli gratia:
```
# Make it more obvious that a PR is a work in progress and shouldn't be merged yet

pr_title = github.pr_title
warn("PR is classed as Work in Progress") if pr_title.include? "[WIP]"
```