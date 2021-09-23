# Quick Start - Install idk3

> [!TIP]
> idk3 is installable via [instl.sh](https://instl.sh).\
> You just have to run the following command and you're ready to go!

<!-- tabs:start -->

#### ** Windows **

### Windows Command

```powershell
iwr instl.sh/MarvinJWendt/idk3/windows | iex
```

#### ** Linux **

### Linux Command

```bash
curl -sSL instl.sh/MarvinJWendt/idk3/linux | sudo bash
```

#### ** macOS **

### macOS Command

```bash
curl -sSL instl.sh/MarvinJWendt/idk3/macos | sudo bash
```

#### ** Compile from source **

### Compile from source with Golang

?> **NOTICE**
To compile idk3 from source, you have to have [Go](https://golang.org/) installed.

Compiling idk3 from source has the benefit that the build command is the same on every platform.\
It is not recommended to install Go only for the installation of idk3.

```command
go install github.com/MarvinJWendt/idk3@latest
```

<!-- tabs:end -->
