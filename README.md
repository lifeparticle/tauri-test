## Error You must change the bundle identifier in `tauri.conf.json > tauri > bundle > identifier`. The default value `com.tauri.dev` is not allowed as it must be unique across applications.

## https://tauri.app/v1/guides/building/macos

```shell
yarn tauri build
```

`src-tauri/target/release/bundle/dmg`

## https://github.com/tauri-apps/tauri/blob/dev/.gitignore

## https://tauri.app/v1/guides/distribution/updater/

## https://github.com/Loothound/Loothound

```yml
- uses: tauri-apps/tauri-action@v0
env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
    TAURI_PRIVATE_KEY: ${{ secrets.TAURI_PRIVATE_KEY }}
    TAURI_KEY_PASSWORD: ${{ secrets.TAURI_KEY_PASSWORD }}
```
