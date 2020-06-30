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

### Some Partial/Feature

#### Examples

### Settings

Settings are added to the project's parameter under the `tnd_content-unit-tests` map as shown below.

```yaml
# config.yaml
params:
  tnd_content-unit-tests:
    [...]
```

#### Configure Key 1

#### Configure Key 2

Given the example above, passing the following arguments to `tnd-imgix/GetSRC`
```
{{ $src := "/uploads/an-image.jpg" }}
{{ $args := dict "src" $src "width" 1024 "pixel" 2 "ch" "Width,DPR" }}
```

Will produce: `https://imgix.domain.com/image.jpg?w=1024&dpr=2&ch=Width,DPR`

#### Defaults

ld copy/paste the above to your settings and append with new extensions.

## theNewDynamic

This project is maintained and love by [thenewDynamic](https://www.thenewdynamic.com).