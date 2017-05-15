## Creating binaries

First of all, in `package.json`, rename "xinstall" to "install",
and vice-versa.

Tag release, e.g. `npm version minor` and push it: `git push && git push --tags`.

On Mac:

```
NODE_PRE_GYP_GITHUB_TOKEN=XXXXXX npm run publish-binaries-mac
```

On Linux:

Make sure to install libsecret headers: `sudo apt-get install libsecret-1-dev`.

```
NODE_PRE_GYP_GITHUB_TOKEN=XXXXXX npm run publish-binaries-linux
```

On Windows:

```
SET NODE_PRE_GYP_GITHUB_TOKEN=XXXXXX
npm run publish-binaries-windows
```
