
[![Travis branch](https://img.shields.io/travis/lacrossefootwear/magento2-theme-blank-sass/master.svg)](https://travis-ci.org/SnowdogApps/magento2-theme-blank-sass)

SASS based version of Magento 2 Blank theme, which aims to be as close to the core code as possible.

## Installation
1. Add this repo to your project repositories `composer config repositories.theme-blank-sass vcs https://github.com/lacrossefootwear/magento2-theme-blank-sass`
2. Add this to your project dependencies list `composer require lacrossefootwear/theme-blank-sass`
3. Set you application to `developer` mode
4. Run `bin/magento setup:upgrade` to register theme
5. Compile SASS files using [Frontools](https://github.com/SnowdogApps/magento2-frontools) or tools of choice

## Compatibility
* Magento 2.4: v1.5.0 or later (missing styles for newer modules)
* Magento 2.3: v1.2.0 or later
* Magento 2.2: v1.0.0 or later
* Magento 2.1: v0.11.0 or older
* Magento 2.0: v0.6.0 or older

### Sass Compatibility
* dart-sass: v2.0 or later
* libsass: v2.0 or older

## Bug reports and contribution rules
- Before reporting an issue, check if you can reproduce it on the clean Magento instance with LESS version of the Blank theme. If that's true, submit issue to the Magento 2 repository, not here
- If you know how to fix an issue, which is reproducible in Magento core, submit PR to the core product first, then here, with a link to PR in Magento 2 repository
- If issue is related only to the SASS port, feel free to submit issue or PR
