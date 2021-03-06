## Ruby configuration layer

Adds support for basic ruby and rails programming by utilizing:
 - [ruby-test](https://atom.io/packages/ruby-test)
 - [ruby-block](https://atom.io/packages/ruby-block)
 - [blockconverter](https://atom.io/packages/ruby-block-converter)
 - [linter-ruby](https://atom.io/packages/linter-ruby)
 - [linter-rubocop](https://atom.io/packages/linter-rubocop)
 - [rubocop-auto-correct](https://atom.io/packages/rubocop-auto-correct)

If you are a ruby dude, please feel free to improve this layer.

### Install

Add `:lang/ruby` to your layers.

### Requirements

- [rsense](https://github.com/rsense/rsense)
- [rubocop](https://github.com/bbatsov/rubocop)

### Configuration

Check out [atom-ruby-test](https://github.com/moxley/atom-ruby-test) for configurations for test runners

| Name                             | Default         | Type     | Description                   |
|----------------------------------|-----------------|----------|-------------------------------|
| `ruby-linter.rubyExecutablePath` | "/usr/bin/ruby" | __string__ | which ruby to use for linting |
| `ruby-rubocop.executablePath`    | null            | __string__ | path to rubocop gem |

### Ruby bindings

can be executed with <kbd>SPC m</kbd> or <kbd>,</kbd>

| Key Binding          | Description                                          |
|----------------------|------------------------------------------------------|
| <kbd>SPC m c d</kbd> | Convert {} block to do..end block                    |
| <kbd>SPC m c D</kbd> | Convert {} block to do..end block without collapsing |
| <kbd>SPC m c b</kbd> | Convert do..end block to {} block                    |
| <kbd>SPC m c B</kbd> | Convert do..end block to {} block without joining    |
| <kbd>SPC m t t</kbd> | Toggle test panel                                    |
| <kbd>SPC m t a</kbd> | Run all tests                                        |
| <kbd>SPC m t f</kbd> | Run current file                                     |
| <kbd>SPC m t l</kbd> | Run current file at line                             |
| <kbd>SPC m t .</kbd> | Repeat last test                                     |
| <kbd>SPC m t c</kbd> | Cancel all tests                                     |
| <kbd>SPC =</kbd>     | Rubocop auto format                                  |
