# enumhardlinks

Enumerate all hardlinks to a file on Windows:

```
import enumhardlinks

enumhardlinks.get_hardlinks('/path/to/file')
```

Returns a list of all hardlinks to the specified file (at least one, the file itself!)


Available on pypi.org

```
pip install enumhardlinks
```
