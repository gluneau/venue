# Venue

[![Waffle.io - Columns and their card count](https://badge.waffle.io/788f7f3e551eb1946976e0b26b0ef823.svg?columns=all)](https://waffle.io/Volentix/venue)

[![standard-readme compliant](https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square)](https://github.com/RichardLitt/standard-readme)
[![MIT](https://img.shields.io/github/license/mashape/apistatus.svg)](https://choosealicense.com/licenses/mit/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=102)

> A community engagement platform for the Volentix community

Venue is a platform which brings together members of the Volentix community to
facilitate distribution of VTX and thus grow the Volentix community.

Venue is a platform which brings together members of the Volentix community to
facilitate distribution of VTX and thus grow the Volentix community. This is
supported through:

* **Campaigns**: Users perform actions which earn them points, and users compete for
the most points. At the end of the campaign, a pool of VTX is split between the
competitors based upon how many points each person earns.
  * The first campaign is a signature campaign on the main Bitcoin Forum, known as
[Bitcoin talk](https://bitcointalk.org/). Users who maintain a Volentix signature earn
points for each post.
* **Bounties**: Work which is needed for Volentix projects is posted to Venue, and members
can accept and perform the work in exchange for a reward of VTX. This is the next main
feature to be added to Venue
* **News**: News relevant to the Volentix community will also be posted on Venue.

For deployment, we are using:
  * [Docker](https://www.docker.com/)
  * [CircleCi](https://circleci.com/)
  * [Kubernetes](https://kubernetes.io/)

The actual code is stored in sub-repositories:
* [Venue client](https://github.com/Volentix/venue-client)
* [Venue server](https://github.com/Volentix/venue-server)

We track all work in [waffle](https://waffle.io/Volentix/venue). This board contains issues
from all 3 repositories.

## Table of Contents

- [Install](#install)
- [Usage](#usage)
  - [Running](#running)
  - [Building](#building)
- [Maintainers](#maintainers)
- [Contribute](#contribute)
- [License](#license)

## Install

1. Install the [Venue server](https://github.com/Volentix/venue-server#install)
2. Install the [Venue client](https://github.com/Volentix/venue-client#install)

## Usage

1. Start the [Venue server](https://github.com/Volentix/venue-server#usage)
2. Start the [Proxy server](https://github.com/Volentix/venue-client#proxy)
3. Start the [Venue client](https://github.com/Volentix/venue-client#usage)

## Maintainers

[@shawnlauzon](https://github.com/shawnlauzon)

## Contribute

Venue is a project which was originally created by Volentix Labs, but is owned and
maintained by the Volentix community. We actively support and appreciate anyone
who wants to improve this or any project within the community.

See [CONTRIBUTING.md](https://github.com/Volentix/volentix/blob/master/CONTRIBUTING.md)

Small note: If editing the README, please conform to the [standard-readme](https://github.com/RichardLitt/standard-readme) specification.

## License

MIT © 2018 Volentix Labs Inc
