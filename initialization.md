#
# Initialization

This part describe the main functionality and communication methods available in the library. 

{% method %}
## vscphlp_newSession

Opens a new communication session. This is the first method that should be called before TCP/IP communication can be established. 

long vscphlp_newSession( void )

###Parameters
none

###Return Value
A session handle or zero if a session could not be created. 

{% sample lang="c" %}
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
fmt.Println("My first method")
```

{% common %}
Whatever language you are using, the result will be the same.

```bash
$ My first method
```
{% endmethod %}