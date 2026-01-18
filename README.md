# Blog

A peronal blog hosted using zola.

## Address

* https://c7a6.github.io

## Tasks

### publish

```bash
#!/usr/bin/env bash

set -x
set -e

zola build

git commit --all -m "chore: xc publish"
```
