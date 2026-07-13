# ingcreators Scoop Bucket

[Scoop](https://scoop.sh) manifests for [ingcreators](https://github.com/ingcreators) tools.

## Install

```powershell
scoop bucket add ingcreators https://github.com/ingcreators/scoop-bucket
scoop install tesseraql
```

## Apps

| App | Description |
|---|---|
| `tesseraql` | CLI for [TesseraQL](https://ingcreators.com/tesseraql), the SQL-first hypermedia application framework. Uses the Windows app image with a bundled Java runtime — no JDK required. |

## Updating

Manifests track the [GitHub releases](https://github.com/ingcreators/tesseraql/releases)
and carry `checkver`/`autoupdate` metadata, so `scoop update` follows new
tags once the manifest hash is bumped (or via an autoupdate workflow later).
