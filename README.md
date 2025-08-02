# .dotfiles

My configuration dotfiles for macOS, managed by
[Dotbot](https://github.com/anishathalye/dotbot) which handles linking and
running scripts.

[Homebrew](https://brew.sh) is used as the package manager and will be installed
if not present and then any packages listed in `data/Brewfile` will be
installed.

## Installation

The `Command Line Tools` need to be installed before cloning and installing
the dotfiles. Run the following command to install them.

```shell
xcode-select --install
```

Then run the following commands to clone and install the dotfiles.

```shell
git clone https://github.com/AnarielTeleri/.dotfiles.git
.dotfiles/install
```
