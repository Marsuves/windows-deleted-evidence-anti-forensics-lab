# GitHub Upload Steps

Recommended repository name:

`windows-deleted-evidence-anti-forensics-lab`

Recommended description:

`Windows 11 DFIR lab demonstrating deleted-file recovery, Recycle Bin artifacts, LNK analysis, SDelete execution, Prefetch, browser history, E01 imaging, and timeline reconstruction.`

## Before uploading

1. Copy your real `MASTER_SHA256.csv` and `WORKING_SHA256.csv` from `C:\DFIR_Lab\Hashes\` into this package's `hashes/` folder.
2. Do **not** copy the E01 or VMDK files into the repository. The included `.gitignore` is designed to block common forensic-image and VMware disk formats.
3. Open `README.md` locally and confirm the screenshots display correctly.

## Upload through GitHub.com

1. Sign in to GitHub and select **New repository**.
2. Repository name: `windows-deleted-evidence-anti-forensics-lab`.
3. Set visibility to **Public** if this is part of your job-search portfolio.
4. Do not initialize with another README, `.gitignore`, or license because this package already contains a README and `.gitignore`.
5. Create the repository.
6. Choose **uploading an existing file**.
7. Drag the contents of this package into the upload area. Preserve the folders: `screenshots`, `reports`, and `hashes`.
8. Commit message: `Add Windows deleted evidence forensic investigation lab`.
9. Click **Commit changes**.
10. Open the repository README and verify every image renders.

## Suggested GitHub topics

`digital-forensics` `dfir` `autopsy` `ftk-imager` `windows-forensics` `incident-response` `ediscovery` `sysinternals` `prefetch` `ntfs`

## Pin it to your profile

After publishing, open your GitHub profile, select **Customize your pins**, and pin this repository alongside your Apollo eDiscovery lab.
