# Privacy Policy

**Application:** rclone (personal Google Cloud OAuth client)
**Operator:** Waleed Ahmed
**Contact:** waleedjawad2020@gmail.com
**Last updated:** 8 November 2026

## What this application is

This is a personal OAuth client registered so that [rclone](https://rclone.org), an open source command line file sync tool, can access the operator's own Google Drive account.

It is not a product, a service, or an app offered to anyone else. It has exactly one user, the operator, and it runs on the operator's own computer.

## What data it accesses

When authorised, the application uses the Google Drive API to read and write files in the Google Drive account of the person who authorised it. This is the `https://www.googleapis.com/auth/drive` scope.

It accesses that data only to mount the Drive account as a folder on the operator's own machine, so files can be opened, edited and saved as if they were local.

## What data it collects, stores or shares

None.

- No file contents, file names or account information are transmitted to the operator or to any server the operator controls.
- No analytics, telemetry or logging of user data is performed.
- No data is sold, shared or disclosed to any third party.

All communication is directly between the rclone software running on the operator's own machine and Google's APIs. The OAuth token issued by Google is stored locally in the rclone configuration file on that machine and is never transmitted elsewhere.

Files that rclone caches while the drive is mounted are written to local disk on the operator's machine only.

## Retention

Because no data is collected, there is nothing retained. The locally stored OAuth token persists until it is revoked or replaced.

## Revoking access

Access can be withdrawn at any time from the Google account permissions page at https://myaccount.google.com/permissions, which immediately invalidates the stored token.

## Changes

Any change to this policy will be committed to this repository, and its history serves as the record of previous versions.

## Contact

Questions about this policy can be sent to waleedjawad2020@gmail.com.
