# Development Environment Setup

This document walks through the local development experience with the codebase,
and what you should know if you desire to contribute.

## JS Development

If you are working with JS files, you should ensure you have a current version of
[NodeJS](https://nodejs.org) and [Yarn](https://yarnpkg.com/) installed. There
are helpful tools installed that require these to be available.

With those tools installed, you can then install the packages required:

```shellsession
$ yarn
```

We use `prettier` to execute a consistent format to the code, and at any time
you can run this command to ensure your changes are formatted correctly:

```shellsession
$ yarn prettify
```

You should also confirm the code fulfills the rules defined in the `eslintrc.json`
config file:

```shellsession
$ yarn lint
```

These rules will be tested as part of every pull request into the project, but
please ensure you run these commands locally to catch any issues before a
reviewer gets involved.
