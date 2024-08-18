<div align="center">

# asdf-fetch-pass [![Build](https://github.com/mrjk/asdf-fetch-pass/actions/workflows/build.yml/badge.svg)](https://github.com/mrjk/asdf-fetch-pass/actions/workflows/build.yml) [![Lint](https://github.com/mrjk/asdf-fetch-pass/actions/workflows/lint.yml/badge.svg)](https://github.com/mrjk/asdf-fetch-pass/actions/workflows/lint.yml)

[fetch-pass](https://github.com/mrjk/fetch-pass) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add fetch-pass
# or
asdf plugin add fetch-pass https://github.com/mrjk/asdf-fetch-pass.git
```

fetch-pass:

```shell
# Show all installable versions
asdf list-all fetch-pass

# Install specific version
asdf install fetch-pass latest

# Set a version globally (on your ~/.tool-versions file)
asdf global fetch-pass latest

# Now fetch-pass commands are available
--version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/mrjk/asdf-fetch-pass/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mrjk](https://github.com/mrjk/)
