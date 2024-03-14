# `package.json`

This is my favorite `package.json` template.

## How use?

Copy my template and edit it for your purposes. You can open the template file in the repository by [this link](https://github.com/socnik/my-package-json/blob/main/template.package.json) or copy it from the bottom code block. This `package.json` includes my [Prettier config](https://github.com/socnik/my-prettier-config). If you want to use it execute these commands:

- **Pnpm:** `pnpm add -D prettier @socnik/my-prettier-config`
- **Npm:** `npm i --dev prettier @socnik/my-prettier-config`

## Template content:

```json
{
  "name": "",
  "version": "0.0.0",
  "description": "",
  "keywords": [],
  "homepage": "https://github.com/socnik/{{repo}}#readme",
  "bugs": {
    "url": "https://github.com/socnik/{{repo}}/issues"
  },
  "license": "MIT",
  "author": {
    "name": "Nikita"
  },
  "files": [],
  "main": "",
  "bin": [],
  "repository": {
    "type": "git",
    "url": "git+https://github.com/socnik/{{repo}}"
  },
  "scripts": {},
  "engines": {
    "node": ">=18.0.0"
  },
  "private": false,
  "prettier": "@socnik/my-prettier-config",
  "packageManager": "pnpm@8.10.5"
}
```
