# Home Assistant External Logs App

[![Version][version-shield]][releases]
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Supports armhf Architecture][armhf-shield]
![Supports armv7 Architecture][armv7-shield]
![Supports i386 Architecture][i386-shield]
![Build][build-shield]
[![Github Sponsors][gh-sponsors-shield]][gh-sponsors]

This allows a `home-assistant.log` file to be written to any directory. The app
mounts network shares, so you can, for instance configure to write to a NAS
named `my_nas` with:

```yaml
directory: /share/my_nas
```

## Install

[![Add app repository to Home Assistant.][supervisor-add-badge]][supervisor-add-link]

[version-shield]: https://img.shields.io/github/v/release/wbyoung/ha-external-logs
[releases]: https://github.com/wbyoung/ha-external-logs/releases
[issue]: https://github.com/wbyoung/ha-external-logs/issues
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[armhf-shield]: https://img.shields.io/badge/armhf-no-red.svg
[armv7-shield]: https://img.shields.io/badge/armv7-no-red.svg
[i386-shield]: https://img.shields.io/badge/i386-no-red.svg
[supervisor-add-badge]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[supervisor-add-link]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fwbyoung%2Fha-apps
[build-shield]: https://img.shields.io/github/actions/workflow/status/wbyoung/ha-external-logs/ci.yaml
[gh-sponsors-shield]: https://img.shields.io/badge/GitHub%20Sponsors-grey?&logo=GitHub-Sponsors&logoColor=EA4AAA
[gh-sponsors]: https://github.com/sponsors/wbyoung
