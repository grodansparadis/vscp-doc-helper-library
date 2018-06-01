{% method %}
## vscphlp makeTimeStamp


```c
unsigned long vscphlp_makeTimeStamp( void )
```

### Parameters

#### handle
Handle for the communication channel obtained from a call to [vscphlp_newsession](vscphlp_newsession.md).

### Return Value
Timestamp in microseconds.

### Description
Get new VSCP timestamp. 

**Example** {% sample lang="c" %}

```c
printf( "vscphlp_makeTimeStamp  %04X\n", vscphlp_makeTimeStamp() );
```

{% endmethod %}

{% include "./bottom_copyright.md" %}