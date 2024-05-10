# .github

This is a special repository that can be used for a few GitHub features.

Example:
- https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile

## Renovate

It also contains our [shared Renovate bot preset](https://docs.renovatebot.com/config-presets/#github-hosted-presets).
To use the preset create a renovate.json file with this content:

```json
{
  "$schema": "https://docs.renovatebot.com/renovate-schema.json",
  "extends": [
    "local>stackabletech/.github:renovate-config"
  ]
}
```
