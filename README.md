
# ya*JS*api

The JS/TS port of [yapapi, Golem's Python API](https://github.com/golemfactory/yapapi)

## Prerequisites

- [node](https://nodejs.org/en/) >= v12.13.0
- [yarn](https://classic.yarnpkg.com/en/docs/install/) >= v1.22.3
<br/><br/>

# Building the Library
_(not needed for running examples)_
### Installation
- run `yarn` in main folder

### Building
- run `yarn build` in main folder
- build is ready in `dist` folder!
<br/><br/>

### Testing
| Command | Description |
| --- | --- |
| `yarn test:unit` | Run all unit test
|`yarn cov` | Show tests coverage
| `yarn cov:html` | GeneratedDetailed test coverage report (HTML in `coverage` directory)
| `yarn cov:lcov` | Generate lcov.info file

# Running Examples
### Installation
- `cd examples`         will take you to examples folder
- `yarn`                will install dependencies for the examples
- add `YAGNA_APPKEY` as environment variable; 
```
export YAGNA_APPKEY=your_yagna_app_key_here
```

### When ready
- `npm run js:blender`  will start blender javascript example
- `npm run ts:blender`  will start blender typescript example
- `npm run js:low`      will start javascript low level api example
- `npm run ts:low`      will start typescript low level api example

### Need more logs
Call `-d` or `--debug` flag on your example script, e.g. `npm run ts:blender -- -d`

### Subnet
Use the `--subnet-tag` option, e.g. `npm run ts:blender -- --subnet-tag YOUR_SUBNET`.
