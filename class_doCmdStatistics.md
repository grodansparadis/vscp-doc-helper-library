
{% method %}
## doCmdStatistics

```c
int doCmdStatistics(canalStatistics *pStatistics)
```

### Parameters

#### pStatistics
Pointer to canalStatistics structure that will get the VSCP remote server statistics.

### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure. 

### Description
Get the CANAL statistics structure from the VSCP remote server. 

{% endmethod %}

{% include "./bottom_copyright.md" %}
