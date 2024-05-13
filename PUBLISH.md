# How to publish this extension

## Installation

```sh
npm install -g @vscode/vsce
```

## Bump a new version

When use the `npm version` command, the version in `package.json` will be updated and a new commit will be created. Also, there is a `Tag` created for the new version.

1. Major change

    ```sh
    npm version major
    ```

2. Minor change

    ```sh
    npm version minor
    ```

3. Patch change

    ```sh
    npm version patch
    ```

## Package

```sh
vsce package
```

## Publish

```sh
vsce publish
```

## Reference

- [Publishing Extensions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)
