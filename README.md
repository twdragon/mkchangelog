# `mkchangelog`

`mkchangelog` is the helper Git utility to convert the commit history of the given Git repository (mainly, the one versioned with tags) to the convenient Debian changelog file. This utility has no external dependencies as it is written in pure Bash, and it is intended to be included as a part of the packaging pipeline or CI that generates the Debian source package.

## Usage

```bash
./mkchangelog [/path/to/changelog-file] [ [distro-codename] [package-codename] [vendor-name] [vendor-email] [vendor-team-description] [urgency-marker] ]
```
