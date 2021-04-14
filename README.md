# template-build-lib

A template of project building configs for js library.

This zp module itself is of type `template-build`.

## Features

- [x] support node and browser based library
- [x] support babel only or rollup
- [x] support eslint
- [ ] support typescript

## Project directory structure

```bash
.
├── /template-build/               # main template directory of zp module
│   ├── /.zp/                      # zp module config files directory
│   │   ├── /.zp-module.toml       # zp module config
│   │   └── /.zp-vars.toml         # zp module middleware config (optional)
│   └── [template files]                    # template file (optional)
├── [files not important]
├── package.json
└── README.md
```

## Recently changes

See the [change log](CHANGELOG.md).

## License

[MIT](LICENSE)
