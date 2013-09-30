Disk image test suite for OS X.
===============================

I used a superset of these tests to test the golden master OS X
disk images I used to create at Google.

Usage:

```
run_image_tests.py /path/to/your.dmg
```

This will need work if you're going to use it - this release is so
old now that it uses Python 2.5. That said, there shouldn't be too
much deprecated code here, nothing in these tests is all that
complex.
