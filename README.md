# OpenCannabis Project
![Version: V1](https://img.shields.io/badge/Version-V1-lightgray.svg?style=flat-square)
[![Status: Raw](https://img.shields.io/badge/Status-Raw-lightgray.svg?style=flat-square)](https://rfc.opencannabis.info/2/#Raw-Specifications)
[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg?longCache=true&style=flat-square)](https://www.gnu.org/licenses/gpl-3.0)
[![Code Climate](https://img.shields.io/codeclimate/maintainability/OpenCannabis/RFC.svg?style=flat-square&label=code%20quality)](https://codeclimate.com/github/OpenCannabis/RFC)
[![Travis branch](https://img.shields.io/travis/OpenCannabis/RFC.svg?style=flat-square)](https://travis-ci.org/OpenCannabis/RFC)



_OpenCannabis_ is a multilateral industrial effort to create an interoperable technical data specification tailored for
the **worldwide legal cannabis market**.

As legal markets to buy, sell, cultivate and manufacture cannabis products come online, a need is emerging for a
universal way of connecting data systems and components that work with cannabis or cannabis-related data.

#### Why write a spec?
Currently, the state of the art in cannabis technology is one of two options: Massive, sweeping ecosystems of
proprietary code (that frequently break), and isolated, SaaS-style startups that provide great tools but without the
ecosystem around them for maximal value.

Some business operators opt for the big players, and feel the pain when they go down. Others spread that pain out over
many smaller providers but both are still unhappy. What's the answer to fixing these problems?

An open specification, for cannabis data. For menus, transactions, customers, and so on - so that when one provider
isn't enough, or it's time to switch, or you want to write your own code - your data and your business aren't locked
away.

<div style="text-align:center;width:100%;">
<img align="center" src="https://storage.googleapis.com/ocs-media/backers-v4.png" alt="Spec Adopters">
</div>

### Authors and backers

OpenCannabis was conceived at [Bloombox](https://bloombox.io), but it's open and free to the world (under the GNU GPLv3
license). Early adopters and collaborators include industry players across the global cannabis supply chain, including
[Caliva](https://caliva.menu), [Nabis](https://www.nabisholdings.com), [GLH](https://chalicefarms.com) and
[Abatin Sacramento](https://abatinsacramento.com).

If you'd like to adopt the spec, or list yourself as a backer, file a pull request and we'll get you added!


| Contributor       | Website                                              | Category                                                           | Location                  |
|-------------------|------------------------------------------------------|:-------------------------------------------------------------------|:--------------------------|
| Cookies           | [cookies.co](https://cookies.co)                     | Cultivator, Retailer, Manufacturer                                 | San Francisco, California |
| Green Thumb       | [gtigrows.com](https://gtigrows.com)                 | Cultivator, Retailer, Manufacturer                                 | Chicago, Illinois |
| Golden Leaf       | [chalicefarms.com](https://chalicefarms.com)         | Cultivator, Retailer, Manufacturer                                 | Portland, Oregon |
| Caliva            | [caliva.menu](https://caliva.menu)                   | Cultivator, Retailer, Manufacturer                                 | San Jose, California      |
| Greendata         | [greendata.ai](https://greendata.ai)                 | Software Provider                                                  | San Francisco, California |
| Bloombox          | [bloombox.io](https://bloombox.io)                   | Software Provider                                                  | San Francisco, California |
| Abatin Wellness   | [abatinsacramento.com](https://abatinsacramento.com) | Retailer                                                           | Sacramento, California |


### Contributing

You can start contributing by sending a pull request to [OpenCannabis/RFC](https://github.com/OpenCannabis/RFC) on
GitHub. See [CONTRIBUTING.md](./CONTRIBUTING.md) for more information, including guidance on filing pull requests and
issues.

#### Contributor License Agreements (CLAs)

Each individual and corporate contributor must complete and sign a _Contributor License Agreement_ before contributions
may be accepted. This agreement stipulates that contributions to the _OpenCannabis Project_ are owned by the _Project_
and automatically made open source, among other things.

You can preview the CLAs in PDF form before signing. They very closely follow the Apache Foundation CLAs:
- [Individual Contributor License Agreement (ICLA)](./3/OpenCannabis-ICLA.pdf)
- [Corporate Contributor License Agreement (CCLA)](./3/OpenCannabis-CCLA.pdf)

### Guidelines

* Specifications **MUST** be created and modified by pull requests according to [RFC 1/C4](1/README.md)
* Specifications **MUST** follow the lifecycle defined in [RFC 2/COSS](2/README.md)
* Specifications **MUST** use a share-alike compatible license.
* Specifications **SHOULD** use [GPL v3]() or a later version of the license
* Specifications **SHOULD** use [RFC 2119](http://tools.ietf.org/html/rfc2119) key words.
* Specifications **MUST** be considered immutable, except for cosmetic changes, after exiting *Draft* status.

#### On the shoulders of giants

The OpenCannabis Specification and related materials are written with modern, cutting-edge tools. The project structure
is inspired by [Unprotocols RFC](https://github.com/unprotocols/rfc), which is a repository for universal, cross-project
protocols used in software development, ranging from workflow to technical.

The specification is codified in a series of documents - referred to as the "*Specification*," or "*Spec*," and a
software implementation, referred to as the "*Protocol*," which is written in
[Protocol Buffers](https://developers.google.com/protocol-buffers/), a language from Google. Other specifications
written in industrial circumstances have seen success with this exact model (see:
[OpenRTB](https://openrtb.github.io/OpenRTB/)).

## Copyright Notice

Copyright (©) 2019, the OpenCannabis Editor and Contributors. All rights reserved.

## License  [![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg?longCache=true&style=flat-square)](https://www.gnu.org/licenses/gpl-3.0)

This Specification is free software; you can redistribute it and/or modify it under the terms of the
[GNU General Public License](3/LICENSE.md) as published by the Free Software Foundation; either version 3 of the
License, or (at your option) any later version.

This Specification is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied
warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, see
http://www.gnu.org/licenses.
