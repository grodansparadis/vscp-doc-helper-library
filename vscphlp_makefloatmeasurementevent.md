
{% method %}
## vscphlp_makeFloatMeasurementEvent

```c
int vscphlp_makeFloatMeasurementEvent( vscpEvent *pEvent, 
                                float value,
                                unsigned char unit,
                                unsigned char sensoridx )
```

### Parameters

#### pEvent
Pointer to a VSCP event that will get the result as it's data.

#### psize
The size of the written data will be returned here.

#### value
Floating point value to write as a 32-bit float.

#### unit
A unit value 0-3

#### sensorid
A sensor index value 0-7

### Return Value
VSCP_ERROR_SUCCESS is returned on success.

### Description
Make a floating point ()32-bit) coded event from floating point data.

**Example** {% sample lang="c" %}

```c
Example will be added. TODO
```

{% endmethod %}

{% include "./bottom_copyright.md" %}