
{% method %}
## setRemoteVariableLUA

```c
int setRemoteVariableLUA( const wxString& name, wxString& lua )
```

### Parameters

#### name
Name of remote variable to set value for.

#### lua
Reference to BASE64 encoded LUA data to write to variable.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Set remote variable value from BASE64 encoded LUA data. 

{% endmethod %}

{% include "./bottom_copyright.md" %}