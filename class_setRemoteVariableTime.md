
{% method %}
## setRemoteVariableTime

```c
int setRemoteVariableTime( const wxString& name, 
                            wxDateTime& time )
```

### Parameters

#### name
Name of remote variable to set value for.

#### time
VSCP time to write to remote variable.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Set remote variable value from VSCP time. 

{% endmethod %}

{% include "./bottom_copyright.md" %}