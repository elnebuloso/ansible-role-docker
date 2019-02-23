# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).


## [4.1.0] - 2018-02-24
### Changed
- download package if not downloaded before


## [4.0.0] - 2017-12-03
### Changed
- Install Docker Package
- Removed Installation of Docker Compose, use ansible-role-docker-compose
- Removed Installation of Docker PIP, use ansible-role-docker-pip


## [3.0.0] - 2017-09-28
### Changed
- choosable docker version
- choosable install of docker-compose
- choosable install of docker python


## [2.10.0] - 2017-07-27
### Changed
- renamed server_base_os to docker_os
- optimized docker install, using os variables


## [2.9.0] - 2017-04-22
### Changed
- check server_base_os is defined
- uninstalling python docker-py


## [2.8.0]
### Added
- python docker

### Changed
- bugfix latest docker-compose to version number


## [2.6.0]
### Changed
- removed installation docker_install_linux_image_extra
- added config setting for docker-py installation


## [2.5.0]
### Changed
- install docker-compose


## [2.4.0]
### Changed
- new config docker_install_linux_image_extra


## [2.3.0]
### Changed
- removed pip for docker tools, use role elnebuloso.pip


## [2.2.0]
### Changed
- upgrade to latest pip


## [2.1.0]
### Changed
- pip install docker compose


## [2.0.0]
### Changed
- supporting ubuntu 16.04 xenial


## [1.3.0]
### Changed
- os specific configuration
- ubuntu14 specific configuration


## [1.2.1]
### Changed
- updated documentation


## [1.2.0]
### Changed
- python-pip
- docker-py


## [1.1.0]
### Changed
- different bugfixes
- documentation


## [1.0.0]
### Changed
- initial commit