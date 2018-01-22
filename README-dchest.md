## Creating binaries

On Mac:

```
npm run build-mac
```

On Linux:

Make sure to install libsecret headers: `sudo apt-get install libsecret-1-dev`.

Linux x86_64:

```
npm run build-linux
```

Linux arm (Raspberry Pi):

```
npm run build-linux-arm
```

On Windows:

```
npm run build-windows
```

Put all the binaries into `lib/binding/Release` in `{platform}-{arch}` directories:

```
lib
├── binding
│   └── Release
│       ├── darwin-x64
│       │   └── keytar.node
│       ├── linux-x64
│       │   └── keytar.node
│       ├── win32-ia32
│       │   └── keytar.node
│       └── win32-x64
│           └── keytar.node
└── keytar.js
```
