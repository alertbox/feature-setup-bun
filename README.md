<p align="center">
  <a href="https://bun.sh"><img src="https://github.com/user-attachments/assets/50282090-adfd-4ddb-9e27-c30753c6b161" alt="Logo" height=170></a>
</p>
<h1 align="center">Setup Bun</h1>

Download, install, and setup specific version of [Bun](https://bun.sh/) in your Dev Container.


## Quick Start

[![Open a Dev Container](https://img.shields.io/static/v1?style=for-the-badge&label=Dev+Container&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/alertbox/try-bun)

You can also add this feature to your `devcontainer.json` file.

```json filename="devcontainer.json"
"features": {
    "ghcr.io/alertbox/oven-sh/bun:1": {}
}
```
### Installing packages globally

You can also install packages globally, using the `packages` option. Typically this is used for installing CLI tools and the like.

```json filename="devcontainer.json"
"features": {
    "ghcr:io/alertbox/oven-sh/bun:1": {
        "packages": "cowsay"
    }
}
```

### Node.js not needed

You don't need to use the feature [node](https://github.com/devcontainers/features/tree/main/src/node#readme) in most cases.

## Options

See [src/setup-bun](./src/setup-bun/README.md) folder to learn more about options.


## Contributing

The official repo to contribute would be [@oven-sh/bun](https://github.com/oven-sh/bun?tab=readme-ov-file#readme).

Have a suggestion or a bug fix? Just open a pull request or an issue. Include clear and simple instructions possible.

## License

Copyright (c) The Alertbox, Inc. (@alertbox). All rights reserved.

The source code is license under the [MIT license](#MIT-1-ov-file).
