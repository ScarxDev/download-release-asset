# GitHub Action - Download Release Asset

This GitHub Action helps download release asset from a private repository with personal access token.

# Usage

```
- name: Download Release Assets
  id: download_release_asset
  uses: noobly314/download-release-asset@v1
  with:
    owner: owner_of_repo
    repo: repo_name
    tag: tag_or_latest
    file: file_name
    auth: ${{ secrets.PERSONAL_ACCESS_TOKEN }}
```
