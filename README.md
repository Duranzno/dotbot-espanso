<h1 align="center">Welcome to dotbot-espanso</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0-blue.svg?cacheSeconds=2592000" />
  <a href="#" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-yellow.svg" />
  </a>
  <a href="https://twitter.com/duranzno_dev" target="_blank">
    <img alt="Twitter: duranzno_dev" src="https://img.shields.io/twitter/follow/duranzno_dev.svg?style=social" />
  </a>
</p>

> Install [espanso](https://espanso.org/) [packages](https://hub.espanso.org/) with dotbot
## Prerequirements

This plugin requires [`dotbot`](https://github.com/anishathalye/dotbot/) to be installed.

Also, at runtime this plugin requires `espanso` command to be installed.

## Installation

1. Run:

```bash
git submodule add https://github.com/duranzno/dotbot-espanso.git
```

2. Modify your `./install` with new plugin directory:

```bash
"${BASEDIR}/${DOTBOT_DIR}/${DOTBOT_BIN}" -d "${BASEDIR}" -p "${BASEDIR}/dotbot-espanso/espanso.py"  -c "${CONFIG}" "${@}"
```

## Usage

Add required packages to your [`install.conf.yaml`](/example.yaml):
```yaml
- espanso:
  - all-emojis
  - lorem
  - gitmojis
```
Available packages can be found on [the espanso hub](https://hub.espanso.org/)


## License

MIT. See [LICENSE](/LICENSE) for more details.

## Author

👤 **Alejandro Duran**

* Website: https://duranzno.now.sh
* Twitter: [@duranzno\_dev](https://twitter.com/duranzno\_dev)
* Github: [@duranzno\_](https://github.com/duranzno)
* LinkedIn: [@duranzno](https://linkedin.com/in/duranzno)

## Show your support

Give a ⭐️ if this project helped you!

***
_This README was generated with ❤️ by [readme-md-generator](https://github.com/kefranabg/readme-md-generator)_
