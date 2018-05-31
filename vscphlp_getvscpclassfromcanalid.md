
{% method %}
## vscphlp_getVSCPclassFromCANALid

```c
unsigned short 
vscphlp_getVSCPclassFromCANALid( unsigned long id )
```

### Parameters

#### id
Extended 29-bit CANAL id to get head from.

### Return Value
VSCP class. 

### Description
Get the VSCP class from a CANAL message id. 

**Example** {% sample lang="c" %}

```c
unsigned long canalid = 0x0c0a0601;
unsigned short can_vscpclass = vscphlp_getVSCPclassFromCANALid( canalid );
if ( 10 == can_vscpclass ) {
    printf("VSCP Class = %d\n", can_vscpclass );
}
else {
    printf("\aError: vscphlp_getVSCPclassFromCANAALid = %d\n", can_vscpclass );
}
```

{% endmethod %}

{% include "./bottom_copyright.md" %}