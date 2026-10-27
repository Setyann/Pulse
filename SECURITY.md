# Security Policy

## Supported versions

Only the latest release receives security fixes. Older versions are not updated.

| Version | Supported |
|---------|-----------|
| 1.2.x   | Yes       |
| 1.1.x   | No        |
| older   | No        |

## What Pulse does with your data

Pulse plays music files stored on your device. It has no accounts, no servers
of its own and does not collect personal data. The only network request is the
check for new releases on GitHub, and the APK download when you choose to
update.

## Reporting a vulnerability

Please do not open a public issue for security problems.

Report them privately through GitHub: go to **Security** → **Report a
vulnerability** on this repository. Include:

- a description of the problem and its impact;
- the Pulse version and the Android version of your device;
- steps to reproduce, or a short proof of concept.

I will reply as soon as I can and will work with you on a fix before any public
disclosure. Good-faith research within this scope is welcome.

## Scope

In scope:
- issues that let another app or a malicious file access data it should not;
- problems with how the update check or the APK download is handled;
- issues with permissions requested by the app.

Out of scope:
- problems in Android itself or in other apps;
- social engineering;
- issues that require physical access to an already unlocked device.

## Signing keys

Release signing keys and passwords are never stored in this repository.
If you find a key or password in the code or its history, report it as above.
