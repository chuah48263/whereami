# whereami

`whereami` is a command tool to avoid confusion between real and virtual directories.

# Installation

Install `whereami` by issuing the following command in your teminal:
```
$ git clone https://github.com/chuah48263/whereami.git ~/.whereami/ && chmod +x ~/.whereami/whereami && ln -s ~/.whereami/whereami /usr/local/bin/whereami
```

# Usage

```
$ mkdir test && cd test && whereami
Current dir: ~/test

$ cd .. && ln -s test demo && cd demo && whereami
Symlink dir: ~/demo
Target dir: ~/test
```
