
{% method %}
## vscphlp_isSameGUID

```c
int vscphlp_isSameGUID( const unsigned char *pGUID1, 
                        const unsigned char *pGUID2 )
```

### Parameters

#### pGUID1
GUID1 to compare.

#### pGUID2
GUID2 to compare.


### Return Value
True (non-zero) if GUIDs are the same. 

### Description
Check if two GUID's is equal to each other. 

**Example** {% sample lang="c" %}

```c
if ( vscphlp_isSameGUID( emptyGUID, GUID2) ) {
    printf( "\aError: vscphlp_isSameGUID\n");
}
else {
    printf( "vscphlp_isSameGUID  - Correct, GUIDs are not the same.\n" );
}
```

{% endmethod %}

{% include "./bottom_copyright.md" %}