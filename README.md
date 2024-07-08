# typescript-dep-error

When the `@types/send` package attempts to reference `mime` it ends up importing `mime`(`@^4`) and not `@types/mime`, even though it's package.json dependency specifically references that version.


