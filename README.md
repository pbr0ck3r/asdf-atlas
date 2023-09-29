<div align="center">

# asdf-atlas [![Build](https://github.com/pbr0ck3r/asdf-atlas/actions/workflows/build.yml/badge.svg)](https://github.com/pbr0ck3r/asdf-atlas/actions/workflows/build.yml) [![Lint](https://github.com/pbr0ck3r/asdf-atlas/actions/workflows/lint.yml/badge.svg)](https://github.com/pbr0ck3r/asdf-atlas/actions/workflows/lint.yml)

[atlas](https://github.com/ariga/atlas) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add atlas
# or
asdf plugin add atlas https://github.com/pbr0ck3r/asdf-atlas.git
```

atlas:

```shell
# Show all installable versions
asdf list-all atlas

# Install specific version
asdf install atlas latest

# Set a version globally (on your ~/.tool-versions file)
asdf global atlas latest

# Now atlas commands are available
atlas version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pbr0ck3r/asdf-atlas/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Phil Brocker](https://github.com/pbr0ck3r/)
