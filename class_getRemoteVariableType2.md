
{% method %}
## getRemoteVariableType

```c
int getRemoteVariableType( const wxString& name, 
                            uint8_t *pType )
```

### Parameters

#### name
Name of remote variable to get information for.

#### pType
Pointer to uint8_t that will get the variable type for the remote variable.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure.

### Description
Get type on numeric form for a remote variable. 

{% endmethod %}

{% include "./bottom_copyright.md" %}