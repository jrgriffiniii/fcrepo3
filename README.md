# Fedora Commons Repository 3
[![Docker Pulls](https://img.shields.io/docker/pulls/samveralabs/fcrepo3.svg?maxAge=604800)](https://hub.docker.com/r/samveralabs/fcrepo3)

Jump in: [![Slack Status](http://slack.samvera.org/badge.svg)](http://slack.samvera.org/)

_Please note that this was originally the work of [botimer](https://github.com/botimer) undertaken on behalf of the [Samvera Core Component Maintenance Working Group](https://wiki.duraspace.org/pages/viewpage.action?pageId=104569141)._

## Primary Contacts

### Product Owner
[James Griffin](https://github.com/jrgriffiniii)

## Help

The Samvera community is here to help. Please see our [support guide](./SUPPORT.md).

This Docker repository contains tagged images for the legacy Fedora 3 releases.  It should please be noted that Fedora 3 releases have reached the end of [their life cycle](https://github.com/fcrepo3/fcrepo). The last stable release was [3.8.1](https://github.com/fcrepo3/fcrepo/releases).

## Usage

To run a generic Fedora 3 server (unsecured and with the default administrator username `fedoraAdmin` and password `fedoraAdmin`), please execute the following:

```bash
docker run -ti -p 8983:8983 samveralabs/fcrepo3:VERSION
```

e. g.:
```bash
docker run -ti -p 8983:8983 samveralabs/fcrepo3:3.8.1
```

One may also pull the image directly from GitHub by invoking:

```bash
docker build -t="samveralabs/fcrepo3" github.com/samvera-labs/fcrepo3
```

## Acknowledgments

This software has been developed by and is brought to you by the Samvera community.  Learn more at the
[Samvera website](http://samvera.org/).

![Samvera Logo](https://wiki.duraspace.org/download/thumbnails/87459292/samvera-fall-font2-200w.png?version=1&modificationDate=1498550535816&api=v2)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/samvera-labs/fcrepo3

If you're working on PR for this project, create a feature branch off of `main`.

This repository follows the [Samvera Community Code of Conduct](https://samvera.atlassian.net/wiki/spaces/samvera/pages/405212316/Code+of+Conduct) and [language recommendations](https://github.com/samvera/maintenance/blob/master/templates/CONTRIBUTING.md#language).  Please ***do not*** create a branch called `master` for this repository or as part of your pull request; the branch will either need to be removed or renamed before it can be considered for inclusion in the code base and history of this repository.
