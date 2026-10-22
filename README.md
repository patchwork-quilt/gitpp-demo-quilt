# gitpp-demo-quilt

**The git.pp dogfood project, hosted on GitHub.** The poc-quilt-1
record set — eight provenance-carrying records under
`.gitpp/records/` — whose derived state is `config.timeout = 45`,
decided by `override-1` ("captain: 45 is the safe value"), with
task-a, task-b and task-d preserved as losers.

This repo is the Mapping A transplant from the git.pp GitHub road:
the same records that live on the Cloudflare testbed, hosted here so
the **gitpp-app** GitHub App can be installed on it and exercised
end-to-end (webhooks in, derived state back as an advisory Check).

Family: [git.pp-ng](https://github.com/patchwork-quilt/git.pp-ng)
(the spec + engine) ·
[gitpp-action](https://github.com/patchwork-quilt/gitpp-action) ·
[gitpp-app](https://github.com/patchwork-quilt/gitpp-app)

Webhook loop test: 2026-10-21 — pushed to prove the gitpp-app receiver verifies and records deliveries.

Derivation-loop live proof: the gitpp-app should answer this push with a git.pp state Check.
