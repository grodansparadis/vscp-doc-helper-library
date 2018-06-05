
{% method %}
## getRemoteVariableLUA

```c
int getRemoteVariableLUA( const wxString& name, wxString& lua )
```

### Parameters

#### name
Name of remote variable to set value for.

#### lua
Reference to LUA data that get the value of the BASE64 encoded LUA variable.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Get remote variable value from a base64 ENCODED LUA variable. 

{% endmethod %}

{% include "./bottom_copyright.md" %}