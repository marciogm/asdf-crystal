<div align="center">
<h1>asdf-crystal</h1>
<span><a href="https://crystal-lang.org">Crystal</a> plugin for asdf version manager</span>
</div>
<hr />

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/asdf-community/asdf-crystal/Main%20workflow?style=flat-square)](https://github.com/asdf-community/asdf-crystal/actions)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/github/license/asdf-community/asdf-crystal?style=flat-square&color=brightgreen)](https://github.com/asdf-community/asdf-crystal/blob/master/LICENSE)

## Installation

```
asdf plugin-add crystal https://github.com/asdf-community/asdf-crystal.git
```

## Usage

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions.

## Useful information

asdf uses the `.tool-versions` for auto-switching between software versions. To
ease migration, you can have it read `.crystal-version` file to find out what
version of Crystal should be used. This only works with the exact version. To do
this, add the following to `~/.asdfrc`:

```
legacy_version_file = yes
```
