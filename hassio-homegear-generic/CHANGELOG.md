**Features**
- Latest homegear stable version included
- Updated image from debian buster (10) to bullseye (11)
- Support to run as different user - see config section (e.g. as root to be able to use spi devices)
- Possibility to use SPI-Devices [EXPERIMENTAL]

**Bugfixes**
- Fixed issues with uninstalling the extension
- Improved logging during startup

**Breaking changes**
- Removed i386 support
- It looks like homegear now starts the web ui on port 2004 per default. This does not have an effect on existing setups. For new setups it is recommended to follow these instructions to access the admin ui: https://github.com/devRoemer/hassio-homegear-generic/wiki/Accessing-the-admin-ui

Homegear stable 0.7.51-3497 (Februar 19, 2022)



