
{% method %}
## setRemoteVariableUser

```c
int setRemoteVariableUser( const wxString& name, 
                            wxString& user )
```

### Parameters

#### name
Name of remote variable to set value for.

#### user
Reference to BASE64 encoded user data to write to variable.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Set remote variable value from BASE64 encoded user data. 

{% endmethod %}

{% include "./bottom_copyright.md" %}