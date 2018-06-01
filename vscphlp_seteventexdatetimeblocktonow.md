
{% method %}
## vscphlp_setEventExDateTimeBlockToNow

```c
int vscphlp_setEventExDateTimeBlockToNow( vscpEventEx *pEventEx )
```

### Parameters

#### pEventEx
Pointer to event that willhave its daettime block set to the current time.

### Return Value
VSCP_ERROR_SUCCESS is returned on success. 

### Description
Get date/time block for an ex event. 

**Example** {% sample lang="c" %}

```c
vscpEventEx *pEventEx;
vscphlp_setEventExDateTimeBlockToNow( pEventEx );
```

### See Also
[vscphlp_setEventDateTimeBlockToNow](vscphlp_seteventdatetimeblocktonow.md)

{% endmethod %}

{% include "./bottom_copyright.md" %}