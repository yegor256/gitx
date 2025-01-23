# Mass Changes to Git Repos in One-Click

[![shellcheck](https://github.com/yegor256/gitx/actions/workflows/shellcheck.yml/badge.svg)](https://github.com/yegor256/gitx/actions/workflows/shellcheck.yml)

Let's say, you have a many repositories locally and you
need to `git pull` all of them. Instead of going one by one,
you simply do this:

```bash
gitx pull
```

The script will find all repos in the current directory and
will do `git pull` in each of them.

The software is not yet safe, be careful!
