
{% method %}
## doCmdStatistics

```c
int doCmdStatistics(VSCPStatistics *pStatistics)
```

### Parameters

#### pStatistics
Pointer to VSCPStatistics structure that will get the VSCP remote server statistics.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Get the VSCP statistics structure from the VSCP remote server. 

{% endmethod %}

{% include "./bottom_copyright.md" %}