# Backport

Backport (cherry-pick) commits made on a list of tracked files, from a given
branch to the local one. Or just display the list. This tool is used to maintain
stable branches with additional newer features coming from a subset of files.

Example: a Linux branch based on a stable version, onto which you want to apply
newer changes for the drivers and architecture code of a particular platform.

## Usage

```
$ backport -c ../blacklist.cfg branch-to-backport-from
$ backport branch-to-backport-from --apply
$ backport branch-to-backport-from --apply -f
$ backport branch-to-backport-from --apply --cmd="make -j6"
```

## Help

```
$ backport -h
```

## License

This file is licensed under the terms of the GNU General Public
License version 2. This program is licensed "as is" without any
warranty of any kind, whether express or implied.
