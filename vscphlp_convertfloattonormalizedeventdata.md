
{% method %}
## vscphlp_convertFloatToNormalizedEventData

```c
int vscphlp_convertFloatToNormalizedEventData( 
                            unsigned char *pdata,        unsigned short *psize,    
                            double value, 
                            unsigned char unit,
                            unsigned char sensoridx )
```

### Parameters

#### pdata
Pointer to data buffer that will get the result. The buffer should be large enough to hold the normalized data. That is bigger than eight bytes.

#### psize
The size of the written data will be returned here.

#### psize
Floating point value to write as a 64-bit double.

#### unit
A unit value 0-3

#### sensoridx
A sensor index value 0-7

### Return Value
VSCP_ERROR_SUCCESS is returned on success.

### Description
Write a 64-bit floating point value as event measurement data. 

**Example** {% sample lang="c" %}

```c
Example will be added. TODO
```

{% endmethod %}

{% include "./bottom_copyright.md" %}