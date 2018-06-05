
{% method %}
## getRemoteVariableNote

```c
int getRemoteVariableNote( const wxString& name, 
                            wxString& strNote )
```

### Parameters

#### name
Name of remote variable to get information for.

#### strNote
Reference to string that will get the note for the remote variable.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Get note for remote variable. 

{% endmethod %}

{% include "./bottom_copyright.md" %}