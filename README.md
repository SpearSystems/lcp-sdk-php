# LCP PHP SDK (generated mirror)

**Do not edit here.** This repository is a generated mirror of
[`implementations/sdk/php`](https://github.com/SpearSystems/LCP/tree/main/implementations/sdk/php)
in [SpearSystems/LCP](https://github.com/SpearSystems/LCP).

It exists because Packagist only reads packages whose `composer.json` sits at the
repository root, and LCP keeps every SDK in one monorepo. Each LCP release tag is
mirrored here at the same tag name, so Composer resolves versions from these
tags.

## Install

```bash
composer require spearsystems/lcp-sdk
```

## How the mirror is produced

`.github/workflows/mirror.yml` checks out the LCP tag named in the run, copies
`implementations/sdk/php/` to the repository root, commits, and pushes the same
tag here. Run it from **Actions → Mirror PHP SDK from LCP → Run workflow** with
the LCP tag (for example `v1.1.1`).

Report issues against the source repository, not this mirror.
