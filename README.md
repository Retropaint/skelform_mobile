A mobile port of [SkelForm](https://github.com/Retropaint/SkelForm), compiled as the web version and built with [Capacitor](https://capacitorjs.com/).

# Building

Install [Node LTS](https://nodejs.org/en) and [npm](https://www.npmjs.com/).

Bonus: Install [nvm](https://github.com/nvm-sh/nvm) to easily manage Node versions.

Building commands usually look like this:

```bash
$ npm run install
$ npx cap sync android # or ios
$ npx cap build android # or ios
```

More options:
```bash
$ npx cap open android # opens Android Studio
$ npx cap run android # builds apk directly into a device
```

Please note that iOS is untested.
