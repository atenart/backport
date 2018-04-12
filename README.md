# Backport commits

Backport (cherry-pick) commits made on a list of tracked files, from a given
branch to the local one. Or just display the list.

## Usage

```
$ backport-commits -c ./tracked.txt branch-to-backport-from
$ backport-commits --apply branch-to-backport-from
$ backport-commits --apply -f branch-to-backport-from
```

## Help

```
$ backport-commits -h
```

## License

This file is licensed under the terms of the GNU General Public
License version 2. This program is licensed "as is" without any
warranty of any kind, whether express or implied.
