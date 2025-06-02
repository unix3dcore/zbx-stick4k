# Xiaomi Mi TV Stick 4K Template for Zabbix

This is a Zabbix template for basic monitoring of the Xiaomi Mi TV Stick 4K (model MiTV-AYFR0), designed for use **without root access**.

## Features

- CPU frequencies
- Memory usage
- Network information
- Uptime and basic device status
- Partitions info (used/free/total/percent)
- No root required

## Triggers

![triggers](https://github.com/user-attachments/assets/53839680-6c80-4376-bb36-f812ae973c95)

## Graphs

![graphs](https://github.com/user-attachments/assets/91f63120-e9a0-444d-9db3-3e03a5ec96c7)

Tested on Zabbix **7.2.7**.

## Requirements

This template uses an **unofficial Zabbix agent for Android** created by regis (a.k.a. dentier).
More info and APK: [https://blog.damongeot.fr/unofficial-zabbix-agent-for-android/](https://blog.damongeot.fr/unofficial-zabbix-agent-for-android/)

## Installation

1. Install the Zabbix agent APK on your Android TV Stick.
2. Import `template_xiaomi_mitv4k.yaml` into your Zabbix server.
3. Link the template to your host.

> ⚠️ No additional macros or configuration are required.

## Author

Created by [f1x](https://github.com/unix3dcore)

## License

MIT — see [LICENSE](./LICENSE)
