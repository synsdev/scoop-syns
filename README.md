# synsdev/scoop-syns

Scoop bucket for the [syns CLI](https://github.com/synsdev/syns-cli).

Auto-bumped on every `synsdev/syns-cli` release by the `scoop-bump.yml` workflow in `synsdev/syns-cli`.

## Usage

```powershell
scoop bucket add syns https://github.com/synsdev/scoop-syns
scoop install syns
```

(Currently requires the upstream `synsdev/syns-cli` repository to be public for the `scoop install` step to fetch the release zip. The bucket manifest itself is public.)
