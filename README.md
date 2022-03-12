# [pakages repo](https://arch-setup.github.io/packages/)

### sha256sum Validity
to fill this filed, set the checksum result for each file in the source in an array.

```
$ sha256sum 'filename' 'index.html' 'README.md'

4018af35b12db502a8a9aebbe75c29594fcfde550522c204930f7d9afbd29562  filename
4018af35b12db502a8a9aebbe75c29594fcfde550522c204930f7d9afbd29562  index.html
445fa5a10a59f14ce8d8b52632b4917ebfa147af091a85d913fe17972568e7d2  README.md

```


### [host custom packages gh-pages]((https://www.youtube.com/watch?v=CYqd2AHXosk))
to make a custom repo is enogut to create a folder under `x86_64/` and run
```
repo-add 'name.db.tar.gz' *.pkg.tar.zst
```
to create a db.
Like this

<img src="docs/repo_db.png"/>
