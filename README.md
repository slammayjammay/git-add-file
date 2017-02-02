# `git-add-file`

This package is not on NPM, so installation is [pretty tedious](https://github.com/npm/npm/issues/3055).
```sh
# clone the repo
$ git clone https://github.com/slammayjammay/git-add-file.git
$ cd git-add-file
# install dependencies
$ npm install
# generate tarball
$ npm pack
# install the generated tarball
$ npm install -g git-add-file-X.X.X.tgz # XXX is the semantic version
# remove the repo
$ cd ../ && rm -rf git-add-file
```

I alias this with "ga":
```sh
# in .bash_profile
alias ga="git-add-file"
```

# Usage
```sh
$ git-add-file html # adds all .html files, for example
$ git-add-file readme # adds the README.md file
```
