# Simple Tab Groups (Arc Theme)

## Usage

```bash
$ cd addon
$ npm install
$ npm run build
```

### `npm run build`

Build the extension into `addon/dist` folder for **development**.

### `npm run build-prod`

Build the extension into `addon/dist` folder for **production**.

### `npm run watch`

Watch for modifications then run `npm run build`.

### `npm run watch-prod`

Watch for modifications then run `npm run build-prod`.

### `npm run build-zip`

Build a zip file following this format `<name>-v<version>-(dev|prod).zip`, by reading `name` and `version` from `manifest.json` file.
Zip file is located in `dist-zip` folder.

## License and Credits

This project is licensed under the terms of the [Mozilla Public License 2.0](LICENSE).
