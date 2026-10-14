---
"@patternfly/elements": patch
---

Expose `@patternfly/elements/custom-elements.json` through the package exports map so tooling can resolve the published Custom Elements Manifest without accessing `node_modules` directly.
