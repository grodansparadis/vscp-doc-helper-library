


```clike
int vscphlp_tableGetLastDate( const unsigned char *pName, 
                        const char *pFrom, 
                        const char *pTo,
                        char *pLast )
```

### Parameters

#### tblName
Name of an existing table.

#### from
Date/time from which resulting data should be fetched. Set to “0000-01-01T00:00:00” for beginning of time.

#### to
Date/time to which resulting data should be fetched. Set to “9999-12-31T23:59:59” for end of time.

#### pLast
A string buffer that will get the last date/time in the interval on success. The buffer is supposed to hold a ISO formatted date/time value (YYYY-MM-DDTHH:MM:SS) so it should be able to hold at least twenty characters.


### Return Value
CANAL_ERROR_SUCCESS on success or an error code on failure.

### Description
Get the last data/time for an interval in a named table. 

### See Also
[vscphlp_tableGetFirstDate](vscphlp_tablegetfirstdate.md)



[filename](./bottom_copyright.md ':include')