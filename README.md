# EduBeyond Eslint Config

> As the name implies, this is the preferred eslint config for EduBeyond projects.

Some things to note:

- This config assumes the following:
  - You are using React
  - You are using Typescript
  - You are using Prettier

Other notes:

- This config extends from:
  - [typescript-eslint](https://github.com/typescript-eslint/typescript-eslint)
  - [prettier](https://github.com/prettier/prettier-eslint)
  - [unicorn](https://github.com/sindresorhus/eslint-plugin-unicorn)

## Installation

```bash
npm install --save-dev eslint-config-edubeyond
```

## Usage

Add the following to your `.eslintrc` file:

```json
{
  "extends": "@edubeyond/eslint-config-edubeyond"
}
```
