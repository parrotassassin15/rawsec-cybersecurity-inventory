---
id: install
title: Installation and building
---
## Inventory

Install dependencies:

```plaintext
$ yarn global add gulp-cli
$ yarn install
```

Now you can simply build the site by using the following command:

```plaintext
$ gulp
```

The build output reside inside the `build/` folder.

For example you can view it with Firefox:

```plaintext
$ firefox build/index.html
```

## Documentation

Go inside the documentation folder:

```plaintext
$ cd docusaurus
```

Install dependencies:

```plaintext
$ yarn install
```

Build the documentation:

```plaintext
$ yarn run build
```

You can manually browse it in the `build/` (`docusaurus/build/`) folder or run `yarn start`.

For more information on how the documentation works, check [Docusaurus](https://docusaurus.io/) website.
