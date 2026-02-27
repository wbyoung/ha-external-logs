# Home Assistant External Logs App

[![Version](https://img.shields.io/github/v/release/wbyoung/ha-external-logs)][releases]
![Downloads](https://img.shields.io/github/downloads/wbyoung/ha-external-logs/total)
![Supports aarch64 Architecture][aarch64-shield]
![Supports amd64 Architecture][amd64-shield]
![Build](https://img.shields.io/github/actions/workflow/status/wbyoung/ha-external-logs/builder.yaml)
[![Github Sponsors](https://img.shields.io/badge/GitHub%20Sponsors-grey?&logo=GitHub-Sponsors&logoColor=EA4AAA)][gh-sponsors]

This allows a `home-assistant.log` file to be written to any directory. The app
mounts network shares, so you can, for instance configure to write to a NAS
named `my_nas` with:

```yaml
directory: /share/my_nas
```

[![Add app repository to Home Assistant.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fwbyoung%2Fha-external-logs)

[releases]: https://github.com/wbyoung/ha-external-logs/releases
[aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[gh-sponsors]: https://github.com/sponsors/wbyoung
