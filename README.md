# Deploy Example

To try it out, create a new PR editing the README. It should automerge to `dev`, then create a new PR to merge to `prod`. That new PR will then be automerged while running deploy a deploy action.

## TODO

1. Merge queue auto lands code from prs to `dev`.
2. Bot PRs land automatically
3. PRs tagged with hotfix have higher priority
4. prs are squashed

## Notes

```
# Validate mergify config
curl -F 'data=@.mergify.yml' https://engine.mergify.io/validate/
```
Newchange
