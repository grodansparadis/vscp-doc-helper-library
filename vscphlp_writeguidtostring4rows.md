
{% method %}
## vscphlp_writeGuidToString4Rows

```c
int vscphlp_writeGuidToString4Rows( const vscpEvent *pEvent, 
                                      char *strGUID,
                                      size_t len )
```

### Parameters

#### pEvent
VSCP event.

#### strGUID
String that get formatted GUID.

#### len
Size of string buffer.

### Return Value
VSCP_ERROR_SUCCESS on success. 

### Description
Write GUID from VSCP event to string with four bytes on each row separated by “\r\n”. 

**Example** {% sample lang="c" %}

```c
if ( VSCP_ERROR_SUCCESS == vscphlp_writeGuidToString4Rows( pEvent, strguid2, sizeof( strguid2 )-1 ) ) {
    printf( "GUID\n%s\n", strguid2 );
}
else {
    printf( "Error: vscphlp_writeGuidArrayToString\n");
}
```

### See Also
[vscphlp_writeGuidToString4RowsEx](vscphlp_writeguidtostring4rowsex.md)

{% endmethod %}

{% include "./bottom_copyright.md" %}