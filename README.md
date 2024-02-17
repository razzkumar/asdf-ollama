<div align="center">

# asdf-ollama [![Build](https://github.com/razzkumar/asdf-ollama/actions/workflows/build.yml/badge.svg)](https://github.com/razzkumar/asdf-ollama/actions/workflows/build.yml) [![Lint](https://github.com/razzkumar/asdf-ollama/actions/workflows/lint.yml/badge.svg)](https://github.com/razzkumar/asdf-ollama/actions/workflows/lint.yml)

[ollama](https://ollama.com/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add ollama
# or
asdf plugin add ollama https://github.com/razzkumar/asdf-ollama.git
```

ollama:

```shell
# Show all installable versions
asdf list-all ollama

# Install specific version
asdf install ollama latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ollama latest

# Now ollama commands are available
ollama --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/razzkumar/asdf-ollama/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [razzkumar](https://github.com/razzkumar/)
