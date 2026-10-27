# Application Releases

A shared distribution hub for installers and update files for the applications maintained by this project. Each application keeps its source code in its own repository; this repository contains release artifacts only.

## Download an app

Open the [Releases page](https://github.com/swamy-guruvelli/app-releases/releases), choose the release for the application and version you need, then download the installer for your operating system. You do not need Git to install or update an app.

Release notes should list the applications and versions included. Asset names identify the app and platform so the correct installer is easy to find.

## In-app updates

Applications may use the update metadata published with their release assets. Keep each app's metadata file, installer, and blockmap together for the same version. App-specific update channels must use distinct metadata names when they share this repository.

## Repository contents

- Installers and platform-specific packages
- Update metadata files such as `latest.yml`
- Blockmaps, checksums, and release notes needed by the updater

Source code, development builds, credentials, and unrelated project files belong elsewhere.

## Access

This repository is public, so anyone can view and download its releases. If visibility changes to private, repository permissions control manual downloads, and each app's updater must also be configured to authenticate. A private release feed may require app-specific credentials on each user's device.
