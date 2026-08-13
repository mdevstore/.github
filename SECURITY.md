# Security Policy

## Reporting a vulnerability

If you've found a security issue in an mdev resource - an exploit, a permission bypass, an unvalidated server event, or anything that lets a player do something they shouldn't, **please don't open a public issue.**

Report it privately instead:

- Open a private security advisory on the relevant repository, or
- Contact a member of staff directly in the [Discord](https://discord.gg/mdevstore)

Include the resource name and version, what the issue allows, and reproduction steps if you have them. Proof-of-concept code is welcome but not required.

## What to expect

You'll get an acknowledgement within a few days. Confirmed issues are patched and pushed to Tebex as a version update, with a note in the changelog describing the fix in general terms.

If you'd like credit in the changelog, say so in your report, otherwise reports are handled anonymously.

## Scope

This policy covers resources published by md-dev. It does not cover:

- Vulnerabilities in FiveM itself - report those to [Cfx.re](https://forum.cfx.re)
- Vulnerabilities in third-party frameworks (QBCore, ESX, ox_core) - report those to their maintainers
- Server misconfiguration or issues caused by modified resource code

## Please don't

Test exploits on live servers you don't own. Use a local test server.
