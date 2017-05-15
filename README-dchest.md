## Creating binaries

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
NODE_PRE_GYP_GITHUB_TOKEN=XXXXXX npm run publish-binaries-windows
```
