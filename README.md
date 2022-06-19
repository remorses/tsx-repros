Cannot import named export from a typescript file in a workspace package if entry is using es modules and other package is not.

Repro:
```
pnpm i
pnpm run import-ts-file
```
