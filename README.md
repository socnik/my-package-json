# `package.json`

My preferred `package.json` templates which I use between projects.

## Usage

### Stage 0

Download selected `package.json` template with [`degit`](https://github.com/Rich-Harris/degit).

#### `package.json` for apps

`package.json` template optimized for applications.

```shell
npx degit @socnik/my-package-json/app.package.json
```

#### `package.json` for libraries

`package.json` template optimized for libraries (it includes fields such `keywords`, `repository`, `files`, etc.)

```shell
npx degit @socnik/my-package-json/lib.package.json
```

### Stage 1 (_optional_)

Setup Prettier.

This `package.json` template includes a pre-configured Prettier with my [Prettier config](https://github.com/socnik/my-prettier-config). If you want to use it, follow the guide in [socnik/my-prettier-config](https://github.com/socnik/my-prettier-config#usage) repository.

### Stage 2

**Enjoy 🚀!**
