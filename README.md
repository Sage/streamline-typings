# streamline-typings

This package contains the typeScript type definitions for `streamline-runtime`.

These type definitions used to be bundled with `streamline-runtime` but this does not work well with `npm link`
because the definitions end up copied, which creates type conflicts because some definitions are ambient.