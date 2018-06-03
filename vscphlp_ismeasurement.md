
{% method %}
## vscphlp_isMeasurement

```c
int vscphlp_isMeasurement( const vscpEvent *pEvent )
```

### Parameters

#### pEvent
Pointer to VSCP measurement event.

### Return Value
VSCP_ERROR_SUCCESS is returned if the event is a measurement, VSCP_ERROR_ERROR is returned if the event is not a measurement. 

### Description
Check if an event is a measurement. 


{% endmethod %}

{% include "./bottom_copyright.md" %}