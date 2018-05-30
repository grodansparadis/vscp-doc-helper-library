{% method %}
## vscphlp_newSession

```c
long vscphlp_closeSession( void )
```

### Parameters
none

### Return Value
A session handle or zero if a session could not be created. 

### Description
Opens a new communication session. This is the first method that should be called before TCP/IP communication can be established.

**Example** {% sample lang="c" %}
Initialize the library using c.

```c
handle1 = vscphlp_newSession();
if (0 != handle1 ) {
    printf( "Handle for channel 1 OK %d\n", handle1 );
}
else {
    printf("\aError: Failed to get handle for channel 1\n");
}
```

{% sample lang="python" %}
Initialize the library using Pyhton.

```python
pyvscphlp_closeSession(h1)
```

###See Also
[vscphlp_closeSession](vscphlp_closesession.md)

{% endmethod %}

{% include "./bottom_copyright.md" %}