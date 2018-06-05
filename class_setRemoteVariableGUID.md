
{% method %}
## setRemoteVariableGUID

```c
int setRemoteVariableGUID( const wxString& name, 
                            cguid& guid)
```

### Parameters

#### name
Name of remote variable to set value for.

#### guid
Reference to guid value that will be set to the remote variables value.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Set remote variable value for VSCP guid variable. 


{% endmethod %}

{% include "./bottom_copyright.md" %}