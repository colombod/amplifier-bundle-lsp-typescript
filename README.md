# amplifier-bundle-lsp-typescript

> **DEPRECATED — This bundle has been consolidated into
> [amplifier-bundle-typescript-dev](https://github.com/microsoft/amplifier-bundle-typescript-dev).**

This repository is now a **forwarding stub**. It transparently loads `typescript-dev`
so existing configurations continue to work. A deprecation warning will appear on
session start to guide you through migration.

## Migration

Update your bundle includes:

```diff
- - bundle: git+https://github.com/microsoft/amplifier-bundle-lsp-typescript@main
+ - bundle: git+https://github.com/microsoft/amplifier-bundle-typescript-dev@main
```

## What Changed?

The `lsp-typescript` bundle provided LSP/typescript-language-server support only. The
new `typescript-dev` bundle includes everything `lsp-typescript` had, plus:

- **Code quality tools** — prettier, eslint, and tsc integration
- **Automatic checking** — hooks that run on file write/edit
- **Stub detection** — identifies generated/declaration files
- **Expert agent** — `typescript-dev` agent with full TypeScript/JavaScript development knowledge

## Timeline

This forwarding stub will remain active for 2–3 months to allow migration.
After that, this repository will be archived.

## License

This project is licensed under the MIT License — see [LICENSE](LICENSE) for details.

This project has adopted the
[Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
