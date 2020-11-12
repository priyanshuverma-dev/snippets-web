# Generated Snippets

## Overview

This directory contains snippets generated by the `separate-snippets` script.
Snippets in this folder should **never** be updated directly instead please
edit the source file (indicated by a comment at the top).

## Regenerating the Snippets

Run `npm run snippets` from the root of this repository.

## Using the Separator

For a file to be included in the separator script it must contain a comment like this:

```js
// [SNIPPETS_SEPARATION enabled]
```

By default separated snippets will have their name suffixed with `_modular`
but you can override this with a commment:

```js
// [SNIPPETS_SUFFIX _banana]
```