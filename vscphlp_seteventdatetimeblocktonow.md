
{% method %}
## vscphlp_setEventDateTimeBlockToNow

```c
int vscphlp_setEventDateTimeBlockToNow( vscpEvent *pEvent )
```

### Parameters

#### pEvent
Pointer to event that will get the datetime block set to **now**.

### Return Value
VSCP_ERROR_SUCCESS is returned on success. 

### Description
Get date/time block for an event. 

**Example** {% sample lang="c" %}

```c
vscpEvent *pEvent;
vscphlp_setEventDateTimeBlockToNow( pEvent );
```
[vscphlp_setEventExDateTimeBlockToNow](vscphlp_seteventexdatetimeblocktonow.md)

{% endmethod %}

{% include "./bottom_copyright.md" %}