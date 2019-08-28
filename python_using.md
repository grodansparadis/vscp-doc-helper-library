# Using from Python {#c_python}

See exempamples [here](https://github.com/grodansparadis/pyvscp/tree/master/vscp) of helperlib usage.

Import with

>from vscp import vscphelper

and then prefix all methods with **vscphelper.**

Example
```python
h1 = vscphelper.pyvscphlp_newSession()
if (0 == h1 ):
    vscphelper.pyvscphlp_closeSession(h1)
    raise ValueError('Unable to open vscphelp library session')
```


{% include "./bottom_copyright.md" %}