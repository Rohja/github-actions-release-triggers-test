# github-actions-release-triggers-test

With the trigger `created` ([see here](https://github.com/Rohja/github-actions-release-triggers-test/blob/e3e0e76d3ce17aeff34977a6c0b304ef45e9c65f/.github/workflows/test_release_triggers.yml#L3)):
 - The Action is not triggered when the release is published if the release is previously created as Draft.
 - The Action *IS* triggered when the release if directly published without a draft.

With the trigger `published` ([see here](https://github.com/Rohja/github-actions-release-triggers-test/commit/3edaf7b799761e8d1961431e18804ee4aa000a93)):
 - The Action is triggered when a release is published from a draft.
