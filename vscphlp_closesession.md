{% method %}
## vscphlp_closeSession

```c
void vscphlp_closeSession( long handle )
```

### Parameters
none

### Return Value
Nothing

### Description
Close an open session. This is the last operation that should be done after you are done with a TCP/IP session. 

**Example** {% sample lang="c" %}
This is a simple windows console example that log on to a server that is on the host 192.618.1.9 and standard port 9598 and issue the NOOP command and then terminates. You link to the vscphelper.lib library and make sure the vscphelper.dll is in the path. 

```c
#include "vscphelperlib.h"
 
int main(int argc, char* argv[])
{
    long handle;
    handle = vscphlp_newSession();
 
    vscphlp_open( handle, 
                 "127.0.0.1:9598",
                 "admin",
                 "secret" ); 
 
    vscphlp_noop( handle );
 
    vscphlp_close( handle );
    vscphlp_closeSession( handle );
 
    return 0;
}
```

{% sample lang="python" %}
There is no Python sample yet

```python

```

###See Also
[vscphlp_closeSession](vscphlp_newsession.md)

{% endmethod %}

{% include "./bottom_copyright.md" %}