
{% method %}
## getRemoteVariableBool

```c
int getRemoteVariableBool( const wxString& name, 
                            bool *bValue)
```

### Parameters

#### name
Name of remote variable to get value for.

#### bValue
Pointer to boolean value that will be set to the remote variables value.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Get remote variable value for boolean variable. 

{% endmethod %}

{% include "./bottom_copyright.md" %}