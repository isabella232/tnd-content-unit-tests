# unit-tests
A repository of testing content

## Requirements

Requirements:
- Go 1.14
- Hugo 0.61.0


## Installation

If not already, [init](https://gohugo.io/hugo-modules/use-modules/#initialize-a-new-module) your project as Hugo Module:

```
$: hugo mod init github.com/theNewDynamic/tnd-content-unit-tests
```

Configure your project's module to import this module:

```yaml
# config.yaml
module:
  imports:
  - path: github.com/theNewDynamic/hugo-module-tnd-content-unit-tests
```

## Usage
The test content will be imported into the `content/tnd-content-unit-tests` folder. The test images will be imported into the `static/tnd-content-unit-tests/images` folder.

## theNewDynamic

This project is maintained and love by [thenewDynamic](https://www.thenewdynamic.com).