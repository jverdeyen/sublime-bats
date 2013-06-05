# Sublime Text 2 package for Bats tests.

Bash Automated Testing System ([Bats](https://github.com/sstephenson/bats)) is a test library running in Bash/Shell, created by [@sstephenson](https://github.com/sstephenson).

## Usage

All `.bats` files should automatically be assigned the `Bats` language/grammar.

The following snippets/commands exist:

* `env` - use at the top of a file to set the environment to `#!/usr/bin/env bats`
* `test` - inserts a `@test "name" { ... }` test block
* `line` - inserts a `[ "${lines[0]}" = "something" ]` assertion

