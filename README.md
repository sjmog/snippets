# Snippets

Useful command-line snippets to do stuff I don't want to do more than once.

## Getting started
Add `<wherever-you-cloned-this-to>/bin` to your `PATH`.

## Library

### `snadd`

**Usage**

`snadd <snippet-name>`

Creates a new Ruby shell script in ./bin, makes it executable and opens it in Sublime Text.

### `rubyapp`

**Usage**

`rubyapp <app-name>`

Creates a new directory containing a Ruby app with RSpec, and opens it in Sublime Text.

### `sinatrapp`

**Usage**

`sinatrapp <AppName>`

> Note that you should use the constantized version of `AppName` with this one.

Creates a new directory containing a Sinatra app with: 

- Capybara and RSpec.
- A views directory with index and layout templates.
- Default CSS styles.
- Dotenv for secrets.