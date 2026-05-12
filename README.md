# cloud-capacitor-pnpm-demo

[![Capawesome](https://github.com/capawesome-team/cloud-capacitor-pnpm-demo/actions/workflows/capawesome.yml/badge.svg)](https://github.com/capawesome-team/cloud-capacitor-pnpm-demo/actions/workflows/capawesome.yml)

A demo project that shows how to build a [Capacitor](https://capacitorjs.com/) app managed with [pnpm](https://pnpm.io/) using [Capawesome Cloud](https://capawesome.io/cloud/).

## Stack

- [Capacitor](https://capacitorjs.com/) — Android + iOS
- [pnpm](https://pnpm.io/) — package manager
- [Swift Package Manager](https://www.swift.org/documentation/package-manager/) — native iOS dependencies
- [Vite](https://vitejs.dev/) — web build

## Continuous Integration

[`.github/workflows/capawesome.yml`](.github/workflows/capawesome.yml) builds the app on every push to `main`, on pull requests, and on manual dispatch using the [Capawesome CLI](https://capawesome.io/docs/cloud/cli/).

A [`capawesome.config.json`](capawesome.config.json) file at the repository root tells Capawesome Cloud to install dependencies and build the web assets using `pnpm`.

### Required GitHub Secrets

| Secret | Description |
| --- | --- |
| `CAPAWESOME_CLOUD_TOKEN` | API token for Capawesome Cloud. |
| `CAPAWESOME_CLOUD_APP_ID` | ID of the corresponding app in Capawesome Cloud. |

## License

See [LICENSE](LICENSE).
