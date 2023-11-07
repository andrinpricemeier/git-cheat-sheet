# List of useful commands

## Show where .gitconfig is

`git config --list --show-origin`

## Sign commit

`git commit -S -m "MSG"`

## Sign tags

`git tag -s MYTAG`
`git tag -v MYTAG`

## Only push tags that are annotated and reachable
## Pushes both commits and tags
## Keep lightweight tags for local dev to avoid clashes!
`git push origin --follow-tags`

### Don't use this!
`git push --tagz`

