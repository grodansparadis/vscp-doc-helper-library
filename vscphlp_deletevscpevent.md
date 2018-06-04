
{% method %}
## vscphlp_deleteVSCPevent

```c
void vscphlp_deleteVSCPevent( vscpEvent *pEvent )
```

### Parameters

#### pEvent
VSCP event.


### Return Value
None.

### Description
Delete VSCP event. 

**Example** {% sample lang="c" %}

```c
vscphlp_deleteVSCPevent( pEvent );
```

### See Also
[vscphlp_newVSCPevent](vscphlp_newvscpevent.md)  
[vscphlp_deleteVSCPevent_v2](vscphlp_deletevscpevent_v2.md)

{% endmethod %}

{% include "./bottom_copyright.md" %}