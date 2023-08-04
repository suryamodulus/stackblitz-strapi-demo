# 🚀 Stackblitz Strapi Demo (Sqlite)

### `Build`

```
yarn build
```

### `Start`

```
yarn start
```

## Changes

- Added @webassembly/sqlite3 to package.json
- Added patch to sqlite dialect to disable ```returning```
- Added postinstall script
- Added Seed DB (There is still some issue with DB initalization)
- Removed develop command (It runs successfully, but doesn't work)

## TODOS
- Debug DB initalization (Maybe prepared statements are the issue?)
- Debug develop command (Maybe cluster mode or chokidar is the issue?)
