{% method %}
## vscphlp_getGuidFromStringEx


```c
int vscphlp_getGuidFromStringEx( vscpEvent *pEvent, 
                            const char * pGUID )
```

### Parameters

#### pEvent
VSCP event ex.

#### pGUID
Pointer to GUID in string form.


### Return Value
VSCP_ERROR_SUCCESS on success.

### Description
Write GUID into VSCP event ex from a string. 

**Example** {% sample lang="c" %}

```c
char strguid[64], strguid2[64];
 
if ( VSCP_ERROR_SUCCESS == vscphlp_getGuidFromStringEx( &ex3, strguid ) ) {        
    vscphlp_writeGuidToStringEx( &ex3, strguid2, sizeof( strguid2 )-1 );
    printf( "GUID=%s\n", strguid2 );
}
else {
    printf( "\aError: vscphlp_writeGuidArrayToString\n");
}
```

### See Also
[vscphlp_getGuidFromString](vscphlp_getguidfromstring.md)

{% endmethod %}

{% include "./bottom_copyright.md" %}