MusedBox Spec
------------

*Working Draft - 0.1*

**Introduction**
The MusedBox is a Raspberry-Pi running a customised Arch Linux distro that has the ability to:
- Serve web content via a WiFi network broadcast from a WiFi adapter connected to the Pi.
- Provide a [RESTful JSON API](https://github.com/asyrique/ourjson) that stores it's data in a Mongo database hosted on the box.
- **In Progress** An [RESTful asset storage service](https://github.com/asyrique/assetstore) that exposes an API similar to Amazon S3, and provides syncing capability with an online asset repository.
- **In Progress** A [remote management client](https://github.com/asyrique/et-ssh) running over WebSockets that allows remote orchestration debugging.
- **Planned** An admin UI that will allow on-the-fly configuration of the box, including WiFi network name and key, users, asset-syncing and "installing" apps.

# Hardware specs

* Model: Raspberry Pi 2 B+
* Processor: 1Ghz ARMv7 Broadcom SoC
* RAM: 1GB
* SDCard: 8GB (**standard**), expandable up to 32GB.
* Wifi radius: Tested up 30m (through walls), theoretically 100-150m
* Max Wifi clients: Tested up to 8 simultaneous clients. Theoretically 30++
* Power input: 5V, 2A micro USB.
* Things to note:
  - Wifi AP capability is activated out-of-the-box. Wifi client capability needs to be manually configured for now.
  - Ethernet connectivity works out-of-the-box.
  - Currently, the box is "shutdown" by unplugging the power. Once the admin interface is completed, shutdown will be via that interface instead.

# Documentation

*Coming soon*

In the meantime, check [here](https://github.com/asyrique/picake) for more technically-advanced documentation of the build-process.

# Known issues

*Coming soon*
