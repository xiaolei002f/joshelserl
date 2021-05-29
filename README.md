## Introduction

This is a trivial example of connecting to the Apache HBase Thrift1 server using Python.

First, set up the virtual environment to install the necessary dependencies

```
$ ./setup.sh
```

Modify `get_row.py` to point to the location where the HBase Thrift1 server is running.

Ensure you have a Kerberos ticket (hint: `kinit`), then execute the script:

```
$ python get_row.py
```
