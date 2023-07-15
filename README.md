# Lerna Sharepoint SPFX 1.4.1

This repo is a small example of using Lerna 5+.

Watch this [10-minute walkthrough](https://youtu.be/1oxFYphTS4Y) to see how new versions of Lerna work.

This repo contains three packages or projects:

- `external_react` (a library of React components)
- `spfx` (an app written using the Spfx which depends on `external_react`)

```
external_react/
    src/
        ...
    package.json
    webpack.config.json

spfx/
    app/
        ...
    public/
    package.json
    remix.config.js
package.json
```
