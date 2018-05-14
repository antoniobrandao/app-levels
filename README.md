# app-levels

Solve your z-index: 999 problems: A set of zIndex defaults.

## Install

With [npm](http://npmjs.org) do:

```bash
$ npm install app-levels --save-dev

or

$ yarn add app-levels
```

## Usage

In Javascript

    import appLevels from 'app-levels'
    <div style={{ zIndex: appLevels.LEVEL_POPUP}}></div>

In SASS

    import '../node_modules/app-levels/index.sass'

    .my-popup {
      z-index: $LEVEL_POPUP
    }


## Available levels:

    LEVEL_SUPPORT_OVERLAY: 60
    LEVEL_ALERT: 50
    LEVEL_POPUP: 40
    LEVEL_NAV_MOBILE: 30
    LEVEL_NAV: 20
    LEVEL_OVERLAYS: 10
    LEVEL_BASE: 0
    LEVEL_BACKGROUND: -10


## License

MIT
