# Brewfile

Homebrew is a package manager for macOS and makes it easy to install software and keep it up to date.

## Get started

First, install Homebrew. You can find installation instructions and documentation on the [brew.sh](https://brew.sh/) website.

### Enable brew bundle

Install the bundle tap

``brew tap homebrew/bundle``

### Create Brewfile

Create a Brewfile from all installed packages on your existing system. You can use it to provision a new macOS device.

``brew bundle dump``

By default, the Brewfile is located at `~/Brewfile`.

### Install packages from Brewfile

Install all packages from the specified Brewfile. Software that is already installed is automatically skipped or updated if a newer version is available.

``brew bundle install --file=/path/to/Brewfile``