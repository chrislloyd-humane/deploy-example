# Deploy Example

1. Merge queue auto lands code from prs to `dev`.
2. Bot PRs land automatically
3. PRs tagged with hotfix have higher priority
4. prs are squashed

Another backport test

```
curl -F 'data=@.mergify.yml' https://engine.mergify.io/validate/
```
