
{% method %}
## vscphlp_calcCRC4GUIDArray

```c
unsigned char vscphlp_calcCRC4GUIDArray( unsigned char *pguid )
```

### Parameters

#### pguid
Array of sixteen bytes containing GUID on MSB→LSB order.


### Return Value
8-bit CRC for GUID.

### Description
Calculate 8-bit crc for a GUID array. 

**Example** {% sample lang="c" %}

```c
// Calculate CRC for GID array
unsigned char GUID2[16];
memset( GUID2, 0, 16 );
for ( int i=0;i<16; i++ ) {
    GUID2[i] = i;
}
unsigned char crc8 = vscphlp_calcCRC4GUIDArray( GUID2 );
printf("CRC = %02X\n", crc8 );
```

{% endmethod %}

{% include "./bottom_copyright.md" %}