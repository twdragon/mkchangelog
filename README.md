# `mkchangelog`

`mkchangelog` is a helper Git utility that converts the commit history of the given Git repository (mainly the one versioned with tags) to a convenient Debian changelog file. This utility has no external dependencies as it is written in pure Bash, and it is intended to be included as a part of the packaging pipeline or CI that generates the Debian source package. Now this script is used to package [IPFS Kubo](https://github.com/ipfs/kubo/) in https://github.com/twdragon/ipfs-debian-pkg

## Usage

```bash
./mkchangelog [/path/to/changelog-file] [ \
    [distro-codename] \
    [package-codename] \
    [vendor-name] \
    [vendor-email] \
    [vendor-team-description] \
    [urgency-marker] ]
```
