# @taskyz/prettier-config

This library contains the [Prettier](https://prettier.io) configuration used by [Taskyz](https://github.com/taskyz).

## Installing the library

```bash
npm install -D @taskyz/prettier-config
```

## Using the library

To use the library, you'll need to add the following to your `.prettierrc.json` file:


```json
"@taskyz/prettier-config"
```

## Publishing updates

- Update the version field in the `package.json` file;
- Stage and commit all changes;
- Tag the new commit with the new version number; and
- Push all changes to the GitHub repository.

This can be done using the following commands:

```bash
npm version patch
git push origin main --tags
```

A GitHub Actions workflow will then automatically publish the package to the NPM registry.
