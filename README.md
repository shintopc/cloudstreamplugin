# My Personal CloudStream Extensions

This repository packages the `.cs3` files supplied by the repository owner for CloudStream.

## Setup

1. Create a **public** GitHub repository (for example `my-cloudstream-plugins`).
2. Upload every file in this folder to the repository root, preserving the filenames.
3. Replace `shintopc/cloudstreamplugin` in both `repo.json` and `plugins.json` with your actual GitHub username/repository name.
4. Commit the changes to the `main` branch.
5. In CloudStream, open **Settings → Extensions → Add Repository**.
6. Paste this URL, replacing the username and repository:
   `https://raw.githubusercontent.com/shintopc/cloudstreamplugin/main/repo.json`

CloudStream's repository manifest points to `plugins.json`, which lists each `.cs3` package and its SHA-256 hash.

## Included packages

- XXXTime
- xVideos
- XHamster
- Watchporn
- FreePornVideos
- BrazzPw
- Aagmaal

## Security

These `.cs3` files contain executable DEX code. Their archive structure and SHA-256 hashes were checked while assembling this repository, but the code itself has not been audited for safety. Only install extensions whose source you trust.

## Important

This is a static package repository, not source code for the extensions. The uploaded `.cs3` packages are redistributed byte-for-byte without modification. Confirm you have permission to redistribute them before making this repository public.
