# Dune Assets

Static visual assets for the private Dune browser table.

This directory is meant to be pushed as a public GitHub repository and served through jsDelivr. The packaged handoff copy may not contain `.git`; initialize or clone the real repository before pushing updates.

## CDN URL

The game server can load these files through jsDelivr by setting:

```bash
ASSET_BASE_URL=https://cdn.jsdelivr.net/gh/Oasis7311/dune-assets@<commit-sha>/public
```

Current production commit:

```text
2ba71815d05dea50319f54c853d75417e5f9a505
```

## Sync From App

From the sibling `dune/` directory:

```bash
rsync -a --delete --exclude '.DS_Store' public/card-art/ ../dune-assets/public/card-art/
rsync -a --delete --exclude '.DS_Store' public/generated/ ../dune-assets/public/generated/
```

Then commit and push this repository, and update `ASSET_BASE_URL` to the new commit sha.

## Size Notes

GitHub warns on ordinary Git files over `50MiB` and blocks files over `100MiB`. Current files are well below that. If future assets include video, long audio, or large source images, use Git LFS or object storage instead of ordinary Git.
